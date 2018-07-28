# Portfolio - 42 Silicon Valley
https://www.42.us.org/

Situated in the Bay Area, 42 is a revolutionary peer-to-peer educational center. Projects are given to students as specifications written on PDFs. As there are no instructors, all information is gathered from peers or through internet research. Almost all projects are coded in C, following a strict coding guideline known as the "norm". The norm, in short, is a long list of restrictions on what we cannot do in our code.

##### A few norm highlights:
- no `for` loops
- max 4 arguments per function
- max 25 lines per function
- incredibly specific tabulation
- declarations and instantiations must be separate
- no memory leaks, no segmentation faults, no exceptions
- most importantly, no use of C Standard Library functions outside of a select few (`write`, `malloc`, `free`, `open`, `read`), unless otherwise specified

# Projects Completed
These are the projects I have completed during my time spent at 42, from April 2017 - June 2018. I've included repositories containing my work for most of the projects. For those I have not, they're either spaghetti or lost in the void.

## Intro

#### C Piscine
Before being accepted by the school, new students are entered into a 1 month intensive selection program called the Piscine (French for swimming pool), where only the most rigorous and tenacious are selected to enter the main program. Introduction to the C programming language and simple data structures.

([Repository](https://github.com/kraxx/42_C_Piscine))

#### Libft
First project after starting the main program. We code our own library in lieu of using the C Standard Library, to use for the rest of our projects. As we progress in the curriculum, new functions are constantly added to our personal libraries.

([Repository](https://github.com/kraxx/42_libft))

#### Fillit
The goal of fillit is to implement a very specific algorithm that packs a list of teris tetrominoes (input) into the smallest square possible. Due to the nature of the rules, the only real solution is done through recursive backtracking.

#### Get Next Line
Recode `getline` from the C Standard Library. A true test of rigor.

## Algorithms Branch

#### Printf
Recode `printf` from the C Standard Library. A true test of endurance.

([Repository](https://github.com/kraxx/42_ft_printf))

#### Push Swap
Implement an algorithm that takes a list of numbers and sorts it under very specific contraints:
- use only 2 stacks
- limited to specific operations (push from stack A to B, rotate stack A or B, rotate both, etc.)
- must not exceed a certain amount of operations proportional to the input size

#### Lemin
Given a map of coordinates and a ton of ants, implement a graph traversal algorithm to efficiently move all ants from start to finish.

#### Core War
Recreate the 1984 programming game. An assembler must be written to parse champion files written in pseudo-assembly into compiled byte code. We must also write the virtual machine through which our champion binaries are loaded to battle it out in a game of memory elimination.

## Graphics Branch
#### FdF (Wireframe)
Given a topographic coordinate map, write a program that generates a 3D graphical representation of the map.

([Repository](https://github.com/kraxx/42_FdF))

#### Fractal
Write a program that generates and displays various fractals that can be mutated via mouse input, where the XY coordinates represent the real/complex numbers that comprise fractals.
([Repository](https://github.com/kraxx/42_fractal))

## Security Branch
#### SSL DES
Recode OpenSSL's implementation of the DES encryption algorithm.

([Repository](https://github.com/kraxx/42_ssl_des))

## DevOps Branch
#### Docker
Introduction to Docker through a collection of shell scripts and Dockerfiles. Covers the basics all the way up to deploying swarms and standalone containerized applications.

## Web Branch
#### Camagru 
Instagram clone. Though previously encouraged to be built in JavaScript and PHP with no frameworks, I decided to build it using modern frameworks. Built in React and Redux for the frontend, Node.js for the backend, and PostgreSQL for the database. Currently deployed to Google Cloud Platform.

([Web Page](https://camagru.jchow.club), [Repository](https://github.com/kraxx/Camagru))

## Piscines
In addition to the C Piscine used as a selection period, 42 occasionally offers 2 week intensives that act as introductory crash courses to other programming paradigms.

#### PHP Piscine
The basics of web architecture, learned through PHP.

([Repository](https://github.com/kraxx/42_PHP_Piscine))

#### C++ Piscine
An intensive introduction to the wonderful world of Object Oriented Programming.
Of particular note is the dope Asteroid-like space shooter a partner and I built over a weekend rush, check it out [here](https://github.com/kraxx/42_CPP_Piscine/tree/master/rush00)!

([Repository](https://github.com/kraxx/42_CPP_Piscine))

#### Starfleet Piscine
Introduces BigO notation and covers the fundamentals of popular whiteboard algorithms.

#### Tensorflow Piscine
Exactly as it sounds, a crash course on machine learning principles. Utilizes TensorFlow, Keras, and other frameworks written in Python.
Completed a handful of Machine Learning challenges on Kaggle.

([Kaggle Kernels](https://www.kaggle.com/kraxximus/kernels))

### Exams
C exams are held once every week. These exams are electronically graded akin to the ones held by popular coding challenge websites. There are currently 2 levels: beginner and intermediate. The beginner exam focuses on fundamental C concepts, whereas the intermediate exam focuses more on algorithms. Passing an exam entails obtaining a high aggregate score (75+ for beginner, 84+ for intermediate) across multiple attempts.
I solved all the intermediate exam problems and created an answer key [here](https://github.com/kraxx/42_C_Exam_Intermediate)
