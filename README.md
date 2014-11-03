# mdb-sqlite

Fork of mdb-sqlite

Original repo is at https://code.google.com/p/mdb-sqlite/

## Description

Provides automated conversion of MS Access 2000 databases to SQLite on any
platform, utilizing Jackcess and SQLite Java libraries. No native driver
required.

MDB-SQLite is used by Plausible Labs to read government-supplied Access databases.

## Usage

To compile, run:

    ant dist

This will create a standalone jar in `dist/mdb-sqlite.jar`

To convert a database file:

    java -jar dist/mdb-sqlite.jar source.mdb output.sqlite
