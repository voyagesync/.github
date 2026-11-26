# Security policy

## Reporting a vulnerability

Do not report vulnerabilities in public issues, discussions, or pull requests.

Report them privately through either channel:

- GitHub private vulnerability reporting: open the **Security** tab of this repository and choose **Report a vulnerability**.
- Email: **security@team.voyage**

Include the affected version or commit, steps to reproduce, and a proof of concept that demonstrates the impact. Reports without a reproduction cannot be triaged. If several people report the same issue, we credit the first valid report and treat later ones as duplicates. We credit reporters in the advisory unless you ask us not to.

## Scope

This policy covers the code, configuration, and documentation of the voyagesync repositories. A repository with its own `SECURITY.md` follows that file instead.

We are most interested in issues that affect the confidentiality or integrity of user data, including encryption, key handling, access control, and authentication.

## Out of scope

- Output from automated scanners that has not been checked by hand.
- Missing security headers, version banners, or other information disclosure without a demonstrated impact.
- Denial of service, including high-volume automated testing.
- Social engineering or phishing of maintainers or contributors.
- Issues in third-party software, unless Voyage's use of it makes them exploitable. Please report those upstream.

## Testing rules

Test only systems and data that you own or that are set up for testing. Do not access, modify, or keep other people's data. Do not degrade availability for others. If you reach data you should not see, stop, do not keep a copy, and report it to us.

## What to expect

| Step | Target |
| --- | --- |
| Acknowledgement of your report | within 3 working days |
| Initial assessment and severity | within 7 days |
| Fix for a vulnerability with CVSS 7.0 or higher | as fast as possible, with a release planned within 14 days |

We coordinate disclosure with you and publish a GitHub security advisory, with a CVE where appropriate, once a fix is available.

## Supported versions

| Version | Supported |
| --- | --- |
| latest release | yes |
| older releases | no |

Before 1.0, only the latest release receives security fixes.
