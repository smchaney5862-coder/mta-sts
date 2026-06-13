# MTA-STS Policy for lonestarbackuppower.com

This repository hosts the MTA-STS (Mail Transfer Agent Strict Transport Security) policy for:

- lonestarbackuppower.com

## Policy Location

The policy file is available at:

https://mta-sts.lonestarbackuppower.com/.well-known/mta-sts.txt

## Current Policy

```text
version: STSv1
mode: testing
mx: smtp.google.com
max_age: 604800
```

## Purpose

MTA-STS helps protect email communications by requiring TLS encryption and validating mail server identities for inbound email delivery.

## References

- https://datatracker.ietf.org/doc/html/rfc8461
- https://support.google.com/a/answer/9261504
