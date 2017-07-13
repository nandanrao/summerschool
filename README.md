# Machine Learning Fundamentals for Programmers

This course will teach participants the fundamental building blocks of statistical learning needed to see opportunities in real-life data and pick techniques that can be shipped in product today. It is designed for those who have no background in machine learning or statistics, but a love for hacking.

Attendees are expected to have a background in programming and basic working knowledge of at least one language with basic statistical libraries (Python, R, Julia, Java/Scala/Clojure, Matlab/Octave, Go). Days will consist of morning lectures focused on building theoretical knowledge, followed by open-ended exercises in the afternoon, completed in any language/framework of the students' preference, designed to demystify the theory and show the underlying hackability of these ideas.

Everyone is encouraged to bring data, ideas, products, and problems to work on specifically and will start on a personal project on the last day that can be continued after the course, professionally or personally.


## Precourse
* Intro to Probability/Statistics


## Statistical Learning Theory

Here we formulate the basic problem: how to measure the effectiveness of a model. After this we look at two of the most fundamental ideas that will be woven throughout the week: what does it mean for a model to overfit and how can we trade off the bias and variance of a model to make it more effective.

#### Topics:
* History of Statistical Learning
* Formulating the Problem: Approximation vs Estimation Error
* Controlling the Bayes Risk
* Overfitting
* Bias / Variance

#### Exercises:
* Perceptron
* K-nearest Neighbors


## Regression and Continuous Distributions

We formulate the problem of regression, and consider how assumptions about noise affect our predictive ability. We introduce Bayesian regression to show how formalizing prior knowledge into a distribution allows us to learn more from the data than we would otherwise be able to learn.

#### Topics:
* What does the mean really tell you?
* Probability distributions and noise.
* Bayes' Rule. Bayesian Regression.
* Latent variables. Underfitting!
* Regularization

#### Exercises:
* Condition Numbers and Inversions
* BYO Regularization
* Robust Regression
* Gaussian Processes


## Small Shapes in Big Data

Data often consists of many variables and in order to generalize we believe the same outcomes can be described with much fewer, even if we need to create them ourselves. Here we understand what it means to work with high-dimensional data.

#### Topics:
* A Brief History of Data Visualization
* Manifolds, Factors, and Lower-Dimensional Structure
* Sparsity
* Egeindecomposition & PCA

#### Exercises:
* Probablistic PCA
* Multidimensional Scaling


## Simple NLP

Text is everywhere, and understanding how turn natural language into a statistical distribution is key to understanding how we can work with it. This module is interesting not just because there are so many simple techniques that can be extremely useful, but also because it will allow us to extend our knowledge of Bayesian formulations and see again how reasonable assumptions allow us to learn vast amounts from our data.

#### Topics:
* Preprocessing, Tokenization, Bag-Of-Words Models, TF-IDF.
* Discrete distributions.
* Naive Bayes + LDA
* Word and Document Embedding
* Neural Nets?

#### Exercises:
* Kaggle Competition


## Implementation / Odds & Ends

Our last day will consist of a brief overview of some other interesting topics we didn't get a chance to cover, after which attendees will start a personal project that they can continue after the workshop.

* Intro to Network/Graph Analysis
* Optimization
* Probablistic Programming
* Big Data

#### Exercises:
* Final Personal Project.
