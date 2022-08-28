# New SQL(ns) object storage PostgreSQL extension for AWS S3
A high-performance PostgreSQL extension to import and export object storage from AWS S3 with Rust.
## 1. Functions 
## 2. To build extension
```
cargo pgx run pg14
create extension ns_object_storage_s3;

select hello_s3();
drop extension ns_object_stroage_s3();
```
