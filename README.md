# Open Source Macroeconomics Laboratory (OSM Lab) Boot Camp 2017

This public repository contains the training materials, tutorials, and code for the seven-week Boot Camp of the Open Source Macroeconomics Laboratory (OSM Lab) at Becker Friedman Institute of the University of Chicago, June 19 to August 4. The OSM Lab was founded by Dr. Richard W. Evans, Senior Lecturer at the University of Chicago M.A. Program in Computational Social Science and Fellow at the Becker Friedman Institute. The OSM Lab is funded primarily from a 5-year grant from the Charles Koch Foundation. Part of this grant also included the creation of the Dynamic Analysis Center at the Baker Institute at Rice University, which is directed by John Diamond.

This `README.md` serves as a syllabus and reference for the OSM Lab Boot Camp. This document has 11 sections.

1. [OSM Lab leadership](https://github.com/OpenSourceMacro/BootCamp2017#1-osm-lab-leadership)
2. [Boot Camp schedule](https://github.com/OpenSourceMacro/BootCamp2017#2-boot-camp-schedule)
3. [Instructions for installing the Anaconda distribution of Python](https://github.com/OpenSourceMacro/BootCamp2017#3-instructions-for-installing-the-anaconda-distribution-of-python)
4. [Text editor suggestions](https://github.com/OpenSourceMacro/BootCamp2017#4-text-editor-suggestions)
5. [PEP 8, docstring commenting, and module structure](https://github.com/OpenSourceMacro/BootCamp2017#5-pep-8-docstring-commenting-and-module-structure)
6. [Using LaTeX](https://github.com/OpenSourceMacro/BootCamp2017#6-using-latex)
7. [Git and GitHub.com tutorial](https://github.com/OpenSourceMacro/BootCamp2017#7-git-and-github-tutorial)
8. [Jupyter notebooks](https://github.com/OpenSourceMacro/BootCamp2017#8-jupyter-notebooks)
9. [Python tutorials](https://github.com/OpenSourceMacro/BootCamp2017#9-python-tutorials)
10. [C++ tutorials](https://github.com/OpenSourceMacro/BootCamp2017#10-c-tutorials)
11. [References](https://github.com/OpenSourceMacro/BootCamp2017#11-references)


## 1. OSM Lab Leadership

**Director: [Dr. Richard W. Evans](https://sites.google.com/site/rickecon/) [(rwevans@uchicago.edu)](mailto:rwevans@uchicago.edu).** The Director and Founder of the OSM Lab is [Richard W. Evans](https://sites.google.com/site/rickecon/). Dr. Evans is a Senior Lecturer at the University of Chicago and a Fellow at the Becker Friedman Institute.

**Logistics and finances: Grace Hammond, Becker Friedman Institute [(gohammond@uchicago.edu)](mailto:gohammond@uchicago.edu)**: Grace Hammond is the Associate Director for Operations, Programs, and Finance at the Becker Friedman Institute. She coordinates the student and instructor travel, housing, and financial matters.

**Instructors.** The OSM Lab has excellent instructors and presenters from economics, math, and computation. Below is a list of this year's instructors and presenters in alphabetical order by last name. To see what they teach and when, check the respective [math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math), [econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ), and [computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) detailed schedule pages.

Senior Instructors and Presenters
* [Jorge Barro](http://www.jorgebarro.com/), Rice University
* [Jason DeBacker](http://www.jasondebacker.com/), University of South Carolina
* [Richard Evans](https://sites.google.com/site/rickecon/), University of Chicago
* [Lars Hansen](http://larspeterhansen.org/), University of Chicago
* [Matthew Jensen](http://www.aei.org/scholar/matthew-h-jensen/), Open Source Policy Center, American Enterprise Institute
* [Greg Kaplan](https://gregkaplan.uchicago.edu/), University of Chicago
* [Casey Mulligan](https://economics.uchicago.edu/directory/casey-mulligan), University of Chicago
* [Kerk Phillips](https://sites.google.com/site/kerkphillips/home), Brigham Young University
* [Thomas Sargent](http://www.tomsargent.com/), New York University
* [Simon Scheidegger](https://sites.google.com/site/simonscheidegger/), University of Zurich and Hoover Institution
* [Karl Schmedders](http://www.business.uzh.ch/en/professorships/qba/members/schmedders.html), University of Zurich
* [John Stachurski](http://johnstachurski.net/), Australia National University
* [Viktor Tsyrennikov](https://sites.google.com/site/vtsyrennikov/), Promontory Financial Group

Graduate Instructors
* [Zachary Boyd](http://www.math.ucla.edu/~zach.boyd/), University of California Los Angeles
* Justin Gardiner, Northwestern University
* John Van den Berghe, University of Chicago


## 2. Boot Camp Schedule

The OSM Lab Boot Camp begins on Monday, June 19 and ends on Friday, August 4. Classes will be held Monday through Friday, 8am to noon in Saieh Hall, Room 247 at the University of Chicago. Breakfast will be served every day from 7:15-8:00am. The curriculum consists of equal parts math, economic theory, and computational methods.

|      Broad topic      | Days of week |      Time      |
|:--------------------- |:------------ | --------------:|
| [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) | M, W, F |  8:00-9:50am   |
| [Economics](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) | M, W, F | 10:00-11:50am  |
| [Computational Methods](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) | T, Th | 8:00 - 11:50am |

Below is a summary schedule of topics. More detailed schedules are on the respective [math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule), [econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ), and [computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) detailed schedule pages.

### Week 1

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
6-19  | M   | Introduction | Overlapping generations |              | [Casey Mulligan](https://economics.uchicago.edu/directory/casey-mulligan), "CAD Reasoning for Theory Problems" |
6-20  | T   |              |                         | Python intro, standard library |     |
6-21  | W   | Prob & stats | Overlapping generations |              |     |
6-22  | Th  |              |                         | Object oriented programming |     |
6-23  | F   | Prob & stats | Overlapping generations |              |     |

### Week 2

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
6-26  | M   | Inner product spaces | Dynamic programming |                     |     |
6-27  | T   |                      |                     | Data visualization  |     |
6-28  | W   | Inner product spaces | Dynamic programming |                     | [Greg Kaplan](https://gregkaplan.uchicago.edu/), "Macro, Inequality, and Computation" |
6-29  | Th  |                      |                     | Pandas |     |
6-30  | F   | Inner product spaces | Dynamic programming |                     |     |

### Week 3

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
7-3  | M   | NO CLASSES: HOLIDAY | NO CLASSES: HOLIDAY | NO CLASSES: HOLIDAY  |     |
7-4  | T   | NO CLASSES: HOLIDAY | NO CLASSES: HOLIDAY | NO CLASSES: HOLIDAY  |     |
7-5  | W   | Spectral theory     | Firm dynamics       |                      |     |
7-6  | Th  |                     |                     | Sparse matrices, SVD |     |
7-7  | F   | Spectral theory     | Firm dynamics       |                      | [Matt Jensen](http://www.aei.org/scholar/matthew-h-jensen/) |

### Week 4

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
7-10  | M   | Continuous optimization | Firm dynamics              |                     |     |
7-11  | T   |                         |                            | Data visualization  |     |
7-12  | W   | Continuous optimization | Structural estimation: MLE |                     | [Lars Hansen](http://larspeterhansen.org/) |
7-13  | Th  |                         |                            | Root find, minimize |     |
7-14  | F   | Convex analysis         | Structural estimation: GMM |                     |     |

### Week 5

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
7-17  | M   | Convex analysis     | Structural estimation: SMM |                  |     |
7-18  | T   |                     |                            | Large data       |     |
7-19  | W   | Convex analysis     | DSGE modeling              |                  |     |
7-20  | Th  |                     |                            | High dimensional approx. |     |
7-21  | F   | Linear optimization | DSGE linear approximation  |                  | [Simon Scheidegger](https://sites.google.com/site/simonscheidegger/) "HPC in Economics" |

### Week 6

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
7-24  | M   | Linear optimization    | Perturbation methods      |                      |     |
7-25  | T   |                        |                           | HPC/parallel compute |     |
7-26  | W   | Linear optimization    | Filtering and cyclicality |                      |     |
7-27  | Th  |                        |                           | HPC/parallel compute |     |
7-28  | F   | Nonlinear optimization | Macro-financial modeling  |                      | TBA |

### Week 7

| Date | Day | [Math](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Math#schedule) (8-10am) | [Econ](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Econ) (10am-noon) | [Computation](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Computation) (8am-noon) | Lunch speaker |
|:---:|:---:|:--- |:--- |:--- |:--- |
7-31 | M   | Nonlinear optimization | Macro-financial modeling |                      |     |
8-1  | T   |                        |                          | HPC/parallel compute |     |
8-2  | W   | Nonlinear optimization | Macro-financial modeling |                      |     |
8-3  | Th  |                        |                          | HPC/parallel compute |     |
8-4  | F   | [Conclusion:](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Conclusion_BootCamp.pdf) Hwk due    | [Conclusion:](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Conclusion_BootCamp.pdf) Hwk due      | [Conclusion:](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Conclusion_BootCamp.pdf) Hwk due  | TBA |

This will be an intensive seven weeks. We expect that your attendance of lectures plus homework time will average 60 hours per week of work.

Have provided 7 areas of tutorials that you benefit from reading before the training. We will, of course, teach these things as we go through the material. But we will be able to proceed at a faster pace if the attendees are already familiar with most of the concepts below.

Pre-course Tutorial Areas

1. Instructions for installing the Anaconda distribution of Python
2. Text editor suggestions (Atom, Sublime Text 3, Vim)
3. PEP8, docstring commenting, and module structure
4. Git and GitHub tutorial
5. Jupyter Notebooks
6. Basic Python tutorials (data structures, logic, functions and modules, pandas, root finders and minimizers)


## 3. Instructions for installing the Anaconda distribution of Python

We will be using the [Python](https://www.python.org/) programming language and many of its powerful libraries for writing the code that will run most of the computational methods we will use during the Boot Camp. Using an open source language, such as Python, has the advantage of being free and accessible for anyone who wishes to learn these materials or contribute to these projects. Being open source also allows Python users to go into the source code of any function to modify it to suit one's needs.

We recommend that each participant download the Anaconda distribution of Python provided by [Continuum Analytics](https://www.continuum.io/). We recommend the most recent stable version of Python, which is currently Python 3.6. This can be done from the [Anaconda download page](https://www.continuum.io/downloads) for Windows, Mac OSX, and Linux machines.


## 4. Text editor suggestions

In our recommended Python development workflow, you will write Python scripts and modules (`*.py` files) in a text editor. Then you will run those scripts from your terminal. You will want a capable text editor for developing your code. Many capable text editors exist, but we recommend three.

1. [Atom](https://atom.io)
2. [Sublime Text 3](https://www.sublimetext.com)
3. [Vim](http://www.vim.org)

Atom and Vim are completely free. A trial version of Sublime Text 3 is available for free, but a licensed version is $70 (US dollars). In the following subsections, we give some of the details of each of the above three text editors.


### 4.1. Atom

[Atom](https://atom.io) is an open source text editor developed by people at GitHub.com. This editor has all the features of Sublime Text 3, but it also allows users full customizability. Further, it has been a while now that the users of Atom have surpassed the critical mass necessary to keep the editor progressing with the most cutting edge additions.

There are several packages you'll want to install with Atom.  Once Atom is installed, you can add packages by navigating Atom->Preferences->Install and then typing in the name of the package you would like to install.  

For work with Python, we recommend the following packages be installed:

* MagicPython
* python-indent
* tabs-to-spaces
* minimap
* open-recent
* linter-python-pep8

For development with GitHub we recommend:

* merge-conflict

If using LaTex in this editor, the following packages are helpful:

* atom-latex
* latextools
* autocomplete-bibtex
* dictionary
* latexer
* pdf-view

In addition, you will also want to download the [Skim](http://skim-app.sourceforge.net) PDF viewer to aid in displaying PDF files compiled from TeX with Atom.


### 4.2. Sublime Text 3

[Sublime Text 3](https://www.sublimetext.com) is the most widely used and versatile private software text editor. It has tremendous flexibility, as well as the polish of a piece of professional software. Sublime Text 3 will cost $70 for a license, although you can use a trial version indefinitely without charge while only having to suffer through frequent reminders to buy the full version.


### 4.3. Vim

[Vim](http://www.vim.org) is free and very powerful. Vim is the hard core developer's text editor of choice. The learning curve for using vim is a little steeper than that of Atom and Sublime Text 3, but it also has some advantages for efficient programming. Vim has navigation that does not use a mouse or trackpad. Eventually, your fingers never leave your keyboard. Further, most terminals have Vim built in so you can use Vim to edit scripts and modules on the fly with your terminal session.  


## 5. PEP 8, docstring commenting, and module structure

Computer code executes some set of commands in an organized way. In every case, there are often many ways to execute a set of instructions--some ways more efficient than others. However, code has at least three functions.

1. Efficiently execute the task at hand.
2. Be accessible and usable to other programmers.
3. Be scalable and integrable with other projects and procedures.

Bill Gates is credited with the following plea for efficiency and parsimony in code writing.

> "Measuring programming progress by lines of code is like measuring aircraft building progress by weight."

Strong support for points (2) and (3) is Eagleson's Law.

> "Any code of your own that you haven't looked at for six or more months might as well have been written by someone else."

Because of the latter two characteristics, Python code has developed some conventions and best practices, some of which have been institutionalized in the [PEP 8--Style Guide for Python Code](https://www.python.org/dev/peps/pep-0008/) ("PEP" stands for Python Enhancement Proposals). Key examples PEP 8 Python coding conventions are the following.

* Indents should be 4 spaces (not tab)
* Limit all lines to a maximum of 79 characters long blocks of text being limited to 72 characters
* Use a space after a comma
* Use a space before and after arithmetic operators

In the text editors Atom, Sublime Text 3, and Vim, you can install Linter packages that highlight areas of your code that break PEP 8 rules and tell you what the violation is.

There are fewer conventions in docstring structure, but we have developed some of our own that are outlined in the [PythonFuncs.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonFuncs.ipynb) Jupyter notebook. See especially Sections 3 and 4 of the Jupyter notebook.


## 6. Using LaTeX

You will turn in all of your assignments by using the LaTeX document preparation platform. LaTeX produces documents with a sophisticated mathematical equation engine. Because LaTeX is standard in mathematical and theoretical document exposition, we will be using it in this class. The [LaTeX tutorial PDF chapter](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/LaTeX/LaTeX_tutorial.pdf) in the [`/Tutorials/LaTeX/`](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Tutorials/LaTeX) directory is a great reference for installing and running LaTeX. We have also included in that directory a template [`LaTeX_probset_template.tex`](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/LaTeX/LaTeX_probset_template.tex) as well as the PDf file [(`LaTeX_probset_template.pdf`)](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/LaTeX/LaTeX_probset_template.pdf) generated by compiling that `.tex` file.


## 7. Git and GitHub tutorial

We have included a tutorial on using [Git and GitHub.com](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/git_tutorial.pdf) in the [Tutorials](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Tutorials) directory of this repository. Git is a powerful version control software that comes natively installed on many machines and is widely used. GitHub.com is the most widely used online platform for hosting open source projects and integrating with Git software. Git has a significant learning curve, but it is essential for large collaborations that involve software development.

A more comprehensive Git resource is [*Pro Git*](https://git-scm.com/book/en/v2), by Chacon and Straub (2014). This book is open access, and is available online at [https://git-scm.com/book/en/v2](https://git-scm.com/book/en/v2). But I like having it in my library in hard copy. This book is the difinitive guide with everything Git, and it has as its primary application the interaction between Git and GitHub. However, the workflow described in the tutorial above was hard to find in this Git book.


## 8. Jupyter Notebooks

[Jupyter notebooks](http://jupyter.org/) are files that end with the `*.ipynb` suffix. These notebooks are opened in a browser environment and are an open source web application that combines instructional text with live executable and modifyable code for many different programming platforms (e.g., Python, R, Julia). Jupyter notebooks are an ideal tool for teaching programming as they provide the code for a user to execute and they also provide the context and explanation for the code. We have provided a number of Jupyter notebooks in the [Tutorials](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Tutorials) folder of this repository.

These notebooks used to be Python-specific, and were therefore called iPython notebooks (hence the `*.ipynb` suffix). But Jupyter notebooks now support many programming languages, although the name still pays homage to Python with the vestigal "py" in "Jupyter". The notebooks execute code from the kernel of the specific programming language on your local machine.

Jupyter notebooks capability will be automatically installed with your download of the [Anaconda distribution](https://www.continuum.io/downloads) of Python. If you did not download the Anaconda distribution of Python, you can download Jupyter notebooks separately by following the instructions on the Jupyter [install page](http://jupyter.org/install.html).


### 8.1. Opening a Jupyter notebook

Once Jupyter is installed--whether through Anaconda or through the Jupyter website--you can open a Jupyter notebook by the following steps.

1. Navigate in your terminal to the folder in which the Jupyter notebook files reside. In the case of the Jupyter notebook tutorials in this repository, you would navigate to the `~/OG-JRC/Tutorials/` directory.
2. Type `jupyter notebook` at the terminal prompt.
3. A Jupyter notebook session will open in your browser, showing the available `*.ipynb` files in that directory.
4. Double click on the Jupyter notebook you would like to open.

It is worth noting that you can also simply navigate to the URL of the Jupyter notebook file in the GitHub repository on the web (e.g., [https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonReadIn.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonReadIn.ipynb)). You can read the Jupyter notebook on GitHub.com, but you cannot execute any of the cells. You can only execute the cells in the Jupyter notebook when you follow the steps above and open the file from your terminal.


### 8.2. Using an open Jupyter notebook

Once you have opened a Jupyter notebook, you will find the notebook has two main types of cells: Markdown cells and Code cells. Markdown cells have formatted Jupyter notebook markdown text, and serve primarily to present context for the coding cells. A reference for the markdown options in Jupyter notebooks is found in the [Jupyter markdown documentation page](http://jupyter-notebook.readthedocs.io/en/latest/examples/Notebook/Working%20With%20Markdown%20Cells.html).

You can edit a Markdown cell in a Jupyter notebook by double clicking on the cell and then making your changes. Make sure the cell-type box in the middle of the top menu bar is set to `Markdown`. To implement your changes in the Markdown cell, type `Shift-Enter`.

A Code cell will have a `In [ ]:` immediately to the left of the cell for input. The code in that cell can be executed by typing `Shift-Enter`. For a Code cell, the  cell-type box in the middle of the top menu bar says `Code`.


### 8.3. Closing a Jupyter notebook

When you are done with a Jupyter notebook, you first save any changes that you want to remain with the notebook. Then you close the browser windows associated with that Jupyter notebook session. You must then close the local server that was opened to run the Jupyter notebook in your terminal window. On a Mac or Windows, this is done by going to your terminal window and typing `Ctrl-C` and then selecting `y` for yes and hitting `Enter`.


## 9. Python tutorials

For this training, we have included in this repository six basic Python tutorials in the [`Tutorials`](https://github.com/OpenSourceMacro/BootCamp2017/tree/master/Tutorials) directory.

1. [PythonReadIn.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonReadIn.ipynb). This Jupyter notebook provides instruction on basic Python I/O, reading data into Python, and saving data to disk.
2. [PythonNumpyPandas.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonNumpyPandas.ipynb). This Jupyter notebook provides instruction on working with data using `NumPy` as well as Python's powerful data library `pandas`.
3. [PythonDescribe.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonDescribe.ipynb). This Jupyter notebook provides instruction on describing, slicing, and manipulating data in Python.
4. [PythonFuncs.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonFuncs.ipynb). This Jupyter notebook provides instruction on working with and writing Python functions.
5. [PythonVisualize.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonVisualize.ipynb). This Jupyter notebook provides instruction on creating visualizations in Python.
6. [PythonRootMin.ipynb](https://github.com/OpenSourceMacro/BootCamp2017/blob/master/Tutorials/PythonRootMin.ipynb). This Jupyter notebook provides instruction on implementing univariate and multivariate root finders and unconstrained and constrained minimizers using functions in the [`scipy.optimize`](https://docs.scipy.org/doc/scipy/reference/optimize.html) sub-library.

To further one's Python programming skills, a number of other great resources exist.

* The [official Python 3 tutorial site](https://docs.python.org/3/tutorial/)
* [QuantEcon.net](https://lectures.quantecon.org/py/index.html) is a site run by [Thomas Sargent](http://www.tomsargent.com/) (NYU Stern) and [John Stachurski](http://johnstachurski.net/) (Australia National University). QuantEcon has a very large number of high-quality economics focused computational tutorials in Python.
* [Python computational labs](http://www.acme.byu.edu/2016-2017-materials/) of the Applied and Computational Mathematics Emphasis at Brigham Young University
* [Code Academy's Python learning module](https://www.codecademy.com/learn/python)

In addition, a number of excellent textbooks and reference manuals are very helpful and may be available in your local library. Or you may just want to have these in your own library. Lutz (2013) is a giant 1,500-page reference manual that has an expansive collection of materials targeted at beginners. Beazley (2009) is a more concise reference but is targeted at readers with some experience using Python. Despite its focus on a particular set of tools in the Python programming language, McKinney (2013) has a great introductory section that can serve as a good starting tutorial. Further, its focus on Python's data analysis capabilities is truly one of the important features of Python. Rounding out the list is Langtangen (2010). This book's focus on scientists and engineers makes it a unique reference for optimization, wrapping C and Fortran and other scientific computing topics using Python.


## 10. C++ tutorials

Although we will be using Python for most of the Boot Camp, we will use C++ for the computational labs taught by [Simon Scheidegger](https://sites.google.com/site/simonscheidegger/) on July, 20, 25, 27,, August 1,and 3. These computational labs treat high performance computing, parallel computing, and high dimensional approximation. Using supercomputing resources is much more accessible with C++.

[TODO: Include tutorial materials here.]


## 11. References

* Beazley, David M., *Python Essential Reference*, 4th edition, Addison-Wesley (2009).
* Chacon, Scott and Ben Straub, [*Pro Git: Everything You Need To Know About Git*](https://git-scm.com/book/en/v2), 2nd edition, Apress (2014).
* Langtangen, Hans Petter, *Python Scripting for Computational Science*, Texts in Computational Science and Engineering, 3rd edition, Springer (2010).
* Lutz, Mark, *Learning Python*, 5th edition, O'Reilly Media, Inc. (2013)
* McKinney, Wes, *Python for Data Analysis*, O'Reilly Media, Inc. (2013)

