### MNIST and USPS datasets as Numpy image arrays and PNG files

Python file *__mnist_usps.py__* contains the definition for the function dataset() that could be used for creating an image numpy array for MNIST and USPS datasets.
Also it could be used for storing the images as .png files.<br />
Jupyter notebook *__usps_mnist_data_preparation.ipynb__* demnonstrates an example for using the above function and also for converting labels into onehot encoding format.<br /> 

*__Function__*<br />
mnist_usps.dataset(normalisation=False, store=False,m=.1,n=.1)<br />

*__Parameters__*<br />
_normalisation_: True, False (If True, then the data will be normalised to the range [0,1])<br />
_store_: True, False (For storing dataset in the current folder as .png files)<br />
_m,n_: between 0-1 (Validation split for mnist and usps data respectively )<br />


