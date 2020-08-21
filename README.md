# Rock Paper Scissior Classifier
App has been deployed in **Heroku** using **mondodb Atlas** database. Link of website is given below:

[Rock Paper Scissors](https://rockpaperscissiorclassifier.herokuapp.com/)

In thisproject, we will use a pre-trained MobileNet model to classify hand gestures of Rock, Paper, and Scissors captured by a **webcam**.

You can use Brackets to open the **index.js** file and take a look at the code. You can find the **index.js** file in the following folder in the GitHub repository for this course:
[dlaicourse/TensorFlow Deployment/Course 1 - TensorFlow-JS/Week 4/Examples/](https://github.com/lmoroney/dlaicourse/tree/master/TensorFlow%20Deployment/Course%201%20-%20TensorFlow-JS/Week%204/Examples)

When you launch the **retrain.html** file in the Chrome browser make sure to open the Developer Tools to see the output in the Console.

### Below are a few tips that can help you get started.
1. To prevent overfitting do not add a lot a of dense layers. Using the same layers as in the Rock, Paper, Scissors example should be good enough.
2. Collecting between 50 to100 images for each hand gesture should be good enough for most models. However, feel free to experiment and try to train your model with less or more images.
3. **Wait until Training has Finished before you Download the Model.** To make sure training has completed, open the Developer Tools and look at the Console output. When the browser alerts that "Training is Done!" click Ok. After you click Ok, you will see the value of the LOSS being printed in Console. Once the LOSS values stop being printed, you can go ahead and click the "Download Model" button to download the model and its weights.
