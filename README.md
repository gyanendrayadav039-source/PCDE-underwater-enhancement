PCDE: Underwater Image Enhancement
Overview

This repository contains the implementation and comparative evaluation of three decomposition models for underwater image enhancement using Piecewise Color Correction and Dual-Prior Optimized Contrast Enhancement.

Implemented Models
Model 1: Original decomposition model.
Model 2: Global-L2 spatial prior + L0 texture prior.
Model 3: Global-L2 spatial prior only.
Methodology
Piecewise Color Correction (PCC)
RGB to HSV conversion
Base and detail layer decomposition
ADMM optimization
Base layer enhancement
Detail layer enhancement
Final image reconstruction
Repository Structure
notebooks/ – Complete Jupyter Notebook implementation.
results/visualizations/ – Experimental visualizations.
results/comparison/ – Comparative results of the three models.
Experimental Results

Visual comparisons, decomposition outputs, convergence plots and model comparisons are available in the results directory.

Implementation

See the notebooks/ directory for the complete implementation.
