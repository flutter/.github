# Security Policy

## Supported Versions

We commit to publishing security updates for the version of Flutter currently
on the `stable` branch.

## Expectations
We treat security issues equivalent to a P0 priority level. This means that we attempt to fix them as quickly as possible.
We will release a beta or hotfix for any major security issues found in the most recent stable version of our SDK. 

Any vulnerability reported for any Flutter websites like flutter.dev does not require a release and will be 
fixed in the website itself.
Security issues (other than via issue [72555](https://github.com/flutter/flutter/issues/72555)) are not tracked explicitly in the issue database. 

## Reporting a Vulnerability

To report a vulnerability, please e-mail `security@flutter.dev` with a description of the issue,
the steps you took to create the issue, affected versions, and if known, mitigations for the issue.

We should reply within three working days, probably much sooner.

We use GitHub's security advisory feature to track open security issues. You should expect
a close collaboration as we work to resolve the issue you have reported. Please reach out to
`security@flutter.dev` again if you do not receive prompt attention and regular updates.

You may also reach out to the team via our public [Discord](https://github.com/flutter/flutter/wiki/Chat) chat channels; however, please make
sure to e-mail `security@flutter.dev` when reporting an issue, and avoid revealing information about
vulnerabilities in public if that could put users at risk.

##  Flagging Existing Issues as Security-related
If you believe that an existing issue is security-related, we ask that you send an 
email to `security@flutter.dev`. The email should include the issue ID and a short 
description of why it should be handled according to this security policy.

## Disclosure Process

This section describes the process used by the Flutter team when handling vulnerability reports.

Vulnerability reports are received via the `security@flutter.dev` e-mail alias. Certain team members
who have been designated the "vulnerability management team" receive these e-mails. When receiving
such an e-mail, they will:

1. Reply to the email acknowledging its receipt, cc'ing `security@flutter.dev` so that the other 
members of the team are aware that they are handling the issue. If the email does not describe
an actual vulnerability, the process will stop here. (Unfortunately, we do receive spam at this 
address, and well-meaning but ultimately misguided reports that do not represent issues for which this 
process is appropriate.)
2. Security steward will triage the issue to evaluate its impact and if it is a security issue.
3. The issue is assigned to an owner who will drive it through the fix and release process.
4. Security steward will work with the team and product manager to determine if the issue 
requires a security advisory.
5. If an advisory is required, the steward will create a new 
[security advisory](https://github.com/flutter/flutter/security/advisories/new). 
One must be the repo admin to do this. Security stewards who are not also a repo admin will 
reach out to the repo admins until they find one who can create the advisory. The repo admins
who are also vulnerability management team members (security stewards) @Hixie and @tvolkert.
6. Security steward will add the issue reporter, relevant team lead and issue owner to the 
security advisory [Add the reporter](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/adding-a-collaborator-to-a-security-advisory) to the security advisory so that they can get updates.
8. Every security advisory will have a CVE number. As a Googler they can request a CVE number from go/cve-request.
9. Reopen [Issue 72555](https://github.com/flutter/flutter/issues/72555) to ensure that security vulnerabilities
   will be checked during critical triage.
10. As the fix is being developed, they will then reach out to the reporter to ask them if they would 
like to be involved and whether they would like to be credited. For credit, the GitHub security advisory 
UI has a field that allows contributors to be credited.

## Receiving security updates

The best way to receive security updates is to subscribe to the [flutter-announce] (https://groups.google.com/forum/#!forum/flutter-announce) mailing list or updates to the Discord [channel] (https://discord.com/channels/608014603317936148/608116355836805126).
We will also announce security advisories in the technical release blog post.

Flutter does not have a bug bounty program.

## References
- If team members need additional help, as a Googler they can review [Dash Security Playbook](https://docs.google.com/document/d/1tz3FUpXwDN-HbRFxc46S-bSx4XWwFUDJB8tnORyPJbk/edit#)
- For more information on security advisories, see 
[the GitHub documentation](https://docs.github.com/en/free-pro-team@latest/github/managing-security-vulnerabilities/managing-security-vulnerabilities-in-your-project).
