## Data Cleaning 101 

Welcome to the code repository for Practical Data Cleaning with Python! This is a two-day training offered through Safari with O'Reilly media. You can sign up by searching for the course on Safari.

This course aims to give you a practical overview of data cleaning and validation libraries and methods in Python. Since we only have 6 hours, it can't go massively in-depth into any one library or tool, but I have tried to include useful tools I have found in my work and incorporate a mixture of the munging and testing I have seen in my own and others workflows. 

If you have a suggestion for another library or additional topic, feel free to drop me a line :)

### Installation

These lessons has been tested for Python 3.4 and Python 3.6 and primarily uses the latest release of each library, except where versions are pinned. You likely can run most of the code with older releases, but if you run into an issue, try upgrading the library in question first.

```pip install -r install_reqs.txt```


I believe this will also work with Conda, although I am less familiar with Conda so please report issues!

```conda install --yes --file conda_reqs.txt```

You will then need to `pip install dedupe` (this is not yet available via Conda).

In addition, you will need to install [sqlite3](https://www.sqlite.org/) or make changes to the second day case study with a connection string to your database of choice. [more info](https://dataset.readthedocs.io/en/latest/quickstart.html#connecting-to-a-database)

### Repository structure

Each day coincides with a particular notebook folder. For day one, we will use `cleaning-notebooks`. Day two will focus on `validation-notebooks`. The `data` folder holds data we will use throughout the course. The `queue_example.py` file is used in the day two case study.


### Python2 v. Python3

This repository has been built with Python 3. If you are using Python 2 and need help porting some logic or finding alternatives, please let me know and I will try and help. :)

### Corrections?

If you find any issues in these code examples, feel free to submit an Issue or Pull Request. I appreciate your input!

### Questions?

Reach out to @kjam on Twitter or GitHub. @kjam is also often on freenode. :)
