# Monsters API Backend Project


![Monsters-API](/monsters-api.png)

An API build in Node/Express and PostgreSQL to master backend web development concepts.

This server keeps tracks of ficticious monsters, their habitats and a who lives where. All these relations are tracked by a PostgreSQL database.

## Highlights of this project

- [x] Created a `bin` direcotory and included a directory with the `sql` folder and the `monsters.sql` database, a `configure` shell script and a `www` executable file with the `#!` shebang unix notation.

- [x] Setup organized router to redirect the queries to predetermined endpoints.

- [x] Each table can use the methods `GET`, `POST`, `PUT` and `DELETE`. The exception is the joining table, which as only the method `GET`.


## Useful PostgreSQL and SQL commands

- SELECT 
- SELECT * FROM
- INSERT INTO tablename 
- VALUES($1, $2, $3) 
- UPDATE 
- SET 
- WHERE 
- DELETE FROM
- JOIN
- ON
- ORDER BY id ASC

## Important Concepts to know

### Node / Express
 - NPM and modules
 - HTTP and server setup
 - HTTP and web requests
 - JSON
 - Endpoints
 - The event loop
 - Call stack and queue
 - Methods: POST, GET, PUT, DELETE
 - Error handling


### Databases and PostgreSQL

- The Relational Model and SQL
- Creating and insterting tables
- Creating SQL scripts
- Selecting table data
- Relational tables
- Joining tables
- PSQL 

