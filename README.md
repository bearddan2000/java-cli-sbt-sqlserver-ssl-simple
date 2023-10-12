# java-cli-sbt-sqlserver-ssl-simple

## Description
A java sbt build, that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- java
- sbt
  - 6.8.2

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- hseeberger/scala-sbt:11.0.2-oraclelinux7_1.3.5_2.12.10

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
