# Image Recognition with ResNet50
This Python code uses the ResNet50 model, which is a pre-trained deep learning model, to recognize the image and predict its class with a certain level of accuracy. The code is written using Python, and it requires OpenCV, Matplotlib, and TensorFlow libraries to be installed.

# How to use the code
The code loads a pre-trained ResNet50 model and predicts the class of an input image. You can change the image source by replacing the <code>imageSrc</code> variable with the path to your image. You can also change the top number of predictions by modifying the <code>top</code> parameter in the <code>decode_predictions</code> function.

# Prerequisites
Before executing the code, you must have the following installed:

<ul>
  <li>Python 3.x</li>
  <li>OpenCV</li>
  <li>Matplotlib</li>
  <li>TensorFlow</li>
</ul> 

To install these dependencies, you can use the following commands:
```bash
pip install opencv-python
pip install matplotlib
pip install tensorflow
```
# Steps to Execute the Code
<ol>
  <li>Clone or download the repository to your local machine.</li>
  <li>Navigate to the directory where the files are located</li>
  <li>Open the command prompt and run the following command to execute the code:</li>
  
  <code>jupyter lab</code>
  
  <li>The code will load the ResNet50 model, preprocess the image, and predict the class of the input image</li>
  <li>The output will be displayed in the command prompt, showing the predicted class and accuracy percentage.</li>
  <li>Additionally, the image will be displayed using Matplotlib.</li>
  
  # Customization
  To customize the code for your own use, you can change the <code>imageSrc</code> variable to point to your own image file. You can also modify the <code>top</code> parameter in the <code>decode_predictions</code> function to change the number of predictions displayed.
  
  
