# How SVM Kernels Shape the Decision Boundary: A Visual Tutorial

**Author:** Riyanka Dhar  
**Student ID:** 23096051  

This repository contains the Jupyter notebook, figures, and PDF tutorial submitted for the Machine Learning assignment. The project demonstrates how different Support Vector Machine (SVM) kernels influence the decision boundary on non-linear data.

## Contents

- **SVM_Kernel_Analysis.ipynb**  
  Notebook that generates all figures and results used in the tutorial.

- **figures/**  
  Folder containing exported PNG figures (dataset visualisation, kernel comparisons, C and gamma effects, spiral dataset).

- **tutorial.pdf**  
  The written tutorial, submitted as part of the coursework (added once complete).

- **requirements.txt**  
  Python dependencies required to run the notebook.

- **LICENSE**  
  MIT License for this repository.

## How to Run

1. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
2. Launch Jupyter Notebook or JupyterLab:
   ```bash
   jupyter notebook SVM_Kernel_Analysis.ipynb
   ```
3. Run all cells to reproduce the figures used in the PDF tutorial.
## Description
**The notebook explores:**
- The limitations of a linear SVM on non-linear data
- The flexibility of polynomial kernels
- The effectiveness of the RBF (Gaussian) kernel
- How hyperparameters C and gamma alter model behaviour
- Performance on both standard synthetic data (make_moons) and a custom spiral dataset
The goal is to provide an intuitive understanding of how kernel choice affects the shape and complexity of decision boundaries in SVM classification.
## License
This project is distributed under the MIT License.
See the LICENSE file for details.
