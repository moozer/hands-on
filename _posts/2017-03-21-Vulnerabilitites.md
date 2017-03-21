---
layout: post
title:  "CVEs and vulnerabilities"
categories: sysadmin
---

1. Read up on CVEs ans CVSS

    Go [here](https://cve.mitre.org/about/) and [here](https://www.first.org/cvss)

1. Go to [https://www.debian.org/security/](https://www.debian.org/security/)

    to see the current security advisories related to debian

2. Select an advisory for a package you know

    E.g. [https://www.debian.org/security/2017/dsa-3811](dsa-3811) related to Wireshark

3. Read the information and notice the referenced CVEs

4. Click on one of the CVEs referenced

    E.g. [https://security-tracker.debian.org/tracker/CVE-2017-6473](CVE-2017-6473)

5. Notice

    a. Status is different depending on package version, and they are "fixed" in the security release

    b. Links to official CVE list at mitre.org

    c. Links to the apps specific mailing list

6. Go to the CVE description at mitre.org

    E.g. [https://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2017-6473](CVE-2017-6473)

7. Continue to NVD for the CVSS

    E.g. [https://web.nvd.nist.gov/view/vuln/detail?vulnId=CVE-2017-6473](CVE-2017-6473)

8. On the Debian page, note which version was affected and the application specific number for the vulnerability

    E.g. for CVE-2017-6473, it is [wireshark bug 13431](https://bugs.wireshark.org/bugzilla/show_bug.cgi?id=13431) and it is fixed in version 2.2.5

9. Find the release notes or the changelog for the relevant application

    E.g. [Wireshar version 2.2.5 realease notes](https://www.wireshark.org/docs/relnotes/wireshark-2.2.5.html#_bug_fixes)

For gory details of vulnerabilities in general, see [full discloosure](http://seclists.org/fulldisclosure/) mailing list on [seclists.org](seclists.org)
