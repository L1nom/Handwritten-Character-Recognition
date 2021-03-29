Upon downloading the repository, make sure all the files and folders are located under one directory

The main files should be:
emnist.model [folder]
images [folder]
balanced_dataset.zip [folder]
emnist-balanced-mapping.txt [text file]
emnist.ipynb [notebook file]
gui.ipynb [notebook file]
preprocess.ipynb [notebook file]

The emnist.model file contains the model used for predicting the images. 
The mapping.txt file contains the ASCII Values of the various classes for classification
emnist.ipynb contains the process of training the model with a neural network
preprocess.ipynb shows how to contain analyze the data and view it raw from the csv files
emnist_model.pdf file contains a pdf version of the main jupyter notebook used for training the model
Images folder contains 28x28 pixel drawn images that can be used as reference. 0-46 == 0-9, A-Z, a, b, d, e, f, g, h, n, p, q, r, t

STEPS FOR RUNNING THE CODE:
1. Extract the balanced_dataset.zip folder into the same working directory. 
You should now have two csv files, balanced-train and balanced-test

2. Download Anaconda free installation for Windows. https://www.anaconda.com/products/individual#Downloads
	During installation, make sure to add Anaconda to path. This is important for accesssing the jupyter
	notebook software from any directory
	
	Open Anaconda application, and navigate to environments. In the search packages bar, search for:
		pandas
		numpy
		tensorflow
		keras
		pillow
		matplot
		emnist
	make sure these packages are installed within the root environment

3. Navigate to the directory where the GitHub Repository is downloaded. Open command prompt (cmd) in this 
directory. Once open, type jupyter notebook and press enter. This will open up jupyter notebook on local host

4. On jupyter notebook, navigate the the gui.ipynb file. Click on Cell > Run All
This will compile the code and open up a small interface for you to draw on. After drawing your image, click the
predict button. If a mistake is made, just click on the clear button to reset the canvas

