# chronex-backend

# How to run the app.
1. Add .env files
2. Change the following .env data to your own data.

# Posgres Database
DB_USER=
DB_PASS=
DB_HOST=
DB_PORT=
DB_NAME=

# If local environment you can just use this.
DB_USER=postgres
DB_PASS=root
DB_HOST=localhost
DB_PORT=5432
DB_NAME=postgres

# For Email Sending
EMAIL_USER=""
EMAIL_PASS=""

After you've done that just type the following on the terminal.
~ make proto
~ make migrate (Use Gitbash on this)
~ make server