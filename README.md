# From Regulatory Text to Executable Compliance: A Case Study on European Judicial Workflows  

## Authors

Roberto Nai (1), Vittoria Margherita Sofia Trifiletti (1), Emilio Sulis (1) and Alessandro Gianola (2)

<sub>(1) University of Turin<br>(2) Universidade de Lisboa</sub>
---

## About the Paper

This repository accompanies the study:

**From Regulatory Text to Executable Compliance: A Case Study on European Judicial Workflows**

The work presents an empirical study on automated compliance analysis in European judicial processes. Regulatory procedural norms expressed in natural language are transformed into executable declarative constraints and evaluated against real-world judicial workflow data.

The case study is grounded in publicly available data from the Court of Justice of the European Union (CJEU), retrieved via the InfoCuria portal. The methodological pipeline combines:

- LLM-based rule extraction from regulatory texts  
- Declarative modelling using Declare  
- Deterministic conformance checking via Declare4Py  
- Rule impact ranking through leave-one-rule-out analysis  
- LLM agreement study on high-impact constraints  

The study demonstrates how regulatory text can be operationalised into machine-executable compliance specifications and evaluated in an institutional judicial setting.

---

## Figures

The `images` folder contains the high-resolution figures used in the paper.

---

## Related Repositories

The implementation is organised across two repositories:

### 1 - Data Collection & Event Log Construction  

Automated retrieval of InfoCuria case data and construction of the event log.  
*[https://github.com/roberto-nai/CURIA-DOWNLOADER](https://github.com/roberto-nai/CURIA-DOWNLOADER)*

### 2 - Compliance Analysis Pipeline  

Rule extraction, Declare model generation, deterministic conformance checking, impact ranking, and LLM disagreement study.  
*[https://github.com/roberto-nai/CURIA-CONFORMANCE](https://github.com/roberto-nai/CURIA-CONFORMANCE)*

---

## Contact

**Roberto Nai**   
Email: *roberto.nai@unito.it*  

---

## Citation

If you use this work, please cite the corresponding paper (citation details will be added upon publication).
