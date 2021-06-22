# Fruit-Quality-Detection-Using-Computer-Vision

### Problem Statement
To automate the process of sorting of fruits on the basis of their quality and ripeness. To reduce the amount of manual labour and human errors in doing monotonous work of sorting exponentially. Reduce the losses experienced by retailers by predicting degraded quality due to mechanical stresses eg. in mango at an early stage.

### Inspiration for Idea
Every year tons of fruits are wasted in the process of them reaching from farmers to retailers and retailers to consumers because of lack of awareness regarding freshness of fruits and vegetables. In large scale factories where huge processing and packaging of fruits is required everyday, then picking fruits based on instincts and manual check is both inaccurate and time consuming. 

### Existing solutions in the Market 

1.Clarifruit \
The Israeli startup Aclar Tech   has developed a Mobile App that allows monitoring, in real time, the ripeness, freshness, and quality of fruit and vegetables. With the Aclaro meter, users scan the fruit with their built-in smartphone camera and with a standard portable molecular sensor. This captures a large set of measurements about the fruit and its environment, revealing data like the fruit’s sugar content, acidity, firmness, weight and color, as well as its GPS location and weather conditions at the time of sampling.\

2.Machine Learning: Using Algorithm to Sort Fruit at Amazon : \
The automated ripeness detection system consists of a conveyor belt that transports the food in containers to a particular sensor. The sensor looks like a normal camera, but it can capture information which is invisible to the human eye. We teach the machine what good and bad products look like by inputting new product variants on a daily basis. The products are photographed and made available to the machine in the shape of data. That way, the computer gradually understands the quality standards.
The fresh produce is divided into four categories: “OK”, “Damaged”, “Badly damaged” and “Expired”. Containers of the different ripeness categories are randomly offered to the machine.


### Proposed Solution
We have focused on two fruits, mango and pear.
Using computer vision techniques we have successfully trained our model to predict the ripeness and quality of mango as well as predict the quality of pear. The model can be easily incorporated into any existing systems that require processing and sorting at a very large scale.


### Brief Description
Our aim is to detect the freshness of fruit (mango and pear) and classify them on the basis of their ripeness and quality. 

Mango is classified into the following categories : ripe and good, ripe and bad, unripe and good, unripe and bad. 

Pear is classified into good, bruised and worst.

Though the aim of our project is to deploy our machine learning model in factories and large processing units,to present our work we have built a naive android application predicting the freshness of mango and pear using computer vision and image processing techniques. 
We do require manual selection of which fruit needs to be assessed (mango or pear) on a light background and will predict the quality of only one fruit at a time. The user can capture the image using the phone's camera or load an image from the gallery. The quality and ripeness of fruit is then flashed on the screen.

The mango dataset is trained on mobilenetv2 and for pear a custom model is used for best achievable results.


### Software/ Hardware used
* All the models were trained using  google colab and pytorch on gpu.
* All the apps were built on Android Studio version 3.6.3 and tested on android devices connected via usb and android emulator min api level 7.1.1.


### References
1. Mango dataset :
  * http://dx.doi.org/10.17632/fmfncxjz3v.1#folder-dbe8ca34-9ddb-4470-b6fc-cdfddbd45e69 \
  * http://dx.doi.org/10.17632/nsjggt7tyz.1#folder-162bec68-dd7a-4dcf-9578-c88c4265a001 \
2. Banana dataset :
  * https://github.com/giovannipcarvalho/banana-ripeness-classification/tree/master/data
3. Pear dataset :
  * Google images

4. For building android app :
  * https://github.com/tusharck/Object-Detector-Android-App-Using-PyTorch-Mobile-Neural-Network

