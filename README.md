# Social Media Forensics & Disinformation Tracking

This project explores how **disinformation, fake news, deepfakes, and coordinated manipulation campaigns** operate across social media platforms, and how digital forensics and OSINT techniques can be used to investigate them responsibly.

The work focuses on identifying relevant digital evidence, analyzing real-world incidents, and understanding how investigators map online infrastructure while maintaining legal and ethical boundaries.

---

## Project Overview

Social media has become a primary channel for information exchange, but its openness has also enabled large-scale misuse. This project examines how malicious actors leverage fake accounts, bots, and manipulated media to influence public opinion, and how forensic investigators can trace such activity using structured methodologies.

The analysis is supported by real-world case studies, including election interference campaigns, deepfake incidents, and viral extremist content, highlighting the evolving challenges in social media forensics.

---

## Investigation Approach

The investigation followed a structured forensic workflow:

1. Identifying relevant **social media evidence types** (posts, comments, metadata, account artifacts and network relationships)
2. Performing **OSINT-based reconnaissance** to uncover related infrastructure
3. Correlating entities to identify potential coordination patterns
4. Preserving findings while considering **legal and ethical constraints**

---

## Tools & Techniques Used

- **SpiderFoot** – Automated OSINT collection and correlation  
- **Maltego** – Relationship and network visualization  
- **Sherlock** – Username enumeration across platforms  
- **Autopsy** – Digital forensics workflows and evidence handling concepts  

SpiderFoot was used as a core tool to demonstrate how automated OSINT can reveal relationships between domains, IP addresses, email reuse, SSL certificates, and internal links associated with potential disinformation infrastructure.

---

## OSINT Analysis Snapshots

### SpiderFoot Scan Summary
This view shows the distribution of discovered data types from the OSINT scan, helping identify which artifacts are most prevalent during reconnaissance.

![SpiderFoot Summary](assets/spiderfoot-summary.png)

---

### Discovered Infrastructure & Artifacts
The scan results highlight discovered domains, IP addresses, URLs, SSL certificates, and related metadata used to pivot further during analysis.

![SpiderFoot Results](assets/spiderfoot-results.png)

---

### Correlation & Risk Indicators
Correlation results help identify suspicious relationships such as cloned domains, reused identifiers, or blacklisted infrastructure.

![SpiderFoot Correlations](assets/spiderfoot-correlations.png)

---

### Relationship Graph Visualization
The graph view visualizes how domains, IPs, and other entities connect, making coordinated activity easier to reason about at scale.

![SpiderFoot Graph](assets/spiderfoot-graph.png)

---

## Key Learnings

- Disinformation campaigns rely heavily on **infrastructure reuse and coordination**, not just content
- OSINT tools are most effective when combined with **methodical analysis**, not isolated scans
- Evidence handling, documentation, and ethical awareness are as critical as technical tooling
- Visualization plays a major role in understanding complex online relationships

---

## Legal & Ethical Considerations

All analysis in this project is based on **publicly available information** and is conducted strictly for educational purposes. No private accounts were accessed, and no unauthorized data collection was performed. The project emphasizes responsible OSINT usage and compliance with applicable legal frameworks.

---

## Documentation

- Full project report: [`docs/report.pdf`](docs/report.pdf)
- References and sources: [`docs/references.md`](docs/references.md)

---

## Author

**Rohan Dalvi**  
Master’s in Cybersecurity  
University at Buffalo

---

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
