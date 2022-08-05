# simpsons-classifier
A project whose task is to classify the characters of the animated series The Simpsons.

# Description 📝

The project has a name derived from the [dataset](https:\www.kaggle.com\datasets\romankossinov\journey-to-springfield) of the same name "Journey to Springfield". The task is to help the FOX television company in the processing of their content. As you know, the Simsons series has been on television for over 25 years, and during this time a lot of video material has accumulated. Characters have changed along with changing graphic technologies and Homer 2022 is not very similar to Homer 1989. Our task will be to learn how to classify the characters living in Springfield. To classify images, we will use the method of "convolutional neural networks"
The project is written in Python using Google Colab, a cloud shell that allows you to work with GPUs.

# Project Structure 🖇

The project consists of 6 episodes:
1. Import - importing the necessary modules and packages.
2. Loading data - We determine the modes of operation of the neural network. We write a class for processing raw data, implement a function for displaying pictures, download the archive, process it, load pictures.
3. Data analysis - check the balance between classes using graph and data.
4. Building a simple neural network
5. Neural network training
6. The power of deep networks - applying the Fine tuning method, training networks VGG16, ResNet152 - getting results

# Initial data and result 📁
The input is an image of a character from The Simpsons:

<img src="https://user-images.githubusercontent.com/79962819/183069888-eab2e18e-3bbd-440d-a9a1-b8ce2b61b927.png" width="600">

The result of the program is displayed graphical and textual information (the result of system prediction):

<img src="https://user-images.githubusercontent.com/79962819/183070520-37eaee7a-b03b-4155-934c-0752120a13ea.png" width="400">

Learning information:

<img src="https://user-images.githubusercontent.com/79962819/183070898-0976f082-a997-4079-aa26-204b35e61db9.png" width="480">

metrics f1_score:

<img src="https://user-images.githubusercontent.com/79962819/183071174-79c099a9-d094-4521-98eb-646b10b81a7c.png" width="480">

# User's Manual 🥷
You can start the project using google colab. Just enough:
1. open file simpsons_classification.ipynb
2. Enable GPU: runtime -> change runtime -> hardware accelerator: GPU
3. Upload [dataset](https:\www.kaggle.com\datasets\romankossinov\journey-to-springfield) to google drive
4. Run code on each cell
