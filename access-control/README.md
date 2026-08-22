# Access Control

This section documents the access control and permission-hardening exercises performed in the Secure Data Infrastructure Lab.

The objective was to identify overly permissive access settings and apply more restrictive permissions following the principle of least privilege.

## Linux File Permissions

A test script named `backup.sh` was initially configured with permissions equivalent to:

```text
777
