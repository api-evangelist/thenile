---
name: thenile-provision-database
description: Create a Nile Postgres database in a workspace, mint a connection credential, and confirm it is ready.
api: thenile:nile-global-api
operations: [listRegions, createDatabase, getDatabase, createCredential]
generated: '2026-10-13'
method: generated
---
1. `listRegions` to pick a region the workspace can use.
2. `createDatabase` in the workspace with the chosen region (bearer JWT from `getToken` / the console).
3. Poll `getDatabase` until the database reports ready.
4. `createCredential` to obtain a Postgres user/password; connect over the Postgres wire protocol.
Errors follow errors/thenile-problem-types.yml. No idempotency key is documented: check `listDatabases` before retrying a create.
