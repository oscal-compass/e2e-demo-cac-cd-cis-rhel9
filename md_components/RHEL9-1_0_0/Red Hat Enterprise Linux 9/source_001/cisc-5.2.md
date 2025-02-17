---
x-trestle-comp-def-rules:
  Red Hat Enterprise Linux 9:
    - name: CIS-5.5.3
      description: The `/etc/security/opasswd` file stores the users' old passwords
        and can be checked to ensure that users are not recycling recent passwords.  -
        remember=<5> - Number of old passwords to remember
x-trestle-global:
  profile:
    title: CIS Controls
    href: catalogs/cis-v8/catalog.json
  sort-id: cisc-05.02
---

# cisc-5.2 - \[\] Use Unique Passwords

## Control Statement

Use unique passwords for all enterprise assets. Best practice implementation includes, at a minimum, an 8-character password for accounts using MFA and a 14-character password for accounts not using MFA.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cisc-5.2 -->

### Rules:

  - CIS-5.5.3

### Implementation Status: planned

______________________________________________________________________
