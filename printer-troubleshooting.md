# Printer Troubleshooting

## Problem

A user reports they cannot print.

Common symptoms:

- Print job stuck in queue
- Printer shows offline
- Printer not listed
- Poor print quality
- User can print to one printer but not another

## Troubleshooting Process

### 1. Determine Scope

Ask:

- Is the issue affecting one user or multiple users?
- Can other users print to the same printer?
- Can the user print to a different printer?

This helps identify whether the problem is user-specific, device-specific or printer-wide.

### 2. Check Printer Status

Confirm:

- Printer is powered on
- No paper jam
- Paper tray is loaded
- Toner or ink is available
- Printer display shows no error

### 3. Check Connection

Depending on printer type:

- USB cable connected
- Network printer online
- Wi-Fi printer connected
- Ethernet cable connected

### 4. Check Print Queue

On Windows:

1. Open Printers & Scanners.
2. Select the printer.
3. Open print queue.
4. Clear stuck jobs if appropriate.

### 5. Restart Printer

Power cycle the printer and test again.

### 6. Restart Print Spooler

If appropriate and permitted:

```cmd
net stop spooler
net start spooler
```

This can clear stuck print jobs.

### 7. Check Default Printer

Confirm the user is printing to the correct printer.

### 8. Reinstall or Reconnect Printer

If required:

- Remove printer
- Re-add printer
- Confirm driver is installed
- Test print

## Common Causes

### Stuck Print Job

A failed job can block later jobs.

### Printer Offline

The device may be powered off, disconnected or unreachable.

### Incorrect Printer Selected

User may be printing to the wrong device.

### Driver Issue

Printer driver may be missing, outdated or corrupt.

### Network Issue

Network printer may be unreachable due to connectivity issues.

## Escalation Criteria

Escalate if:

- Multiple users cannot print
- Printer hardware fault is suspected
- Network connectivity issue is suspected
- Driver deployment requires admin rights
- Print server issue is suspected

## Interview Questions

### A user says they cannot print. What would you check first?

> I would determine whether the issue affects only that user or multiple users, check the printer status, confirm the correct printer is selected, review the print queue and test whether other users can print.

### Why is checking scope important?

> It helps determine whether the issue is with one user, one device, the printer itself or a wider network or print server issue.

### What does it mean if multiple users cannot print to the same printer?

> It suggests the issue may be with the printer, network connection or print server rather than one user's device.

### What is the print spooler?

> The print spooler is a Windows service that manages print jobs before they are sent to the printer.

## Interview Summary

A strong 1st line explanation:

> When troubleshooting printer issues, I would determine scope, check the printer status and connection, review the print queue, confirm the correct printer is selected and escalate if the issue appears to affect multiple users or involves printer hardware, network or print server problems.
