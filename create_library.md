# Create your own library
Pyromix provides two convenient methods for creating your own custom .msp (NIST Mass Spectral Library) files, allowing you to build a library of compounds of interest from your own data for deeper further research. This is a powerful feature for researchers working with novel or specific compound sets.

## Method 1: Saving a Raw or Preprocessed Spectrum
This method is ideal for saving a mass spectrum directly from a specific point in your chromatogram. You can choose to save the raw spectrum or a version that has undergone preprocessing.
1.	Navigate to the **Data Overview** tab.
2.	In the **Mass spectrum overview** section, `right-click` on the spectrum you wish to save.
3.	In the context menu that appears, select `Save to MSP`.
This process will save the spectrum as a new .msp file. The saved spectrum will reflect the preprocessing steps you have selected in the File explorer tab (e.g., denoised, baseline-corrected, etc.), but it will not be a deconvoluted spectrum.

## Method 2: Saving a Deconvoluted Compound Spectrum
This method is recommended for saving the "pure" spectrum of a compound that has been isolated through the deconvolution process. This is the more accurate way to create a library, as the deconvoluted spectrum has reduced noise and signals from co-eluting compounds.
1.	Navigate to the **Deconvolution results** tab.
2.	`Right-click` on the mass spectrum of the desired compound.
3.	In the context menu, select `Save all` or `Save selected`, and then choose `MSP`.

> The key difference between these two methods lies in the quality of the saved spectrum. The first method saves a raw or preprocessed spectrum from a single point in time, which may still contain contributions from other compounds. The second method saves a deconvoluted spectrum, representing the pure chemical component that the MCR-AR algorithm has resolved, making it a much cleaner and more reliable entry for a custom spectral library.
