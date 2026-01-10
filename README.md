# Social Media Forensics & Disinformation Tracking

This project explores how **disinformation, fake news, deepfakes and coordinated manipulation campaigns** operate across social media platforms and how digital forensics and OSINT techniques can be used to investigate them responsibly.

The work focuses on identifying relevant digital evidence, analyzing real-world incidents and understanding how investigators map online infrastructure while maintaining legal and ethical boundaries.

---

## Project Overview

Social media has become a primary channel for information exchange but its openness has also enabled large-scale misuse. This project examines how malicious actors leverage fake accounts, bots and manipulated media to influence public opinion and how forensic investigators can trace such activity using structured methodologies.

The analysis is supported by real-world case studies, including election interference campaigns, deepfake incidents and viral extremist content, highlighting the evolving challenges in social media forensics.

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

SpiderFoot was used as a core tool to demonstrate how automated OSINT can reveal relationships between domains, IP addresses, email reuse, SSL certificates and internal links associated with potential disinformation infrastructure.

---

## OSINT Analysis Snapshots

### SpiderFoot Scan Summary
This view shows the distribution of discovered data types from the OSINT scan, helping identify which artifacts are most prevalent during reconnaissance.

<div align="center">
  <img width="985" height="488" alt="image" src="https://github.com/user-attachments/assets/85d5c33c-a4bc-4ca5-908c-3c78bd1aacb0" />
  <p><em>Fig 1. SpiderFoot Summary Results</em></p>
</div>

---

### Discovered Infrastructure & Artifacts
The scan results highlight discovered domains, IP addresses, URLs, SSL certificates and related metadata used to pivot further during analysis.

<div align="center">
  <img width="985" height="1088" alt="image" src="https://github.com/user-attachments/assets/e5dee919-6b98-416a-b29b-d0926b3bca3e" />
  <p><em>Fig 2. Results for the domain “victorlivestockfarm.co.za”</em></p>
</div>

---

### Correlation & Risk Indicators
Correlation results help identify suspicious relationships such as cloned domains, reused identifiers or blacklisted infrastructure.

<div align="center">
  <img width="985" height="197" alt="image" src="https://github.com/user-attachments/assets/fedc3d14-ee44-46de-854b-c72aa8a1d211" />
  <p><em>Fig 3. Correlations Results for the domain</em></p>
</div>

<div align="center">
  <img width="985" height="162" alt="image" src="https://github.com/user-attachments/assets/1979a3c5-fd04-4631-8a30-e68459e24dc6" />
  <p><em>Fig 4. Blacklisted Internet name of that domain</em></p>
</div>

---

### Relationship Graph Visualisation
The graph view visualizes how domains, IPs and other entities connect, making coordinated activity easier to reason about at scale.

<div align="center">
  <img width="985" height="555" alt="image" src="https://github.com/user-attachments/assets/52154612-d5f8-41ab-9349-d4baca6895a4" />
  <p><em>Fig 5. Graph result for the domain</em></p>
</div>
---

## Key Learnings

- Disinformation campaigns rely heavily on **infrastructure reuse and coordination**, not just content
- OSINT tools are most effective when combined with **methodical analysis**, not isolated scans
- Evidence handling, documentation, and ethical awareness are as critical as technical tooling
- Visualization plays a major role in understanding complex online relationships

---

## Legal & Ethical Considerations

All analysis in this project is based on **publicly available information** and is conducted strictly for educational purposes. No private accounts were accessed and no unauthorised data collection was performed. The project emphasizes responsible OSINT usage and compliance with applicable legal frameworks.

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
