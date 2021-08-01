# EAI21
Embedded AI

## 1 Introduction
[Link to Notebook w/ the work](https://colab.research.google.com/drive/1jcbjiK7cLZcBlydXtKi2YaiWwx9Iq9Xl?usp=sharing)

#### Assessment
Modify the NN at the end of the program to boost the performance of the NN. 
	You can make it deeper, wider, etc. 
Submit your Notebook or its link to your git under a new folder called: `Lab3_CNN`. Answer on top and add me “memoatwit” [1]:

- What is your MSE/MAE with linreg vs tuned network? 

MSE/MAE - Default (13, 1) - 24.29 
MSE/MAE - Tuned (64, 32, 16, 1) - 11.51

- What happens to your train and test results if you add 5 hidden layers with 128 neurons each? 

If we add five hidden layers, each with 128 neurons, the MSE went up.
The reason being, there is not enough data to train all the neurons in the hidden layers, and as a result, some of the weights of those neurons are zero.

## 2 Intro to convolution operations: padding

[Link to Notes](https://drive.google.com/file/d/1vJ5YH-ZjCZ3tILekvzd3rDQRZo8udxt2/view?usp=sharing)

#### Assessment
Grab a pen/paper or your favorite note-taking device and follow the examples in the video on your own.

## 3 Convolution parameters: stride and pooling

[Link to Notes and Work for Assessment](https://drive.google.com/file/d/11P1SVDLA9mYjCyzcgiFzMLOyVsXa7a_y/view?usp=sharing)

#### Assessment

Follow the examples in the video on your own.  
Answer in your Git repo: 
If I apply pooling of 2 (2,2 window with a stride of 2) to a (6,6) array, what is the resulting size?

Answer: 3x3

## 4 ConvNet Architectures, layers

[Link to Notebook]()

#### Assessment
Follow the examples in the video on your own.  Answer in your Git repo:
- What is my output size if: Input = (100,100), kernel size=(2,2), stride of 1 and no pooling? 


- How many weights do I have if I have 24 such filters stacked (conv2_24)?


- What is a better idea: To use one larger kernel (7,7) or multiple stacked smaller ones, 3x(3,3)? 


- Solve for the padding (P), in terms of I, F and S, if we want the input and output size to remain the same. 



## 5 Practical patterns

#### Assessment
[Required] PA5: Contest on Cat/Dog classification on Jupyter. Train/test CNN with cats and dogs on Jupyter. 
Once you fetch PA5 on Jupyter, you will have access to ~20k cat/dog images. Build a classifier model in Keras to correctly identify a given image as Cat/0 or Dog/1. Images have been resized to 50x50 grayscale pixels to assist you. 

Please fetch the PA5 notebook on Jupyter for more information.
[Optional] Design your own VGG (based on the VGG article architecture `E`) in Keras. 


## Submission of assessments to Git
- Create a repo on your favorite git (hub, lab, etc.)
- call it EAI21
- can be private
- add me ('ergezerm@wit.edu' or 'memoatwit')
- push code / add text
- add Readme.md with link to results
- Share the link to your repo with me on BrightSpace
