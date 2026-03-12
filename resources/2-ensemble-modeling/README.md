# Direction 2: Ensemble Modeling

**Ensemble Modeling**

---

## 📖 Overview

Ensemble modeling integrates multiple modeling approaches to construct unified prediction frameworks, serving as the core component connecting data processing and reliability analysis.

## 📂 Sub-directions

### 2.1 Basic Modeling Methods
Regression models, classification models, traditional statistical modeling methods

### 2.2 Model Ensemble Methods
Ensemble learning, model fusion, multi-model collaboration

### 2.3 Foundation Model Library
Pre-trained models, model libraries, model standardization

### 2.4 Time Series Prediction Methods
Time series analysis, sequence modeling, dynamic system prediction

### 2.5 Deep Learning-Based Physics Field Modeling Methods
Physics-informed neural networks, deep learning surrogate models, hybrid modeling

---

## 📚 Related Papers

### Basic Modeling

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| Gaussian Processes for Machine Learning | Rasmussen, C. E. & Williams, C. K. I. | 2006 | MIT Press | [Book](http://www.gaussianprocess.org/gpml/) | - |
| Probabilistic Machine Learning: An Introduction | Murphy, K. P. | 2022 | MIT Press | [Website](https://probml.github.io/pml-book/) | [GitHub](https://github.com/probml/pml-book) |

### Model Ensemble

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| Ensemble Methods: Foundations and Algorithms | Zhou, Z.-H. | 2012 | Chapman & Hall/CRC | [Link](https://www.cs.ox.ac.uk/people/varun.kanade/mlss2014/mlss2014_zhou_ens.pdf) | - |
| Deep Ensembles: A Necessity for Training Physics-Informed Neural Networks | Pfade, M. et al. | 2024 | NeurIPS | [arXiv](https://arxiv.org/abs/2405.13291) | - |
| Deep Ensembles for Uncertainty Estimation | Fort, S. et al. | 2019 | NeurIPS | [arXiv](https://arxiv.org/abs/1812.05552) | [GitHub](https://github.com/google/edward2) |
| BatchEnsemble: An Alternative Approach to Efficient Ensemble and Lifelong Learning | Wen, Y. et al. | 2020 | ICLR | [arXiv](https://arxiv.org/abs/2002.06715) | [GitHub](https://github.com/google/edward2) |
| Bayesian Model Averaging and Ensemble Learning | Yao, Y. et al. | 2022 | Nature Machine Intelligence | [DOI](https://doi.org/10.1038/s42256-022-00485-0) | - |

### Time Series Prediction

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| Time-series forecasting with deep learning: a review | Lim, B. & Zohren, S. | 2021 | Phil. Trans. R. Soc. A | [DOI](https://doi.org/10.1098/rsta.2020.0209) | - |
| Temporal Fusion Transformer: Interpretable Multi-horizon Time Series Forecasting | Lim, B. et al. | 2021 | IJF | [arXiv](https://arxiv.org/abs/1912.09363) | [GitHub](https://github.com/google-research/google-research/tree/master/tft) |
| N-BEATS: Neural basis expansion analysis for interpretable time series forecasting | Oreshkin, B. N. et al. | 2020 | ICLR | [arXiv](https://arxiv.org/abs/1905.10437) | [GitHub](https://github.com/ServiceNow/N-BEATS) |
| Informer: Beyond Efficient Transformer for Long Sequence Time-Series Forecasting | Zhou, H. et al. | 2021 | AAAI | [arXiv](https://arxiv.org/abs/2012.07436) | [GitHub](https://github.com/zhouhaoyi/Informer2020) |
| Autoformer: Decomposition Transformers with Auto-Correlation for Long-Term Series Forecasting | Wu, H. et al. | 2021 | NeurIPS | [arXiv](https://arxiv.org/abs/2106.13008) | [GitHub](https://github.com/thuml/Autoformer) |

### Physics Field Modeling

| Full Title | Authors | Year | Venue | Paper Link | Code |
|------------|---------|------|-------|------------|------|
| Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear PDEs | Raissi, M., Perdikaris, P. & Karniadakis, G. E. | 2019 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2018.10.045) | [GitHub](https://github.com/maziarraissi/PINNs) |
| Deep Polynomial Chaos: An approximation theory approach | Zhang, D., Lu, L., Guo, L. & Karniadakis, G. E. | 2021 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2021.110543) | - |
| Neural network enhanced polynomial chaos method for uncertainty quantification | Zheng, X., Yao, W. & Chen, X. | 2024 | RESS | [DOI](https://doi.org/10.1016/j.ress.2024.110123) | [GitHub](https://github.com/Xiaohu-Zheng/Deep-Polynomial-Chaos-Neural-Network-Method) |
| Physics-informed neural networks for uncertainty quantification | Yang, L. et al. | 2021 | CMAME | [DOI](https://doi.org/10.1016/j.cma.2021.113743) | - |
| Deep learning for computational physics: A review | Beck, A. et al. | 2021 | JCP | [DOI](https://doi.org/10.1016/j.jcp.2021.110331) | - |
| Neural operators with local and nonlocal attention mechanisms for physics-informed learning | Li, Z. et al. | 2023 | JCP | [arXiv](https://arxiv.org/abs/2302.09561) | [GitHub](https://github.com/NeuralOperator) |
| Fourier Neural Operator for Parametric Partial Differential Equations | Li, Z. et al. | 2021 | ICLR | [arXiv](https://arxiv.org/abs/2010.08895) | [GitHub](https://github.com/zongyi-li/fourier_neural_operator) |
| DeepONet: Learning nonlinear operators for identifying differential equations based on the universal approximation theorem of operators | Lu, L. et al. | 2021 | Nature Machine Intelligence | [DOI](https://doi.org/10.1038/s42256-021-00302-5) | [GitHub](https://github.com/lululxvi/deeponet) |

---

## 🛠️ Related Tools

### Machine Learning Frameworks

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| scikit-learn | Python | Classical ML algorithms | [GitHub](https://github.com/scikit-learn/scikit-learn) |
| PyTorch | Python | Deep learning framework | [GitHub](https://github.com/pytorch/pytorch) |
| TensorFlow | Python | Deep learning framework | [GitHub](https://github.com/tensorflow/tensorflow) |

### Surrogate Models

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| SMT | Python | Surrogate Modeling Toolbox | [GitHub](https://github.com/SMTorg/smt) |
| DeepXDE | Python | Deep learning for differential equations | [GitHub](https://github.com/lululxvi/deepxde) |
| Deep-aPCE | Python | Adaptive PCE with neural network | [GitHub](https://github.com/Xiaohu-Zheng/Deep-aPCE) |

### Time Series Prediction

| Tool | Language | Description | Link |
|------|----------|-------------|------|
| statsmodels | Python | Statistical modeling | [GitHub](https://github.com/statsmodels/statsmodels) |
| prophet | Python | Time series forecasting | [GitHub](https://github.com/facebook/prophet) |
| NeuralForecast | Python | Neural forecasting models | [GitHub](https://github.com/Nixtla/neuralforecast) |

---

## 📊 Related Datasets

| Dataset | Description | Link |
|---------|-------------|------|
| Time series benchmarks | Standard forecasting benchmarks | [Monash Time Series Forecasting Archive](https://forecastingdata.org/) |

---

*Last Updated: March 2026*