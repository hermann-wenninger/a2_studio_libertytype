### Restapi
#### with Rust, Diesel, Postgres
##### First we need to install the diesel_cli:
+ install postgres
+ install cargo 1.77
+ cargo install diesel_cli --no-default-features --features postgres

#####  the .env file:
+ DATABASE_URL=postgres://username:password@localhost/databasename
+ diesel setup
+ diesel migration generate create_events
+ diesel migration run
+ cargo run
