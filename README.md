# NCL-ipython-notebooks

NCL notebook examples using an NCL kernel for Jupyter notebooks. 

## Used Software

### NCL kernel

You need to install suvarchal's IPyNCL IPython notebook NCL kernel before you can start using the examples.
https://github.com/suvarchal/IPyNCL

### NCL

Install the newest version of NCL (current version is 6.5.0) from http://ncl.ucar.edu/Download/. I recommend to use conda to install the software.

### ImageMagicks

Some scripts use ImageMagicks *convert* program to cut off white space of the plot files. If you don't want to install it you have to uncomment the relevant code lines.

## Known Problems

The examples won't run correctly online in GitHub because the NCL kernel and ImageMagicks is not installed.
Download the notebooks, install the NCL kernel (and ImageMagicks) and run the notebooks on your local computer

	jupyter notebook

Sometimes you have to run all cells again when the plots won't be updated. If this won't help save the notebook, click on *'file -> close and halt'* and reopen the notebook.
