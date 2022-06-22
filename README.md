# ABSTARCT
Basically this project deals with image classification which was carried out with the help of machine learning instead of deep learning techniques. This project is completely based on facial recognization using machine learning classifiers. The facial patterns were been detected wuth the help of haar cascade files. The files help in seeing the eyes and face of a human. The logistic regression provided the best results in achieving an accuracy of 88%. This project completely deals with facial recognition based on face patterns with the help of haar cascade files, not with the help of local binary patterns. The classifiers are been tuned (Hyperparamter tuning) to acheive best reults and improved accuracy in bulit models.
# METHODOLOGY
The normal image is converted into a grey scale image it's done because ML models can only recognize greyscale images.

# This is original image as RGB pattern
![normal](https://user-images.githubusercontent.com/92075957/174955413-b9384eef-dff8-40d8-bf4d-ea227c48ccf4.png)
# This image is a greyscale image that was converted from a normal image.
![grey](https://user-images.githubusercontent.com/92075957/174955495-d2539004-ffa5-43fe-ac02-38ab35d87da6.png) 
# Facial recognition using haar cascade files which shows eyes face has been detected.
![facial](https://user-images.githubusercontent.com/92075957/174955623-d8bc3fb5-c426-4686-a123-67f58439126f.png) 
# If both eyes and face have been recognized accurately the image will get cropped else it doesn't recognize consider the image.
![cropped](https://user-images.githubusercontent.com/92075957/174956557-7874a161-6554-4c45-854d-58cf4e8ab79f.png)
# PyWavelets have been used to recognize the patterns in the cropped face
![patterns](https://user-images.githubusercontent.com/92075957/174956671-c1011c63-f2e1-4e5f-b05d-892c8c544292.png)
The complete procedure followed was been provided in the code.
# USER INTERFACE 
The user interface has been developed for this project which deals with classifying the image based on his facial features. 
![image](https://user-images.githubusercontent.com/92075957/174959546-cca97dd0-952d-4133-8ca4-ca528691a082.PNG)
This how the interface looks like we need to upload any images which are not trained or in test data after uploading the image the results will be shown in below image:
![prediction](https://user-images.githubusercontent.com/92075957/174963430-d48e47f6-e34a-4faf-a931-77e6a67613dd.PNG)
The results show the probability score or accuracy of the image which means how much percentage that the uploaded image match with ML model.
If the face or eyes are not recognized properly in the uploaded image the output result will be 
![no](https://user-images.githubusercontent.com/92075957/174964161-3b86018e-85aa-46e0-9f9e-1db7505aae7b.PNG)
It shows a pop-up message that face and eyes are not found
