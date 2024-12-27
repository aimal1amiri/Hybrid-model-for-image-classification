<h1 align="center">Hybrid Feature Fusion for Monkeypox (Mpox) Classification Using Inception and DenseNet</h1>

###

<h4 align="left">Abstract</h4>

###

<p align="left">This project implements a hybrid classification approach for Monkeypox (Mpox) detection using feature fusion of two advanced deep learning architectures: Inception and DenseNet. By combining the hierarchical, multi-scale feature extraction of Inception with the fine-grained, localized feature extraction of DenseNet, this method achieves exceptional classification accuracy of 98%. The algorithm is optimized to handle challenging, visually similar classes in medical imaging datasets.</p>

###

<h2 align="left"></h2>

###

<h5 align="left">Features</h5>

###

<p align="left">Feature Fusion: Combines intermediate feature maps from Inception and DenseNet to create a unified feature representation.<br>Multi-Class Classification: Includes six classes—Chickenpox, Cowpox, HFMD, Measles, Healthy, and Monkeypox.</p>

###

<h2 align="left"></h2>

###

<h5 align="left">Dataset</h5>

###

<p align="left">The dataset includes images from six skin lesion classes:<br><br>    Chickenpox<br>    Cowpox<br>    Healthy<br>    HFMD<br>    Measles<br>    Monkeypox<br><br>Preprocessing steps include:<br><br>    Resizing images to 224×224 pixels.<br>    Normalization of pixel values to [0, 1].<br>    Data augmentation: rotations, flips, brightness adjustments, and cropping.</p>

###

<h2 align="left"></h2>

###

<h5 align="left">Methodology</h5>

###

<p align="left">Steps :<br><br>    Preprocessing:<br>        Resize and normalize images.<br>        Apply augmentation to increase variability and prevent overfitting.<br><br>    Feature Extraction:<br>        Extract hierarchical and multi-scale features using Inception.<br>        Extract fine-grained and localized features using DenseNet.<br><br>    Feature Fusion:<br>        Concatenate feature maps from the final convolutional layers of Inception and DenseNet.<br>        Apply fully connected layers for dimensionality reduction and classification.<br><br>    Classification:<br>        Use the unified feature representation to classify images into six classes with a Softmax activation function.</p>

###

<h2 align="left"></h2>

###

<h5 align="left">Results</h5>

###

<p align="left">Classification Metrics:<br><br>    Accuracy: 98%<br>    F1-Score for Monkeypox: 0.97<br><br>Confusion Matrix:<br><br>    Minimal misclassifications between similar classes, showcasing the robustness of the fusion approach.</p>

###

<h2 align="left"></h2>

###

<h2 align="left">code with</h2>

###

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" height="40" alt="tensorflow logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jupyter/jupyter-original.svg" height="40" alt="jupyter logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" height="40" alt="numpy logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/matlab/matlab-original.svg" height="40" alt="matlab logo"  />
</div>

###
