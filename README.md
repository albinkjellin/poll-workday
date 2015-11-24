# Workday Polling Example

## Description
Very basic application to illustrate how to poll workday for updates in the employee object using Datawave. The application currently just logs Employee name and ID. 

## Get started
Open the file mule-project.xml and fill in the following values:
+ wday.user=
+ wday.password=
+ wday.endpoint=

## Ok its working, what do I do now?
Once you have this done you can start processing the data and syncing it up with any other system. The best way to get start is to build a flow for that and reference that from the for-each loop.

## Improvements
Currently the string to datetime conversion is created in variable however this should be done in data weave, however there is an issue with string to date conversions there at the moment.