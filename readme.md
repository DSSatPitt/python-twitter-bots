# Tutorial on Python Twitter Bots


## Description in Plain English
This is a Twitter Bot tutorial [@mcburton](http://twitter.com/mcburton) put together for [Annette Vee's](http://twitter.com/anetv) course on [computational media](http://www.annettevee.com/2015fall_computationalmedia/). The workshop was a blast and if anyone wants to use this tutorial please let me know.

This README is sparse, please see the Jupyter Notebook [index.ipynb](index.ipynb) for all the juicy details.



## Live Demo
You can now run this tutorial LIVE using [Binder](http://mybinder.org/) by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/DSSatPitt/python-twitter-bots)

**NOTE:** There is a unicode bug opening the text file when running this tutorial on Binders that I haven't fixed yet.
```python
# open Robin's Edgar Allen Poe data file and read every line into memory
with open('data/thats-so-raven.txt','r') as filename:
    lines = filename.readlines()
```
This code cell should be tweaked to explicitly declare the encoding:
```python
# open Robin's Edgar Allen Poe data file and read every line into memory
with open('data/thats-so-raven.txt','r', encoding='utf-8') as filename:
    lines = filename.readlines()
```

## How to Install

These instructions assume experience with the unix/linux command line and installing/running Python.

If you want to run this tutorial on your own machine you need to have [Jupyter](https://jupyter.org/) installed. I recommend reading [their documentation about installing Jupyter and Jupyter Notebooks.](http://jupyter.readthedocs.org/en/latest/install.html#how-to-install-jupyter-notebook)

Once you have Jupyter installed you should clone this repository to your local machine. You will install the [tweepy](http://www.tweepy.org/) python library (from requirements.txt) and then launch a Jupyter Notebook from within the repository directory.

```bash
git clone https://github.com/DSSatPitt/python-twitter-bots.git
cd python-twitter-bots
pip install -r requirements.txt
jupyter notebook
```

These are very quick and dirty instructions, please contact me if you have further questions.


## License



[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)
