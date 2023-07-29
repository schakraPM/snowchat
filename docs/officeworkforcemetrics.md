**Table 1: TEST_DB.TEST_SCHEMA.OFFICEWORKFORCEMETRICS ** (Stores office workforce metric information)

This table contains the data about office workforce metrics.

- MEASURENAME VARCHAR (30) [Primary Key, Not Null]
- OFFICENUMBER NUMBER (38,0) [Primary Key, Not Null]
- FISCALMONTHNBR NUMBER (38,0) [Primary Key, Not Null]
- COMPLETEDWEEKS NUMBER (38,0)
- DAYSINCALENDARMONTH NUMBER (38,0)
- MEASUREACTUAL NUMBER (12,2)
- MEASUREBUDGET NUMBER (12,2)
- LOADEDDATE DATE