---
title: "ML-EDM"
excerpt: "ml_edm package: a Python toolkit for Machine Learning based Early Decision Making<br/><img src='/images/mledm.png'>"
collection: portfolio
---


## Early Decision Making
More and more applications require early decisions, i.e. taken as soon as possible from partially observed data. However, the later a decision is made, the more its accuracy tends to improve, since the description of the problem to hand is enriched over time. Such a compromise between the earliness and the accuracy of decisions has been particularly studied in the field of Early Classification of Time Series (ECTS), for which an extensive benchmark is available in [8]. However, the current definition of ECTS is limited to:

    - a classification problem ;
    - an available training set which contains completely and properly labeled time series ;
    - a decision deadline that is finite, fixed and known ;
    - unique decisions for each incoming time series ;
    - decisions that once made can never be reconsidered ;
    - fixed decision costs which do not depend on the triggering time and the decisions made.

In order to overcome these limitations, we introduce a more general problem, called Machine Learning based Early Decision Making (ML-EDM), which consists in optimizing the decision times of models in a wide range of settings where data is collected over time. After defining the ML-EDM problem, ten challenges are identified and proposed to the scientific community to further research in this area. These challenges open important application perspectives.


## Python Lib
ml_edm : A python package for Machine Learning for Early Decision Making tasks

Repository: https://github.com/ML-EDM/ml_edm

Many situations require decisions to be made quickly to avoid the costs associated with delaying the decision. A doctor who needs to choose which test to perform on their patient and an agent considering whether a certain behavior on a network is caused by a hacker are examples of individuals confronted with such situations. However, taking a decision too hastily may lead to more mistakes, resulting in additional costs that could have been avoided.

In these situations, where there is a trade-off between the earliness of the decision and the accuracy of the prediction, the Machine Learning for Early Decision Making (ML-EDM) framework offers AI solutions not only to make a prediction but also to decide when to trigger its associated decision.

The ml_edm package provides tools to facilitate dealing with the early classification of time series (ECTS) problem, whose goal is to determine the class associated with a time series before it reaches its last timestamp/measurement T as early as possible.

A detailed guide on how to install and use the package can be found in the “Get Started” notebook available in the repository. This notebook can be explored by downloading the repository and using jupyter notebook. Documentation can be found in the notebook and in the source code.

For more information about the ML-EDM research domain, please have a look at the ML-EDM research [GitHub](https://github.com/ML-EDM/ML-EDM).
