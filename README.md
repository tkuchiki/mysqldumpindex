# mysqldumpindex
Generate "CREATE(DROP) INDEX" from MySQL tables

# Usage

```
Usage: mysqldumpindex [options]
    -u, --user USER                  The MySQL user name to use when connecting to the server
        --host HOST                  Connect to the MySQL server on the given host
    -d, --dbname DBNAME              The database to use. This is useful primarily in an option file
    -p, --password PASSWORD          Password to use when connecting to server
        --skip-primary               Skip PRIMARY
        --dump-drop-sql              Dump DROP INDEX SQL
        --dump-create-sql            Dump CREATE INDEX SQL
    -v, --version                    Show version
```
