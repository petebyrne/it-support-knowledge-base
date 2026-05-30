# Microsoft 365 Support

## What Is Microsoft 365?

Microsoft 365 is Microsoft's cloud-based productivity platform that provides services including:

- Outlook
- Teams
- OneDrive
- Word
- Excel
- PowerPoint
- SharePoint
- Exchange Online

It allows users to collaborate, communicate, store files, and access applications from multiple devices.

---

## Common 1st Line Support Tasks

### Password Reset

Used when a user cannot access Microsoft 365 services.

Steps:

1. Verify the user's identity.
2. Reset the password if required.
3. Confirm the user can sign in.
4. Check MFA if login issues continue.
5. Document actions taken.

---

### Multi-Factor Authentication (MFA)

MFA adds an extra layer of security beyond a password.

Examples:

- Microsoft Authenticator
- SMS codes
- Phone calls
- Hardware security keys

Common issues:

- User changed phone
- Authenticator app removed
- MFA prompt not appearing
- Incorrect MFA setup

Basic troubleshooting:

1. Confirm internet connectivity.
2. Confirm correct account is being used.
3. Verify MFA device registration.
4. Re-register MFA if necessary.
5. Escalate if authentication issues persist.

---

## Outlook Support

### Outlook Not Sending Emails

Symptoms:

- Messages stuck in Outbox
- Send/Receive errors
- Delayed delivery

Checks:

1. Determine scope (one user or multiple users).
2. Confirm internet connectivity.
3. Check Outlook Web Access (OWA).
4. Check Outbox.
5. Restart Outlook.
6. Verify credentials.
7. Test sending a new email.

If webmail works but Outlook does not, the issue is likely local to the user's device.

---

### User Cannot Access Outlook

Checks:

1. Verify username and password.
2. Check MFA prompts.
3. Test Outlook Web Access.
4. Restart Outlook.
5. Check Microsoft 365 service status if multiple users are affected.

---

## Microsoft Teams Support

### User Cannot Sign In

Checks:

1. Verify internet connectivity.
2. Confirm Microsoft 365 login works.
3. Check MFA.
4. Sign out and sign back in.
5. Restart Teams.

### Poor Call Quality

Checks:

1. Confirm internet connection stability.
2. Test wired versus Wi-Fi connection.
3. Close unnecessary applications.
4. Confirm headset or microphone functionality.

---

## OneDrive Support

### Files Not Syncing

Checks:

1. Confirm user is signed in.
2. Verify internet connectivity.
3. Check available storage.
4. Restart OneDrive.
5. Check for sync errors.

Common causes:

- Insufficient storage
- Invalid file names
- Large file uploads
- Authentication issues

---

## SharePoint Support

Common issues:

- Access denied
- Missing documents
- Permission problems

Checks:

1. Confirm user permissions.
2. Verify group membership.
3. Confirm site availability.
4. Test access using another user account.

---

## Common Microsoft 365 Support Scenario

### User Can Access Teams But Not Outlook

Possible causes:

- Outlook profile issue
- Local application issue
- Corrupt Outlook cache
- Outlook-specific authentication issue

Because Teams works, the user has already authenticated successfully.

---

## Escalation Criteria

Escalate if:

- Multiple users are affected
- Microsoft 365 services appear unavailable
- Exchange Online issues are suspected
- Security concerns are identified
- Administrative permissions are required

---

## Interview Questions

### What is Microsoft 365?

> Microsoft 365 is Microsoft's cloud-based productivity platform providing services such as Outlook, Teams, OneDrive, Word, Excel and SharePoint.

### What is MFA and why is it used?

> Multi-Factor Authentication requires two or more methods of verification and helps protect accounts if passwords are compromised.

### A user says Outlook isn't sending emails. What would you check first?

> I'd determine whether the issue affects one user or multiple users, check internet connectivity, verify Outlook's connection status and test Outlook Web Access.

### Why would you test Outlook Web Access?

> If Outlook Web Access works, it helps isolate the issue to the Outlook client or local device rather than the user's account or Microsoft 365 service.

### What would you do if a user could not access Teams?

> I'd verify internet connectivity, confirm Microsoft 365 login works, check MFA, restart Teams and gather any error messages before escalating if necessary.

### What are common causes of OneDrive sync issues?

> Authentication problems, insufficient storage, invalid file names, internet connectivity issues or large file uploads.

### What would you do if multiple users suddenly reported email issues?

> I'd suspect a wider Microsoft 365 or Exchange Online issue and check service status before troubleshooting individual devices.


## Interview Summary

A strong 1st line explanation:

> Microsoft 365 is Microsoft's cloud-based productivity platform. Common support tasks include helping users with Outlook, Teams, OneDrive, MFA, password resets, and account access issues while escalating more complex problems when required.
