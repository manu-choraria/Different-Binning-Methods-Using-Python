# Different-Binning-Methods-Using-Python
The following repository describe the implementation of different binning methods in python. I have taken the dataset in the form of a list and performed equal binning, binning by mean, binning by median and binning by boundaries using math and numpy libraries.

# What is binning?
Data binning, also known as discrete binning or bucketing, is a data pre-processing technique that is used to decrease data noise. The original data values are separated into small intervals known as bins, and then a general value produced for that bin replaces them. The general value can be a specific value, the mean of the values in the bin, the middle of the values in the bin, or the bin's boundary values.

# Types of Binning techniques
There are mainly four types of binning techniques;
1.Equal Bins: To replace all values in bin by specific value.
2.Bins by Mean: To replace all values in bin by mean value of the bins.
3.Bins by Median: To replace all values in bin by median value of the bins.
4.Bins by Boundaries: To replace values of bins as per the distance between point and minimum,maximum boundary value.

# Code Implementation
To implement the binning code I have taken the dataset in the form of list and then performed necessary operations. I have used following modules for code implementation:

1. Numpy: To initialize bins.
2. Math: To perform mathematical operations.

First we have initialized four bins having three zeros in each bin. Then we have performed the required four operations using the nested for loops.
