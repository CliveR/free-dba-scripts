Free DBA Scripts
================
Downloaded 12 November 2026 from the authors' own sites. All free to use; check each licence.

sp_WhoIsActive (Adam Machanic) - release 20260409
  sp_whoisactive-20260409.zip -> sp_WhoIsActive.sql (the 2019 folder has a version for SQL Server 2019+)
  Run it in master (or your DBA database), then: EXEC sp_WhoIsActive;
  https://github.com/amachanic/sp_whoisactive

First Responder Kit (Brent Ozar) - release 20260708
  First-Responder-Kit-20260708.zip -> Install-All-Scripts.sql installs sp_Blitz, sp_BlitzIndex,
  sp_BlitzCache, sp_BlitzFirst, sp_BlitzWho and the rest.
  https://github.com/BrentOzarULTD/SQL-Server-First-Responder-Kit

Ola Hallengren Maintenance Solution
  MaintenanceSolution.sql - backups, integrity checks and index maintenance. Read the settings at
  the top before running (it can create Agent jobs).
  https://ola.hallengren.com

Glenn Berry Diagnostic Information Queries
  One file per SQL Server version (2016 SP2, 2017, 2019, 2022, 2025). Use the one matching the
  server (SELECT @@VERSION). Read-only; run a query at a time.
  https://glennsqlperformance.com/resources/

Not downloaded (install on the laptop instead):
  dbatools:   Install-Module dbatools -Scope CurrentUser    (https://dbatools.io/download/)
  Formatter:  VS Code extension "Poor Man's T-Sql Formatter", or npm install -g poor-mans-t-sql-formatter-cli
