<div align="center">

```mermaid
mindmap
  root((Static Application </br> Security Testing))

    Frontend
      Lexer
      Parser
      AST

    Program Analysis
      CFG
      DFG
      Call Graph
      Symbol Table

    Analysis Methods
      Pattern Matching
      Data Flow
      Control Flow
      Taint Analysis
      Symbolic Execution

    Security Weaknesses
      SQL Injection
      XSS
      Command Injection
      Buffer Overflow
      Integer Overflow
      Hardcoded Secrets
      Race Conditions

    Compliance
      OWASP
      CWE
      CVE
      CERT

    Tools
      Semgrep
      CodeQL
      SonarQube
      Fortify
      Checkmarx
      Coverity

    DevSecOps
      IDE Scanning
      Pull Request Scanning
      CI CD Integration
      Build Gates
```

# **`Awesome`** Static Application Security Testing ([SAST](https://wikipedia.org/wiki/Static_application_security_testing)) [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)]()

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefense"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart LR

A[Source Files]

--> B[Parser]

--> C[AST]

--> D[Analysis Engine]

D --> E[Data Flow]

D --> F[Control Flow]

D --> G[Taint Analysis]

D --> H[Pattern Matching]

E --> I[Security Report]
F --> I
G --> I
H --> I

style A fill:#3498db,color:#fff
style D fill:#f1c40f,color:#000
style I fill:#e74c3c,color:#fff
```

## 📖 Contents
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

---
---

- [Opengrep](https://github.com/opengrep/opengrep) - Static code analysis engine to find security issues in code.
- [Semgrep](https://github.com/semgrep/semgrep) - Lightweight static analysis for many languages. Find bug variants with patterns that look like source code.


##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing
[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors
[Thanks goes to these contributors](https://github.com/cybersecurity-dev/awesome-sast/graphs/contributors)!

### License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

[🔼 Back to top](#awesome-static-application-security-testing-sast-)
