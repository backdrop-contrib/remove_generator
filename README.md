Remove Generator META tag
=========================

Remove [Backdrop's](https://backdropcms.org/) Generator META tag to hinder web application fingerprinting.

```
<meta name="Generator" content="Backdrop CMS 1 (http://backdropcms.org)" />
```

The [OWASP web application fingerprinting guide](https://www.owasp.org/index.php/Fingerprint_Web_Application_%28OTG-INFO-009%29) discusses methods to identify web applications and their version to determine known vulnerabilities and appropriate exploits. In the remediation advice, OWASP recommends removing HTML code or anything else that explicitly points to a specific framework to be sure the framework cannot be detected by automatic scans.

One of the identifiers OWASP recommends removing is the META generator tags. This module provides that increment to improve the security posture of Backdrop installations.

No configuration required!

Current Maintainer
------------------

- David Norman (https://github.com/deekayen)

Maintainers
-----------

- Originally written for Drupal by Sean Dunaway (https://www.drupal.org/u/rump)
- Ported to Backdrop by David Norman (https://github.com/deekayen)

License
-------

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
