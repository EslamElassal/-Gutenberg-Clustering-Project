# Group 8 Data Science Applications Clustering Assignment Project 2
A simple and well designed structure is essential for any machine learning project, project template that combines **simplicity, best practice for CODE structure** and **good CODE design**. 
The main idea is that there's much same stuff you do every time when you start our machine learning project, so wrapping all this shared stuff will help you to change just the core idea every time you start our machine learning project. 

**So, here’s a simple readme template that help you get into our project faster and just focus on your notice and explainations, etc)**

In order to decrease repeated code shunks, increase the time that can read the code in, flexibility an reusability we used a functional programming structure that focused on split all problems in our project in functions and use that functions many times in many places in the code without repeating the code.

![Gutenberg](https://drive.google.com/uc?export=view&id=1bOd8Hiv-sU8Skj1gYR-2cxLUEBIretyZ)


In this project, we selected some books from the Gutenburg library from different categories and then select random paragraphs from them and labeled these paragraphs by the book name for ground truth. After creating the dataset we used many transformation algorithms to embed the text to numbers for the modeling processes like (Word Embedding,LDA, TF_IDF, BOW, Cohernce)
<br><br>
After this, we tried many clustering algorithms like(K-means, Expected-maximization(EM), and Hierarchical) and chose the champion one which achieved the kappa and silhouette score.

**Recommended using GPU to compile the code much faster.
But it works well for CPU too.**
- GPU takes around 40 min, while CPU may take hours.

# Requirements
- [numpy](https://numpy.org/) (The fundamental package for scientific computing with Python)
- [pandas](https://pandas.pydata.org/) (pandas is a fast, powerful, flexible and easy to use open source data analysis and manipulation tool, built on top of the Python programming language.) 
- [Pytorch-Transformers](https://pytorch.org/hub/huggingface_pytorch-transformers/) (High-level library to help with text augmentation using deep learning in PyTorch)
- [sklearn](https://scikit-learn.org/stable/) (TMachine Learning and Data Analysis Library in Python)
- [nltk](https://www.nltk.org/) (The fundamental package for Natural Language Procesing with Python)
- [matplotlib](https://matplotlib.org/) (Matplotlib is a comprehensive library for creating static, animated, and interactive visualizations in Python)
- [seaborn](https://seaborn.pydata.org/) (Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.)
- [gensim](https://radimrehurek.com/gensim/index.html) (library for training of vector embeddings, topic modelling, document indexing and similarity retrieval with large corpora – Python or otherwise.)
- [pyldavis](https://pyldavis.readthedocs.io/en/latest/readme.html) (pyLDAvis is designed to help users interpret the topics in a topic model that has been fit to a corpus of text data. The package extracts information from a fitted LDA topic model to inform an interactive web-based visualization.)
- [yellowbrick](https://www.scikit-yb.org/en/latest/) (Yellowbrick: Machine Learning Visualization.)
- [wordcloud](https://pypi.org/project/wordcloud/) (A little word cloud generator in Python)
- [spacy](https://spacy.io/) (spaCy is a free open-source library for Natural Language Processing in Python.)

# Run the Code
- Upload the ipynb code file into "Google Colab" or Anaconda "Jupyter Notebook"
- Press "Run All" in the control panel or "Restart Kernel and Run All" to run all code 
- In case of run each code cell alone, press the run button that appear at each code cell
 tents
 
# Contributing
Any kind of enhancement or contribution is welcomed.

![alt text](images/Group8_ClusteringAssignment_page-0001.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0002.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0003.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0004.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0005.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0006.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0007.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0008.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0009.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0010.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0011.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0012.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0013.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0014.jpg)
![alt text](images/Group8_ClusteringAssignment_page-0015.jpg)
