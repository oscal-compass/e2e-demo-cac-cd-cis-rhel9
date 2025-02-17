---
x-trestle-comp-def-rules:
  Red Hat Enterprise Linux 9:
    - name: CIS-5.1.2
      description: The `/etc/crontab` file is used by `cron` to control its own jobs.
        The commands in this item make sure that root is the user and group owner
        of the file and that only the owner can access the file.
    - name: CIS-5.1.3
      description: This directory contains system `cron` jobs that need to run on
        an hourly basis. The files in this directory cannot be manipulated by the
        `crontab` command, but are instead edited by system administrators using a
        text editor. The commands below restrict read/write and search access to user
        and group root, preventing regular users from accessing this directory.
    - name: CIS-5.1.4
      description: The `/etc/cron.daily` directory contains system cron jobs that
        need to run on a daily basis. The files in this directory cannot be manipulated
        by the `crontab` command, but are instead edited by system administrators
        using a text editor. The commands below restrict read/write and search access
        to user and group root, preventing regular users from accessing this directory.
    - name: CIS-5.1.5
      description: The `/etc/cron.weekly` directory contains system cron jobs that
        need to run on a weekly basis. The files in this directory cannot be manipulated
        by the `crontab` command, but are instead edited by system administrators
        using a text editor. The commands below restrict read/write and search access
        to user and group root, preventing regular users from accessing this directory.
    - name: CIS-5.1.6
      description: The `/etc/cron.monthly` directory contains system cron jobs that
        need to run on a monthly basis. The files in this directory cannot be manipulated
        by the `crontab` command, but are instead edited by system administrators
        using a text editor. The commands below restrict read/write and search access
        to user and group root, preventing regular users from accessing this directory.
    - name: CIS-5.1.7
      description: The `/etc/cron.d` directory contains system `cron` jobs that need
        to run in a similar manner to the hourly, daily, weekly and monthly jobs from
        `/etc/crontab` , but require more granular control as to when they run. The
        files in this directory cannot be manipulated by the `crontab` command, but
        are instead edited by system administrators using a text editor. The commands
        below restrict read/write and search access to user and group root, preventing
        regular users from accessing this directory.
    - name: CIS-5.1.8
      description: 'If `cron` is installed in the system, configure `/etc/cron.allow`
        to allow specific users to use these services. If `/etc/cron.allow` does not
        exist, then `/etc/cron.deny` is checked. Any user not specifically defined
        in those files is allowed to use cron. By removing the file, only users in
        `/etc/cron.allow` are allowed to use cron.   _Note: Even though a given user
        is not listed in `cron.allow`, cron jobs can still be run as that user. The
        `cron.allow` file only controls administrative access to the crontab command
        for scheduling and modifying cron jobs._'
    - name: CIS-5.1.9
      description: If `at` is installed in the system, configure `/etc/at.allow` to
        allow specific users to use these services. If `/etc/at.allow` does not exist,
        then `/etc/at.deny` is checked. Any user not specifically defined in those
        files is allowed to use at. By removing the file, only users in `/etc/at.allow`
        are allowed to use at.   **Note:** Even though a given user is not listed
        in `at.allow`, at jobs can still be run as that user. The `at.allow` file
        only controls administrative access to the at command for scheduling and modifying
        at jobs.
x-trestle-global:
  profile:
    title: CIS Controls
    href: catalogs/cis-v8/catalog.json
  sort-id: cisc-03.03
---

# cisc-3.3 - \[\] Configure Data Access Control Lists

## Control Statement

Configure data access control lists based on a user’s need to know. Apply data access control lists, also known as access permissions, to local and remote file systems, databases, and applications.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: cisc-3.3 -->

### Rules:

  - CIS-5.1.2
  - CIS-5.1.3
  - CIS-5.1.4
  - CIS-5.1.5
  - CIS-5.1.6
  - CIS-5.1.7
  - CIS-5.1.8
  - CIS-5.1.9

### Implementation Status: planned

______________________________________________________________________
