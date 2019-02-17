# Java_python_bridge_using_py4j
Enables Python programs to dynamically access arbitrary Java objects 

[Py4J](https://pypi.org/project/py4j/) enables Python programs running in a Python interpreter to dynamically access Java objects in a Java Virtual Machine. Methods are called as if the Java objects resided in the Python interpreter and Java collections can be accessed through standard Python collection methods. Py4J also enables Java programs to call back Python objects.

Here is a real example of using Java-based package for Machine Learning in Pyhton.

In this reposetory we use [Mallet](http://mallet.cs.umass.edu/index.php) for topic modeling or clustering text without convrting the text to the numerical format.

For this task we must create a java gateway to make the bridge between Java and Python.
