# Security Policy

## Supported Versions

We commit to publishing security updates for the version of Flutter currently
on the `stable` branch.

## Expectations
We treat security reports equivalent to a P0 priority level. This means that we attempt to fix them as quickly as possible.
We will release a beta or hotfix for any major security report found in the most recent stable version of our SDK. 

Any vulnerability reported for any Flutter websites like flutter.dev does not require a release and will be 
fixed in the website itself.

## Reporting a Vulnerability

To report a vulnerability, please e-mail `security@flutter.dev` with a description of the problem,
the steps you took to reproduce the problem, affected versions and any known mitigations.

We should reply within three working days, probably much sooner.

We use GitHub's security advisory feature to track open security reports. You should expect
a close collaboration as we work to resolve the security vulnerability you have reported. Please reach out to
`security@flutter.dev` again if you do not receive prompt attention and regular updates.

You may also reach out to the team via our public [Discord](https://github.com/flutter/flutter/wiki/Chat) chat 
channels; however, please make sure to e-mail `security@flutter.dev` when reporting a vulnerability, and avoid revealing information about
vulnerabilities in public if that could put users at risk.

##  Flagging Existing Issues as Security-related
If you believe that an existing github issue is security-related, we ask that you send an 
email to `security@flutter.dev`. The email should include the github issue ID and a short 
description of why it should be handled according to this security policy.

Security reports are not tracked explicitly in the github issue database 
(other than via issue [72555](https://github.com/flutter/flutter/issues/72555)). 

## Disclosure Process

This section describes the process used by the Flutter team when handling vulnerability reports.

Vulnerability reports are received via the `security@flutter.dev` e-mail alias. Certain team members
who have been designated the "vulnerability management team" receive these e-mails. When receiving
such an e-mail, one of the vulnerability management team members will:

1. Reply to the email acknowledging its receipt, cc'ing `security@flutter.dev` so that the other 
members of the team are aware that they are handling the security report. If the email does not describe
an actual vulnerability, the process will stop here. (Unfortunately, we do receive spam, and well-meaning but ultimately misguided reports that do not represent issues for which this process is appropriate, at this address.)
2. Triage the report to evaluate its impact and if it is a security vulnerability.
3. Collaborate with the appropriate team lead to ensure that an owner is assigned to the report. 
The owner will drive it through the fix and release process.
4. Work with the team lead and product manager to determine if this security report requires a security advisory.
5. Create a new [security advisory](https://github.com/flutter/flutter/security/advisories/new) if an advisory is required. 
One must be the repo admin to do this. Vulnerability management team members who are not also a repo admin will reach out to the repo admins until they find one who can create the advisory. The repo admins who are also vulnerability management team members are @Hixie and @tvolkert.
6. Reach out to the reporter to ask them if they would like to be involved and whether they would like to be credited. 
For credit, the GitHub security advisory UI has a field that allows contributors to be credited.
7. Add the [vulnerability reporter](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-collaborator-to-a-security-advisory), relevant team lead and fix owner to the security advisory so that they can get updates.
8. If the security issue does not yet have a CVE number, as a Googler, request one from go/cve-request. Every security advisory will have a CVE number.
9. Reopen [Issue 72555](https://github.com/flutter/flutter/issues/72555) to ensure that security vulnerabilities
will be checked during critical triage.
10. Work with the release and PR team to coordinate the publication of the security advisory.
11. Recommend to the reporter that they file their report through [g.co/vulnz](https://g.co/vulnz) to qualify for Google's Bug Hunters bounty program, including the link to the GitHub security advisory, and CVE number when available.

## Bug Bounty programs

Contributing teams are welcome to include Flutter within the scope of their bug bounty programs.
To have your program listed, please contact `security@flutter.dev`.

Google considers Flutter to be in scope for the [Google Open Source Software Vulnerability Reward Program](https://bughunters.google.com/open-source-security).
For expediency we ask that reporters please contact `security@flutter.dev` before using Google's vulnerability reporting flow,
as described above.

## Receiving security updates

The best way to receive security updates is to subscribe to the [flutter-announce](https://groups.google.com/g/flutter-announce) mailing list or updates to the Discord [channel](https://discord.com/channels/608014603317936148/608116355836805126).
We will also announce security advisories in the technical release blog post.

## References
- If team members need additional help, as a Googler they can review [Dash Security Playbook](https://docs.google.com/document/d/1tz3FUpXwDN-HbRFxc46S-bSx4XWwFUDJB8tnORyPJbk/edit#)
- For more information on security advisories, see 
[the GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/managing-security-vulnerabilities-in-your-project).

[SECURITY.md](https://github.com/flutter/.github/files/12672960/SECURITY.md)

**If team members from other organizations would like their team'# Security Policy

## Supported Versions

We commit to publishing security updates for the version of Flutter currently
on the `stable` branch.

## Expectations
We treat security reports equivalent to a P0 priority level. This means that we attempt to fix them as quickly as possible.
We will release a beta or hotfix for any major security report found in the most recent stable version of our SDK. 

Any vulnerability reported for any Flutter websites like flutter.dev does not require a release and will be 
fixed in the website itself.

## Reporting a Vulnerability

To report a vulnerability, please e-mail `security@flutter.dev` with a description of the problem,
the steps you took to reproduce the problem, affected versions and any known mitigations.

We should reply within three working days, probably much sooner.

We use GitHub's security advisory feature to track open security reports. You should expect
a close collaboration as we work to resolve the security vulnerability you have reported. Please reach out to
`security@flutter.dev` again if you do not receive prompt attention and regular updates.

You may also reach out to the team via our public [Discord](https://github.com/flutter/flutter/wiki/Chat) chat 
channels; however, please make sure to e-mail `security@flutter.dev` when reporting a vulnerability, and avoid revealing information about
vulnerabilities in public if that could put users at risk.

##  Flagging Existing Issues as Security-related
If you believe that an existing github issue is security-related, we ask that you send an 
email to `security@flutter.dev`. The email should include the github issue ID and a short 
description of why it should be handled according to this security policy.

Security reports are not tracked explicitly in the github issue database 
(other than via issue [72555](https://github.com/flutter/flutter/issues/72555)). 

## Disclosure Process

This section describes the process used by the Flutter team when handling vulnerability reports.

Vulnerability reports are received via the `security@flutter.dev` e-mail alias. Certain team members
who have been designated the "vulnerability management team" receive these e-mails. When receiving
such an e-mail, one of the vulnerability management team members will:

1. Reply to the email acknowledging its receipt, cc'ing `security@flutter.dev` so that the other 
members of the team are aware that they are handling the security report. If the email does not describe
an actual vulnerability, the process will stop here. (Unfortunately, we do receive spam, and well-meaning but ultimately misguided reports that do not represent issues for which this process is appropriate, at this address.)
2. Triage the report to evaluate its impact and if it is a security vulnerability.
3. Collaborate with the appropriate team lead to ensure that an owner is assigned to the report. 
The owner will drive it through the fix and release process.
4. Work with the team lead and product manager to determine if this security report requires a security advisory.
5. Create a new [security advisory](https://github.com/flutter/flutter/security/advisories/new) if an advisory is required. 
One must be the repo admin to do this. Vulnerability management team members who are not also a repo admin will reach out to the repo admins until they find one who can create the advisory. The repo admins who are also vulnerability management team members are @Hixie and @tvolkert.
6. Reach out to the reporter to ask them if they would like to be involved and whether they would like to be credited. 
For credit, the GitHub security advisory UI has a field that allows contributors to be credited.
7. Add the [vulnerability reporter](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-collaborator-to-a-security-advisory), relevant team lead and fix owner to the security advisory so that they can get updates.
8. If the security issue does not yet have a CVE number, as a Googler, request one from go/cve-request. Every security advisory will have a CVE number.
9. Reopen [Issue 72555](https://github.com/flutter/flutter/issues/72555) to ensure that security vulnerabilities
will be checked during critical triage.
10. Work with the release and PR team to coordinate the publication of the security advisory.
11. Recommend to the reporter that they file their report through [g.co/vulnz](https://g.co/vulnz) to qualify for Google's Bug Hunters bounty program, including the link to the GitHub security advisory, and CVE number when available.

## Bug Bounty programs

Contributing teams are welcome to include Flutter within the scope of their bug bounty programs.
To have your program listed, please contact `security@flutter.dev`.

Google considers Flutter to be in scope for the [Google Open Source Software Vulnerability Reward Program](https://bughunters.google.com/open-source-security).
For expediency we ask that reporters please contact `security@flutter.dev` before using Google's vulnerability reporting flow,
as described above.

## Receiving security updates

The best way to receive security updates is to subscribe to the [flutter-announce](https://groups.google.com/g/flutter-announce) mailing list or updates to the Discord [channel](https://discord.com/channels/608014603317936148/608116355836805126).
We will also announce security advisories in the technical release blog post.

## References
- If team members need additional help, as a Googler they can review [Dash Security Playbook](https://docs.google.com/document/d/1tz3FUpXwDN-HbRFxc46S-bSx4XWwFUDJB8tnORyPJbk/edit#)
- For more information on security advisories, see 
[the GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/managing-security-vulnerabilities-in-your-project).

[SECURITY.md](https://github.com/flutter/.github/files/12672960/SECURITY.md)

**If team members from other organizations would like their team's playbook listed here for their reference (even if it is not a public resource), please submit a PR.**
s playbook listed here for their reference (even if it is not a public resource), please submit a PR.**
