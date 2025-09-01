# Tutorial: Plot the first gravitational wave
You want to learn how to plot the data of the first observed gravitational wave with python?

Then this tutorial is a great point to start.

You will learn
1. How to work with `numpy` arrays and plot with `matplotlib.pyplot`
2. How to load and plot gravitational wave data

The tutorial is written for people with high school math knowledge (e.g. you should now `sin(x)`), but does not require familiarity with `python` programming. 

### Installation
To get the code to run, you have to generate a virtual environment with `python` in your terminal, where we will install all packages required for this tutorial.
```
python -m venv venv-tutorial-plot-gw
```
You can activate the environment with 
```
source venv-tutorial-plot-gw/bin/activate
```
Now, you should see the name of the virtual environemnt at the beginning of your command line.

After navigating into the folder `tutorial_plot_the_first_gravitational_wave` via `cd tutorial_plot_the_first_gravitational_wave/`, you can install the packages with
```
pip install -r requirements.txt
```

### Starting the jupyter server
For the tutorial, we will be using jupyter notebooks on a jupyter server. You can start the jupyter server by typing
```
jupyter lab
```
in the terminal. This should print a link in the terminal and open a new tab in your internet browser.
There, you can click on the file you want to work on. 

### Running jupyter cells
To execute a jupyter cell, you click on the cell and press `shift` and `enter` simultaneously.

### (1) Notebook 1: Learn plotting
This preliminary [tutorial](https://github.com/annalena-k/tutorial_plot_the_first_gravitational_wave/blob/main/01_learn_plotting.ipynb) will introduce you to `numpy` arrays and how to visualize data with the package `matplotlib`. Here, we will use data that is easier to understand than gravitational wave data, for example temperature values measured over a day.

### (2) Notebook 2: Plot gravitational wave data
Since you now know how to visualize data, we will learn how to load data from a file, inspect the contents and plot the result.

I hope this is interesting for you. If you have ideas for extensions, write me an email.
Feel free to re-use the tutorials if you give proper attribution.
