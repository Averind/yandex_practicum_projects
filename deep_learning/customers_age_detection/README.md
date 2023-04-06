**'Age Detection of Customers' project **

Input data: a dataset of more than 7500 photos of people with their ages ranging from 1 year to 100 years old. Based on this data, a neural network was trained after conducting several researches. The goal is to build a model that can determine the approximate age of a person based on their photo. In turn, capturing photos in the checkout area with age determination is necessary to:

- analyze purchases and suggest products that may interest customers in that age group;
- control the honesty of cashiers when selling alcohol.

During the project, the following analyses were conducted:

- analysis of age distribution in the dataset;
- analysis of images in the dataset.

Subsequently, a neural network was trained on a server with a graphics processing unit (GPU) consisting of 50 convolutional layers using the ResNet architecture and 1 fully connected layer with 1 neuron.

On the test dataset, the neural network showed a result with a MAE value of 6.37.
