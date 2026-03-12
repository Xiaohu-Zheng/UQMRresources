# UQMRsources

<div align="center">

**Uncertainty Quantification & Multiscale Reliability Analysis Resources**

*Papers, Tools, Datasets, and Learning Materials*

[![GitHub stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRsources?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMRsources/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/Xiaohu-Zheng/UQMRsources?style=flat-square)](https://github.com/Xiaohu-Zheng/UQMRsources/network/members)
[![License](https://img.shields.io/github/license/Xiaohu-Zheng/UQMRsources?style=flat-square)](LICENSE)

</div>

---

## 📖 Introduction

This project systematically organizes academic papers, open-source tools, datasets, and learning resources in the field of **Uncertainty Quantification and Multiscale Reliability Analysis**, covering the complete research chain from data processing to reliability-based design.

### 🎯 Research Directions

This project is organized along five research directions:

```
┌─────────────────────────────────────────────────────────────┐
│         Uncertainty Quantification & Multiscale Reliability  │
├─────────────────────────────────────────────────────────────┤
│                                                              │
│  ┌──────────────┐    ┌──────────────┐    ┌──────────────┐   │
│  │ 1. Data      │───▶│ 2. Ensemble  │───▶│ 3. Multiscale│   │
│  │ Processing   │    │ Modeling     │    │ Reliability  │   │
│  └──────────────┘    └──────────────┘    └──────────────┘   │
│         │                   │                   │            │
│         └───────────┬───────┴───────────────────┘            │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 4. Uncertainty   │                               │
│           │ Analysis (Core)  │                               │
│           └──────────────────┘                               │
│                     │                                        │
│                     ▼                                        │
│           ┌──────────────────┐                               │
│           │ 5. Uncertainty-  │                               │
│           │ Based Design     │                               │
│           └──────────────────┘                               │
│                                                              │
└─────────────────────────────────────────────────────────────┘
```

---

## 📂 Content Navigation

### 🔬 Five Research Directions

#### [Direction 1: Data Processing and Analysis](resources/1-data-processing/)

Data preprocessing, visualization, and correlation analysis methods

**Sub-directions:**
- Data preprocessing methods
- Data visualization methods
- Auto/cross-correlation analysis methods

**Integrated Content:**
- 📄 Papers: 17+ papers on preprocessing, visualization, and correlation analysis
- 🛠️ Tools: pandas, numpy, scipy, matplotlib, seaborn, plotly, bokeh, altair, statsmodels
- 📊 Datasets: Standard UQ benchmarks

---

#### [Direction 2: Ensemble Modeling](resources/2-ensemble-modeling/)

Unified prediction framework construction, integrating multiple modeling approaches

**Sub-directions:**
- Basic modeling methods
- Model ensemble methods
- Foundation model library
- Time series prediction methods
- Deep learning-based physics field modeling methods

**Integrated Content:**
- 📄 Papers: 20+ papers on Gaussian processes, ensembles, time series, and physics-informed methods
- 🛠️ Tools: scikit-learn, PyTorch, TensorFlow, SMT, DeepXDE, Deep-aPCE, prophet, NeuralForecast
- 📊 Datasets: Monash Time Series Forecasting Archive

---

#### [Direction 3: Multiscale Reliability](resources/3-multiscale-reliability/)

Reliability assessment of complex systems across different temporal and spatial scales

**Sub-directions:**
- Anomaly detection methods
- Bayesian compression modeling methods
- Fault diagnosis methods
- Remaining useful life prediction methods

**Integrated Content:**
- 📄 Papers: 23+ papers on anomaly detection, fault diagnosis, and RUL prediction
- 🛠️ Tools: PyOD, Alibi Detect, OpenSees, FERUM, UQMRLib
- 📊 Datasets: NASA Bearing, PHM Challenge, C-MAPSS, FEMTO Bearing

---

#### [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/) ⭐ Core

Core methods for uncertainty quantification and propagation

**Sub-directions:**
- Uncertainty calibration
- Uncertainty quantification in deep learning (model uncertainty, data uncertainty)
- Uncertainty fusion methods
- Polynomial chaos expansion (PCE) methods

**Integrated Content:**
- 📄 Papers: 35+ papers on calibration, deep learning UQ, and polynomial chaos expansion
- 🛠️ Tools: UQpy, OpenTURNS, ChaosPy, UQLab, Dakota, Uncertainty Toolbox, Bayesian Torch, Blitz, SALib
- 📊 Datasets: UQ Benchmark Problems, NASA UQ Challenge
- 🏷️ Author's Core Projects:
  - [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE)
  - [Deep-PCE-NN](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method)
  - [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR)

---

#### [Direction 5: Uncertainty-Based Design](resources/5-uncertainty-design/)

Reliability-driven engineering design optimization methods

**Sub-directions:**
- Generative design methods
- Generative robust optimization methods
- Generative reliability-based optimization methods

**Integrated Content:**
- 📄 Papers: 26+ papers on generative design, robust optimization, and RBDO
- 🛠️ Tools: pyomo, scipy.optimize, NLopt, Dakota, OpenSees, UQMRLib, GPyTorch
- 📊 Datasets: Design optimization benchmarks
- 🏷️ Author's Project: [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization)

---

### 📚 Shared Resources

| Resource | Description | Integrated Content |
|----------|-------------|-------------------|
| [**Books & Tutorials**](shared/books-tutorials.md) | Classic textbooks, online courses, video tutorials | UQ textbooks, deep learning books, online courses |
| [**Conferences & Journals**](shared/conferences-journals.md) | Core journals, major conferences, submission guides | RESS, JCP, NeurIPS, ICML, etc. |
| [**Research Groups**](shared/research-groups.md) | Global research institutions and academic communities | MIT, ETH, NUDT, Sandia, etc. |

---

## 🔍 Quick Index

### By Content Type

| Type | Count | Description |
|------|-------|-------------|
| 📄 Papers | **120+** | Core papers covering five directions (2021-2026 focused) |
| 🛠️ Tools | 30+ | Python/MATLAB/C++ open-source tools |
| 📊 Datasets | 10+ | Standard benchmark datasets |
| 📚 Books | 8+ | Classic textbooks and tutorials |
| 🎓 Conferences & Journals | 15+ | Core publication venues |

### By Direction

| Direction | Papers | Tools | Datasets |
|-----------|--------|-------|----------|
| Direction 1: Data Processing | 17+ | 9 | 1 |
| Direction 2: Ensemble Modeling | 20+ | 10 | 1 |
| Direction 3: Multiscale Reliability | 23+ | 5 | 4 |
| Direction 4: Uncertainty Analysis ⭐ | 35+ | 10 | 2 |
| Direction 5: Uncertainty-Based Design | 26+ | 7 | 1 |

### By Keywords

| Keyword | Related Direction | Integrated Papers |
|---------|-------------------|-------------------|
| Polynomial Chaos Expansion (PCE) | Direction 4 | 12 papers |
| Deep Learning Uncertainty | Direction 4 | 10 papers |
| Physics-Informed Neural Networks (PINN) | Direction 2 | 8 papers |
| Reliability-Based Design Optimization (RBDO) | Direction 5 | 9 papers |
| Remaining Useful Life (RUL) Prediction | Direction 3 | 8 papers |
| Anomaly Detection | Direction 3 | 8 papers |
| Time Series Forecasting | Direction 2 | 5 papers |
| Generative Design | Direction 5 | 8 papers |

---

## 🚀 Quick Start

### For Beginners

1. 📖 Read [Direction 4: Uncertainty Analysis](resources/4-uncertainty-analysis/) to understand core concepts
2. 🛠️ Use [UQpy](https://github.com/SURGroup/UQpy) or [ChaosPy](https://github.com/jonathf/chaospy) to start practicing
3. 📚 Refer to [Books & Tutorials](shared/books-tutorials.md) for in-depth learning

### For Researchers

1. 📰 Check [Conferences & Journals](shared/conferences-journals.md) for publication venues
2. 🔬 Browse [Research Groups](shared/research-groups.md) for collaboration opportunities
3. 🛠️ Explore open-source tools in each direction to accelerate research

---

## 🛠️ Core Open-Source Projects

Core open-source tools maintained by the project author:

| Project | Description | Direction | Stars |
|---------|-------------|-----------|-------|
| [Deep-aPCE](https://github.com/Xiaohu-Zheng/Deep-aPCE) | Deep learning enhanced adaptive polynomial chaos expansion | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-aPCE?style=flat-square) |
| [Deep-Polynomial-Chaos-Neural-Network-Method](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) | Polynomial chaos neural network method | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method?style=flat-square) |
| [Physics-informed-Deep-MC-QR](https://github.com/Xiaohu-Zheng/Physics-informed-Deep-MC-QR) | Physics-informed deep Monte Carlo quantile regression | Direction 4 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Physics-informed-Deep-MC-QR?style=flat-square) |
| [Binary-Compression-Algorithm](https://github.com/Xiaohu-Zheng/Binary-Compression-Algorithm) | Binary compression algorithm for satellite system reliability analysis | Direction 3 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/Binary-Compression-Algorithm?style=flat-square) |
| [UQMRLib](https://github.com/Xiaohu-Zheng/UQMRLib) | AI-enhanced uncertainty quantification and multiscale reliability library | All directions | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/UQMRLib?style=flat-square) |
| [missile-design-optimization](https://github.com/Xiaohu-Zheng/missile-design-optimization) | Missile design optimization | Direction 5 | ![Stars](https://img.shields.io/github/stars/Xiaohu-Zheng/missile-design-optimization?style=flat-square) |

---

## 🤝 Contributing

Contributions are welcome!

### How to Contribute

1. **Fork** this repository
2. **Add** papers, tools, or resources to the corresponding direction directory
3. **Submit** a Pull Request

### Contribution Guidelines

- Paper format: `| Full Title | Authors | Year | Venue | Paper Link | Code |`
- Tool format: `| Tool | Language | Description | Link |`
- Please ensure links are valid and categorization is accurate

---

## 📝 Citation

If you find this project helpful for your research, please consider citing:

```bibtex
@misc{uqmrsources,
  author = {Zheng, Xiaohu},
  title = {UQMRsources: A Curated Collection of Papers and Resources for Uncertainty Quantification and Multiscale Reliability Analysis},
  year = {2026},
  publisher = {GitHub},
  url = {https://github.com/Xiaohu-Zheng/UQMRsources}
}
```

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact

- **Author**: Xiaohu Zheng
- **Research Area**: Uncertainty Quantification and Multiscale Reliability Analysis
- **GitHub**: [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

---

<div align="center">

**⭐ If this project is helpful, please give it a Star!**

Made with ❤️ by [Xiaohu-Zheng](https://github.com/Xiaohu-Zheng)

</div>