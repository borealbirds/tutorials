Fetch data from SQL Server
====

## First Steps

* [Set up an ODBC connection to the BAM SQL server and ensure you can connect to it (test using MS Access) ](https://github.com/borealbirds/tutorials/blob/master/establish-odbc-to-sql-server/README.md)
* Install RODBC package `install.packages("RODBC")`
* Known your SQL username and password

## Establish ODBC Connection
`library(RODBC)` 
`r library(RODBC)`

``` {r}
cn <- odbcDriverConnect(connection="Driver={ODBC Driver 13 for SQL Server};server=boreal.biology.ualberta.ca;trusted_connection=no; UID=userid; PWD=pwd;")
```






