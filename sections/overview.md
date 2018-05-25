# Overview

This tutorial will give a brief overview of the considerations and tools involved in basic text analysis with Python. By completing this tutorial, you will have a general sense of how to turn text into data using the Python package, NLTK. You will also be able to take publicly available text files and transform them into a corpus that you can perform your own analysis on. Finally, you will have some insight into the types of questions that can be addressed with text analysis. 

# Cloning the repository

Before getting started, clone [this repository]() to your local machine. Instructions for cloning Git repositories can be found [here](https://github.com/DHRI-Curriculum/git/blob/master/sections/cloning.md).

# Getting Started

You already installed the [Anaconda](https://www.anaconda.com/download/) distribution of Python 3. You will need nltk and matplotlib to complete this tutorial, both packages come installed with Anaconda. To check to be sure you have them, open a new Jupyter Notebook (or any IDE to run Python).

Find Anaconda on your computer, Launch a Jupyter Notebook. 

![jupyter](https://github.com/michellejm/NLTK_DHRI/blob/master/Images/jupyter.png)

It will open in the browser. All of the directories (folders) in your home directory will appear. For now, select 'New' >> Python3 in the upper right corner.

![jupyter](https://github.com/michellejm/NLTK_DHRI/blob/master/Images/jupyter1.png)

A blank page with an empty box should appear.

![jupyter](https://github.com/michellejm/NLTK_DHRI/blob/master/Images/jupyter2.png)

We want to double check that everything is installed, so first we will check for the packages we will definitely use. In the box, type:

`import nltk`

`import matplotlib`

Press **Shift** + **Enter** to run the cell (or click run at the top of the page). 

![jupyter](https://github.com/michellejm/NLTK_DHRI/blob/master/Images/jupyter3.png)

If nothing happens, they are installed and you are ready to move on! If you get an error message, either you have a typo or they are not installed. First double check your spelling, then revisit the [installation instructions LINK TO INSTALL](). 

<!-- 
If nothing happens, they are installed and you are ready to move on! If you get an error message, either you have a typo or they are not installed. If it is the later, open the command line and type:

`pip install nltk`

`pip install matplotlib`


Now we need to install the nltk corpus. This is very large and may take some time if you are on a weak connection. 

In the next cell, type:

`nltk.download()` and run the cell.

The NLTK downloader should appear. Please install all of the packages. If you are short on time, focus on 'book' for this tutorial, and come back to this step. 

Yours will look a little different, but the same interface. Click on the 'all' option and then 'Download'. Once they all trun green, you can close the Downloader dialogue box.

![nltk downloader](https://github.com/michellejm/NLTK_DHRI/blob/master/Images/nltk.png)
 -->


In the next cell of your Jupyter Notebook, type:

`from nltk.book import *`

A list of books should appear. If this happens great! If not, return to the downloader to make sure everything is ok.

Close this Notebook without saving - the only purpose was to check if we have the appropriate packages installed.