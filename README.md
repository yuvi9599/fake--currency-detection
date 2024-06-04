In today’s world every day thousands of people get scammed because of fake notes. According to a survey by RBI fake notes of 2000 have increased by 55 % this year. For a normal person, it’s not that much of a problem to detect the difference between a fake and a real note, but in the case of visually impairedpersons, it’s not the same as they can’t see the minor differences. In this project we are using HOG (Histogram of Oriented Gradients) and Region-based Convolutional Neural Networks (R-CNN) to create an AI/ML model. 
 
In India though there are special symbols embossed on different denominations, still the task is tedious for blind people. The lack of identification devices motivated the need of a handheld device for segregation of different denominations. In this project, features of the images are compared with all the reference images of the currency, if the difference is less than the threshold then the numeric part of the currency is extracted and compared if it matches then the matched currency denomination is recognized. 
 
We are using HOG because it has a few key ad vantages over other descriptors. Since it operates on local cells, it is invariant to geometric and photometric transformations, except for object orientation. 
 
The key reason behind using the R-CNN series is region proposals. Region proposals are used to localize objects within an image. For data sets we are using kaggle and mendeley dataset. For development we are using Anaconda platform and Jupyter notebook as our main ide. 
 



# fake--currency-detection
