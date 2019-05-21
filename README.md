# Gaussian

Gaussian distribution class for calculating and visualizing a Gaussian distribution.

## Available Methods

- `calculate_mean()` 
    Function to calculate the mean of the data set.
- `calculate_stddev()` 
    Function to calculate the standard deviation of the data set.
- `read_data_file()`
    Function to read in data from a txt file. The txt file should have one number (float) per line. The numbers are stored in the data attribute. After reading in the file, the mean and standard deviation are calculated.
- `plot_histogram()`
    Function to output a histogram of the instance variable data.
- `pop_density()`
    Probability density function calculator for the gaussian distribution.
- `plot_histogram_pdf()`
    Function to plot the normalized histogram of the data and a plot of the probability density function along the same range.

## Available Operations

- Addition of Two Gaussian Deviation

## Representation Format

`"mean {}, standard deviation {}".format(self.mean, self.stdev)`