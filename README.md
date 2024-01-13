# Sprig Training

## DDEV

```shell
# Starts the DDEV project.
ddev start

# Seeds the database.
ddev import-db db/seed.sql.zip

# Returns an impersonation URL for the “admin” user. Alternatively, log in using the password “project”.
ddev craft users/impersonate 1 
```
