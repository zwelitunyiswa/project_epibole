# Wound Care Open Data Standard (WCODS)

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)

## Overview
The **Wound Care Open Data Standard (WCODS)** is a community-driven effort to create a shared, interoperable specification for documenting, exchanging, and analyzing wound care data.  
Our goal is to establish a transparent, flexible, and open framework that can be adopted by clinicians, researchers, payers, software vendors, and regulators to improve outcomes and accelerate innovation in wound care.

## Objectives
- Define a **common vocabulary** for wound care concepts (e.g., wound type, stage, location, size, healing trajectory).  
- Provide a **structured data model** for interoperability across electronic health records (EHRs), research databases, and registries.  
- Support both **clinical care workflows** (point of care documentation) and **research/analytics use cases** (real-world evidence, registries, payer reporting).  
- Ensure **open access** to the specification while maintaining flexibility for vendors and contributors.  

## Target File Formats
To ensure maximum interoperability and scalability, the WCODS specification will be implemented in:  
- **JSON** → human- and machine-readable format for interoperability, APIs, and lightweight data exchange.  
- **Parquet** → columnar, compressed format optimized for large-scale analytics, registries, and cloud storage.  

This dual-format approach allows easy adoption across both **clinical software systems** and **analytics pipelines**.  

## Why This Matters
Wound care data is often siloed, inconsistent, and difficult to compare across settings. By creating an open standard:
- Clinicians gain more consistent documentation tools.  
- Researchers gain better data for comparative effectiveness studies.  
- Payers and policymakers gain clearer insights into outcomes and costs.  
- Patients ultimately benefit from more effective, evidence-driven care.  

## Contributing
We welcome contributions from **clinicians, researchers, software developers, standards experts, and industry partners**.  
Please see [CONTRIBUTING.md](CONTRIBUTING.md) (to be created) for guidelines on:
- How to propose changes or extensions to the specification.  
- Coding/documentation standards.  
- Review and approval process.  

If you are new to GitHub collaboration, check out the [GitHub Getting Started Guide](https://docs.github.com/en/get-started/quickstart).  

## License
This project is licensed under the **Apache License 2.0**.  
You are free to use, modify, and distribute this project under the terms of the license. See [LICENSE](LICENSE) for details.

## Community & Governance
We intend to build a transparent governance model that balances **clinical expertise, technical standards, and real-world implementation needs**.  
Stay tuned for details on steering groups, working groups, and release schedules.  

## Roadmap (Draft)
- **v0.1 (Initial Draft):** Define core wound descriptors.  
- **v0.2:** Add patient-level metadata, treatment categories, and outcomes.  
- **v0.3:** Extend to support advanced analytics (risk adjustment, registries, payer reporting).  
- **v1.0:** Stable release for implementation in pilot systems.  

---

💡 If you’re interested in collaborating, please open an [issue](../../issues) or start a [discussion](../../discussions).  
