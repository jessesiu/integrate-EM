# integrate-EM

## What is it?
EM system will generate the daily report send to the Gmail Account. It contains the new manuscripts information and
updated manuscripts information. The script will access the Gmail account and read the email from EM daily. 
After parsing the report it will insert into database and save the actions as the log file to allow the curators to check.

## Installation
JDK 1.7 with the jar packages list in the script.

## Workflow

1. Access the Gmail use IMAP and read the email from EM which sent in 24 hours
2. Downaload the attachment xlsx file, Save it to the directory
3. read the xlsx file including insert new records and update records
4. generate the database actions report and save it to the directory, and update the database

The detail requirement will refer to [https://github.com/gigascience/gigadb-website/projects/1](https://github.com/gigascience/gigadb-website/projects/1)
