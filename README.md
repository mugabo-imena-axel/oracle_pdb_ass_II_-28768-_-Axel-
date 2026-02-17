# oracle_pdb_ass_II_-28768-_-Axel-
## Overview of tasks
This assignment focuses on hands-on practice with Oracle Multitenant Architecture, specifically the creation, management, and deletion of Pluggable Databases (PDBs).
The objective was to strengthen practical database administration skills that are essential for future PL/SQL labs, practical tests, and examinations.
## Oracle environment used
Oracle Database 21c

SQL*Plus

SQL developer

Oracle Enterprise Manager (OEM)

## Explanation of each task
### Task1 :PDB creation
> create pluggable database ax_pdb_28768

> admin user pdbadmin identified by axel

> file_name_convert=('c:\ORACLE21c\ORADATA\ORCL\DATAFILE\', 'c:\ORACLE21c\ORADATA\ORCL\DATAFILE\ax_pdb_28768');
### Task2 :Create and delete pdb
> create pluggable database ax_to_delete_pdb_28768

> admin user pdbadmin identified by axel

> file_name_convert=('c:\ORACLE21c\ORADATA\ORCL\DATAFILE\', 'c:\ORACLE21c\ORADATA\ORCL\DATAFILE\ax_to_delete_pdb_28768');

> To delete the pdb: drop pluggable database ax_to_delete_pdb_28768 including datafiles;


### Task3: Oracle Enterprise Manager(OEM)
Successfully configured and accessed Oracle Enterprise Manager.

The OEM dashboard reflects:

>My Oracle environment

>The created PDB

>My configured user

>Database instance status


[repository Link](https://github.com/mugabo-imena-axel/oracle_pdb_ass_II_-28768-_-Axel-)

*PDB Name Created: ax_pdb_28768*

*Issues Encountered: During the initial setup, I encountered issues related to memory allocation and service configuration. This was resolved by adjusting system resources and ensuring Oracle services were running properly before attempting PDB creation again.*

