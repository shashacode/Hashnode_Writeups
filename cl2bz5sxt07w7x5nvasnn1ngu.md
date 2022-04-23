## Workflow for carrying out Data science projects and Useful Data Science Library

There really is no specific pattern for carrying out a Data science project but for beginners to Data science, having a workflow might help in carrying out a project successfully. Also, there are certain libraries that can’t be missed when working with datasets. The number of libraries that can be used is far from exhaustive but while some can be done without, there are some important ones you can’t miss when carrying out a data science project. 
The basic workflow stages are outlined below:
- Data Analysis
- Machine learning models
- Web Deployment

## Data Analysis
This can be divided into two major branches which are Data Wrangling and Visualization.

#### Data Wrangling
This is the process of cleaning Data by finding missing values, filling it up, making necessary deletions and overall preparation of the data for further analysis. This reduces errors during analysis.
There are two major libraries used here which include: Numpy and Pandas. For every data scientist, these are the basic libraries imported to work on a dataset.

**Numpy** is also known as Numerical Python is used mainly used when working with arrays. It is used in place of Python list when dealing with numeric involving matrices operation.

**Pandas** is the short form of “Python Data Analysis Library”. It is an open-source Python package used for loading data into a data frame for easy analysis and visualization. I sometimes wonder what life will look like without pandas phew.
#### Visualization
After analysis, the next thing every data scientist would want to do is visualize their data so there can be a sense of direction in knowing more about the dataset.

The major tool used is **Matplotlib** though Pandas is capable of performing visualization, Matplotlib is much more vast than Pandas. Matplotlib contains a lot of plotting packages like line plot, bar plot, scatter plot and many more.

**Seaborn** is another useful library built on Matplotlib but it is more aesthetic than matplotlib and offers some visualization matplotlib does not have like Violin plot.

## Machine Learning Models
The basic library used for machine learning training is Scikit-learn. The models it offers include Regression, Clustering, Classification, and Dimensionality Reduction. It can also be used to carry out normalization. 

## Web Deployment
This is the deployment stage in which the data science project is hosted online on an interface for others to access. This is done at the Production stage. When working with big data this stage is usually carried out by a Data Engineer using Machine learning toolkit like Kubeflow to create model pipelines but there are simple frameworks that can be used by a data scientist especially when not dealing with big data. There are a lot of frameworks used in deploying but the most preferred amongst data scientists is Streamlit and FastAPI because it is easy to work with especially if you are not familiar with web development. 

These are just some of the libraries Data scientists utilize in carrying out Data Science projects.

