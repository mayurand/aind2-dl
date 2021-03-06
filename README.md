# aind2-dl

* Note: The conda environment from this repo (aind-dl) could be created only on Anaconda 3. I tried working on the Anaconda 2 but had several issues. 
* Also the file aind-dl-mac-linux.yml has been edited to remove the packages like qt, appnope etc. which are for the mac.

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/udacity/aind2-dl.git
		cd aind2-dl
	```

2. Obtain the necessary Python packages, and switch Keras backend to Tensorflow.  
	
	For __Mac/OSX__ or __Linux__:
	```
		conda env create -f requirements/aind-dl-mac-linux.yml
		source activate aind-dl
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
	```

	For __Windows__:
	```
		conda env create -f requirements/aind-dl-windows.yml
		activate aind-dl
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
	```
	
3. Enjoy!
