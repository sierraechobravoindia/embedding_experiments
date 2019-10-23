# Readme

This project is my Capstone Project for a udacity Machine Learning class.


## Data

The data corpus for this project is built from 3 different sources (language German:
+ specialist books: copyright-protected material, hence not possible to provide
+ text from software change requests: confidential information, hence not possible to provide
+ patents: downloaded from the "Deutsches Patent- und Markenamt" (German Patent Office, www.DPMA.de) via the DEPANITnet database. Filters used were the years 2015-2018, keywords "Brennkraftmaschine" (internal combustion engine) and corresponding IPC classes 

To use this code, other data corpora can be used, either pdf or plain text. The preprocessing pipeline requires a list of list of strings input format, the multiclass classification metric a labelled dataset of text, the other metrics operate directly on embeddings. 


## Running the code

The code is organized in 4 Jupyter Notebooks found in the "Notebooks" folder:
+ Data Collection.ipynb: Contains the data scraping and preprocessing.
+ Embeddings.ipynb: Contains the training of the domain specific embeddings, word2vec and FastText.
+ LSTM.ipynb: Contains the multiclass classification model, called M<sub>1</sub> in the documentation to evaluate the trained embeddings.
+ Metrics.ipynb: Contains the other metrics M<sub>2</sub>-M<sub>5</sub> employed to evaluate the trained embeddings.

To run the code, execute these 4 notebooks in the presented order. The intermediate results are serialized to disk in bewteen the notebooks.



## Web Resources

All sources used are documented in the notebooks and the project report, found in the folder "ProjectReport"
