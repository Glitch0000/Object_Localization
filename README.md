## Image Classification and Object Localization 

In this repsitory, we'll build a CNN from scratch to:

classify the main subject in an image
localize it by drawing bounding boxes around it.
We'll use the MNIST dataset to synthesize a custom dataset for the task: 

Place each "digit" image on a black canvas of width 75 x 75 at random locations.
Calculate the corresponding bounding boxes for those "digits".
The bounding box prediction can be modelled as a "regression" task, which means that the model will predict a numeric value (as opposed to a category).


![image](https://user-images.githubusercontent.com/64538407/113101691-b428da00-9205-11eb-9589-06b1737cca23.png) للل

![image](https://user-images.githubusercontent.com/64538407/113101728-bdb24200-9205-11eb-8520-66b1b9349ff0.png)

The results:

![image](https://user-images.githubusercontent.com/64538407/113101782-cf93e500-9205-11eb-9741-39c2b76f523c.png)


![image](https://user-images.githubusercontent.com/64538407/113101803-d6225c80-9205-11eb-9119-243507ee2ddb.png)

