#Image Classification and Object Localization

In this repsitory, we'll build a CNN from scratch to:

classify the main subject in an image
localize it by drawing bounding boxes around it.
We'll use the MNIST dataset to synthesize a custom dataset for the task:

Place each "digit" image on a black canvas of width 75 x 75 at random locations.
Calculate the corresponding bounding boxes for those "digits".
The bounding box prediction can be modelled as a "regression" task, which means that the model will predict a numeric value (as opposed to a category).
