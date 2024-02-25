# PostgreSQL and PostGIS

This is a brew tap for installing PostgreSQL and PostGIS. Currently this tap has the following formulas:
* `postgis@15` and `postgis@16`
* `postgresql@15` and `postgresql@16`

## How do I install these formulae?

`brew install ozeias/postgresql/<formula>`

Or `brew tap ozeias/postgresql` and then `brew install <formula>`.

## Install PostgreSQL 15.6 with PostGIS 3.3

Please ensure that you do not have any other installation of PostgreSQL 15 via Homebrew:

`brew rm postgresql@15`

To install:

`brew install ozeias/postgresql/postgis@15`

To run:

`brew services start ozeias/postgresql/postgresql@15`

More information:

`brew info ozeias/postgresql/postgresql@15`

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
