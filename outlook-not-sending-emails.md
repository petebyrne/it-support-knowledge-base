# Outlook Not Sending Emails

## Symptoms

- Emails remain in Outbox
- Send/Receive reports an error
- Messages are delayed or never delivered
- Outlook appears connected but mail is not sending

## Troubleshooting Steps

### 1. Check Internet Connectivity

- Confirm the device is connected to the internet
- Open a web browser and test multiple websites

### 2. Check Outlook Connection Status

- Verify Outlook shows "Connected"
- If disconnected, restart Outlook

### 3. Test Webmail Access

- Log in through Outlook Web Access (OWA)
- If webmail works, the issue is likely local to Outlook

### 4. Check Outbox

- Look for messages stuck in the Outbox
- Remove large attachments if necessary

### 5. Restart Outlook

- Close Outlook completely
- Reopen and attempt to send again

### 6. Check Account Credentials

- Confirm password is correct
- Re-authenticate if prompted

### 7. Review Recent Changes

- New VPN?
- Password recently changed?
- New security settings or MFA prompts?

### 8. Escalate If Required

Escalate if:

- Multiple users are affected
- Exchange Online service issues are suspected
- Mail flow appears disrupted

## Resolution Confirmation

- Send a test email
- Confirm successful delivery
- Update ticket notes and close the incident

## Interview Scenario

### User Reports

"Outlook isn't sending emails."

Good response:

> First I'd determine whether the issue affects only that user or multiple users. I'd then check internet connectivity, verify Outlook's connection status, test Outlook Web Access, check for messages stuck in the Outbox, review credentials and recent changes, and identify whether the issue is local to Outlook or a wider Microsoft 365 service issue.

---

## Interview Questions

### What would you do if Outlook stopped sending emails?

> I'd first determine whether the issue affects one user or multiple users. I'd then check internet connectivity, Outlook connection status, Outlook Web Access, the Outbox, user credentials and any recent changes before escalating if required.

### Why would you test Outlook Web Access?

> If Outlook Web Access works but the Outlook desktop application does not, it helps isolate the issue to the local device or Outlook client rather than the user's account or Microsoft 365 service.

### What would messages stuck in the Outbox suggest?

> It could indicate a connectivity issue, authentication problem, oversized attachment or an Outlook client issue preventing messages from being sent.

### If multiple users suddenly reported email problems, what would you suspect?

> I would suspect a wider Microsoft 365, Exchange Online or network-related issue and would investigate service status before focusing on individual devices.

---

## Interview Summary

A strong 1st line explanation:

> When troubleshooting Outlook email issues, I would first determine the scope of the problem, verify connectivity, test Outlook Web Access, review credentials and recent changes, and identify whether the issue is local to the user or part of a wider Microsoft 365 service problem.
