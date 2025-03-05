---
x-trestle-comp-def-rules:
  Red Hat Enterprise Linux 9:
    - name: CIS-5.2.16
      description: The `MaxAuthTries` parameter specifies the maximum number of authentication
        attempts permitted per connection. When the login failure count reaches half
        the number, error messages will be written to the `syslog` file detailing
        the login failure.
x-trestle-global:
  profile:
    title: CIS Controls
    href: catalogs/cis-v8/catalog.json
  sort-id: cisc-08.05
---

# cisc-8.5 - \[\] Collect Detailed Audit Logs

## Control Statement

Configure detailed audit logging for enterprise assets containing sensitive data. Include event source, date, username, timestamp, source addresses, destination addresses, and other useful elements that could assist in a forensic investigation.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cisc-8.5 -->

### Rules:

  - CIS-5.2.16

### Implementation Status: planned

______________________________________________________________________
