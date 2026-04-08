# Project IMACE Security Policy

Project IMACE is an open research initiative. While it is not a production-grade software system, maintaining the integrity, safety, and reliability of its codebase, documentation, and infrastructure is essential.

This policy defines how to report, handle, and respond to security vulnerabilities and related issues.

---

## 1. Scope

This policy applies to:

- all repositories under the `project-imace` organization  
- code, scripts, and experimental systems  
- documentation and research artifacts  
- repository configurations, workflows, and templates  

---

## 2. Reporting Security Vulnerabilities

### Standard Reporting (Preferred)

All non-sensitive security issues should be reported via GitHub using the **Bug Report** issue template.

When submitting:

- clearly prefix the title with **[Security]**
- follow the full structure of the bug report template  
- provide complete and accurate information  

Example: `[Security]: exposed credential in config file`

---

### Sensitive or Critical Issues

If the issue involves:

- exposed credentials or secrets  
- access control vulnerabilities  
- infrastructure-level risks  
- any issue that should not be publicly disclosed  

**Do NOT create a public issue.**

Instead, report directly via email:

- **General Contact**: mail@imace.online  
- **Research Coordination**: research@imace.online  
- **Project Coordinator**: coordinator@imace.online  
- **Chief Research Organiser (CRO)**: cro@imace.online  

---

## 3. Required Report Content

Whether reporting via issue or email, include:

- clear description of the vulnerability  
- affected repository, file, or component  
- steps to reproduce (if applicable)  
- potential impact and severity  
- supporting evidence (logs, screenshots, references)  

Incomplete or vague reports may not be actionable.

---

## 4. Types of Security Issues

### Code and Development
- vulnerabilities in code or scripts  
- unsafe execution paths or logic  
- insecure dependencies or integrations  

### Repository and Infrastructure
- exposed secrets, API keys, or credentials  
- permission or access control issues  
- misconfigured repository settings  

### Research Integrity
- unauthorized modification of research artifacts  
- manipulation or misrepresentation of data or results  

---

## 5. Responsible Disclosure

Contributors and reporters must:

- avoid public disclosure of sensitive issues before review  
- not exploit vulnerabilities beyond necessary demonstration  
- act in good faith and with responsible intent  

---

## 6. False Reporting and Malicious Activity

All reports must be made in good faith.

- false or misleading vulnerability claims may be treated as misconduct  
- deliberate attempts to introduce vulnerabilities into the codebase are strictly prohibited  
- intentional disruption, manipulation, or malicious contribution may lead to removal and escalation  

Such actions may result in formal action by the **Project IMACE Research Coordination Committee**, including potential legal review in cases of defamation or intentional harm.

---

## 7. Response Process

Project IMACE may:

- acknowledge receipt of reports  
- assess severity and scope  
- investigate and validate the issue  
- apply mitigation or corrective changes  
- update affected repositories or documentation  

As a research initiative, response timelines may vary.

---

## 8. Security Practices

Contributors are expected to:

- avoid committing secrets or sensitive data  
- review dependencies and configurations responsibly  
- document assumptions and limitations  
- maintain transparent and traceable changes  

---

## 9. Limitations

Project IMACE:

- is not a production-grade system  
- does not provide formal security guarantees or SLAs  
- does not assume liability for downstream usage  

Users must evaluate risks independently.

---

## 10. Summary

Project IMACE maintains a responsible security model based on:

- structured vulnerability reporting  
- responsible disclosure practices  
- integrity of research and codebase  
- accountability in contribution  

Security issues should be reported through the appropriate issue template or directly via email depending on sensitivity.
