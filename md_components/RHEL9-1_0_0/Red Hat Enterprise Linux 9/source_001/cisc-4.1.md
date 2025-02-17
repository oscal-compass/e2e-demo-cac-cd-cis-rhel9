---
x-trestle-comp-def-rules:
  Red Hat Enterprise Linux 9:
    - name: CIS-5.2.13
      description: SSH port forwarding is a mechanism in SSH for tunneling application
        ports from the client to the server, or servers to clients. It can be used
        for adding encryption to legacy applications, going through firewalls, and
        some system administrators and IT professionals use it for opening backdoors
        into the internal network from their home machines
    - name: CIS-5.2.15
      description: The `Banner` parameter specifies a file whose contents must be
        sent to the remote user before authentication is permitted. By default, no
        banner is displayed.
    - name: CIS-5.2.17
      description: The `MaxStartups` parameter specifies the maximum number of concurrent
        unauthenticated connections to the SSH daemon.
    - name: CIS-5.2.18
      description: The `MaxSessions` parameter specifies the maximum number of open
        sessions permitted from a given connection.
    - name: CIS-5.6.1.1
      description: The `PASS_MAX_DAYS` parameter in `/etc/login.defs` allows an administrator
        to force passwords to expire once they reach a defined age. It is recommended
        that the `PASS_MAX_DAYS` parameter be set to less than or equal to 365 days.
x-trestle-global:
  profile:
    title: CIS Controls
    href: catalogs/cis-v8/catalog.json
  sort-id: cisc-04.01
---

# cisc-4.1 - \[\] Establish and Maintain a Secure Configuration Process

## Control Statement

Establish and maintain a secure configuration process for enterprise assets (end-user devices, including portable and mobile, non-computing/IoT devices, and servers) and software (operating systems and applications). Review and update documentation annually, or when significant enterprise changes occur that could impact this Safeguard.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cisc-4.1 -->

### Rules:

  - CIS-5.2.13
  - CIS-5.2.15
  - CIS-5.2.17
  - CIS-5.2.18
  - CIS-5.6.1.1

### Implementation Status: planned

______________________________________________________________________
