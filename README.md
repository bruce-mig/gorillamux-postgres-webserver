# gorillamux-postgres-webserver

This is a stocks API using Postgres database with Golang. 
it implements gorillamux, lib/pq and database/sql packages.

### Step 1

To begin fork project using http or ssh.
Create a new Postgres database and begin Postgres service.

### Step 2

Set up .env file in root folder.

```bash
POSTGRES_URL="postgres://<username>:<password>@localhost:5432/<dbname>"
```

## Step 3

In terminal run:

```bash
go mod tidy
```

This will install the required dependencies

### Step 4

To start server, run the following in root directory:

```bash
go run main.go
```

Congrats🥳, your Go server is up and running!