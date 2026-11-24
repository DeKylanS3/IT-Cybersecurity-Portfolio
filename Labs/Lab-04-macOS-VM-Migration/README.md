# Lab 04 - macOS Administration and VM Migration

## Project Date
November 23-24, 2026

## Objective
Create a dedicated technical workspace on macOS
and migrate an existing Ubuntu virtual machine
without reinstalling the guest operating system.

## Environment
- Apple MacBook Air M5
- macOS
- UTM
- Ubuntu Linux ARM64
- 29GB virtual machine package

## Implementation
1. Verified administrator privileges.
2. Created a dedicated standard user account.
3. Verified administrator group exclusion.
4. Located the existing virtual machine package.
5. Created a temporary transfer copy.
6. Created a dedicated virtual machine directory.
7. Copied the virtual machine to the new account.
8. Configured file ownership.
9. Verified storage usage and permissions.
10. Logged into the new account.
11. Successfully launched Ubuntu.
12. Verified the existing IT-Home-Lab directory.

## Commands Used
- sysadminctl
- dscl
- dseditgroup
- whoami
- id
- find
- ditto
- mkdir
- chown
- du -sh
- df -h
- ls -ld
- open -a

## Troubleshooting
Resolved a case-sensitive command syntax error
during user account creation.

Distinguished directory entry size from actual
virtual machine storage consumption.

## Security Considerations
- Principle of least privilege
- Account separation
- File ownership
- Access control
- Data preservation

## Results
Successfully migrated a 29GB Ubuntu virtual machine
to a dedicated standard macOS account without
reinstalling Ubuntu.

Verified successful boot and preservation of the
existing lab directory.

## Status
Migration successful. Backup cleanup pending.
