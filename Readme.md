# Taipei Mixed Martial Art Project

## Background
After I finished implementing the ERP system for this company. They asked me to add in several extra functions, including report and batch processing. 
After 5 new functions, executing individul code started to become tedious. 
Therefore, I created a application to organize all the extra functions so that they can be more productive.


## file introduction
### 1. TMMAinfo.txt
This file works as a config file. It records the following information for MSSQL database.

serverid      &nbsp;&nbsp;&nbsp;&nbsp;   __*// SQL server id*__

user           &nbsp;&nbsp;&nbsp;&nbsp;   __*// SQL user account*__

passward      &nbsp;&nbsp;&nbsp;&nbsp;    __*// SQL account*__

database      &nbsp;&nbsp;&nbsp;&nbsp;     __*// target database*__

apploginpwd    &nbsp;&nbsp;&nbsp;&nbsp;    __*// the password to login into this application. (They need some safety control)*__

fontpath      &nbsp;&nbsp;&nbsp;&nbsp;    __*// for special font*__

outputpath     &nbsp;&nbsp;&nbsp;&nbsp;   __*// sometimes their staff need to create some plots by themselves. So this path where output excel file will go*__

### 2. TMMA.py
This file is a login interface.


### 3. TMMA_program.py
This file is for all the logic and commend for the application.

### 4. All the .sql
I created a lot of store procedures in the database. Those .sql files are to call those store procedures when they click certain buttons.
1. Buyonegetonefree.sql  &nbsp;&nbsp;&nbsp;&nbsp; __*// Automatically insert cretain genre of products to a buy one get on free table*__

2. Adjustmin.sql        &nbsp;&nbsp;&nbsp;&nbsp;   __*// Automatically adjust the POS system's price of certain product*__

3. posall.sql          &nbsp;&nbsp;&nbsp;&nbsp;  __*// Automatically insert cretain genre of products to a pos buy one get on free table*__


## Check here to see the [application interface introduction!](https://github.com/red574890/TMMA-report-project/blob/main/interface_guide/interface_guide.md)

