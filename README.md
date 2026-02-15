# EconoGNN

**A Graph Neural Network Framework for Temporal Economic Resilience Insights**

-Early Warning Systems for the Global Economy: Leveraging Temporal Graph Neural Networks to Safeguard Regional Resilience

[![Published in PLOS ONE](https://img.shields.io/badge/Published-PLOS%20ONE-blue)](https://doi.org/10.1371/journal.pone.0343683)

This repository contains the code and processed datasets accompanying the paper published in [PLOS ONE](https://doi.org/10.1371/journal.pone.0343683).

## Overview

EconoGNN integrates complexity theory, economic modeling, and machine learning to predict and explain regional economic resilience across 183 countries over 25 years. The framework combines over 81 million trade records and 500,000 macroeconomic observations, adopting an official resilience metric from the World Bank.

### Key Results

- **F1-score:** 0.750 (GConvGRU architecture)
- **AUC-ROC:** 0.792
- **PR-AUC:** 0.757
- Robust performance across recovery thresholds (F1 range: 0.730–0.771)
- GNNExplainer validation: Fidelity+ = 0.827, Characterization = 0.913

## Data Sources

The raw datasets used in this study are publicly available:

| Source | Description | URL |
|--------|-------------|-----|
| UN COMTRADE | International trade records (81M+ records) | https://comtradeplus.un.org/TradeFlow |
| Penn World Table | Macroeconomic indicators (500K+ observations) | https://www.rug.nl/ggdc/productivity/pwt/?lang=en |
| Resource Trade Earth | Trade network visualization and data | https://resourcetrade.earth/ |

## Repository Structure

```
EconoGNN/
├── README.md
├── data/                  # Processed datasets
│   ├── trade/             # COMTRADE processed trade networks
│   └── macro/             # PWT macroeconomic features
├── src/                   # Source code
│   ├── labeling/          # Resilience labeling algorithms
│   ├── models/            # GNN and baseline model implementations
│   ├── explainability/    # GNNExplainer analysis
│   └── utils/             # Data processing and helper functions
├── configs/               # Model configurations and hyperparameters
├── notebooks/             # Exploratory and reproducibility notebooks
└── results/               # Pre-computed results and figures
```

> **Note:** This repository is being organized for public release. Full code and processed datasets will be uploaded shortly.

## Requirements

*To be documented upon full release.*

## Usage

*To be documented upon full release.*

## Citation

If you use this work, please cite:

```bibtex
@article{araujo2025econognn,
  title={EconoGNN: A Graph Neural Network Framework for Temporal Economic Resilience Insights},
  author={Araujo, Marcus and Rodrigues, Francisco and Parros, Elaine},
  journal={PLOS ONE},
  year={2025},
  doi={10.1371/journal.pone.0343683}
}
```

## Authors

- **[Marcus Araujo](https://linkedin.com/in/YOUR-PROFILE)** — Global AI Manager, [dLocal](https://dlocal.com) (NASDAQ: DLO) | PhD Researcher, University of São Paulo (USP-ICMC) — marcus.santos.araujo@usp.br
- **Francisco Rodrigues** — University of São Paulo (USP)
- **Elaine Parros** — University of São Paulo (USP)

## License

*To be defined.*


This repository contains the code and processed datasets accompanying the paper published in [PLOS ONE](https://doi.org/10.1371/journal.pone.0343683).

## Overview

EconoGNN integrates complexity theory, economic modeling, and machine learning to predict and explain regional economic resilience across 183 countries over 25 years. The framework combines over 81 million trade records and 500,000 macroeconomic observations, adopting an official resilience metric from the World Bank.

### Key Results

- **F1-score:** 0.750 (GConvGRU architecture)
- **AUC-ROC:** 0.792
- **PR-AUC:** 0.757
- Robust performance across recovery thresholds (F1 range: 0.730–0.771)
- GNNExplainer validation: Fidelity+ = 0.827, Characterization = 0.913

## Data Sources

The raw datasets used in this study are publicly available:

| Source | Description | URL |
|--------|-------------|-----|
| UN COMTRADE | International trade records (81M+ records) | https://comtradeplus.un.org/TradeFlow |
| Penn World Table | Macroeconomic indicators (500K+ observations) | https://www.rug.nl/ggdc/productivity/pwt/?lang=en |
| Resource Trade Earth | Trade network visualization and data | https://resourcetrade.earth/ |

## Repository Structure

```
EconoGNN/
├── README.md
├── data/                  # Processed datasets
│   ├── trade/             # COMTRADE processed trade networks
│   └── macro/             # PWT macroeconomic features
├── src/                   # Source code
│   ├── labeling/          # Resilience labeling algorithms
│   ├── models/            # GNN and baseline model implementations
│   ├── explainability/    # GNNExplainer analysis
│   └── utils/             # Data processing and helper functions
├── configs/               # Model configurations and hyperparameters
├── notebooks/             # Exploratory and reproducibility notebooks
└── results/               # Pre-computed results and figures
```

> **Note:** This repository is being organized for public release. Full code and processed datasets will be uploaded shortly.

## Requirements

*To be documented upon full release.*

## Usage

*To be documented upon full release.*

## Citation

If you use this work, please cite:

```bibtex
@article{araujo2025econognn,
  title={EconoGNN: A Graph Neural Network Framework for Temporal Economic Resilience Insights},
  author={Araujo, Marcus and Rodrigues, Francisco and Parros, Elaine},
  journal={PLOS ONE},
  year={2025},
  doi={10.1371/journal.pone.0343683}
}
```

## Authors

- **Marcus Araujo** — University of São Paulo (USP) — marcus.santos.araujo@usp.br
- **Francisco Rodrigues** — University of São Paulo (USP)
- **Elaine Parros** — University of São Paulo (USP)

## License

*To be defined.*
