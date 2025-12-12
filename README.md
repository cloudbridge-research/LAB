# CloudBridge Laboratory Reports

**Comprehensive laboratory and experimental reports supporting CloudBridge networking research and engineering decisions.**

Published by **АНО "Центр исследований и разработок сетевых технологий CloudBridge Research"** (Autonomous Non-profit Organization "CloudBridge Research Center for Network Technologies Research and Development")

---

## About CloudBridge Research Center

CloudBridge Research Center is an independent non-profit research organization dedicated to advancing network technologies through scientific research, open-source development, and educational initiatives.

### Our Mission

We are committed to:
- **Scientific Excellence**: Conducting fundamental and applied research in modern network protocols (QUIC, MASQUE, BGP Anycast)
- **Open Innovation**: Publishing all research results and code under open licenses (MIT, Apache 2.0, Creative Commons)
- **Education**: Collaborating with leading universities to develop courses, workshops, and training programs
- **Global Collaboration**: Partnering with international research institutions and participating in standardization processes (IETF, W3C, IEEE)

### Research Focus Areas

- **QUIC Protocol Optimization**: Performance improvements, congestion control (BBRv3), Forward Error Correction (FEC)
- **MASQUE Tunneling**: Relay scenarios, encapsulation overhead, end-to-end latency optimization
- **BGP Anycast Routing**: Optimization and scaling for distributed systems
- **Zero-Trust Network Architecture**: Formal security verification
- **ML-Enhanced Routing**: Predictive and adaptive optimization
- **Quantum-Safe Networks**: Post-quantum cryptography (PQC) and Quantum Key Distribution (QKD)
- **eBPF and XDP**: High-performance packet processing

### Legal Status

- **Organization Type**: Autonomous Non-profit Organization (АНО)
- **Registration**: In progress with the Federal Tax Service of Russia
- **Founder**: CloudBridge Technologies JSC
- **Director**: Maxim Lanies
- **Location**: Moscow, Russian Federation

---

## Directory Overview

* [Experimental\_QUIC\_Laboratory\_Research\_Report.md](REPORT/Experimental_QUIC_Laboratory_Research_Report.md "mention")
  * Foundational laboratory research on QUIC behavior under controlled conditions
  * Covers: testbed design, traffic models, latency/loss/congestion profiles, repeatability
* [Experimental\_QUIC\_Testing\_Report.md](REPORT/Experimental_QUIC_Testing_Report.md "mention")
  * Consolidated experimental outcomes across multiple QUIC scenarios
  * Covers: test matrix, KPIs, stability observations, operational recommendations
* [QUIC\_Laboratory\_Research\_Report.md](REPORT/QUIC_Laboratory_Research_Report.md "mention")
  * Baseline QUIC research focusing on protocol mechanics and transport tuning
  * Covers: handshake dynamics, congestion control variants, packet pacing
* [QUIC\_Performance\_Comparison\_Report.md](REPORT/QUIC_Performance_Comparison_Report.md "mention")
  * Comparative performance analysis of QUIC implementations and configurations
  * Covers: throughput vs. latency trade-offs, fairness, variability across runs
* [MASQUE\_Laboratory\_Research\_Report.md](REPORT/MASQUE_Laboratory_Research_Report.md "mention")
  * MASQUE tunneling research for relay scenarios and encapsulation overhead
  * Covers: tunnel setup, header overhead, CPU footprint, end-to-end latency
* [PHASE1\_PHASE3\_TESTING\_REPORT.md](REPORT/PHASE1_PHASE3_TESTING_REPORT.md "mention")
  * Phase 1–3 program summary with objectives, methods, and results
  * Covers: test objectives, controlled environment, pass/fail criteria, next steps

***

## How to Use

1. Start with Phase report ( [PHASE1\_PHASE3\_TESTING\_REPORT.md](REPORT/PHASE1_PHASE3_TESTING_REPORT.md "mention") ) to understand scope and objectives.
2. Use foundational QUIC reports to study protocol behavior and baselines.
3. Consult performance comparison for configuration decisions and trade-offs.
4. Review MASQUE report when evaluating tunneling options for relay scenarios.

***

## Reproducibility and Methodology

* Testbeds: hardware profiles, kernel versions, and network emulation details are documented in each report.
* Traffic Models: flows, durations, and distribution parameters are specified for repeatability.
* Metrics: definitions for latency percentiles, jitter, loss, throughput, and CPU usage are standardized across reports.
* Validation: each report includes verification steps and cross-checks where applicable.

---

## Contact Us

We welcome collaboration with researchers, students, universities, and organizations interested in network technologies.

### General Inquiries

- **Website**: [cloudbridge-research.ru](https://cloudbridge-research.ru)
- **Contact Form**: [cloudbridge-research.ru/contact](https://cloudbridge-research.ru/contact)
- **GitHub**: [github.com/cloudbridge-research](https://github.com/cloudbridge-research)

### Research Collaboration

Interested in collaborating on research projects or contributing to our work? Visit our [Research page](https://cloudbridge-research.ru/research) to explore current projects and opportunities.

### Educational Programs

Universities and educational institutions can learn about partnership opportunities on our [Education page](https://cloudbridge-research.ru/education).

### Open Source Contributions

All our projects are available on GitHub under open licenses. Visit our [Open Source page](https://cloudbridge-research.ru/open-source) to find projects you can contribute to.

### Response Time

We respond to all inquiries within 1-2 business days. For urgent matters, please indicate "URGENT" in your message subject.

---

## Partnerships

We collaborate with leading universities and organizations:

### Universities
- Lomonosov Moscow State University (MSU)
- Moscow Institute of Physics and Technology (MIPT)
- Higher School of Economics (HSE)
- Saint Petersburg State University (SPbSU)
- Moscow Power Engineering Institute (MPEI)

### Data Centers & Cloud Providers
- Yandex
- VK Cloud
- Rostelecom
- Other infrastructure providers

---

## Licensing

All laboratory reports in this repository are licensed under **Creative Commons Attribution 4.0 International (CC BY 4.0)**.

[![CC BY 4.0](https://licensebuttons.net/l/by/4.0/88x31.png)](https://creativecommons.org/licenses/by/4.0/)

### What this means:

**You are free to:**
- Share — copy and redistribute the material in any medium or format
- Adapt — remix, transform, and build upon the material for any purpose, even commercially

**Under the following terms:**
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made

### Other CloudBridge Research Center licenses:

- **Research Papers**: Creative Commons BY 4.0
- **Code & Libraries**: MIT, Apache 2.0, GPL 3.0
- **Educational Materials**: Creative Commons BY-SA 4.0

For full license details, see the [LICENSE](LICENSE) file in this repository.

---

## How to Cite

If you use our research in your work, please cite:

```
CloudBridge Research Center. (2025). [Report Title]. 
Retrieved from https://github.com/cloudbridge-research/LAB
```

For specific reports, please refer to the citation information included in each document.

---

**CloudBridge Research Center**  
*Independent Center of Excellence in Network Technologies and Distributed Systems*

Established: November 2025  
Location: Moscow, Russian Federation

