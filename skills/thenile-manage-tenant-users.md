---
name: thenile-manage-tenant-users
description: List the tenants in a Nile database and add or list users within a tenant.
api: thenile:nile-database-api
operations: [listTenants, getTenant, createTenantUser, listTenantUsers]
generated: '2026-10-13'
method: generated
---
1. `listTenants` for the database, then `getTenant` for the target tenant.
2. `createTenantUser` to add a user to that tenant.
3. `listTenantUsers` to confirm membership.
No idempotency key is documented; check `listTenantUsers` before retrying a create.
