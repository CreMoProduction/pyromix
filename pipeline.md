# Pipline
The software provides a range of state-of-the-art methods for each step of the data processing pipeline. This modular approach allows you to customize your workflow and choose the best algorithm for your specific dataset and export the processing settings to a preset file. Tables below provides a concise overview of the available methods for each stage.

| Step                | Methods                                 |
|---------------------|-----------------------------------------|
| [Denoising](denoising.md)           | Gaussian, Moving average                |
| [Baseline correction](baseline_correction.md) | Polynomial fitting, Asymmetric least squares |
| [Sample alignment](sample_alignment.md)    | Correlation optimized warping (COW)          |
| [Deconvolution](deconvolution.md)       | Multivariate curve resolution altrnative regression (MCR-AR)              |
| [Annotation](annotation.md)       | Dot product, Pearson correlation, Neutral loss              |

<br><br>

| MCR-AR Options              | Methods                       |
|----------------------------|-------------------------------|
| Constraints                | Non-negativity least squares  |
| Initial guess              | Shifted Gaussian, PCA         |
| Optimal number of components| Mean Square Error, Eigen value|