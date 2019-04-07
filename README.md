# dand-workshops

![alt text](https://github.com/udacity/dand-workshops/blob/master/images/DAND-workshops.jpg "Real-World Data Science")

### Note for Data Analyst Nanodegree Students

The coursework in your Udacity classroom will make you a good Data Analyst. But, more practice didn't harm anyone. These workshops give you opportunities to collaborate with your fellow students, mentor and work on some real-world problems.

### Setting up Your Own Environment

Udacity workspaces are great! But, we should all know how to setup and maintain our own environments.

1. Python 3.6 or higher: Udacity courses and most professional environments use the newest version of Python.
2. Anaconda: Anaconda includes a great distribution of libraries and software built for data science.

Instructions to install Anaconda:
[Windows](https://docs.anaconda.com/anaconda/install/windows/)

[Linux](https://docs.anaconda.com/anaconda/install/linux/)

[macOS](https://docs.anaconda.com/anaconda/install/mac-os/)

- Git and version control

  These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:

  ```
  conda install git 
  ```

  

  If you'd like to learn more about version control and using `git` from the command line, take a look at our [free course: Version Control with Git](<https://in.udacity.com/course/version-control-with-git--ud123>)

- Create (and activate) a new environment, named `dand-env` with Python 3.6. If prompted to proceed with the install `(Proceed [y]/n)` type y.

  - **Linux** or **Mac**:

  ```
  conda create -n dand-env python=3.6
  source activate dand-env
  ```

  - **Windows**:

  ```
  conda create --name dand-env python=3.6
  activate dand-env
  ```