# Gregory_Rose

Here is the google drive necessary to access the raw data files. You'll need a Berkeley e-mail to access it.
https://drive.google.com/drive/folders/1ilw979EfilQgJuqcI_L_t5Z_CwALAK_U?usp=sharing

The "Simple Setup" document is a basic rundown of how to setup the equipment. If recreating this experiment, this setup can be followed, but users are encouraged to play with the settings to get the data they want.

Download the data file you wish to use (Cs-137, Co-60). Open the associated Jupyter Notebook. You will have to adjust the file location to wherever you have saved the data file, but after that, just run the notebook.

At the end of Cs-137 or Co-60 notebook, take note of the resolutions, FWHMs, and peaks.

The final data from the other two notebooks must be manually input in the "11.15_NE204_Lab1_energy_calibration" notebook to get the actual linear calibration.

If you wish to run a data set for a different isotope through these notebooks, you will need to manually adjust several parameters. Manual adjustments will have to be made to the cells in which the histogram of trapezoid peaks are generated, and the following cell in which these histograms are pared down to isolate peaks. 
