# Application Security

Welcome to the **Application Security** section of the Cyber Security Architecture Series.

This wiki explains why application security matters, how vulnerabilities are introduced and found during software development, and how modern practices like **DevSecOps**, **secure coding**, **SAST**, **DAST**, and **SBOM** help reduce risk.

---

## One-minute summary

- Every real-world application has bugs.
- Some bugs become **security vulnerabilities**.
- Most vulnerabilities are introduced during **coding**, but often found later during **testing** or in **production**.
- Fixing vulnerabilities later is dramatically more expensive — sometimes estimated at up to **640x** the cost of fixing them early.
- Modern security uses a **shift-left** approach: security is applied from design through coding, testing, release, and operations.
- DevSecOps builds security into the entire software delivery process instead of adding it as a final checkpoint.

---

## Why application security matters

Applications are common attack targets because they process data, interact with users, integrate with other systems, and often handle sensitive business information.

If an application is compromised, attackers may be able to:

- steal data
- disrupt services
- install malware
- move laterally into other systems
- damage the organization’s reputation
- create compliance or legal exposure

The goal of application security is not to produce perfectly bug-free software. The goal is to **reduce risk early**, **find problems before release**, and **respond quickly** when new vulnerabilities appear.

---

## Video map

| Time | Topic | Wiki page |
|---:|---|---|
| 0:00 | Introduction to application security | [Application Security](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Application-Security.md) |
| 1:01 | Why vulnerabilities and cost matter | [SDLC & DevSecOps](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/SDLC-and-DevSecOps.md) |
| 2:20 | Traditional SDLC vs DevOps vs DevSecOps | [SDLC & DevSecOps](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/SDLC-and-DevSecOps.md) |
| 5:41 | Secure coding practices | [Secure Coding Practices](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Secure-Coding-Practices.md) |
| 10:45 | Vulnerability testing with SAST and DAST | [Vulnerability Testing](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Vulnerability-Testing.md) |
| 12:57 | AI/chatbot code generation and debugging risks | [AI & Chatbot Code Risks](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/AI-Chatbot-Code-Risks.md) |
| 15:30 | Summary and next topic: data security | [References](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/References.md) |

---

## Main wiki pages

| Page | What it covers |
|---|---|
| [Application Security](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Application-Security.md) | High-level overview and key concepts |
| [SDLC & DevSecOps](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/SDLC-and-DevSecOps.md) | Software development lifecycle, traditional models, DevOps, and DevSecOps |
| [Secure Coding Practices](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Secure-Coding-Practices.md) | Input validation, trusted libraries, OWASP, standard architectures, and SBOM |
| [Vulnerability Testing](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/Vulnerability-Testing.md) | SAST, DAST, and how testing fits into the development lifecycle |
| [AI & Chatbot Code Risks](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/AI-Chatbot-Code-Risks.md) | Using AI to generate or debug code, plus related security risks |
| [References](https://github.com/alishahbaz/Cybersecurity-Architecture-Application-Security/wiki/References.md) | Important resources and further learning |

---

## Application security map

```mermaid
flowchart LR
  A[Application Security] --> B[Why app security matters]
  A --> C[SDLC and DevSecOps]
  A --> D[Secure coding practices]
  A --> E[Vulnerability testing]
  A --> F[AI and chatbot code risks]

  B --> G[Reduce late-stage fix cost]
  C --> H[Shift left security]
  D --> I[OWASP, SBOM, trusted libraries]
  E --> J[SAST and DAST]
  F --> K[Review AI-generated code carefully]
