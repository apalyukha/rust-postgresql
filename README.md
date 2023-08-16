# rust-postgresql

### example code

```
extern crate diesel;

use diesel::pg::PgConnection;
use diesel::prelude::*;

fn main() {
    let _connection =
        PgConnection::establish("postgres://postgres:postgres@localhost/postgres").unwrap();
    println!("Підключення до бази даних встановлено!");
}

```
