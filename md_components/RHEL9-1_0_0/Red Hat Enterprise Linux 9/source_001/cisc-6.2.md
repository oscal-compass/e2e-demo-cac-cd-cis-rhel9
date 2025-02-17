---
x-trestle-comp-def-rules:
  Red Hat Enterprise Linux 9:
    - name: CIS-5.5.2
      description: Lock out users after _n_ unsuccessful consecutive login attempts.  -
        `deny=<n>` - Number of attempts before the account is locked - `unlock_time=<n>`
        - Time in seconds before the account is unlocked   **Note:** The maximum configurable
        value for `unlock_time` is `604800`
x-trestle-global:
  profile:
    title: CIS Controls
    href: catalogs/cis-v8/catalog.json
  sort-id: cisc-06.02
---

# cisc-6.2 - \[\] Establish an Access Revoking Process

## Control Statement

Establish and follow a process, preferably automated, for revoking access to enterprise assets, through disabling accounts immediately upon termination, rights revocation, or role change of a user. Disabling accounts, instead of deleting accounts, may be necessary to preserve audit trails.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cisc-6.2 -->

### Rules:

  - CIS-5.5.2

### Implementation Status: planned

______________________________________________________________________
