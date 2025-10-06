# Technical Inforamtion
[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![Visual Studio](https://badgen.net/badge/icon/visualstudio?icon=visualstudio&label)](https://visualstudio.microsoft.com)
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/Naereen/StrapDown.js.svg)](https://GitHub.com/Naereen/StrapDown.js/releases/)
[![Windows](https://badgen.net/badge/icon/windows?icon=windows&label)](https://microsoft.com/windows/)
[![DOI:10.1007/978-3-319-76207-4_15](https://zenodo.org/badge/DOI/10.1007/978-3-319-76207-4_15.svg)](https://doi.org/10.1007/978-3-319-76207-4_15)
[![Citation Badge](https://api.juleskreuer.eu/citation-badge.php?doi=10.1126/science.1058040)](https://juleskreuer.eu/citation-badge/)
[![git](https://badgen.net/badge/icon/git?icon=git&label)](https://git-scm.com)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
![Static Badge](https://img.shields.io/badge/any_text-you_like-blue)
![Static Badge](https://img.shields.io/badge/just%20the%20message-8A2BE2)



| Feature                        | Details                                                                                                                                         |
|---------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------------|
| **Publications**                | PMID:32541957                                                                                                                                   |
| **Training datasets**           | Yes                                                                                                                                            |
| **Documentation and user guide**| Docsify powered on GitHub                                                                                                 |
| **Download / Web-service link** | Yes                                                                                                                                            |
| **Programming languages**       | Python                                                                                                                                             |
| **Platforms**                   | Windows                                                                                                                    |
| **Output formats**              | CSV                                                                                                                                            |
| **Input formats**               | netCDF     |
| **Web platform**                | No                                                                                                                                             |
| **Desktop client**              | Yes                                                                                                                                            |
| **CLI**                         | No                                                                                                                                            |
| **GUI**                         | Yes                                                                                                                                            |
| **License**                     | LGPL v3 (code) / CC-BY-SA (software)                                                                                                           |

# Data processing

Pyromix provides a range of state-of-the-art methods for each step of the data processing pipeline. This modular approach allows you to customize your workflow and choose the best algorithm for your specific dataset and export the processing settings to a preset file. Tables below provide a concise overview of the available methods for each stage.

| Step                                   | Methods                                                      |
|-----------------------------------------|--------------------------------------------------------------|
| [Denoising](denoising.md)               | Gaussian, Moving average                                     |
| [Baseline correction](baseline_correction.md) | Polynomial fitting, Asymmetric least squares            |
| [Sample alignment](sample_alignment.md) | Correlation optimized warping (COW)                          |
| [Deconvolution](deconvolution.md)       | Multivariate curve resolution alternative regression (MCR-AR) |
| [Annotation](annotation.md)             | Dot product, Pearson correlation, Neutral loss               |

<br><br>

| MCR-AR Options               | Methods                              |
|------------------------------|--------------------------------------|
| Constraints                  | Non-negativity least squares         |
| Initial guess                | Shifted Gaussian, PCA                |
| Optimal number of components | Mean Square Error, Eigen value        |
