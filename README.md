# pgserial2identity

Tool for convert serial to identity for PostgreSQL

## Installation

```shell
go install github.com/acoshift/pgserial2identity
```

## Usage

```shell
pgserial2identity <db_uri>
```

Example

```shell
pgserial2identity postgres://postgres:password@localhost:5432/db_name?sslmode=disable
```

## License

MIT
