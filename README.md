# MTA-STS Policy for lonestarbackuppower.com

This repository hosts the MTA-STS (Mail Transfer Agent Strict Transport Security) policy for the domain:

- lonestarbackuppower.com

## Hosted Policy URL

When configured, the policy will be available at:

https://mta-sts.lonestarbackuppower.com/.well-known/mta-sts.txt

## Current Policy

```text
version: STSv1
mode: testing
mx: smtp.google.com
max_age: 604800
```

## Purpose

MTA-STS helps protect email delivery by requiring TLS encryption and validating the destination mail server during inbound email transport.

## Repository Structure

```text
.
├── README.md
└── .well-known/
    └── mta-sts.txt
```

## References

- RFC 8461: https://datatracker.ietf.org/doc/html/rfc8461
- Google Workspace MTA-STS: https://support.google.com/a/answer/9261504
