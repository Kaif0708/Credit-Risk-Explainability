# Credit Risk Explainability: Explainable AI for Loan Approval  

## Overview  
This repository provides an open-source implementation of the research paper:  
**"An Explainable AI Framework for Credit Evaluation and Analysis"** (*Applied Soft Computing Journal, 2024*).  
📄 **Paper Link:** [Elsevier - Applied Soft Computing](https://www.sciencedirect.com/science/article/pii/S1568494624000814)

The project applies **Machine Learning (ML) and Explainable AI (XAI)** techniques to improve transparency in **credit risk assessment and loan approval decisions**. Using **Random Forest, SHAP, LIME, and Partial Dependency Plots (PDP)**, it explains why a loan is approved or rejected, helping financial institutions and borrowers understand decision-making processes.  

## Features  
- Implements **Logistic Regression, Decision Tree, and Random Forest** for credit risk evaluation.  
- Uses **LIME and SHAP** to provide both local and global explanations of model decisions.  
- **Partial Dependency Plots (PDP)** to visualize feature influence on predictions.  
- **Random Forest achieves 99.8% accuracy** in loan approval classification.  
- Open-source implementation with structured, modular, and well-documented code.  

## Repository Structure  
```
Credit Risk Explainability/
│── XAI_Credit_Evaluation.ipynb  # Google Colab notebook with full implementation
│── requirements.txt              # Dependencies list
│── README.md                     # Documentation
│── LICENSE                       # Open-source license
│── CITATION.md                   # Paper citation details
```

## Getting Started  

### Clone the Repository  
```bash
git clone https://github.com/your-username/Credit-Risk-Explainability.git
cd Credit-Risk-Explainability
```

### Install Dependencies  
```bash
pip install -r requirements.txt
```

### Open in Google Colab  
To run the notebook interactively, use the link below:  

[Open in Google Colab](https://colab.research.google.com/github/Kaif0708/Credit-Risk-Explainability/blob/main/XAI_Credit_Evaluation.ipynb)  

## Results
| Model            | Accuracy | Precision | Recall | F1-Score |
|-----------------|---------|----------|--------|---------|
| Logistic Regression | 0.980  | 0.980  | 0.980  | 0.980  |
| Decision Tree      | 0.997  | 0.996  | 0.995  | 0.997  |
| Random Forest | 0.998  | 0.997  | 0.997  | 0.998  |

### Explainability Results  
- **SHAP Explainer:** Provides both local and global explanations for feature importance.  
- **LIME Explainer:** Highlights feature contributions for individual predictions.  
- **PDP Plot:** Demonstrates the relationship between input features and loan approval decisions.  

## Citation  
If you use this repository in your work, please cite the original paper:  
```bibtex
@article{Nallakaruppan2024XAI,
  title={An Explainable AI framework for credit evaluation and analysis},
  author={M.K. Nallakaruppan, Balamurugan Balusamy, et al.},
  journal={Applied Soft Computing},
  year={2024},
  doi={10.1016/j.asoc.2024.111307}
}
```

## License  
This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.  

## Contributing  
Contributions are welcome. If you find issues or improvements, feel free to open an issue or submit a pull request.  

