# dog-breed-classifier
The main goal of this project was to implement transfer learning on our dataset.In this project, we have  build a pipeline that can be used within a web or mobile app to process real-world, user-supplied images. Given an image of a dog, your algorithm will identify an estimate of the canine’s breed. If supplied an image of a human, the code will identify the resembling dog breed.

# Project Instructions
Clone the repository.
git clone https://github.com/Abhishek1236/dog-breed-classifier

Here's a sample of an output for a dog.
![Sample Output][image1]

And a human.
![Sample Output][image2]

## Data

The training data for this project is located [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). This dataset contains 133 different breeds of dogs and is already split into train, test, and validation sets. Place the training, testing, and validation datasets in the `dogImages` folder.

## Instructions

If you want to run this code on your local computer, you'll also need to download the bottleneck features found [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz). I'll discuss what this is in the Jupyter Notebook, but it's a relatively large file so you may want to go ahead and start the download.

I recommend setting up an environment for this project to ensure you have the proper versions of the required libraries.

Note: You must navigate to the root folder of the project directory in order for the following commands to work properly.

For __Mac/OSX__:
```
	conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

For __Linux__:
```
	conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

For __Windows__:
```
	conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
```

Lastly, fire up the Jupyter Notebook and let's get started.

```
	jupyter notebook dog_app.ipynb
```
