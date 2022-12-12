<h1>UNSW Science Extension 2019 - Marine Heatwaves</h1>

Notebooks and data to investigate marine heatwave (MHW) statistics, change, drivers and impacts.

<h2>Notebooks</h2>

- **Python and Statistics Introduction** 
  * Basic introduction to python, jupyter notebooks and statistical functions (dual tutorial for climate change and MHW student groups)
- **Demo 1 - Marine Heatwave Introduction** 
  * Read, plot and analyse data output from [MHW tracker](http://www.marineheatwaves.org/tracker.html)
- **Demo 2 - Marine Heatwave Drivers** 
  * Investigate the MHW drivers e.g., the role of El Niño–Southern Oscillation driving MHWs off the coast of Western Australia
- **Demo 3 - Marine Heatwave Impacts** 
  * Investigates MHW impacts on coral bleaching & lobster count
- **Demo 4 - Marine Heatwaves and Climate Change** 
  * Investigate changes in MHW metrics over time
- **Marine Heatwaves and Coral Bleaching** 
  * Investigates MHW impacts on coral bleaching using NOAA degree heating week (DHW) data
- **Marine Heatwaves and Lobster Catch** 
  * Investigates MHW biological impacts using statistical tests and plots (e.g., using lobster count/size)
- **Create Nino3.4 and ONI index files.ipynb** 
  * Calculate the Oceanic Niño Index (ONI) from NOAA OISST satellite data

<h2>Setup</h2>

The marine heatwaves project will use the Python language to analyse satellite and marine data. To run Python code, we need a text/code editor to write it in! We will use Anaconda’s Jupyter notebook for this (instructions below). To help familiarise yourself, we recommend that you install Anaconda and practice the given python tutorials using Jupyter notebook before the summer school. We also highly recommend bringing a laptop with you to the summer school, in case you need any help with installation and so that you can pick up right where you left off when the summer school ends!

In case you don’t have access to a computer before the summer school or you are having installation issues, you can use a Google Collaboratory notebook. It is very similar to a Jupyter notebook, but it does not require any installation (although it does require a google account and has limited features). To open a notebook, go to https://colab.research.google.com/notebooks/welcome.ipynb, click File> New Python 3 notebook.

<h3>Installing Anaconda</h3>

To install Anaconda on your computer, you should follow the recommended installation instructions for Windows, macOS or Linux (depending on your operating system). We will go through the Windows installation here with some pictures.

1. Go to the Anaconda download page for:
  * Windows: https://www.anaconda.com/distribution/#windows
  * macOS: https://www.anaconda.com/distribution/#macos
  * Linux: https://www.anaconda.com/distribution/#linux
2. Download the Python 3.7 version by clicking the green download link (or the 64-bit Graphical Installer). The download may take a few minutes.
3. Double click the downloaded file (e.g. Anaconda3-2019.03-Windows-x86_64.exe in your Downloads folder) and click Next  
4. Read the licensing terms and click “I Agree"
5. Select an install for “Just Me"
6. Select a destination folder (e.g. C:\Users\YourName\Anaconda3) and click Next
7. Check the box “Register Anaconda As my default Python 3.7” and click Next

<h3>Installing Python packages</h3>

Now there are a few Python packages that you will need to install manually for this project. Here is how to install them using Anaconda Prompt (or just the terminal if you’re using Linux).

1. Open Anaconda Prompt (likely in your recently added section of the start menu)
2. Type `conda install -c conda-forge xarray dask netCDF4 bottleneck cartopy` and press enter
3. Type `y` and press enter

Optional:

4. Type: `conda install pydrive`
5. Type `y` and press enter
6. Type: `conda install -c conda-forge google-api-python-client`

<h3>Jupyter Notebook</h3>

There are a few ways to open Jupyter Notebook in your default web browser:
  - Open Jupyter Notebook from your start menu,
  - Open Anaconda Prompt and type: `jupyter-notebook`, or
  - Open Anaconda Navigator, find Notebook and click Launch

<h2>Author</h2>

Created by Annette Stellema, Climate Change Research Centre, UNSW, Australia and ARC Centre of Excellence for Climate Extremes.
Lesson plans and notes are available upon request (a.stellema@unsw.edu.au).

<h2>Acknowledgements</h2>

Many thanks to all the support from Angela Maharaj, Ian McAdam, Sanaa Hobeichi and Rishav Goyal, the University of New South Wales, Australia and the ARC Centre of Excellence for Climate Extremes.
