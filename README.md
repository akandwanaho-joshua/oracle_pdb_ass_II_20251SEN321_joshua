# Oracle PDB Assignment II

## Overview of Tasks
- Task 1: Created main PDB and user.
- Task 2: Created and deleted a temporary PDB.
- Task 3: Accessed Oracle Enterprise Manager.
- Task 4: Documented the process.

## Oracle Environment Used
Oracle Database 21c Enterprise Edition on Windows.

## Explanation of Each Task
Task 1: I created a PDB named jo_pdb_20251SEN321 and opened it in READ WRITE mode. I then created and verified my user joshua_plsqlaua_20251SEN321 inside it.
Task 2: I created a temporary PDB jo_to_delete_pdb_20251SEN321, verified it, closed it, and dropped it including datafiles.
Task 3: I attempted to access Oracle Enterprise Manager, but experienced local web server authentication errors (Invalid Database Credentials). A screenshot of the attempt is included.

## Challenges Faced
I got ORA-65016 (FILE_NAME_CONVERT must be specified) because the default file destination was not set. I resolved it by using the FILE_NAME_CONVERT clause.
I was unable to access the OEM Express dashboard due to a local web server authentication loop. I have included a screenshot of the login attempt as proof. My database PDBs and users were verified successfully using SQL*Plus.

## Integrity Statement
I declare that this work is my own individual effort. I did not copy from classmates or use AI to generate my commands. The screenshots are from my own execution.

## Submission Details
Repository Link: https://github.com/akandwanaho-joshua/oracle_pdb_ass_II_20251SEN321_joshua
PDB Name Created: jo_pdb_20251SEN321
Issues Encountered: Yes
