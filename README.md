# IMPORTANT

**If you're planning to code along, make sure to clone, download, or re-pull this repository on the morning of Thursday February 22rd. All edits will be completed by end of day ET Wednesday February 21st.**


# Facebool Live Code Along: A DataFramed special
DataCamp Facebook Live Code Along Session 4: Learn techniques that guests on the DataFramed podcast say are their favorite. Enjoy!


# The favourite techniques of the experts

with Hugo Bowne-Anderson. Follow him on twitter [@hugobowne](https://twitter.com/hugobowne)

DataCamp's Hugo Bowne-Anderson has recently launched a new data science podcast called [`DataFramed`](https://www.datacamp.com/community/podcast), in which he speaks with experts and thought leaders from academia and industry about what data science looks like in practice and how it's changing society. In this _special live coding session_, Hugo will take you through techniques that his guests have professed to be their favourite data sciencey techniques. Join us for this live, intereactive code along and to find out the favorite techniques of DataFramed's first guests, which include Hilary Mason (Cloudera Fast Forward Labs), Chris Volinsky (AT&T), Claudia Perlich (Two Sigma), Robert Chang (airbnb), Jake VanderPlas (University of Washington, Google) and many more! Among other things we'll be checking out some of their favourite data visualization _and_ machine learning techniques, such as decision trees, many types of regression and principal component analysis!

Join Hugo live on Thursday, February 22nd, at 3:00pm ET on Facebook!

<p align="center">
<img src="img/DataFramed 1400x1400.png" width="600">
</p>


## Prerequisites

Not a lot. It would help if you knew

* programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about `pandas` and DataFrames;
* a bit about Jupyter Notebooks;
* your way around the terminal/shell.


**However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.**

Also, if you'd like to watch and **not** code along, you'll also have a great time and these notebooks will be downloadable afterwards also.

If you are going to code along and use the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below), I ask that you install it before the session.

## Getting set up computationally

### 1. Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/datacamp/datacamp_facebook_live_dataframed
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `datacamp_facebook_live_dataframed` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called fb_live_dataframed. To activate the environment on OSX/Linux, execute

```
source activate fb_live_dataframed
```
On Windows, execute

```
activate fb_live_dataframed
```


### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`.

Then open the first notebook and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.
