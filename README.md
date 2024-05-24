
![MySureStart Logo](https://images.squarespace-cdn.com/content/v1/5f45536caa356e6ab51588f4/1599580657611-7A6YX9MGA2YHJCQ46QSB/SureStart+Logo.png)

# Intro to AI with Machine Learning curriculum provided for the PAS4AI program

One of the main goals of PAS4AI is to develop innovative pedagogical materials and scalable tools to teach AI technical skills through a "learning-by-doing" experience, teach crucial team collaboration and communication skills through AI-focused project-based learning, and facilitate autistic community college students to obtain AI-focused summer internships and increase their access to AI careers. 

Towards developing these pedagogical materialsThis curriculum presented below is being licensed to CMU by MySureStart Inc., in accordance with Section 9 of agreement 123699-479504 between CMU and MySureStart Inc. (and Referred to as Retained Works in that section) for use ONLY in this NSF-funded project PAS4AI (Preparing Autistic Students for the AI Workforce NSF Project.) between Dec 19, 2023 and Aug 31, 2025. 

This curriculum was designed by SureStart to be used in a program, in which students go through the 15 modules of the curriculum working in a team-based learning environment, supported by near-peer technical mentors. with a goal to develop knowledge of foundational AI concepts and hands-on Machine Learning skills. 


The modules you will encounter in this curriculum are laid out in the following grid. Their descriptions are presented below the grid.  __We recommend reading through this entire ReadMe before going to the specific modules.__

| [Module 00/1](./Module_00_PreProgram_Python_Review_Fundamentals_I)  | [Module 00/2](./Module_00_PreProgram_Python_Review_Fundamentals_II)  | [Module 1](./Module_01_Python_Review_NumPy)  | [Module 2](./Module_02_Python_Review_Pandas)  | [Module 3](./Module_03_Machine_Learning)  |
|-----------|-----------|-----------|-----------|-----------|
| [__Module 4__](./Module_04_Deep_Learning_and_TensorFlow) | [__Module 5__](./Module_05_Artificial_Neural_Networks)  | [__Module 6__](./Module_06_Convolutional_Neural_Network)  | [__Module 7__](./Module_07_Regression_Loss_Functions)  | [__Module 8__](./Module_08_Classfication_Loss_Functions) |
| [__Module 9__](./Module_09_Optimization) | [__Module 10__](./Module_10_Activation_Functions) | [__Module 11__](./Module_11_Overfitting_and_Underfitting) | [__Module 12__](./Module_12_Regularization) | [__Module 13__](./Module_13_Ethics_and_Bias) |

The modules are as follows:

__Module 00 Pre-program 1__: We start with a review of python fundamentals including I/O, data types, data structures, logical loops, exception handling and file I/O.

__Module 00 Pre-program 2__: Continuing the exploration of python fundamentals, we lightly review some object oriented programming concepts with python, and handling of packages/modules/libraries and debugging errors and exceptions. 

__Module 1__: We introduce Numpy, a staple library for data manipulation, in this module. Specifically, we learn how to make numpy arrays and matrices, and operations we can do on them.

__Module 2__: Working with tabular data is easier with the Pandas library. Hence we look at exploring data using Pandas in this module. 

__Module 3__: We continue Phase 1 with an introduction to machine learning algorithms, and how prebuilt Python libraries makes it easy and fun to run machine learning (ML) models for Linear Regression, Decision Trees, and Random Forests.

__Module 4__: Having had a general introduction to ML through simpler machine learning models, we will now jump into Deep Learning, a more powerful ML modeling approach. We will also get an introduction to Tensorflow, one of the main Python libraries used for building deep neural networks easily and quickly. 

__Module 5__: There exist many Python libraries that make it easy and efficient for us to build complex neural networks. However, these libraries create bit of a "blackbox" around their internal workings of how these networks are actually put together. So, today, with a goal to remove the "blackbox", we will build a simple neural network from scratch, and study the various aspects of these networks step-by-step over the next few modules.

__Module 6__: Going one step further with neural network architectures, we explore a widely used deep architecture called Convolutional Neural Networks (or CNNs). CNNs are known for their ability to compound smaller patterns into larger more human-recognizable ones. CNNs are often used for Computer Vision related modeling tasks.

__Module 7__: An important part of the learning process of any machine learning algorithm is its loss function (or cost function). It maps an event or values of one or more variables onto a real number, intuitively representing some "cost" associated with the event. We start by studying loss functions related to regression-related models.

__Module 8__: Today, we will discuss loss in the context of classification-related algorithms. Classification loss differ from regression loss; regression loss functions aim at predicting quantities while classificaiton loss functions aim at predicting class and labels.

__Module 9__: This module on optimization is very connected to the previous two modules on loss. We can have a loss (or cost) function that represents how accurate a given machine learning model is at the prediction task, but we also need another algorithm that is able to change the weights of the model to lower the loss/cost function, such that the associated model gets better at the prediction task. Such algorithms are referred to as "optimizers", which we will study in this module. 

__Module 10__: If we just consider the perceptrons/nodes, all neural networks are still very linear in their function. But to model complex real-world data, we need to add non-linearity. This is accomplished by adding intermediate nodes that apply non-linear functions called "activation functions" to the outputs of the neural network layer preceding it before it is ingested by the next layer. Today we will explore the various kinds of activation functions.

__Module 11__: Three crucial aspects of any machine learning model are the quality and quantity of data on which it is based, how we train the models, and how long we train the models. Problems with any three of these aspects can result in a model that has not learned enough from the data, or not learned the true patterns in the data and instead glommed onto the wrong details in the data, thus producing sub-optimal predictve outcomes. We learn how to combat such applied problems in this module.

__Module 12__: In this module we continue learning how to handle overfitting and underfitting problems by learning about modifications we can make to our neural network to address them. 

__Module 13__: Given the AI and Machine Learning's growing role in human decision-making and its large implications, today we will consider data ethics, data bias, the negative consequences of failing to make ethical considerations part of the process. We will learn about constructing an Ethical AI Framework to incorporate in our technical development, so that we can build AI, Machine Learning and data-based tech solutions that are inclusive, equitable and fair. 
