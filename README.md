# java-cli-bazel-sqlserver-ssl-simple

## Description
A java bazel build, that connects to sqlserver database.

Sql server uses self-signed ssl.

## Tech stack
- java
- bazel
  - 6.8.2

## Docker stack
- alpine:edge
- mcr.microsoft.com/mssql/server:2017-latest-ubuntu
- l.gcr.io/google/bazel:latest

## To run
`sudo ./install.sh -u`

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`
