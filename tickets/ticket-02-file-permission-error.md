# Ticket 02 - File Permission Error

## Issue
User could not open a project file on the Ubuntu system.

## Environment
Ubuntu Linux workstation

## Symptoms
User received a "Permission denied" message when trying to open the file.

## Steps Taken
Checked that the file existed.
Reviewed file ownership.
Checked file permissions.
Verified the user’s access level.

## Findings
The file was owned by root.
The user did not have read permission for the file.
The issue was caused by incorrect file permissions.

## Resolution
Updated the file permissions and tested access again.

## Status
Resolved

## Lessons Learned
When a file exists but cannot be opened, check ownership and permissions first.
