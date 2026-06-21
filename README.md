# Periodic Table Database

A PostgreSQL and Bash project completed as part of the freeCodeCamp Relational Database Certification.

## Features

* Element lookup by atomic number
* Element lookup by symbol
* Element lookup by name
* Normalized database design
* Foreign key relationships
* Bash script integration with PostgreSQL

## Database Tables

### elements

* atomic_number
* symbol
* name

### properties

* atomic_number
* atomic_mass
* melting_point_celsius
* boiling_point_celsius
* type_id

### types

* type_id
* type

## Technologies Used

* PostgreSQL
* SQL
* Bash Scripting
* Git & GitHub

## Example

```bash
./element.sh H
```

Output:

The element with atomic number 1 is Hydrogen (H). It's a nonmetal, with a mass of 1.008 amu. Hydrogen has a melting point of -259.1 celsius and a boiling point of -252.9 celsius.
