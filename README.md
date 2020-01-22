# CAM-KERAS


This is a further addition to "Distracted-Driver-Detection" project done in the fall semester's course of "Advance Predictive Modelling". 

There are various models that are well estabilished for Computer Vision techniques that are used for modelling purposes in several applications. However, as we know that these models contain lots of hidden layers and how exactly these layers function is remained as a "black-box". We generally evaluate the results and based upon the model selection, classify the images accordingly 

To provide further insight and getting an intuition on how the model is conserding different images and reacting, we can take the output of the last convoluted layer to see in which regions of the image(matrix) our model has provided significant weights (in comparison) after gradient procedures. By looking at such outputs, one will be able to infer if the model is really behaving the way business requries or not and how stable it will be in practical application 

Through this code I am showcasing where in the image is our convolutional model is focusing on with respect to different classes and visualize it by highlighting those regions in the input image. Such a method is called is "Call Activation maps or Grad-CAM" in KERAS. 

The procedure also involves : 

- Basic preprocedures for image datasets 
- Image Augmentation techniques 
- Reusability of model weights using "load_model" function 
- Building a CAM function and applying it to images of two different classes to see the different focus areas on the image 
