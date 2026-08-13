Medical student and student researcher in Moscow working at the intersection of
blood-brain barrier biology, neuropharmacology, cheminformatics, and biomedical
machine learning.

My current work focuses on reproducible computational approaches to CNS drug
discovery, particularly uncertainty-aware prediction of small-molecule
blood-brain barrier penetration and the connection between computational
predictions and subsequent experimental research.

[![GitHub](https://img.shields.io/badge/GitHub-learning2think-181717?style=flat&logo=github)](https://github.com/learning2think)
[![Email](https://img.shields.io/badge/Email-contact-D14836?style=flat&logo=gmail)](mailto:good.bqw@gmail.com)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0007--2325--4678-A6CE39?style=flat&logo=orcid)](https://orcid.org/0009-0007-2325-4678)

---

## Research Interests

- Blood-brain barrier biology and the neurovascular unit
- Neuropharmacology and CNS drug discovery
- Cheminformatics and molecular machine learning
- Uncertainty quantification and selective prediction
- PK/PBPK and mechanistic modeling
- Reproducible biomedical research
- Computational neuroscience and computational psychiatry

---

## Current Research

### In Silico BBB

I am developing In Silico BBB, an open research software platform for early
computational assessment of small-molecule blood-brain barrier penetration,
uncertainty analysis, mechanistic modeling, and planning of subsequent research.

The project currently includes:

- BBB+/BBB- classification and exploratory quantitative total-logBB prediction
- scaffold-based and retrospective temporal validation
- applicability-domain and structural-support assessment
- calibration, bootstrap analysis, conformal prediction, and selective prediction
- molecular descriptors and structural similarity analysis
- research-oriented transport and reduced PBPK simulations
- reproducible research workflows with explicit separation of biological endpoints
- Python package, CLI, REST API, Python SDK, PostgreSQL-backed project storage,
  web client, and desktop client

In retrospective temporal evaluation within B3DB (n = 1,580), a frozen selective
BBB policy achieved 60.76% coverage and 9.27% selective risk, compared with
22.09% risk at full coverage.

These results are retrospective and internal to B3DB; they are **not independent
external, prospective, clinical, or regulatory validation**.

The current scientific question is whether this reduction in risk persists when
the unchanged policy is evaluated on independently curated external data.

Manuscript in preparation.

### BBB Permeability Benchmark

A reproducible molecular ML benchmark exploring how chemically structured
train/test separation affects apparent BBB-classification performance.

The project compares conventional and chemistry-aware validation strategies and
examines discrimination, calibration, and chemical-space overlap.

[Repository](https://github.com/learning2think/bbb-permeability)

---

## Publication

Belchiuk M. P. et al.  
*Blood-Brain Barrier as a Physiological and Toxicological System of Brain
Protection: Structural and Functional Organization, Transport Mechanisms,
and the Significance of Dysfunction in CNS Diseases.*

Medicine in Kuzbass, 2026.  
DOI: 10.24412/2687-0053-2026-2-8-18

---

## Technical Stack

Scientific Python: Python · NumPy · pandas · scikit-learn  
Cheminformatics: RDKit · molecular descriptors · fingerprints · scaffold analysis  
ML: classification · calibration · bootstrap validation · conformal prediction · selective prediction  
Modeling: PK/PBPK · compartmental models · ODE-based simulation · sensitivity analysis  
Software: FastAPI · PostgreSQL · REST APIs · Python SDK · CLI · Git · pytest  
Additional exposure: PyTorch · Next.js · Tauri

---

## Current Goals

1. Independently evaluate the frozen selective BBB policy on externally curated data.
2. Prepare the first In Silico BBB research manuscript and software paper.
3. Connect computational BBB modeling with experimental neuropharmacology.
4. Develop stronger foundations in neuroscience and computational neuroscience.
5. Gain research experience in an international laboratory.

---

I am particularly interested in research environments where computational models
are treated as tools for generating testable biological hypotheses rather than
as substitutes for experimental evidence.
