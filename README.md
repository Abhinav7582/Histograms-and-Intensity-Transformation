# Histograms-and-Intensity-Transformation

A histogram is a graphical representation that organizes a group of data points into user-specified ranges. Similar in appearance to a bar graph, the histogram condenses a data series into an easily interpreted visual by taking many data points and grouping them into logical ranges or bins.

Histograms are commonly used in statistics to demonstrate how many of a certain type of variable occurs within a specific range. For example, a census focused on the demography of a country may use a histogram to show how many people are between the ages of 0 - 10, 11 - 20, 21 - 30, 31 - 40, 41 - 50, etc. This histogram would look similar to the example below.

Histograms can be customized in several ways by the analyst. The first is to change the interval between buckets. In the above example, there are 5 buckets with an interval of ten. This could be changed, for example, to 10 buckets with an interval of 5 instead.

The other consideration is how to define the y-axis. The most basic label is to use the frequency of occurrences observed in the data, but one could also use percentage of total or density instead.


Intensity transformations are applied on images for contrast manipulation or image thresholding. These are in the spatial domain, i.e. they are performed directly on the pixels of the image at hand, as opposed to being performed on the Fourier transform of the image.

The following are commonly used intensity transformations:

Image Negatives (Linear)
Log Transformations
Power-Law (Gamma) Transformations
Piecewise-Linear Transformation Functions

Thresholding is used in image segmentation this means extracting objects from an image. Image segmentation is used in many applications including extracting text, medical imaging, and industrial imaging. Thresholding an image takes a threshold; If a particular pixel (i,j) is greater than that threshold it will set that pixel to some value usually 1 or 255, otherwise, it will set it to another value, usually zero. We can write a Python function that will perform thresholding and output a new image given some input grayscale image.
