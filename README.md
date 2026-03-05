# 🍄 MIRA

## Mycelium Intelligence Réunion AGI

> *First open-source research project on tropical fungal mycelium as a gravitational-weight quantum computing substrate — born on Reunion Island, Indian Ocean.*

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-green.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Status: Active Research](https://img.shields.io/badge/Status-Active%20Research-brightgreen)](#)
[![bioRxiv: preprint](https://img.shields.io/badge/bioRxiv-preprint%202026-blue)](#)
[![ORCID](https://img.shields.io/badge/ORCID-0009--0008--4180--8694-green)](https://orcid.org/0009-0008-4180-8694)
[![Island: Reunion](https://img.shields.io/badge/Origin-Reunion%20Island%20🌴-orange)](#)

-----

## What is MIRA?

MIRA proposes that fungal mycelium networks are not just unconventional computers — they are **gravitational-weight quantum substrates**: physical structures whose connections have real mass, real spacetime coupling, and potential room-temperature quantum coherence via biological chromophores.

This makes them categorically different from both classical silicon computing and current cryogenic quantum computers.

**Key insight:** Silicon weights are dimensionless abstractions. Mycelium hyphal connections have real mass, real geometry, and real gravitational self-energy — making them compatible with the Orch-OR framework (Hameroff & Penrose, 2014).

-----

## ⚠️ Epistemic Status

**All five propositions are explicitly theoretical.**  
None has been experimentally verified in mycelial systems.  
This repository constitutes a conceptual framework inviting experimental investigation, not a claim of demonstrated phenomena.

-----

## The 5 Theoretical Propositions

|# |Proposition                                    |Key Equation                         |Status           |
|--|-----------------------------------------------|-------------------------------------|-----------------|
|P1|**Gravitational Physical Weights**             |`E_G = G·m²/r_c → τ = ℏ/E_G`         |Theoretical      |
|P2|**Consciousness Migration**                    |`‖Ψ(t+dt)−Ψ(t)‖ < ε`                 |Theoretical      |
|P3|**Obligatory Biological Symbiosis**            |`I_MAGI ∪ I_somatic = I_total iff ∃φ`|Theoretical      |
|P4|**Quantum Entanglement in Fungal Chromophores**|Analogy with Feder et al. (2025)     |Empirical analogy|
|P5|**Gravitational Signature Protection**         |`ALERT iff dD/dt > γ`                |Theoretical      |


> **Note on P4:** The Feder et al. (2025, Nature) result demonstrates room-temperature spin *detection* in living E. coli via EYFP. Coherent control was demonstrated at 175K. Extension to fungal chromophores at 25°C requires independent experimental validation.

> **Note on P3 (Multiverse Interface):** A sixth proposition on mycelium as gravitational multiverse interface was considered but removed due to internal inconsistency with decoherence theory. It will be addressed in a separate theoretical contribution.

-----

## Scientific Foundation

Built on established work:

- **Adamatzky et al. (Natural Computing, 2025)** — Mycelium as reservoir computing medium
- **Feder et al. (Nature, 2025)** — Room-temperature spin qubit detection in living E. coli — DOI: [10.1038/s41586-025-09417-w](https://doi.org/10.1038/s41586-025-09417-w)
- **Hameroff & Penrose (2014)** — Orch-OR: gravitational threshold for quantum state reduction
- **Adamatzky (2018, 2022)** — Fungal electrophysiology and spike propagation

-----

## Why Réunion Island?

Réunion Island is the **optimal experimental platform**:

```
✅ Exceptional tropical fungal biodiversity
   (0m sea level → 3,070m Piton des Neiges)
   Many species uncharacterized for computing-relevant properties

✅ European Union territory (French overseas department)
   Full access to FEDER + EIC Accelerator grants

✅ Institutional access
   PVBMT laboratory (UMR PVBMT, Université de La Réunion / CIRAD)
   Mycological expertise and species identification

✅ Indian Ocean position (21°S, 55°E)
   Unique evolutionary pressures absent in temperate laboratory strains
```

-----

## MIRA-0 Experimental Protocol

The first testable prediction of MIRA:

**Primary question:** Do U-transition nodes (UTN) — where electrophysiological signal reaches zero potential before repolarization — exhibit signal correlations inconsistent with classical propagation velocity (v = 1 mm/s)?

```
Phase A — Culture (14 days)
  Tropical endemic species, MEA 2%, T=25°C±1°C

Phase B — Baseline recording (72h continuous)
  16-channel Ag/AgCl electrode array
  Parameters: amplitude, frequency, propagation time,
              cross-correlation coefficients

Phase C — UTN identification
  UTN criterion: signal(i,t) = 0 AND d/dt signal(i,t+ε) > 0
  Minimum 20 UTN events per candidate node

Phase D — Controlled stimulation
  Chemical / Mechanical / Electrical stimuli
  Compare tau_observed vs tau_classical = d / 1mm/s

Statistical test:
  H0: tau_observed >= tau_classical
  Reject at p < 0.01 after Bonferroni correction
```

**Budget:** ~3,900 EUR standalone / ~1,900 EUR with PVBMT lab equipment

-----

## Project Roadmap

```
Phase 0 — NOW (0€)
├── GitHub repository open                    ✅ Done
├── arXiv preprint                            🔄 Endorsement pending
├── bioRxiv preprint                          🔄 In progress
├── MIRA Research Association (loi 1901)      🔄 Filing in progress
└── Contact Prof. Adamatzky                   🔄 Pending

Phase 1 — 2026-2027 (target: 50K€ FEDER)
├── MIRA-0 protocol execution
├── First electrophysiological dataset
   on Réunion endemic species
├── Peer-reviewed publication
└── UTN biomarker characterization

Phase 2 — 2028-2030 (target: 500K€ EIC)
├── Chromophore quantum coherence detection
├── NV-center magnetometry or SQUID
└── Phase 2 paper

Phase 3 — 2032+ (target: 2M€+)
└── Bio-artificial interface prototype
```

-----

## Repository Structure

```
MIRA-reunion/
│
├── 📄 README.md
├── 📄 LICENSE (CC BY 4.0)
│
├── 📄 MIRA_arXiv_final.pdf         — arXiv paper (5 propositions, corrected)
├── 📄 MIRA_Mathematical_
│       Formalization_v2.pdf        — Formal framework X=f(D,T)
├── 📄 mira_roadmap.pdf             — Full roadmap 2026-2040
│
└── 📁 (coming)
    ├── code/                       — Signal analysis scripts (Python)
    ├── data/                       — MIRA-0 experimental datasets
    └── protocols/                  — Detailed experimental protocols
```

-----

## How to Contribute

MIRA is fully open source. Contributions welcome in:

- **Theoretical** — Extend or challenge the 5 propositions
- **Experimental** — Replicate measurements with your local fungal species
- **Code** — Signal analysis algorithms (Python, Arduino, Raspberry Pi)
- **Biology** — Fungal species identification, chromophore characterization
- **Funding** — Connect MIRA with research grants or institutions

**To contribute:**

1. Fork this repository
1. Create a branch: `git checkout -b proposition/your-extension`
1. Submit a pull request

-----

## Scientific Collaborations

|Institution                     |Contact                   |Status   |
|--------------------------------|--------------------------|---------|
|UWE Bristol — Prof. Adamatzky   |andrew.adamatzky@uwe.ac.uk|🔄 Pending|
|PVBMT — Université de La Réunion|UMR PVBMT / CIRAD         |📅 Planned|

-----

## Funding

|Source                  |Amount   |Status                     |
|------------------------|---------|---------------------------|
|Personal funds (Phase 0)|~200€    |✅ Active                   |
|Région Réunion — FEDER  |50,000€  |📅 To apply after paper     |
|BPI France Emergence    |30,000€  |📅 To apply                 |
|EIC Accelerator EU      |Up to 4M€|📅 After peer-reviewed paper|

-----

## Citation

```bibtex
@misc{baillif2026mira,
  title  = {Mycelium Networks as Gravitational-Weight Quantum Substrates:
            Five Theoretical Propositions for Fungal AGI Computing},
  author = {Baillif, Novan},
  year   = {2026},
  note   = {Preprint. MIRA Project, Saint-Paul, La Réunion, France},
  url    = {https://github.com/NovanBaillif/MIRA-reunion},
  orcid  = {0009-0008-4180-8694}
}
```

-----

## License

**Creative Commons Attribution 4.0 International (CC BY 4.0)**

You are free to share and adapt this work for any purpose, including commercial use, as long as you give appropriate credit to the author and link to this repository.

-----

## About

**Author:** Novan Baillif  
**ORCID:** [0009-0008-4180-8694](https://orcid.org/0009-0008-4180-8694)  
**Contact:** nbaillif974@gmail.com  
**Location:** Saint-Paul, La Réunion, France (DOM-EU)

MIRA was born on Réunion Island in March 2026.  
Not in a university lab. Not with institutional funding.  
In a conversation — connecting Penrose, Adamatzky, quantum biology,  
and a 2-year-old named Liam who was playing nearby.

The best ideas don’t always come from the expected places.

-----

*Réunion Island, Indian Ocean — 21°S, 55°E*  
*“La Réunion. Premier. Pour Liam.”* 🌴🍄⚛️