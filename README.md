<p align="center">
  <img src="https://raw.githubusercontent.com/awesome-selfhosted/awesome-selfhosted/master/awesome-web.png" alt="Awesome Web AppSec" width="100" />
</p>

<h1 align="center">Awesome Web AppSec</h1>

<p align="center">
  <strong>A curated list of awesome Web Application Security (AppSec) tools, standards, hardening guides, labs, and best practices for developers and security engineers.</strong>
</p>

<p align="center">
  <a href="https://awesome.re">
    <img src="https://awesome.re/badge.svg" alt="Awesome">
  </a>
  <a href="LICENSE">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT">
  </a>
  <a href="CONTRIBUTING.md">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome">
  </a>
</p>

---

## 📋 Table of Contents

- [Standards & Checklists](#-standards--checklists)
- [SAST & Secret Scanners](#-sast--secret-scanners)
- [DAST & API Security](#-dast--api-security)
- [Hardening & Best Practices](#-hardening--best-practices)
- [Practice & Labs](#-practice--labs)
- [Cheatsheets & References](#-cheatsheets--references)
- [Contributing](#-contributing)
- [License](#-license)

---

## 📜 Standards & Checklists

- [OWASP Top 10](https://owasp.org/www-project-top-ten/) - The standard awareness document for developers and web application security covering the top 10 critical security risks.
- [OWASP ASVS](https://owasp.org/www-project-application-security-verification-standard/) - Application Security Verification Standard offering a framework of security requirements and controls.
- [OWASP WSTG](https://owasp.org/www-project-web-security-testing-guide/) - Comprehensive testing guide for assessing the security posture of web applications and services.
- [OWASP Cheat Sheet Series](https://cheatsheetseries.owasp.org/) - Concise developer-focused guides for secure architecture, coding, and vulnerability mitigation.
- [CWE Top 25](https://cwe.mitre.org/top25/) - List of the most frequent and impactful software weaknesses compiled annually by MITRE.
- [NIST SP 800-53](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final) - Comprehensive catalog of security and privacy controls for information systems and organizations.

---

## 🔍 SAST & Secret Scanners

- [Semgrep](https://semgrep.dev/) - Fast, open-source static analysis engine (SAST) for finding bugs and enforcing code standards using custom pattern rules.
- [TruffleHog](https://github.com/trufflesecurity/trufflehog) - High-performance secret scanner that searches git history and repositories for exposed API keys and credentials.
- [GitGuardian (ggshield)](https://github.com/GitGuardian/ggshield) - CLI tool to detect secrets, API keys, and sensitive tokens in your code before committing or in CI/CD pipelines.
- [SonarQube](https://www.sonarqube.org/) - Continuous code quality and security inspection platform to detect bugs, code smells, and vulnerabilities.
- [Brakeman](https://brakemanscanner.org/) - Static analysis security scanner designed specifically for Ruby on Rails applications.
- [GoSec](https://github.com/securego/gosec) - AST-based static analysis security scanner for inspecting Go source code for security flaws.
- [Bandit](https://github.com/PyCQA/bandit) - Tool designed to find common security issues in Python code by analyzing AST nodes.

---

## 🎯 DAST & API Security

- [OWASP ZAP](https://www.zaproxy.org/) - The world's most widely used open-source web application dynamic security scanner (DAST).
- [Caido](https://caido.io/) - Lightweight and modern web interception proxy designed as a fast alternative for security auditing.
- [Burp Suite Community Edition](https://portswigger.net/burp/communitydownload) - Industry-standard toolkit for manual web application security testing and HTTP/S traffic manipulation.
- [Nuclei](https://github.com/projectdiscovery/nuclei) - Extremely fast, template-driven vulnerability scanner powered by community-curated YAML rules.
- [Schemathesis](https://github.com/schemathesis/schemathesis) - Property-based testing tool that automatically generates test cases from OpenAPI and GraphQL specifications.
- [OWASP Amass](https://github.com/owasp-amass/amass) - Advanced tool for network mapping of attack surfaces and external asset discovery.

---

## 🛡️ Hardening & Best Practices

- [Helmet.js](https://helmetjs.github.io/) - Express middleware for Node.js that helps secure web apps by setting various HTTP security headers.
- [Secure Headers](https://github.com/twitter/secureheaders) - Library that automatically applies security-focused HTTP headers to web applications.
- [Mozilla Observatory](https://observatory.mozilla.org/) - Online suite to evaluate and audit HTTP security headers, TLS configurations, and CSP policies.
- [CSP Evaluator](https://csp-evaluator.withgoogle.com/) - Google-developed tool to validate and harden Content Security Policy (CSP) headers.
- [CORS Cheat Sheet](https://portswigger.net/web-security/cors) - Essential reference guide for implementing safe Cross-Origin Resource Sharing configurations.
- [SSL Labs Server Test](https://www.ssllabs.com/ssltest/) - Deep analysis of the SSL/TLS web server configuration and encryption strength.

---

## 🧪 Practice & Labs

- [PortSwigger Web Security Academy](https://portswigger.net/web-security) - Free interactive online training platform with hands-on labs covering modern web vulnerabilities.
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) - The most modern and sophisticated intentionally insecure web application for security training and CTFs.
- [DVWA (Damn Vulnerable Web App)](https://github.com/digininja/DVWA) - Intentionally vulnerable PHP/MySQL web application to test security tools and pentesting skills.
- [OWASP WebGoat](https://owasp.org/www-project-webgoat/) - Deliberately insecure environment designed to teach application security lessons in Java.
- [Hack The Box](https://www.hackthebox.com/) - Gamified cybersecurity platform featuring practical labs and vulnerable web machines.
- [TryHackMe](https://tryhackme.com/) - Hands-on cybersecurity training platform with guided rooms covering AppSec fundamentals.

---

## 📚 Cheatsheets & References

- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) - Comprehensive repository of useful payloads and bypass vectors for web security testing.
- [HackTricks](https://book.hacktricks.xyz/) - Encyclopedic knowledge base covering web pentesting, ethical hacking, and privilege escalation techniques.
- [SecLists](https://github.com/danielmiessler/SecLists) - The security tester's companion collection of wordlists for fuzzing, usernames, and discovery.
- [OWASP SAMM](https://owaspsamm.org/) - Software Assurance Maturity Model providing an effective framework to analyze and improve an AppSec program.

---

## 🤝 Contributing

Contributions are very welcome! Please review our [`CONTRIBUTING.md`](CONTRIBUTING.md) guide to learn how to submit new resources or improvements.

---

## 📄 License

This project is licensed under the MIT License - see the [`LICENSE`](LICENSE) file for details.
