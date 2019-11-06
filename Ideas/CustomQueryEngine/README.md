# Custom Query Engine

## Brief

The aim of this project is to build the functionality to translate your own custom query language into actions that your program will handle.

> The important part of this project is to gradually build up functionality! Break it up into small tasks.

## Example

```bash
python my_custom_query_engine.py -q "SELECT id, name, age FROM people WHERE age < 25;"
```

## Features

- Given a query string the program should perform the desired action.
- Follow basic logic such as that of SQL

## Bonus Features

- Build out your query language so that it can do more than just querying! If you are dealing with tables then maybe you can make tables and insert data then query off of them.
- Think about your performance and how you can increase it by using indexes and BST's.
- Build your own parser rather than using external libraries

## Helpful links

- [Python - SQLParse](https://sqlparse.readthedocs.io/en/latest/intro/#getting-started)
- [Python - Pandas](https://pandas.pydata.org/pandas-docs/stable/)
