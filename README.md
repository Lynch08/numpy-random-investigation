# numpy-random-investigation
**Investigation of the numpy.random package**


**Assignment:** Programming for Data Analysis, GMIT 2021  

**Lecturer:** Dr Brian McGinley  

**Author:** Enda Lynch   
**Github Username:** Lynch08  
**GMIT Email:** G003987951@gmit.ie  
**Personal Email:** E.Lynch@Kostal.com  

##### Background   
This is my assignment project for the Programming for Data Analysis module, Galway-Mayo Institute of Technology, 2021.  

This GitHub repository documents my initial research, project progress (git version control) and findings.

##### Github Repository

**URL:** https://github.com/Lynch08/numpy-random-investigation  

The repository contains:
 - 1 jupyter notebook (numpy-random.ipynb) that holds the explanation, code, visuals and citeations for the assignment.
 - The Assignment details in PDF form from Dr Brian McGinley 
 - A requirments.txt file that contains all of the dependancies required to run the assignment in the same environment
 - An Images folder where I have stored some PNG files to display in the notebook
 - A readme file explaining the objectives, outcomes and instructions on how to view the notebook in both editable and static format.
 
### Assignment Objectives  
The assignment details the numpy.random package, a part of NumPy library for Python.  

See the Assignment Instructions [here](./ProgDA_Assignment.pdf)

**The Primary Objectives are as follows:**

 - To explain the overall purpose of the package.
 - To explain the use of the "Simple random data" and "Permutations" functions.
 - To explain the use and purpose of at least five "Distributions" functions.
 - To explain the use of seeds in generating pseudo-random numbers.
 - The detailed instructions can be found in the assignment description linked above (pdf).

This project is intended to further familiarisation with data analytics. It is also intended to get familiar with the analytical tools, specifically the NumPy library and its random sampling module. The project will allow to get practical understanding of handling data in Python environment.

As it is a learning exercise for me, I have made attempt to try and comment various functionalities not only for readability but also for my future reference.

**Planned Project Outcomes**
 - To gain experience in project time management by break the project down into small manageable tasks.  
 - To gain an understanding of the functionality of the NumPy library and how some of its functions work, such as the seed.
 - To integrate the skills I had acquired in my first semester with the first 10 weeks of the Programming in Data Analysis module to analyse the library and present a cohesieve and interesting project.  
 - To expand my knowledge of the python libraries and tools to make the code as simple and readable as possible for the reader.  
 - To learn how to best optimise my time between research, programming, problem-solving and analysis.


### Assignment delivery
The project is stored in this GitHub [repository] (https://github.com/Lynch08/numpy-random-investigation).

This README.md file contains background information and introduction to the assignment.

The assignment has been done within the Jupyter Notebook numpy-random.ipynb, stored in this repository.

In the notebook I have conducted the research and described the assignment progress. It is illustrated the applied concepts and methods together with relevant code snippets. The notebook includes also the calculated outputs and plots with accompanied description. Finally, inside the notebook I have included also references to sources being consulted for this assignment.


### View Notebook in Static Format(Online)

If you wish to view the notebook in static (uneditable) format click here:  
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Lynch08/numpy-random-investigation/blob/86648f030548ae171d294aa48f19e1ac12f80650/numpy-random.ipynb)

### How to download this repository (editable version)

- Go to GitHub.
- Go to my repository: https://github.com/Lynch08/numpy-random-investigation
- Click the clone/download button.
- Save the repository to a local folder location on your machine.
- You will need to navigate to this folder location on the command line in order to run the program.
- Details on how to run each individual script in this repository is included later in this Readme file.

### Running the Jupyter Notebook

 - On the command line navigate to the folder location where the repository has been downloaded and saved to using the cd command to change directory.
 - Type jupyter lab on the command line and press enter
 - After a short wait jupyter notebook will open in your web browser (I would suggest Chrome).
 - Open the numpy.random.ipynb notebook in the browser and the notebook containing the code and comments that I wrote for this assignment will be displayed.
 - Before beginning I would suggest going to the Kernel option on the menu bar and if you want to run the notebook yourself choose "Restart Kernel and Clear Outputs". If you want the notebook to run automatically choose "Restart Kernel and Run All Cells"
 - If you want to run the code in any particular cell, click into the cell, hold down the shift key, press enter and the command will run and the output wil be displayed in the next cell.
 - To change between edit and read mode at any time press the ESC key.
 - When you have finished viewing the jupyter notebook close the web browser and return to the command line. Press Ctrl + C on the command line to kill the program.

### Dependancies 

I have a requirements.txt file that you can use to install all of the dependencies required to run the notebook in the exact same environment - however below are the main dependencies if you would like to do that manually. After cloning the repository navigate to the folder using the command prompt and use the ```pip install``` command if you want to use the requirments.txt file.
See this video for full instructions on how to install: https://www.youtube.com/watch?v=mBcmdcmZXJg 


**Required**
- Download Python environment - I recommend ([Anaconda](https://www.anaconda.com/products/individual)) 
    - Libraries to import within the python environment (all are linked to official documentation)
        - [Numpy](https://numpy.org/doc/)
        - [Pandas](https://pandas.pydata.org/docs/)
        - [Scipy](https://scipy.github.io/devdocs/index.html)
        - [matplotlib.pyplot](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.html)
        - [Seaborn](https://seaborn.pydata.org/)
        

**Not required but helpful**  
cmder - this is a command line emulator that in my opinion is easier to use and cleaner than the windows cmd window. [Download Cmder Here](https://cmder.net/)


### Python and the Libraries Used
Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Its natural functionality has been extended by development of external libraries dedicated for specific purposes. Below are listed several python libraries I used for accomplishment of this project.

- Numpy: NumPy is a library for the Python programming language, adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.

 - Pandas: Pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. It was used specifically in this project to read in the data from the csv file used.

 - Matplotlib: Matplotlib is a plotting library for the Python programming language and its numerical mathematics extension NumPy.

 - Seaborn: Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.
 
 - SciPy: SciPy provides algorithms for optimization, integration, interpolation, eigenvalue problems, algebraic equations, differential equations, statistics and many other classes of problems.

 - The assignment has been carried out using Numpy version 1.20.1 ( last updated on 20-11-2021).
 
 
### Notebook Structure
 
The notebook is broken down into 9 sections.  
In the first two sections I go through a brief explanation of what I understand the numpy library to be and its history.  
Then I explain how to install Numpy (once the dependencies above have been met) and link to the documentation if required.  
I then dive into the functionality and tools in the library. First looking at what random data is and how to generate different types.  
Then I look at how that data can be manipulated using permutations and then how it can be interpreted and analysed using different distributions.  
I look at the seed and discuss if random data is really random, and how to make your work with a random number generator reproducible.  
Finally I cite the sources I used to put the notebook together.

##### See the Table Of Contents below
Table of contents is also at the top of the notebook.

1. What is Numpy
    - 1.1 Arrays  
    - 1.2 Popular-uses-for-Numpy   
    
2. A Brief History of Numpy 

3. Installing NumPy
    - 3.1 Importing Libraries and NumPy version check  
    
4. Simple Random Data  
    - 4.1 Random Sampling is really pseudo random!!!!    
    
5. Generating "Random" Data  
    - 5.1 numpy.random.rand  
         - 5.1.1 Visualisation of rand using pyplot (uniform distribution)  
    - 5.2 numpy.random.randn  
        - 5.2.1 Visualisation of randn using pyplot (normal distribution)  
    - 5.3 numpy.random.randint  
    - 5.4 numpy.random.generator.choice  
        - 5.4.1 Assigning Probability  
    - 5.5 numpy.random.RandomState.bytes  
    - 5.6 numpy.random.Generator.integers - and a simple plot   
    
6. Permutations 
    - 6.1 Function random.shuffle  
        - 6.1.1 Using shuffle with a multi dimensional array  
    - 6.2 Function random.permutation   
    
7. Distributions
    - 7.1 Uniform Distribution  
        - 7.1.1 Visualising Uniform Distributions  
    - 7.2 Binomial Distribution  
        - 7.2.1 What is a Binomial Distribution? Real Life Examples  
        - 7.2.2 Visualisation of Binomial Distribution  
        - 7.2.3 Binomal vs Normal Distribution  
    - 7.3 The Poisson Distribution  
        - 7.3.1 Assumptions of the Poisson Distribution  
        - 7.3.2 Probability Mass Function (PMF)  
        - 7.3.3 Poisson distribution in Numpy  
        - 7.3.4 Visualisation of Poisson Distribution  
        - 7.3.5 Normal Distribution vs Poisson Distribution  
        - 7.3.6 Poisson Distribution vs Binomial Distribution  
    - 7.4 Exponential Distribution  
        - 7.4.1 Visualisation of Exponential Distribution  
    - 7.5 Hypergeometric Distribution    
    
8. Seed 
    - 8.1 Random or Pseudo Random??  
    - 8.2 Why would we need to "SEED" data from an RNG???  
    - 8.3 Using the Seed  

9. Citations 
