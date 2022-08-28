# New SQL(ns) object storage PostgreSQL extension for AWS S3
A high-performance PostgreSQL extension to import and export object storage from AWS S3 with Rust.
## 1. Functions 
###  hello_s3()
Test extension hello function
## 2. To build extension
```
cargo pgx run pg14
create extension ns_object_storage_s3;

select hello_s3();

hello_s3  
-----------
 Hello, S3
(1 row)

drop extension ns_object_storage_s3;
```
