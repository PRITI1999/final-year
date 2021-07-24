BATCH 16 - FORECASTING IPL SCORES USING MACHINE LEARNING

PROGRAMMING LANGUAGE SELECTION

Python is dynamic, object oriented and multipurpose programming language. It has a
huge and inclusive standard library. It helps its user express concepts in fewer lines of code
which is not possible for languages such as in C++ and java. It is extended to create WEB
applications as well. Since the project we have worked majorly deals with machine learning
and data analysis, python is one of the best choices we could make use of because of its
dynamic nature.

HTML is hypertext markup language. It is language that helps in creation of web pages
in the internet. We have used HTML language to create GUI for user interactions, where
users input the values for specified features and obtain their results.

CSS is known as cascading style sheets. They create a uniform look across several
pages of a website. It is used to describe how html elements are to be displayed on the screen.
It plays a key role in the web designing.

PLATFORM SELECTION
Our project was developed in Windows 10. This OS was our choice given that our
data needed a lot of fine tuning and visualizations which could be easily provided in the MS
Excel software. Windows provide GUI for its computers. Windows minimizes the need for
commands to operate OS by simply implementing mouse which navigates through menus,
tabs, dialog boxes and icons. Windows was given this name due to its dynamic nature to
allow multiple tasks to run at the same time. We have chosen this platform since its user
friendly, since our project required more of analytics rather than focus on a very powerful
development environment.

GRAPHICAL USER INTERFACE
The success of any project depends on how well it serves the end users. The main
users of our system include doctors or patients who have little/no knowledge of the
implementations. Thus, we require a friendly user interface including text boxes, buttons,
labels etc. The web page is developed in HTML and styles with CSS. Users are provided
with outputs in terms of images, tables and graphs as well to make the results more
comprehensive.

Flask is a web framework coded in python it uses template jinja2. Flask is used to
build WEB applications such as web pages, blogs, or a website. Our first choice of frame
work was flask given its syntax that is very similar to python itself, and the ease to learn the
framework. Flask has it dependencies as follows:
• WSGI which is a utility library.
• Jinja2 which is template engine.

PYTHON LIBRARIES
• Scikit-learn: scikit learn is a wide python library which practices machine learning,
cross validation of data, and preprocessing of data. It is built on NumPy and SciPy.
• Pandas: Pandas is a python package. It provides a designed data structure with fast
expressive and flexible features. It makes the data work easier and intuitive. For many
different kinds of data pandas is well suited such as tabular, matrix, ordered or unordered
data.
• NumPy: NumPy’s main object is a multidimensional array, it holds an array data
structure. NumPy is a core python library which contains a collection of tools and
techniques. One of these tools is multi-dimensional object.
• Matplotlib: It is a library extensively used for visualizing the data.

IMPLEMENTATION STEPS
1. Define a module for loading the .csv file. Check for rows with a few missing values and
fill them with the mode value of each feature. Analyze the data statistically, which
involves plotting the histograms and chi-square test for normality.
2. Define functions for feature selection and extraction which is based on Recursive Feature
Elimination. Keeping only high-performance features.
3. Evaluate the regressor using the metrics such as RMSE, MSE, MAE and accuracy. The
best regressor is to be used for pred.
4. Develop a Score prediction tool using the best performing regression to predict
scores using the current match conditions.
5. Check for consistency among the most important features and find out the covariance
matrix of the top features to check if the features are statistically independent.
6. Develop a graphical user interface to enhance the experience of the end users in obtaining

STEPS TO RUN THE PROJECT
. Download the file conatined in the CD.
. Open terminal and install the following python modules
  . pip install flask
  . pip install pandas
  . pip install python-dotenv
 . Finally, run the project by - 
  . python main.py
 . The web-page will be available at http://localhost:5000
