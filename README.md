- *Container Documentation for Sqlite3**

Enterprise-ready SQLite3 container image providing a self-contained, serverless, zero-configuration, transactional SQL database engine. Optimized for embedded systems, application testing, and lightweight database needs with ACID compliance and high reliability.

- *Key Features**
Core capabilities and strengths of this container

- Zero-configuration, serverless database engine
- ACID-compliant transactions
- Security-hardened base configuration
- Multi-architecture support

- *Common Use Cases**
Typical scenarios where this container excels

- Embedded database applications
- Application testing and development
- Local data storage and caching
- Lightweight database solutions

- *Pull Latest Image**
Download the container image from the registry

```bash
docker pull cleanstart/sqlite3:latest
```

```bash
docker pull cleanstart/sqlite3:latest-dev
```

- *Basic Run**
Run the container with basic configuration

```bash
docker run -it --name sqlite3-test cleanstart/sqlite3:latest-dev
```

- *Multi-Platform Images**

```bash
docker pull --platform linux/amd64 cleanstart/sqlite3:latest
docker pull --platform linux/arm64 cleanstart/sqlite3:latest
```

- *

###

## Resources

- **Official Documentation:** https://www.sqlite.org/docs.html
- **Provenance / SBOM / Signature:** https://images.cleanstart.com/images/sqlite3
- **Docker Hub:** https://hub.docker.com/r/cleanstart/sqlite3
- **CleanStart All Images:** https://images.cleanstart.com
- **CleanStart Community Images:** https://hub.docker.com/u/cleanstart

### Vulnerability Disclaimer

CleanStart offers Docker images that include third-party open-source libraries and packages maintained by independent contributors. While CleanStart maintains these images and applies industry-standard security practices, it cannot guarantee the security or integrity of upstream components beyond its control.

Users acknowledge and agree that open-source software may contain undiscovered vulnerabilities or introduce new risks through updates. CleanStart shall not be liable for security issues originating from third-party libraries, including but not limited to zero-day exploits, supply chain attacks, or contributor-introduced risks.

Security remains a shared responsibility: CleanStart provides updated images and guidance where possible, while users are responsible for evaluating deployments and implementing appropriate controls.
