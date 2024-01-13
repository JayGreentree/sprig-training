# Sprig Training

Source code used in live Sprig training sessions.

https://putyourlightson.com/sprig/training


### Local Develeopment Setup using DDEV

```shell
# Starts the DDEV project.
ddev start

# Seeds the database.
ddev import-db db/seed.sql.zip

# Installs dependencies.
ddev composer install

# Launches the site in a browser.
ddev launch

# Returns an impersonation URL for the “admin” user. Alternatively, log in using the password “project”.
ddev craft users/impersonate 1 
```
