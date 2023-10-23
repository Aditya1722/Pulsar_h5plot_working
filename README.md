# Pulsar_h5plot_working

* Reads the h5 file
* store the dm_time & freq_time values in form of array
* In freq time one extra thing it stores the columns from back and then transpose it and then store it (probably because of some axis issue)
* Replacing every nan value by 0 .
* Taking median and subtracting from every value
* Normalising
* calculating and adjusting length of time samples depending on the
* reading the file attributes and storing their values in a single list
* code to write the attributes beside the plot
* clipping of data for color map scaling
* Defining what to plot in what axis (subplots)
