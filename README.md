# dog_breed_identification

Identification of the dog breed from photo, with onnx model export for Android use.

# Download the data
Data used for this project is available at https://www.kaggle.com/c/dog-breed-identification/data.
Download the data and store it inside the project with labels.csv in the main directory.

# Training notebook
To train the model, run through the steps in breed_identification.ipynb. At the end, there should be dogs.onnx model available to use with ort_image_classifier app.

# Run the app
Clone Android app submodule. Copy dogs.onnx and labels.txt to ort_image_clasification_android/app/main/src/res/raw/ and follow the steps inside the repo to build and run the app.

![Buki](/images/buki.jpeg)