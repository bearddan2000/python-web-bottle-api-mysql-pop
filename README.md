# python-web-bottle-api-mysql-pop

## Description
Simple web app that serves an api
for a bottle project.

Uses sqlalchemy query a table `pop`.

## Tech stack
- python
  - bottle
  - sqlalchemy
- mariadb

## Docker stack
- python:latest
- mariadb:latest

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/pop)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
