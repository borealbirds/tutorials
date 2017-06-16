# Testing ODBC-to-R connection

## Make a dummy MS Access file

1. Open MS Access, create a new database called `test.accdb`,
2. create or import a new table into the database, call it `TABLE1`, and save.

## In R

1. Open R, install and load the **RODBC** R package,
2. set your working directory to the place where the Access file is located (or adjust the path accordingly in the code below),
3. run the following R code and see if what you have in Access and the data frame in R match.

```R
library(RODBC)
setwd("your/path/comes/here")
con <- odbcConnectAccess2007("test.accdb")
tab <- sqlFetch(con, "TABLE1")
close(con)
str(tab)
```

That's all!
