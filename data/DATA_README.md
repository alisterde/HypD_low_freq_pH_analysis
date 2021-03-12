<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.

This dataset is under a CC BY-SA and accompanies the publication:
Alister R. Dale-Evans, Martin J. Robinson, Henry O. Lloyd-Laney, David J. Gavaghan, Alan M. Bond, and Alison Parkin,
"A Voltammetric Perspective of Multi-Electron and Proton Transfer in Protein Redox Chemistry: Insights from Computational Analysis of HypD Fourier Transformed Alternating Current Voltammetry",
Frontiers in Chemistry, Theoretical and Computational Chemistry.

The folders contain PF-FTacV data for Escherichia coli HypD collected at the pH indicated in the folder name (4.0, 5.0, 6.0, 7.0, and 9.0). Three separate equivalent experiments are present at each pH, the experimental parameters associated with each data are given in "XXXX_cv_params.txt", with the raw unprocessed data named as "XXX_cv_current.txt", and two additional data files which have been processed in the following ways:
- A number of data points have been dropped from the end of the data, to ensure an integer number of periods using the frequency given in the associated parameter files.
- The data has been downsampled so that 217 and 543 measurements per period are present, this is indicated by the number at the end of the file name. These are included as the downsample to 217 measurements per period was fitted to in the associated work; while the downsample to 543 measurements per period was used for the published plots.
