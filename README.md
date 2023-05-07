Download Link: https://assignmentchef.com/product/solved-eecs658-assignment-1
<br>
Deliverables:

<ol>

 <li>Copy of Rubric1.docx with your name and ID filled out (do not submit a PDF)</li>

 <li>Python source code for CheckVersions</li>

 <li>Screen print showing the successful execution of CheckVersions</li>

 <li>Python source code for NBClassifier</li>

 <li>Screen print showing the successful execution of NBClassifier 6. Answers to the following questions:

  <ol>

   <li>How many samples in NBClassifer were in the training set?</li>

   <li>How many samples in NBClassifer were in the test set?</li>

   <li>Using the confusion matrix, manually calculate the Accuracy value. Does it match the value calculated by your program? If not, why? (Manually includes using a spreadsheet).</li>

   <li>Using the confusion matrix, manually calculate the Precision values for each iris variety. Do they match the values calculated by your program? If not, why?</li>

   <li>Using the confusion matrix, manually calculate the Recall values for each iris variety. Do they match the values calculated by your program? If not, why?</li>

   <li>Using the confusion matrix, manually calculate the F1 values for each iris variety. Do they match the values calculated by your program? If not, why?</li>

  </ol></li>

</ol>




Assignment:

<ul>

 <li>Install Python on your system if it is not already.

  <ul>

   <li>See “Python for Windows Primer” on BlackBoard (under Assignment 1) for help on Windows</li>

   <li>For help on Linux, see:

    <ul>

     <li><a href="https://wiki.ittc.ku.edu/ittc_wiki/index.php/EECS168:SSH_Instructions">https://wiki.ittc.ku.edu/ittc_wiki/index.php/EECS168:SSH_Instruct </a><a href="https://wiki.ittc.ku.edu/ittc_wiki/index.php/EECS168:SSH_Instructions">ions</a></li>

     <li>Virtual Box: <a href="https://www.virtualbox.org/wiki/Downloads">https://www.virtualbox.org/wiki/Downloads</a></li>

     <li>Ubuntu install: https://ubuntu.com/download/desktop o See “Beginner’s Python Cheat Sheet” on BlackBoard (under Assignment 1) for help with Python.</li>

    </ul></li>

   <li>Install the following Python libraries.

    <ul>

     <li>scipy o numpy o pandas o sklearn</li>

    </ul></li>

   <li>The scipy installation page provides excellent instructions for installing the above libraries on multiple different platforms, such as Linux, mac OS X and Windows. If you have any doubts or questions, refer to this guide, it has been followed by thousands of people.</li>

   <li>To verify you have installed Python and the SciPy libraries write a Python program called CheckVersions that 1) prints out the versions of Python, scipy, numpy, pandas, and sklearn and 2) prints out “Hello World!” o Hint: use this code for part 1): # Python version import sys print(‘Python: {}’.format(sys.version))</li>

  </ul></li>

</ul>

# scipy import scipy

print(‘scipy: {}’.format(scipy.__version__))

# numpy import numpy print(‘numpy: {}’.format(numpy.__version__))

# pandas import pandas

print(‘pandas: {}’.format(pandas.__version__))

# scikit-learn import sklearn

print(‘sklearn: {}’.format(sklearn.__version__))

<ul>

 <li>Write a Python program called NBClassifier that does the following:

  <ul>

   <li>Loads the iris data set (located in iris.csv file in the BlackBoard</li>

  </ul></li>

</ul>

Assignment 1 folder) o Creates a training set with half of the 150 samples and a test set with the rest.

<ul>

 <li>Classifies the iris data set using the Python built-in Naïve Bayesian classifier, GaussianNB.</li>

 <li>Prints out the overall accuracy of the classifier.</li>

 <li>Prints out the confusion matrix. o Prints out the P, R, and F1 score for each of the 3 varieties of iris. o You may (and probably should) use the Python built-in programs.</li>

</ul>




Remember:

<ul>

 <li>Your Programming Assignments are individual-effort.</li>

 <li>You can brainstorm with other students and help them work through problems in their programs, but everyone should have their own unique assignment programs.</li>

</ul>