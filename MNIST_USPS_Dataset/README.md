MNIST and USPS dataset as Numpy image array and Png files
---------------------------------------------------------

Python file usps_mnist.py contains the definition for the function dataset() that could be used for creating an image numpy array for MNIST and USPS datasets.
Also it could be used for storing the images as .png files.

Jupyter notebook usps_mnist_data_preparation.ipynb demnonstrates an example for using the above function. 

Function
usps_mnist.dataset(normalisation=False, store=False,m=.1,n=.1)
Parameters
Normalisation: True, False (If True, then the data will be normalised to the range [0,1])
Store: True, False (For storing dataset in the current folder as .png files)
m,n: between 0-1 (Validation split for mnist and usps data respectively )


