# Assignment 3

##Goal
Optical character recognition (OCR) is the task of extracting text from image sources. 
You will use a perceptron to recognize handwritten numerical digits (0-9). This is a very commercially useful technology, similar to the technique used by the US post office to route mail by zip codes. There are systems that can perform with over 99% classification accuracy.

##Problem
Write the training method of the multi-class perceptron in perceptron.py; the rest of the code is already written for you.  Using the addition, subtraction, and multiplication functionality of the Counter class in util.py, the perceptron updates should be relatively easy to code. Certain implementation issues have been taken care of for you in perceptron.py, such as handling iterations over the training data and ordering the update trials. Furthermore, the code sets up the weights data structure for you. 
Either run your code via PyCharm (IDE), or run your code on the command line with: python dataClassifier.py -c perceptron 

##Your Steps
1. Look at the data input files (data/digitdata) to get a feel for what you are getting as training data; answer question 1 in questions.txt. Show to Dr. Olsen before proceeding.
2. Write code for training on the data. This step will be easiest if you work out an algorithm ahead of time.
3. Answer the questions in the Assignment file in questions.txt, which involves running your code and reasoning about it.
4. Ensure you've committed and pushed all modified files to GitHub to turn it in.
