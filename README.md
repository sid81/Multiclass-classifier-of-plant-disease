# Multiclass-classifier-of-plant-disease
A multi-class image classifier that determines whether leaf or plant is fresh or diseased.Each image has been preprocessed to 224x224 pixels with a batch size of 32.
First i tried with CNN ,but it overfits so i have used inception V3 model.inception is keras model that are available with predefined model weights and just have to
customize the outer layer for better prediction,feature extraction,fine tuning.
## Model Architecture and summary:
![68747470733a2f2f7777772e50657465724d6f7373416d6c416c6c52657365617263682e636f6d2f6d656469612f696d616765732f7265706f7369746f726965732f5472616e736665722d4c6561726e696e672e6a7067](https://user-images.githubusercontent.com/68815179/199227993-90d3eabe-4d07-446d-b350-ba0df938c368.jpg)

- Then i applied image augmenatation using ImageDatagenarator to avoid over-fitting.
- Plot the traing accuracy vs test accuracy and loss using matplotlib. 

![image](https://user-images.githubusercontent.com/68815179/199228443-b547b814-51a7-4b9e-911d-4ea0f048b528.png)

## Conclusion
The Architecture and parameter used in this Inception v3 model are capable of producing accuracy of 97% on Training data,95% on validation data,on which is preety good.
After that i have applied model using flask app which is shown below.

## Screenshots

![image](https://user-images.githubusercontent.com/68815179/199229491-20cca2bb-5fe3-4ef3-aa52-6eb30790bb0f.png)

![image](https://user-images.githubusercontent.com/68815179/199229523-96c3b621-c261-48d3-9445-90970ae232ff.png)

![image](https://user-images.githubusercontent.com/68815179/199229562-bbd9b82c-2239-4be6-a3ca-2d896512e664.png)

![image](https://user-images.githubusercontent.com/68815179/199229601-e3c18c44-c735-4f16-9031-31a5f34ebed5.png)

