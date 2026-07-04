# Ticket 03 - Service Not Running

## Issue
User could not access the internal web application.

## Environment
Ubuntu Linux server

## Symptoms
The application page would not load for the user.

## Steps Taken
Checked that the server was online.
Verified network connectivity.
Reviewed the status of the web service.

## Findings
The server was reachable.
Network connection was normal.
The web service was stopped.

## Resolution
Restarted the web service and tested the application again.

## Status
Resolved

## Lessons Learned
If an application is unreachable but the server and network are working, check whether the related service is running.
