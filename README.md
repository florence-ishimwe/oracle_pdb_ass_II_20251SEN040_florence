# Oracle Pluggable Databases (PDB) Management Report

## 1. Overview of Tasks
This assignment covers the practical management of Oracle Pluggable Databases (PDBs), including PDB creation, user management, temporary PDB lifecycle operations, and Oracle Enterprise Manager (OEM) monitoring.

## 2. Oracle Environment Used
- **Database Version:** Oracle Database 21c Express Edition (XE)
- **Host OS:** Windows 10/11 x86_64
- **Tools Used:** SQL*Plus, Oracle Enterprise Manager (OEM) Express

## 3. Explanation of Tasks

### Task 1: Create a New Pluggable Database
Created a persistent PDB named `fl_pdb_20251SEN040` along with an administrative user `florence_plsqlauca_20251SEN040`. Granted necessary privileges (`CONNECT`, `RESOURCE`, `DBA`) inside the container.

### Task 2: Create and Delete a Temporary PDB
Created a temporary PDB named `fl_to_delete_pdb_20251SEN040` to demonstrate database lifecycle management. Verified its active status via `SHOW PDBS;`, then closed and dropped the database along with its datafiles.

### Task 3: Oracle Enterprise Manager (OEM) Setup
Logged into the OEM Express dashboard at `https://localhost:5500/em` to verify that database performance, memory allocations, and container states reflect the updated environment.

## 4. Challenges Faced and Solutions
- **Issue:** Resolved initial PDB creation file path requirements by explicitly using `FILE_NAME_CONVERT`.
- **Solution:** Configured appropriate directory paths and granted full privileges to the admin user inside the target container.

## 5. Integrity Statement
I confirm that all tasks were performed individually and all provided screenshots reflect my own execution on my local Oracle environment.

---

Repository Link: https://github.com/florence-ishimwe/oracle_pdb_ass_II_20251SEN040_florence
PDB Name Created: fl_pdb_20251SEN040
Issues Encountered: No
