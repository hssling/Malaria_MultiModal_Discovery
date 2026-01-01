# Malaria Multi-Modal Drug Discovery Pipeline

[![CI](https://github.com/hssling/Malaria_MultiModal_Discovery/workflows/CI/badge.svg)](https://github.com/hssling/Malaria_MultiModal_Discovery/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🎯 Overview

Comprehensive 5-module drug discovery framework for **Malaria** integrating:

| Module | Focus | Weight |
|--------|-------|--------|
| **Pathogen-Directed** | Plasmodium targets | 25% |
| **Host-Directed** | Endothelium, inflammation | 25% |
| **Drug Repurposing** | Approved drugs | 20% |
| **Network Pharmacology** | Host-parasite PPI | 15% |
| **AI/ML Integration** | Ensemble scoring | 15% |

## 🔬 Key Findings

### Top Unified Targets

| Rank | Target | Type | Score |
|------|--------|------|-------|
| 1 | **TNF** | Host | 0.514 |
| 2 | **ANGPT2** | Host | 0.459 |
| 3 | **HMOX1** | Host | 0.450 |
| 4 | **HDP** | Plasmodium | 0.444 |
| 5 | **ATP4** | Plasmodium | 0.428 |

### Top Repurposing

| Drug | Mechanism | Score |
|------|-----------|-------|
| **Artesunate** | Heme alkylation | 0.975 |
| **ACT** | First-line | 0.967 |
| **Atorvastatin** | Endothelial HDT | 0.883 |

## 📁 Structure

```
Malaria_MultiModal_Discovery/
├── config/pipeline_config.yaml
├── data/unified_targets.csv
├── outputs/figures/ (8 figures)
└── manuscripts/
```

## 🚀 Quick Start

```bash
git clone https://github.com/hssling/Malaria_MultiModal_Discovery.git
cd Malaria_MultiModal_Discovery
pip install pandas numpy matplotlib seaborn
python run_pipeline.py
```

## 👤 Author

**Dr. Siddalingaiah H S** | SIMS Tumkur | hssling@yahoo.com

## 📄 License

MIT License
