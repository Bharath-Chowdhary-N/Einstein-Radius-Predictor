# Einstein-Radius-Predictor

## Background

   We have trained a DenseNet model KiDS LRGs superimposed by simulated strong lenses (like arcs, rings etc.,). Since we know the Eisntein Radius of simulated lenses, I have trained the DenseNet-BC-121 model as a regression problem for the input images of 101x101x1. So, the input is an image of dimension 101,101,1 and the outrput is a single float value. This is developed for KiDS (Kilo Degree Survey) and in future can be implemented for Euclid.

## For what it is developed for?
   For lens modelling, the Einstein Radius has to initialized as parameter. Good initial parameter value can be really helpful. Hence, we developed this code which enables that Einstein Radius can be predicted the found lens candidate and can be used as the initial parameter guess.

## What it does?

Einstein Radius (in arc sec) can be predicted for input image of shape (101x101x1). 

## True vs Predicted ER
![ER_prediction_img](https://user-images.githubusercontent.com/32049247/194917707-c61033ee-a933-4f9e-b601-fc0af2458a6c.png)

(This data of the plot can be found inside the data/ folder. )

## Images

Image Data can be requested to us. We will provide a drive link upon request
(contact: b.c.nagam@rug.nl)

### Good Predictions
![image](https://user-images.githubusercontent.com/32049247/194918775-1d784b87-a377-4697-b13a-c06e86dabacf.png)
![image](https://user-images.githubusercontent.com/32049247/194918834-a6dab29f-8af9-4462-a7c4-a1f8646fa124.png)
![image](https://user-images.githubusercontent.com/32049247/194918945-e79f18a9-0b69-4c30-bb34-d48975592021.png)


### Bad predictions
![image](https://user-images.githubusercontent.com/32049247/194916942-b5c7c35c-06e5-4907-aa3a-4381158d190e.png)
![image](https://user-images.githubusercontent.com/32049247/194918294-323bcd9a-4abd-412d-9b0e-29e1227798dd.png)
![image](https://user-images.githubusercontent.com/32049247/194918394-edd7a54b-cc35-425d-98dc-fe4c93c0c733.png)

