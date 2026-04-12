
## 👋 Welcome to McHughCyber

We build open-source tooling for the **cybersecurity** community, with a focus on [OpenCTI](https://www.opencti.io/) connectors that enrich threat intelligence platforms with vulnerability data.

---

### 🔧 Projects

| Repository | Description |
|---|---|
| [opencti-cve-org-connector](https://github.com/McHughCyber/opencti-cve-org-connector) | Imports the complete CVE dataset (300,000+ records) from the [CVE Program](https://cve.org/) into OpenCTI. Supports full and incremental (delta) updates, multi-version CVSS extraction (v2–v4.0), and creates AttackPattern, Software, and CourseOfAction entities with rich relationships. |
| [opencti-epss-api-import](https://github.com/McHughCyber/opencti-epss-api-import) | Fetches daily [EPSS](https://www.first.org/epss/) scores from FIRST.org and updates OpenCTI vulnerabilities with exploitation probability and percentile data, enabling risk-based prioritization of CVEs. |

### 🚀 Key Highlights

- **Production-ready** — Docker images, adaptive rate limiting, state management, and error recovery built in.
- **Comprehensive testing** — Unit, integration, and real-data test suites for each connector.
- **Supply-chain transparency** — SBOM generation, container attestation, and automated vulnerability scanning via CI/CD pipelines.
