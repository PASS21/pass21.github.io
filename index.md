![Made with Doom Emacs](https://img.shields.io/badge/Made_with-Doom_Emacs-blueviolet.svg?style=rounded&logo=GNU%20Emacs&logoColor=white) 


---
### Created by [Sai Pranav](https://github.com/maddisaipranav), [ZeStig](https://github.com/ZeRealStig), [Srinath](https://github.com/Srinath-Anand) and Aadhil

| Contents:                              |
|----------------------------------------|
| [Introduction to Python](#introduction-to-python)           |
| [IDEs for Python](#ides-for-python) |
| [Python distributions](#python-distributions) |
| [Popular applications written in  Python](#popular-applications-written-in-python) |
| [Modules used](#modules-used) |
| [Why we chose Python](#why-we-chose-python)                   |
| [A _brief_ explanation of the code](#how-the-program-works)      |
| [How can I get the code?](#how-can-i-get-the-code-)               |
| [Acknowledgements](#acknowledgements)                    |

<!--- https://github.com/PASS21/docs/blob/main/index.md#Python-Distributions -->

## Introduction to Python
![Python Img](https://downloadly.net/wp-content/uploads/2020/03/The-Complete-Python-Programming-Course-for-Beginners-300x300.jpg)

Python is a [dynamic](https://wikipedia.org/wiki/Dynamic_Programming_Language) interpreted [high-level](https://en.wikipedia.org/wiki/High-level_programming_language) language. It is designed to emphasise readability , and is well-known for its significant usage of *code indentation* .

It recently overtook *C* and *Java* to become the most popular programming language in the [TIOBE Index](https://tiobe.com/tiobe-index); this is primarily because Python is easily among the most multi-paradigm programming languages out there - with its extensive *Machine Learning* support bringing in thousands of new learners every month !
Studies have shown that scripting languages like *Python* are more productive than conventional laguages like *C* and *Java*

The latest (stable) version of Python , version `3.10.2` , has optional support for [Static typing](https://developer.mozilla.org/en-us/docs/Glossary/Static_typing), among a host of other features .

## IDEs for Python 
- [Atom](https://atom.io)
- [PyDev](https://pydev.org)
- [Doom Emacs](https://github.com/hlissner/doom-emacs)
- [Spyder](https://Spyder-ide.org)
- [Visual Studio Code](https://code.visualstudio.com)
- [PyCharm](https://jetbrains.com/PyCharm)
- [Visual Studio Community](https://aka.ms/vs)
- [Jupyter Notebooks](https://jupyter.org)


## Python distributions
- Anaconda (uses `conda` as well as `pip` )
- Miniconda (uses `conda` as well as `pip` ) (*recommended*)
- Enthought Canopy
- "Standard" Python install (uses the bundled `pip` )

## Popular applications written in Python
- [Dropbox](https://dropbox.com)
- [Reddit](https://reddit.com)
- [Facebook(backend)](https://facebook.com)
- [Blender](https://blender.org)
- [Pip (the Python package manager - bootstrapped)](https://pip.pypa.io/en/stable/)
- [SageMath](https://sagemath.org)
- [Spyder IDE](https://spyder-ide.org)
- [Google App Engine](https://cloud.google.com/appengine/)
- **Google search engine's entire ML backend uses** [Tensorflow](https://tensorflow.org) - **one of the most popular ML Libraries**

*Note: Julia, Go , Swift , Ruby and Coffeescript are among the languages inspired by the Pythonic syntax*

-----
## Modules used
- [Pandas](https://pandas.pydata.io): \
    Pandas provides a fast,flexible and expressive way to make working with data a breeze . It aims to be the building block for high level data analysis in Python.
    
- [PwnedPasswords](https://pypi.org/project/pwnedpasswords/): \
    *pwnedpasswords* is a small utlilty that checks [HaveIBeenPwned](https://haveibeenpwned.com) and tells you if your password(s) has/have been breached , and how many times.
    
- [SymPy](https://sympy.org): \
    *SymPy* is a Python library - written entirely in Python - that aims to become a full-featured CAS covering the (vast) domains of Physics and Maths . It strives to keep the code as simple as possible, while still being very extensible.
    
-----
## Why we chose Python
- Even though Python has a reputation for being a very slow language , it is super beginner-friendly . It is very extensible and lets beginners build huge projects very easily.
- It has excellent support for libraries capable of manipulating files in a myriad ways.

-----
 
## How the program works

- imports passwords from the browser
- asks the user if he/she wants to see the passwords , and accordingly displays the passwords
- opens the passwords file and writes new logins into it 
- obscures password inputs using the *getpass* module
- lets users modify already saved passwords
- includes a helper script to install the required dependencies

-----
## How can I get the code ?
   1) Visit our [GitHub page](https://github.com/PASS21/Password-Analysis-and-Storage-System) 
   
   2) If you don't have `Git` installed , get Git for [Windows](https://gitforwindows.org), [Linux](https://git-scm.com/download/linux) and [macOS](https://git-scm.com/download/mac) here. 


   3) Open the Command Prompt (Windows) or Terminal (macOS/Linux) and type 
   > `git clone https://github.com/pass21/Password-Analysis-and-Storage-System` 
   
   4) Run the program to install all the required dependencies.[^1]

## Acknowledgements
- [GeeksForGeeks](https://geeksforgeeks.org)
- [Pandas](https://pandas.pydata.org)
- [Wikipedia](https://wikipedia.org)

[^1]: Note: You need to have Jupyter Notebook installed* - type `pip install jupyter` *from the terminal or Command Prompt.*
