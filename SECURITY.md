# Security Policy

## Supported Versions

We commit to publishing security updates for the version of Flutter currently
on the `stable` branch.

## Expectations

We treat security reports equivalent to a P0 priority level. This means that we attempt to fix them as quickly as possible.
Depending on our release schedule, we will release either a new beta or a stable hotfix for any major security report
found in the most recent stable version of our SDK, whichever is most expedient.

Any vulnerability reported for any Flutter websites like flutter.dev does not require a release and will be 
fixed in the website itself.

## Reporting a Vulnerability

To report a security issue, please use [https://g.co/vulnz](https://g.co/vulnz).
We use g.co/vulnz for our intake, and do coordination and disclosure here on
GitHub (including using GitHub Security Advisory). The Google Security Team will
respond within 5 working days of your report on g.co/vulnz.

You may also reach out to the team via our public [Discord](https://github.com/flutter/flutter/blob/master/docs/contributing/Chat.md) chat 
channels; however, please also make sure to make vulnerability reports to g.co/vulnz, and avoid revealing information about
vulnerabilities in public if that could put users at risk.

You should expect a close collaboration as we work to resolve the security vulnerability you have reported. Please reach out to
`security@flutter.dev` *only* if you do not receive a response to a g.co/vulnz report within the above mentioned 5 working days.

##  Flagging Existing Issues as Security-related

If you believe that an existing GitHub issue is security-related, we ask that you both report the issue to g.co/vulnz and send an 
email to `security@flutter.dev`. The email should include the GitHub issue ID and a short 
description of why it should be handled according to this security policy. 

Security reports are not tracked explicitly in the GitHub issue database.
We use GitHub's security advisory feature to track open security reports.

## Disclosure Process

This section describes the process used by the Flutter team when handling vulnerability reports.

Vulnerabilities reported to g.co/vulnz are triaged by the Google Security Team, and routed to
the Flutter team. Certain team members who have been designated the "vulnerability management team"
receive these reports. When receiving such a report, one of the vulnerability management team members will:

1. Work with the Google Security Team to triage the report to evaluate its impact and if it is a security vulnerability.
1. Collaborate with the appropriate Flutter team lead to ensure that an owner is assigned to the report. 
The owner will drive it through the fix and release process.
1. Work with the team lead and product manager to determine if this security report requires a security advisory.
1. Create a new [security advisory](https://github.com/flutter/flutter/security/advisories/new) if an advisory is required. 
One must be the repo admin to do this. Vulnerability management team members who are not also a repo admin will reach out to the repo admins until they find one who can create the advisory. The repo admins who are also vulnerability management team members are @jtmcdole and @Piinks.
1. Add the [vulnerability reporter](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-collaborator-to-a-security-advisory), relevant team lead and fix owner to the security advisory so that they can get updates.
1. If the security issue does not yet have a CVE number, as a Googler, request one from go/cve-request. Every security advisory will have a CVE number.
1. Reopen [Issue 72555](https://github.com/flutter/flutter/issues/72555) to ensure that security vulnerabilities
will be checked during critical triage.
1. Work with the release and PR team to coordinate the publication of the security advisory.

## Bug Bounty programs

Non-Google teams that use or contribute to Flutter are also welcome to include Flutter within the scope of their bug bounty programs.
To have your program listed, please contact `security@flutter.dev`.

Google considers Flutter to be in scope for the [Google Open Source Software Vulnerability Reward Program](https://bughunters.google.com/open-source-security).

## Receiving security updates

The best way to receive security updates is to subscribe to the [flutter-announce](https://groups.google.com/g/flutter-announce) mailing list or updates to the Discord [channel](https://discord.com/channels/608014603317936148/608116355836805126).
We will also announce security advisories in the technical release blog post.

## References
- If team members need additional help, as a Googler they can review [Dash Security Playbook](https://docs.google.com/document/d/1tz3FUpXwDN-HbRFxc46S-bSx4XWwFUDJB8tnORyPJbk/edit#)
- For more information on security advisories, see 
[the GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/managing-security-vulnerabilities-in-your-project).

**If team members from other organizations would like their team's playbook listed here for their reference (even if it is not a public resource), please submit a PR.**
