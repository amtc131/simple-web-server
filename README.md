#simple web server


### Go ###


In this simple web server we have imported three packages –

1- fmt – fmt stands for the Format package. This package allows to format basic strings, values, or anything and print them or collect user input from the console, or write into a file using a writer or even print customized fancy error messages. This package is all about formatting input and output.
2- log – Package log implements a simple logging package.
3- net – Package http provides HTTP client and server implementations. Get, Head, Post, and PostForm make HTTP (or HTTPS) requests

The above diagram represents the three routes from the server file

´/ route´ – This file will simply open the index.html file
/hello route – This route will execute the hello function which is written in the code.
/form route – This will take us to a form, where we will be taking the input of the user’s name and user’s address and after that it will execute the form function, which will display the details that the user has filled in the form.
