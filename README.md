# Looker Explore ERD Generator
This repository shows the code used to generate a PDF of an ERD for a given explore within a Looker model

This repository contains a Jupyter Notebook which contains code used to make Looker API calls to retreive information on joins within an explore, and metadata on fields in a given view, in order to create an ERD like the one shown in this repo. The script assumes that you have the LookerAPI.py (python SDK for Looker's API) file in the working directory, and that there is a config file that has the necessary Looker authentication information. The script also requires that you have installed erd - an open source command line tool, which can be found [here](https://github.com/BurntSushi/erd). The result is a text file, which is transformed into a PDF, using the referenced command line function, called model_erd.pdf saved within your working directory. 

