## To use Docker and create a table:
+ `docker exec -it postgres bash`
+ inside of the docker container
    * `psql -U juan`
    * `\l`
    * `CREATE DATABASE customer;`
+ to view the table
    *  \c customer
    *   \dt
    *   \d
+ we can run
    * select * from customer;
