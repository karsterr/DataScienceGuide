# Data Science Guide

## Description

Welcome to the **Data Science Guide** repository! This project serves as a comprehensive guide to the foundational and advanced concepts of data science, machine learning, and artificial intelligence. It is based on summaries and exercises from four essential books in the field:

1. **Python Crash Course** by Eric Matthes
2. **Data Science for Business** by Foster Provost
3. **Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow** by Aurelien Geron
4. **Designing Machine Learning Systems** by Chip Huyen

Each book is covered chapter by chapter, with summaries and solutions to exercises and problems provided to facilitate learning and application.

---

## Index

### 1. Python Crash Course by Eric Matthes

#### Part I: Basics
- **Chapter 1: Getting Started**
  - Introduction to Python programming.
  - Setting up Python environment.
- **Chapter 2: Variables and Simple Data Types**
  - Understanding variables, strings, numbers, and comments.
- **Chapter 3: Introducing Lists**
  - Working with lists, including indexing and slicing.
- **Chapter 4: Working with Lists**
  - Modifying lists and working with loops.
- **Chapter 5: If Statements**
  - Conditional tests and if statements.
- **Chapter 6: Dictionaries**
  - Key-value pairs, working with dictionaries.
- **Chapter 7: User Input and While Loops**
  - Handling user input and using while loops.
- **Chapter 8: Functions**
  - Writing functions, passing arguments.
- **Chapter 9: Classes**
  - Creating and using classes.
- **Chapter 10: Files and Exceptions**
  - Reading from and writing to files, handling exceptions.
- **Chapter 11: Testing Your Code**
  - Writing tests and debugging code.

#### Part II: Projects
- **Project 1: Alien Invasion**
  - Building a 2D game using Pygame.
- **Project 2: Data Visualization**
  - Visualizing data with Matplotlib and Pygal.
- **Project 3: Web Applications**
  - Building simple web apps with Django.

### 2. Data Science for Business by Foster Provost

- **Chapter 1: Introduction**
  - Understanding data science and its importance in business.
- **Chapter 2: Business Problems and Data Science Solutions**
  - Identifying business problems that can be solved with data science.
- **Chapter 3: Introduction to Predictive Modeling: From Correlation to Supervised Segmentation**
  - Fundamentals of predictive modeling.
- **Chapter 4: Fitting a Model to Data**
  - Techniques for fitting models to data.
- **Chapter 5: Overfitting and Its Avoidance**
  - Understanding and avoiding overfitting.
- **Chapter 6: Similarity, Neighbors, and Clusters**
  - Clustering techniques and similarity measures.
- **Chapter 7: Decision Analytic Thinking I: What Is a Good Model?**
  - Criteria for evaluating model quality.
- **Chapter 8: Visualizing Model Performance**
  - Techniques for visualizing model performance.
- **Chapter 9: Evidence and Probabilities**
  - Working with evidence and probabilities.
- **Chapter 10: Representing and Mining Text**
  - Techniques for text mining and representation.
- **Chapter 11: Decision Analytic Thinking II: Toward Analytical Engineering**
  - Advanced decision analytic thinking.
- **Chapter 12: Other Data Science Tasks and Techniques**
  - Additional tasks and techniques in data science.
- **Chapter 13: Data Science and Business Strategy**
  - Integrating data science with business strategy.
- **Chapter 14: Conclusion**
  - Summary and future directions in data science.

### 3. Hands-on Machine Learning with Scikit-Learn, Keras & TensorFlow by Aurelien Geron

#### Part I: The Fundamentals of Machine Learning
- **Chapter 1: The Machine Learning Landscape**
  - Overview of machine learning, types of machine learning systems.
- **Chapter 2: End-to-End Machine Learning Project**
  - Hands-on project to go through the entire process of a machine learning project.
- **Chapter 3: Classification**
  - Understanding classification algorithms and performance metrics.
- **Chapter 4: Training Models**
  - Techniques for training machine learning models.
- **Chapter 5: Support Vector Machines**
  - Introduction to SVMs and their applications.
- **Chapter 6: Decision Trees**
  - Building and using decision trees.
- **Chapter 7: Ensemble Learning and Random Forests**
  - Combining models to improve performance.
- **Chapter 8: Dimensionality Reduction**
  - Techniques for reducing dimensionality of data.
- **Chapter 9: Unsupervised Learning Techniques**
  - Identifying patterns without labeled data.

#### Part II: Neural Networks and Deep Learning
- **Chapter 9: Introduction to Artificial Neural Networks with Keras**
  - Basics of neural networks, building models with Keras.
- **Chapter 10: Training Deep Neural Networks**
  - Techniques for training deep networks.
- **Chapter 11: Custom Models and Training with TensorFlow**
  - Customizing models and training processes in TensorFlow.
- **Chapter 12: Loading and Preprocessing Data with TensorFlow**
  - Handling and preprocessing data in TensorFlow.
- **Chapter 13: Deep Computer Vision Using Convolutional Neural Networks**
  - Using CNNs for computer vision tasks.
- **Chapter 14: Processing Sequences Using RNNs and CNNs**
  - Working with sequential data using RNNs and CNNs.

### 4. Designing Machine Learning Systems by Chip Huyen

- **Chapter 1: Overview of Machine Learning Systems**
  - Principles and components of machine learning systems.
- **Chapter 2: Introduction to Machine Learning Systems Design**
  - Basics of designing machine learning systems.
- **Chapter 3: Data Engineering Fundamentals**
  - Fundamentals of data engineering for ML systems.
- **Chapter 4: Training Data**
  - Techniques for collecting and preparing training data.
- **Chapter 5: Feature Engineering**
  - Methods for creating and selecting features.
- **Chapter 6: Model Development and Offline Evaluation**
  - Developing models and evaluating them offline.
- **Chapter 7: Model Deployment and Prediction Service**
  - Deploying models and setting up prediction services.
- **Chapter 8: Data Distribution Shifts and Monitoring**
  - Handling data distribution shifts and monitoring models.
- **Chapter 9: Continual Learning and Testing in Production**
  - Techniques for continual learning and testing in production.
- **Chapter 10: Infrastructure and Tooling for MLOps**
  - Infrastructure and tools for machine learning operations.
- **Chapter 11: The Human Side of Machine Learning**
  - Addressing human factors in machine learning projects.

---

## Required Software and Tools

To effectively use the materials and run the code in this repository, you will need the following software and tools installed on your system:

### Python

Make sure you have Python installed. You can download it from [Python's official website](https://www.python.org/downloads/). The repository is compatible with Python 3.7 and above. If you use Linux like me, you can install python package from your distros package manager.

### Python Packages

You will need to install several Python packages. It is recommended to create a virtual environment to manage dependencies. You can use the following commands to create a virtual environment and install the required packages:

1. **Create a Virtual Environment**

   ```bash
   python -m venv data_science
   source data_science/bin/activate  # On Windows use `data_science\Scripts\activate`
   ```

2. **Install Required Packages**

You can install required libraries with pip into your virtual environment data_science:

   ```bash
   pip install -r notebook pygame scikit-learn tensorflow keras matplotlib
   ```

### Additional Tools 

- **Git**

Make sure you have Git installed to clone the repository. You can download it from [Git's official website](https://git-scm.com/downloads). If you use Linux like me, you can install git package from your distros package manager.

- **Docker**

For containerizing and deploying models. Install from [Docker's official website](https://www.docker.com/get-started). If you use Linux like me, you can install docker package from your distros package manager.