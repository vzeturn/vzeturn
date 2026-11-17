# Hi, I'm vzeturn

I build business software for hospitality and retail in Vietnam, and the infrastructure it runs on.

Most of my day-to-day work is private: property management, point of sale, online check-in,
membership and loyalty, and e-invoice integrations with Vietnamese providers. Alongside it I run
the IT side: Active Directory, AWS operations and cost, networks, and security controls mapped
to ISO/IEC 27001.

What I publish here is the reusable part of that work: libraries and tools that solve a problem
I kept meeting on real projects.

## Featured projects

| Project | What it does | Stack |
|---|---|---|
| [SR-Vigil](https://github.com/vzeturn/SR-Vigil) | User-mode endpoint tool for Windows. Classifies every process and network connection as Safe, Unknown or Malicious, explains each verdict, and enforces policy through the Windows Filtering Platform. | Rust |
| [DevLibrary](https://github.com/vzeturn/DevLibrary) | Zero-dependency libraries for business software: JSON, money decimals, dates, logging, UUID, JWT, TOTP, QR, CLI, Vietnam helpers (amount in words, tax codes, VietQR). Tested against RFC and NIST vectors, builds for WebAssembly. | Rust |
| [MultiFactor.NET](https://github.com/vzeturn/MultiFactor.NET) | Pluggable multi-factor authentication: TOTP (RFC 6238), SQLite storage, AES-256-GCM secret protection, headless React hooks. | C#, .NET 10 |
| [NistPass.NET](https://github.com/vzeturn/NistPass.NET) | Password policy checks per NIST SP 800-63B-4, with breached-password lookup (k-anonymity) and ISO 27001 A.5.17 mapping. | C# |
| [FirewallLint.NET](https://github.com/vzeturn/FirewallLint.NET) | Finds shadowed, redundant, correlated and overly permissive firewall rules (Al-Shaer & Hamed). | C# |
| [SlaClock.NET](https://github.com/vzeturn/SlaClock.NET) | SLA due dates in business hours, ITIL 4 impact x urgency priority, pause/resume and breach detection. | C# |
| [RiskLedger.NET](https://github.com/vzeturn/RiskLedger.NET) | Risk scoring and treatment, Statement of Applicability for ISO/IEC 27001:2022 Annex A. | C# |
| [ActiveDirectory.Portal](https://github.com/vzeturn/ActiveDirectory.Portal) | Web portal for everyday AD administration: user lookup, unlock, password reset, group membership. | ASP.NET Core, React |
| [AwsOps.Console](https://github.com/vzeturn/AwsOps.Console) | Serverless AWS operations dashboard: infrastructure, backup and compliance, cost, scheduled actions, Entra ID sign-in. | TypeScript, Lambda, CloudFormation |
| [ZKTeco.Adms.Collector](https://github.com/vzeturn/ZKTeco.Adms.Collector) | Receives ZKTeco ADMS/PUSH attendance uploads into SQL Server, with an admin console. | Python, IIS |

## Tools I use

- **Languages:** C# / .NET, Rust, Go, TypeScript, Python, SQL
- **Front end:** React, Vite
- **Data:** SQL Server, PostgreSQL, SQLite
- **Platforms:** AWS (Lambda, ECS, RDS, CloudFormation), Windows Server and IIS, Docker, GitHub Actions
- **Domains:** hospitality and retail systems, Vietnamese e-invoicing, identity and MFA, IT operations, ISO/IEC 27001

## How I work

- Few dependencies. If a package is small and critical, I would rather own the code.
- Test against the standard. Implementations of RFCs and NIST specs ship with their official test vectors.
- Least privilege by default: separate database logins, scoped cloud permissions, no secrets in the repository.
- Write down why. Design decisions live next to the code.

## Contact

Open an issue on any repository above.
