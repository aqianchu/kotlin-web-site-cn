---
layout: default
title: Security
main_nav_id: security
---

# Kotlin 安全性

We do our best to make sure our products are free of security vulnerabilities. To reduce the risk of introducing a vulnerability,
you can follow these best practices: 

* Always use the latest Kotlin release. For security purposes, we sign our releases published on [Maven Central](https://search.maven.org/search?q=g:org.jetbrains.kotlin) 
with these PGP keys:

  | Key ID: | **kt-a@jetbrains.com** |
  | Fingerprint: | **2FBA 29D0 8D2E 25EE 84C1 32C3 0729 A0AF F899 9A87** |
  | Key size: | **RSA 3072** |

* Use the latest versions of your application’s dependencies. If you need to use a specific version of a dependency, 
periodically check if any new security vulnerabilities have been discovered. You can follow 
[the guidelines from GitHub](https://help.github.com/en/github/managing-security-vulnerabilities/managing-vulnerabilities-in-your-projects-dependencies) 
or browse known vulnerabilities in the [CVE base](https://cve.mitre.org/cgi-bin/cvekey.cgi?keyword=kotlin).

We are very eager and grateful to hear about any security issues you find. To report vulnerabilities that you discover in Kotlin,
please post a message directly to our [issue tracker](https://youtrack.jetbrains.com/issues/KT) (setting the issue type to ['Security Problem'](https://youtrack.jetbrains.com/issues/KT?q=%23%7BSecurity%20Problem%7D%20)) 
or send us an [email](mailto:security@jetbrains.org). For more information on how our responsible disclosure process works, 
please check the JetBrains [Coordinated Disclosure Policy](https://www.jetbrains.com/legal/terms/coordinated-disclosure.html).