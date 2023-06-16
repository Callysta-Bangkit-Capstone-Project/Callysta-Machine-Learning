# A-Z Uppercase Handwritten Alphabet Recognition Classification Using CNN 
This project focuses on building a Convolutional Neural Network (CNN) model using Tensorflow to detect uppercase letters in handwritten images. The goal is to accurately classify the images of handwritten uppercase letters from A to Z.

## Members
This project is developed by team C23-PS363 of Bangkit Academy 2023 Capstone Project
Name | Bangkit ID | Learning Path | Github Profile
:---|:---:|:---:|---:
Ega Fernanda Putra | M038DSX0496 | Machine Learning | [Profile](https://github.com/Fallennnnnn)
Muhammad Raffi Priyadiantama| M038DSX0498 | Machine Learning | [Profile](https://github.com/Raffi-072)
Muhammad Naufal A. |  A013DSX2909 | Mobile Development | [Profile](https://github.com/mhmmdnaufall)
Danil Ardi | A013DSX0990 | Mobile Development | [Profile](https://github.com/danilardi)
Ridho Kartoni Pasaribu | C013DSX0978 | Cloud Computing | [Profile](https://github.com/ridhokartoni)
Ruben Tricahya Boediono | C038DSX0600 | Cloud Computing | [Profile](https://github.com/rubenboediono)


## Dataset
The dataset used for training the models is sourced from Kaggle and consists of handwritten alphabet images. 
The dataset contains 26 folders (A-Z) containing handwritten images in size 28x28 pixels, each alphabet in the image is centre fitted to 2020 pixel box and each image is stored as Gray-level

The Distribution of the Alphabet Letter is stated in below
| Letter | Count  | Letter | Count  | Letter | Count  |
|--------|-------:|--------|-------:|--------|-------:|
| O      |  57825 | S      |  48419 | U      |  29008 |
| C      |  23409 | T      |  22495 | P      |  19341 |
| N      |  19010 | A      |  13869 | M      |  12336 |
| L      |  11586 | R      |  11566 | E      |  11440 |
| Y      |  10859 | W      |  10784 | D      |  10134 |
| B      |   8668 | J      |   8493 | H      |   7218 |
| X      |   6272 | Z      |   6076 | Q      |   5812 |
| G      |   5762 | K      |   5603 | V      |   4182 |
| F      |   1163 | I      |   1120 |        |        |

this is the link to kaggle dataset [A-Z Uppercase Handwritten Alphabet](https://www.kaggle.com/datasets/sachinpatel21/az-handwritten-alphabets-in-csv-format)

## Architecture Used in Model 
Using Convolutional Neural Network (CNN) model to Classify the image, we can modify the model architecture based on requirements and in this project we use this architecture 

![image](https://i.ibb.co/LQ19BGx/Screenshot-169.png)

## Requirements Used in this Project
- Tensorflow
- Python 3
- Pandas
- Matplotlib
- Numpy

## How To Contribute
- Clone this repository
- Install Dependencies based on the requirements above
- Prepare the Dataset as specified above link
- Customize the script, model architecture, and others as needed 
- Run the script
