# Detection: User Account Creation

## Event ID

4720

## Description

Windows generates Event ID 4720 when a new user account is created.

## Test Procedure

1. Created a test user in Active Directory.
2. Verified event collection in Wazuh.
3. Reviewed generated alerts.

## Risk

Unexpected account creation may indicate:

- Persistence
- Unauthorized administration
- Insider threats

## Mitigation

- Review account creation processes
- Audit privileged users
- Monitor administrative activity
