# qb_table_schema_copy
A script that reads table metadata from two different Quickbase applicaiton and the adds/updates/deletes tables in the destination app to match the source app.

The script will request data from a Quickbase table including app IDs for the soruce (appA) and targt (appB).

There are global constants for userToken, configTable, sourceAppFID, and targetAppFID.
