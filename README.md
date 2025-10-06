# Deep Learning Foundations
![Alt text](https://github.com/mofidi80/Deep_Learning_Foundations/blob/821cb4700b3d6b6a543face698376c9699526efc/blob/nano-banana-2025-10-05T17-30-04.png)

## 1. Implementing SVM, SVR models as neural networks
In this project, we attempt to write Support Vector Machine, and Support Vector Regression models as neural networks using pytorch.

### Goals
1. Make SVM as a NN using pytorch
2. Make SVR as a NN using pytorch
3. Make a random classification dataset to test these models

### Outcome
* SVM has an accuracy score of 88%
* SVR has mse of 0.2233


## 2. Use MLPs on Mnist dataset
In this project, we use several Multi Layer Perceptrons with different settings(hidden layer, number of neurons, and activation function) to classify MNIST dataset.

### Goals
1. Test the effectiveness of MLP in classification
2. Test if number of nearons, hidden layer, and activation function have any effect on accuracy
3. See if MLPs can do better than simple linear models

### Outcome
* Since the data are non-linear, non-linear models work better
* If we use softmax in the last layer it works better
* If we decrease the number f neuron and then increase them in the hidden layers, information is lost and the performance decreases immensely



## 3. Use CNN on Mnist dataset
In this project, we Implement a simple 2 layer Convolutional Neural Network yo classify MNIST dataset

### Goals
* Successfully implement and test CNN on Mnist

### Outcome
* After 25 epochs the model reached accuracy of 82%


## Built With (for all projects)
* Python
   + Pytorch
   + Numpy
   + Pandas
   + Matplotlib, Seaborn
   + Scikit-Learn



## Installation
1. First intall jupyter notebook from the link below if you haven't already.
   + https://jupyter.org/install
2. Make sure you have all the libraries mentioned in Built With section installed; If not first run your environment then use the following commands:
+ Pytorch:
  ```console
  pip install torch
  ```
+ Torchvision:
  ```console
  pip install torchvision
  ```
+ Numpy:
  ```console
  pip install numpy
  ```
+ Pandas:
  ```console
  pip install pandas
  ```
+ Matplotlib:
  ```console
  pip install matplotlib
  ```
+ Scikit-Learn:
  ```console
  pip install scikit-learn
  ```


## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request


## Contact
Mohammad Mofidi
* Email: mohammad.mofidi.k@gmail.com
* Linkedin: https://www.linkedin.com/in/mohammad-mofidi-khajeh-2715832b8/
* Instagram: https://www.instagram.com/_mohammadmofidi/



