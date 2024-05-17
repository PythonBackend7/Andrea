# Andrea
Andrea Blog site

## Postgres komandalar
```shell
sudo -u postgres psql
CREATE DATABASE cloudproject;
CREATE USER clouduser WITH PASSWORD 'password';
ALTER USER staff superuser;
GRANT ALL PRIVILEGES ON DATABASE cloudproject TO clouduser;
\q
```