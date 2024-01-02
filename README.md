# 6th Homework of the Java Test Automation Course (2nd block) - Solvd Laba
This repository stores the 6th homework given by our mentor in the 2nd block of 
the Java Test Automation Course at Solvd Laba. It consists in adding JAXB 
annotations to the already created hierarchy in previous homeworks and parse
the created XML files from the resources folder into Java objects using this
library.

## Explanation

To accomplish the requirements of the homework, I've firstly added the JAXB API
dependency with two other dependencies: XML Bind API and JAXB Impl. I realized
that JAXB works with these two other dependencies altogether, otherwise if I 
don't add them I got an error. After that, I added the JAXB annotations to the
whole classes hierarchy to let JAXB know how to map the XML files into each
suitable object. Then, I created a generic method in the main class, to test 
the parsing of the XML files and everything worked as intended. I had to change
the field 'age' from the Person class to 'birthDate', to accomplish the 
requirement of this homework of parsing lists, complex objects and dates as well.

## What did I learn?

In this homework I learnt about the JAXB library and how useful it is to work 
with XML files to not do all that job manually. I used the most common 
annotations to let JAXB understand how it has to do its work for us. I am
surprised about how easy it is to use, since I did not have any major issue
working with it in this task. This is unbelievable, but I think the hardest part
of this homework was looking for the dependency of JAXB without have any error at
runtime. A thing I'd like to clarify is that I did not have to create any adapter
for the 'birthDate' field, since it was automatically parsed by JAXB without 
problem.

## Technologies

- Java
- Maven
- MySQL
- JDBC
- MyBatis
- XML, XSD, SAX Parser
- JAXB

## Set-Up

To run this project you will need an updated version of Java.
First, clone this repository in a folder of your PC.
You have to put the following command in a terminal:

```bash
  git clone this-repo-url
```
You will need an IDE to open the project folder and, finally, run the 
Main.java file to see the program output.

## Author

- [@Nazareno Bucciarelli](https://github.com/nazabucciarelli)
