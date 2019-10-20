# Practical E: Writing your own functions

## Practical Learning Outcomes

This practical looks at how to write your own functions in Python. Functions
are really useful when a program needs to the same thing more than once and
they are crucial in producing readable code that can be maintained by others. 

By the end of Practical E you will be able to:
* Write your own functions
* Understand how to define function arguments, including default arguments.
* Understand how to return and use a value from a function
* Know how to define a docstring describing a function and how to examine
  docstrings using help.

## Preparation
To prepare for this practical you should first work through:

*  *Chapter 1 Writing your own functions*

from the
[DataCamp](https://www.datacamp.com/)
online course: [Python Data Science Toolbox (Part 1)
](https://campus.datacamp.com/courses/python-data-science-toolbox-part-1/),
but stop at the *'Bringing it all together'* video (as this uses functions
with Pandas and dictionaries that we have not yet tackled).

We will then use what you have learnt there to explore how Python functions
can be useful in biological applications. 

## The Practical
To use this practical you should *either*:

* If you are using Azure Notebooks import the practical as a library into your Azure Notebooks account,
  by clicking on (and then accepting default options):\
  [![Azure Notebooks](https://notebooks.azure.com/launch.png)
  ](https://notebooks.azure.com/import/gh/ARU-Bioinf-IBDS/prac-E/)

* *Or* if you are using Google Colab then:
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) workbook_E.ipynb](
    https://colab.research.google.com/github/ARU-Bioinf-IBDS/prac-E/blob/master/workbook_E.ipynb) 
    then *COPY TO DRIVE*.
  * [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg) homework_E.ipynb](
    https://colab.research.google.com/github/ARU-Bioinf-IBDS/prac-E/blob/master/homework_E.ipynb) 
    then *COPY TO DRIVE*.  

* *Or* if you are using a local Jupyter Notebook installation, then 
  * download [workbook_E.ipynb](
    https://raw.githubusercontent.com/ARU-Bioinf-IBDS/prac-E/master/workbook_E.ipynb)
    by right clicking on the link and selecting *"Save Link As"*
  * download [homework_E.ipynb](
    https://raw.githubusercontent.com/ARU-Bioinf-IBDS/prac-E/master/homework_E.ipynb)
    by right clicking on the link and selecting *"Save Link As"*

  Once you have downloaded the notebooks move them to a directory where you are
  storing your work for this module (I would advise calling this `IBDS` and placing this in a
  folder that is automatically backed up to OneDrive, GoogleDrive or similar). 

If this unfamiliar, please go back and look at 
  [Practical A](https://github.com/ARU-Bioinf-IBDS/prac-A) 


Then in Azure Notebooks or Jupyter Notebook:
* open the workbook **workbook_E.ipynb** and work through it.
* once you have completed the workbook, then move onto the homework book **homework_E.ipynb**
* then go on to [Reflection on Practical E: writing your own functions](
  https://canvas.anglia.ac.uk/courses/12178/discussion_topics/10955.

-------------------------

> This exercise is part of 
> [Introduction to Bioinformatics and Data Science, Practicals](https://github.com/ARU-Bioinf-IBDS/index/)
>
> Original author: [Oliver S. Smart](https://www.linkedin.com/in/osmart/),
> developed for [BSc (Hons) Bioinformatics Degree Apprenticeship](
  https://www.anglia.ac.uk/bioinformatician),
> [School of Life Sciences](https://www.anglia.ac.uk/science-and-engineering/life-sciences),
> Anglia Ruskin University
> Copyright (c) 2018-2019 Anglia Ruskin University

> <img src="https://aru-bioinf-ibds.github.io./images/DataCamp_Horizontal_RGB.svg" width="150"> 
>
> **A big thanks to [DataCamp](https://www.datacamp.com/) for supporting this class!**
