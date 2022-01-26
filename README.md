
## Project Overview

this project is part of Udacity’s data science nano degree.

in this project, we were asked to make a machine learning model to:

· classify dog breeds

· find the resembling dog breed of a human

to achieve this we will have to build a pipeline to process the user’s input, in the notebook provided by Udacity the steps to build this model are :

· Step 0: Import Datasets

· Step 1: Detect Humans

· Step 2: Detect Dogs

· Step 3: Create a CNN to Classify Dog Breeds (from Scratch)

· Step 4: Use a CNN to Classify Dog Breeds (using Transfer Learning)

· Step 5: Create a CNN to Classify Dog Breeds (using Transfer Learning)

· Step 6: Write your Algorithm

· Step 7: Test Your Algorithm




## Project Instructions
1-download as zip file 

2-run the dog_app.ipynb file

3- run all cells 

4- add new cell 

5-enter the follwing code and replace the parameters with your image path then run the cell: 
```
dog_classifaier("enter image path here")
show_img("enter image path here")
```

## results examples


![step7_3PNG](https://user-images.githubusercontent.com/93598105/151147872-9b0cec4a-1a94-4926-98e7-5ed3f848c4f3.PNG)
![step7_2PNG](https://user-images.githubusercontent.com/93598105/151147902-251bd37f-f763-4398-9e2d-042c5fe94c9d.PNG)
![step7_1PNG](https://user-images.githubusercontent.com/93598105/151147927-761135cd-ce6a-42f0-804c-451337bcf6a7.PNG)

## Conclusion
In this project, we made a dog breed classifier using transfer learning with the InceptionV3 feature extractor where the algorithm detect from user input (images) if it has a dog, human, or neither.
The model performed well but was not perfect where in some cases the model detected cats as humans

And to improve the model in the future this a few things that can help :

• Train the model to differentiate between dogs and other animals

• Add more data with different resolutions and angles to increase the accuracy

• Increasing the training time (more epochs)
