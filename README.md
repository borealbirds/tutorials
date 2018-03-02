# Tutorials for BAM Folks


## What is this? 
A place to store tutorials, scripts, and documentation for steps that most BAM Team Members will need at some point.

Each tutorial below explains a particular data processing/analysis step in the [overall BAM Modelling Workflow](https://github.com/borealbirds/tutorials/blob/master/overall-bam-modelling-workflow/README.md). 

**BAM Team Members: If you have a new tutorial to share with the group, do the following:**

1. check if the tutorial exists
    * if yes: contact the person who last committed to it and then work out how to improve it
    * if no: create a new one
2. To create a tutorial, create a new folder that has lower case letters and dashes (slugified), like `new-folder` (i.e. not `New Folder`),
2. Include your tutorial within the folder, for file options follow some of the existing tutorials.
4. Once a tutorial is started, add the link below and let Nicole know so it can be added to BAM News. 

**BAM Team Members: If you have any questions about the database or a given processing step, do the following:**

1. Review the open issues to see if your question has already been asked
    * if yes: Add a comment describing your question in the already open issue
    * if no: Open a new issue describing your question
2. Be sure to 'watch' the repo so you receive notifications when people reply


## Tutorials

### BAM Workflow
* [Overall BAM Modelling Workflow](https://github.com/borealbirds/tutorials/blob/master/overall-bam-modelling-workflow/README.md): Understanding this will give you a better sense of what other tutorials you need to review.

### BAM Data and Data Structure
* [Description of the BAM Avian Database](https://github.com/borealbirds/tutorials/blob/master/avian-database-structure/README.md)
* [BAM Biophysical Database (redirect)](https://github.com/borealbirds/tutorials/blob/master/biophysical-data/README.Rmd)
* [Variables needed for Offset calculation](https://github.com/borealbirds/tutorials/blob/master/biophysical-data/README.Rmd#offset-variables)

### Data Processing

* [Connecting to BAM SQL Server via ODBC](https://github.com/borealbirds/tutorials/blob/master/establish-odbc-to-sql-server/README.md)
* [Test fetch data from Access datbase via RODBC](https://github.com/borealbirds/tutorials/blob/master/testing-odbc-to-r-connection/testing-odbc-to-r-connection.md)
* [Fetch data from SQL server via RODBC](https://github.com/borealbirds/tutorials/blob/master/fetch-data-from-sql-server-to-r/README.Rmd)
* [Step A1. Prep data for offset calculation](https://github.com/borealbirds/tutorials/blob/master/prep-for-offset-creation/README.md)
* [Step A2. Prep other covariates for analyses]
* [Apply QPAD](https://github.com/borealbirds/tutorials/tree/master/apply-qpad/README.md)
* [Step B. Calculate Offsets](https://github.com/borealbirds/tutorials/blob/master/offset-estimation/README.md)
* [Step F. Generate prediction grids]

### Data analysis

Coming soon...

## TODO

1. Establishing ODBC connection (**DONE**)
2. Fetch data from db (**DONE**)
3. Database structure (**next!**)
4. Pre-process long format (**next!**)
5. Joining tables and filtering 
6. Species cross tabulation
7. Calculating species offsets
8. Analyzing point count data with QPAD offsets
