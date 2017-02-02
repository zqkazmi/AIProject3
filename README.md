# Assignment 3

##Goal
Optical character recognition (OCR) is the task of extracting text from image sources. 
You will use a perceptron to recognize handwritten numerical digits (0-9). This is a very commercially useful technology, similar to the technique used by the US post office to route mail by zip codes. There are systems that can perform with over 99% classification accuracy.

##Problem
Write the training method of the multi-class perceptron in perceptron.py; the rest of the code is already written for you.  Using the addition, subtraction, and multiplication functionality of the Counter class in util.py, the perceptron updates should be relatively easy to code. Certain implementation issues have been taken care of for you in perceptron.py, such as handling iterations over the training data and ordering the update trials. Furthermore, the code sets up the weights data structure for you. 

Either run your code in PyCharm (the Python IDE), or run your code on the command line with: ``python dataClassifier.py`` 

##Your Steps
1. Look at the data input files (digitdata folder) to get a feel for what you are getting as training data; answer question 1 in questions.txt. 
2. Spend some time understanding what is happening in the code. Everything is already written except the important parts of the training function.
3. Write code for training on the data in the train function in perceptron.py. This step will be easiest if you work out an algorithm ahead of time.
4. Answer the questions in the Assignment file by putting your answers in questions.txt, which involves running your code and reasoning about it.
5. Ensure you've committed and pushed all modified files to GitHub to turn it in (you can commit/push as you go -- Dr. Olsen won't look at your repository until it is time to grade or you ask for help on something).

##Notes on the Code
The code in perceptron.py is in a Perceptron class. Everywhere you see ``self.variable`` it is referring to a class data member. In Python you can create these on the fly, which is why there is no clear data member definition like you are used to in Java. The ``init`` function is the constructor of the class.

DataClassifier.py runs the overall program. It reads in your data for you, and processes it. In the train function you need to add that part of the code that does the learning (try running without modifying anything -- the code will run, it just won't do very well). The code you need to add is NOT complicated, as long as you understand how a multi-class perceptron works.