# Security Policy

Rancher Government Solutions is committed to providing secure software. We sincerely appreciate your assistance in ensuring we can identify and resolve any security issues as soon as possible.

## Reporting a Vulnerability

Before reporting a vulnerability, make sure it impacts the latest minor version of Hauler. We keep the latest release line up-to-date with patches.

### What types of issue to report

This reporting channel focuses on bugs with potential security impact on Hauler.

### What types of issue NOT to report

Some issues are outside of the scope of this channel, and therefore should not be reported:

- CVEs that were found by CVE scanners (e.g. Trivy, Snyk). Public CVEs do not need to be reported as they are fixed as part of the development process.
- Issues or bugs that aren't security related. These should be reported as a new issue (https://github.com/hauler-dev/hauler/issues). 
- Issues with mirrored container images, instead please report them via the security channels of the specific upstream project.
- Issues that require the user to disable security features or downgrade the security of its environment in order for the vulnerability to be exploited.
- Issues that can only be exploited by the administrator itself (after all, the admin is already a privileged user and implicitly trusted).
- Vulnerabilities affecting directly a user or customer environment. Such vulnerabilities must be reported directly to the affected user/customer. Be advised that such reports can constitute law infringement under certain jurisdictions.

If going through all the examples above you are still in doubt, please go ahead and use this channel. After all, it's better be safe than sorry.

## Reporting a Vulnerability

To report a security vulnerability, email carbide@ranchergovernment.com.

We strive to ackknowledge receiving submissions within 5 working days, please wait until that time has past before asking for a status update.

The information contained in your report must be treated as embargoed and must not be shared publicly, unless explicitly agreed with us first. This is to protect Hauler users and enable us to follow through our coordinated disclosure process. The information shall be kept embargoed until a fix is released.

### What information to provide

Feel free to get in touch in whatever way works best for you! If you’re able to include the information below in your report, that would be incredibly helpful and much appreciated:

- Product name and version where the issue was observed. If the issue was observed on the source code, the link to the specific code in GitHub instead.
- Description of the problem.
- Type of the issue and impact when exploited.
- Steps to reproduce or a proof of concept.

The more information you provide, the faster we will be able to reproduce the issue and address your concerns more effectively.
