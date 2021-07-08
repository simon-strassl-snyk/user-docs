# Disclose a vulnerability in an open source package

##  Disclose a vulnerability in an open source package

We at Snyk value the security community and believe that responsible disclosure of security vulnerabilities in open source packages helps us ensure the security and privacy of our users. We aim to provide a disclosure program for the security community by which you can report security issues found within managed open source code, within these languages: JavaScript, Java, Python, .NET, Go, Ruby and PHP.

Our responsible disclosure program aims to protect both the maintainer and the reported researcher: allowing maintainers and developers who use open source code to safely benefit from the discovery of these vulnerabilities prior to public disclosure, and crediting those researchers for their dedication.

The primary steps of our vulnerability disclosure program:

1. Any researcher/developer is invited to submit a [report]() regarding an open-source [security vulnerability](https://snyk.io/learn/security-vulnerability-exploits-threats/) with full details.
2. Our Snyk Security team validates the claims in the report and the severity of the associated risks. See [Triaging and validation]()for details.
3. We contact the owner or maintainer of the affected project, through multiple channels. See [Notification of the maintainer]() for details.
4. We relay the vulnerability details, advise on potential remediation, and collaborate on a public disclosure timeline with the maintainer. See [Remediation assistance]() for details.
5. We publicly disclose the vulnerability, giving full credit to the researcher. See [Public disclosure]() for details.
6. Snyk, as an officially recognized CVE Central Naming Authority \(CNA\), assigns a CVE to the vulnerability.

Vulnerability reports can be submitted by a researcher to report@snyk.io \(`<`[`report@snyk.io`](mailto:report@snyk.io)`>`\) directly, or via the Snyk Vulnerability Disclosure form: [https://snyk.io/vulnerability-disclosure/.](https://snyk.io/vulnerability-disclosure/) A submitted vulnerability report should contain the following details at a minimum:

* affected module
* relevant package manager/ecosystem
* vulnerability details
* steps to reproduce

Upon receipt of the report, Snyk validates and documents each reported vulnerability prior to notifying the maintainer.

Vulnerability disclosures sent to us via email can also be encrypted using the following PGP key:

```text
-----BEGIN PGP PUBLIC KEY BLOCK-----
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
V7JD6Yv5YR5K0Wf9MsSHZA==
=6Uz+
-----END PGP PUBLIC KEY BLOCK-----
```

Upon validation of a submitted vulnerability report, an analyst contacts the submitter \(via the contact details attached to the report\) to acknowledge receipt of the report, and to discuss vulnerability details as well as the severity we’ve assigned.

If the submitted vulnerability was already publicly disclosed and is simply missing from the Snyk vulnerability database \([https://snyk.io/vuln](https://snyk.io/vuln)\), then, once validated by Snyk, this vulnerability will be added and published in the database.

### Notification of the maintainer

Upon successful validation of a submitted vulnerability, Snyk contacts the maintainer of the package in order to provide vulnerability details necessary to begin any internal resolution process.

Snyk follows a 90-day responsible disclosure and remediation timeline, allowing the maintainer of the affected package to make sure a fix is available prior to the vulnerability being made public. Furthermore, an extension can be provided at the maintainer’s request, and depending on the severity of the disclosed vulnerability, Snyk is happy to wait for public disclosure until a patch is made available.

If the maintainer does not acknowledge or reply to the initial disclosure email within 30 business days of the original notification, Snyk retransmits the vulnerability details to the original point of contact of the affected package and at least one secondary contact, if a secondary contact is publicly available.

If an additional ten business days elapse with no response from the maintainer after the second notification \(a total of 40 business days\), vulnerability details are re-sent not only to the previous two contacts, but also to customers and other affected stakeholders at the discretion of Snyk. If the package maintainer does not respond to any of the three notification attempts within an additional ten business days following the third notification \(50 business days since the original notification\), or if the maintainer indicates they do not wish to coordinate disclosure, Snyk may elect to issue a public advisory with no further collaboration.

Maintainers should acknowledge receipt of notification with the following details:

* Confirmation that the vulnerability information has been received
* The scheduled timeline for investigation.
* A point of contact responsible for coordinating and tracking information on the issue from within their organization.
* An estimate as to when they expect to complete their initial investigation of the security issue as was provided in the notification.

Once the maintainer acknowledges receipt of notification, Snyk works with the maintainer to determine how to handle the security issue within ten business days. The following tasks are included in this phase:

* Snyk is happy to provide additional information to assist the maintainer in the development of a solution.
* The maintainer and Snyk collaborate together to time public disclosure and remediation of the issue.

As part of the public disclosure phase, Snyk :

* assigns a Common Vulnerabilities and Exposures \(CVE\) number for public tracking
* adds the vulnerability to its public vulnerability database \([https://snyk.io/vulnerability-disclosure/\)](https://snyk.io/vulnerability-disclosure/%29), providing information about the vulnerability and the related remediation

Public disclosure may be initiated either by completing the Remediation Assistance phase or through a process failure in prior phases.

During the Public Disclosure phase Snyk, and preferably the maintainer, disseminate information about the vulnerability and the remediation to the public. Snyk might disseminate information through public email lists, web pages or any other medium it deems appropriate to reach the intended audiences.
