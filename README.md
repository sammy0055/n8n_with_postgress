<!-- n8n login keys -->
<!-- email: ronicksamuel@gmail.com -->
<!-- password: utk4k)"iP,z7XZ5 -->

<!-- clound loging details -->
<!-- email: ronicksamuel@gmail.com -->
<!-- password: iTmJt72sYhj6GSu -->

# n8n with PostgreSQL

Starts n8n with PostgreSQL as database.

## Start

To start n8n with PostgreSQL simply start docker-compose by executing the following
command in the current folder.

**IMPORTANT:** But before you do that change the default users and passwords in the [`.env`](.env) file!

```
docker-compose up -d
```

To stop it execute:

```
docker-compose stop
```

## Configuration

The default name of the database, user and password for PostgreSQL can be changed in the [`.env`](.env) file in the current directory.
# n8n_with_postgress
