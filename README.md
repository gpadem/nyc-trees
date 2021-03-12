# Data preprocessing - NYC Trees

This project outcome belongs to **Gülce Padem** who is currently a junior Data Scientist/AI Operator in making at BeCode's Theano 2.27 promotion.

**Repository:** nyc-trees

**Type of Challenge:** Learning

**Duration:** 1 day

**Deadline:** 12/03/2021 04:00 PM

**Deployment strategy:** Github page

**Team challenge:** solo

## Mission objectives

* Be able to use pandas
* Be able to clean a data set

### The Mission

The Department of Environmental Conservation, from New York city, has recently made the news by telling the people that they needed their help. Indeed, their request is simple: They needed the people of New York city, whether young or old, to go to the nearest tree in their street and gather information about that tree. This is all in an effort to make the population aware that nature is important, even in big Metropolis like NYC. Now that they have heard back from the people, the DEC noticed that they missed a crucial step. They forgot to give the people a data collection guide, and so the data they received back is a bit messy. It is requested to clean the dataset so that they can begin to raise awareness to ecological issues, such as climate change.

### Table of Contents

* Installation
* Repository
* Visual
* Pending things to do
* Thanks
* Collaboration

### Installation

In this project the dataset was first observed on Power BI desktop version.

For requested packages, conda package manager was used. Needed packages are the following (see the parantheses for the command to install with conda):

* numpy (conda install -c conda-forge numpy)
* pandas (conda install -c conda-forge pandas)

Jupyter Notebook was installed and launched from the Conda navigator activated in the working environment.

### Repository

There are two branches under the repository.

* main
* development

At the and of the project these two were merged and the needed files are now on main.

#### Main Branch

The structure:

* README.md
* data_clean_GOOD_ENOUGH.csv
* nyc-trees-exploration.ipynb
* .gitignore
* nyc-trees.png

`README.md`
You are reading it now. It is important to read the whole file before forking or cloning.

`data_clean_GOOD_ENOUGH.csv`
This file is a good enough cleaned version of an example dataset consisting of 100000 rows from the original dataset that was received. This file gives a broad information about the trees of New York. There were not too many missing values and these were fairly easy to fill in. Thus, no information was lost in the end. The missing values came mainly from the dead and stumped trees. Part of data was deliberately left empty for these trees. There might be more elaborate ways to fill in these data however for a good enough version, their status was used.

`nyc-trees-exploration.ipynb`
This Jupyter notebook is where the results of each step of the code to deduct a cleaner dataset is visible. If you would like to inspect more on the outcomes of the different parts of the code, I recommend the use of the notebook.

`.gitignore`
This file is to ignore the notebook checkpoints.

`nyc-trees.png`
This file has a graph image of the count of trees by their common name


#### Development Branch

Can be discarded for now. Will be back in use for the further developments of the project and the README file will be updated accordingly.

### Visual

![Count of trees by their common name](nyc-trees.png)

### Pending things to do

Because the purpose of the dataset is very broad, the dataset was not manipulated in great lengths. However if the project timeframe was longer, it would be interesting to explore the relationship between the different columns of the dataset and even create new variables. The next step in this project will definetely be the possible relationships such as:

* Can we find what kind of damages are the most severe for the trees or even life threathening?
* Can we gather external data about dead and stumped trees by the help of their location information and find out about possible causes for their end of life and fill in the missing values about them with more insight?
* Does having a stewardess keep a tree more healthy?
* Are guards keeping the trees safe?
* Can we gather external data such as oxygen production, carbon dioxide reduction, etc. by looking at the species and the size of a tree?

### Thanks

I would like to thank my coach Chrysanthi Katrini and Charles Cuigniez from element61 for organizing a Power BI workshop. It makes the exploration of datasets very easy and allows to get quick insights about what to manipulate in pandas. I also would like to thank my coach Alber Dominguez for always offering a listening ear and a helpful hand, as well as my colleagues for making every project a group effort.

### Collaboration

This project is open to collaborations as well as forking or cloning for further development.
