1.POST
Used to create a new resource.

Each call creates a new entry.

The server assigns the resource ID.

Not idempotent – sending the same request twice creates two records.

Example: POST /users → creates a new user.

2.PUT
Used to update an existing resource.

You must know the resource ID .

Replaces or updates the resource completely or partially.

Idempotent – sending the same request multiple times gives the same result.

Example: PUT /users/1 → updates the user with ID 1.  
