# MLDebugger 🔍

A local-first Python library for automated ML model diagnostics and debugging.

## What is MLDebugger?

MLDebugger helps data scientists debug machine learning models by automatically detecting common issues like overfitting, data leakage, class imbalance and feature correlation problems. 

**Save 20+ hours of debugging time. Add one line of code, get instant diagnosis.**

## Key Features:

- **100% Local** - Your data never leaves your machine
- **Jupyter Native** - Works seamlessly in notebooks
- **Instant Analysis** - Get diagnosis in 30 seconds
- **Educational** - Explains WHY issues occur, not just WHAT

## Quick Start
```python
import mldbg

# Train your model normally
model.fit(X_train, y_train)

# Add ONE line for instant diagnosis
mldbg.diagnose(model, X_train, y_train, X_val, y_val)
```

## What MLDebugger Detects

- **Data Leakage** - Features containing future information
- **Overfitting/Underfitting** - Learning curve analysis
- **Class Imbalance** - Skewed target distributions
- **Feature Correlation** - Multicollinearity issues
- **Model Complexity** - Over-parameterization detection

## Installation
```bash
pip install mldbg
```

*Note: Package not yet published. Currently in development.*

## Development Status

**Current Phase:** Week 1 - Project Setup & Core Foundation

### **Completed**
- Project structure setup
- Virtual environment configuration
- Dependencies installed
- GitHub repository initialized

### Coming Next
- Base analyzer architecture
- Learning curve analyzer
- Data leakage detector
- Class imbalance detector
- Feature correlation analyzer

## Target Users

- Data science students
- Junior data scientists
- Kaggle competitors
- Bootcamp graduates
- Anyone debugging ML models

## Architecture

MLDebugger uses a modular analyzer architecture:
- **Local-first design** - All analysis runs on the machine
- **Framework modular** - Currently Scikit-learn, PyTorch/TensorFlow support planned
- **Deterministic rules** - Reliable, explainable diagnostics

## 📊 Project Structure
```
MLDebugger/
├── src/mldbg/           # Main library code
│   ├── core/            # Base analyzer classes
│   ├── analyzers/       # Individual analyzers
│   ├── sklearn/         # Scikit-learn support
│   ├── utils/           # Helper functions
│   └── visualizations/  # Plotting utilities
├── tests/               # Unit tests
├── examples/            # Example notebooks
└── docs/                # Documentation
```

## Contributing

This project is currently in early development. Contributions, ideas, and feedback are welcome!

## Author

Rajdeep - [GitHub](https://github.com/RajdeepOfGithub)

## Development Timeline

- **Week 1-2:** Core foundation + Learning Curve Analyzer + Data Leakage Detector
- **Week 3-4:** Class Imbalance + Feature Correlation + Model Inspector
- **Week 5:** Report generation and visualization
- **Week 6:** Testing on real Kaggle notebooks
- **Week 7:** Documentation
- **Week 8:** PyPI release

---

*Built with ❤️ for the data science community*