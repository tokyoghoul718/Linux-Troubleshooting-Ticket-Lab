# Ticket 01 - Remote Shared Drive Access

## Issue
User could not access the shared drive while working remotely.

## Environment
Remote user workstation

## Symptoms
The user received an error that the network path could not be found.
Internet and email were working.
Mapped drives showed as disconnected.

## Steps Taken
Connected to the user PC through remote support.
Reviewed mapped drives.
Checked VPN connection status.

## Findings
The VPN was disconnected.
Because the user was remote, the shared drive was unavailable without VPN access.

## Resolution
Reconnected the VPN and tested shared drive access again.

## Status
Resolved

## Lessons Learned
If a remote user has internet access but cannot reach internal shared drives, check VPN status first.
