# Detection: Failed Logon Attempts

## Event ID

4625

## Description

Windows generates Event ID 4625 when a logon attempt fails.

## Test Procedure

1. Attempted multiple logins with an incorrect password.
2. Generated failed authentication events.
3. Verified events in Wazuh.

## Risk

Repeated failed logins may indicate:

- Brute force attacks
- Password spraying
- Unauthorized access attempts

## Mitigation

- Account lockout policy
- MFA
- Security monitoring
