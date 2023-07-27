# Probabilistic Graphical Models

Repository to collect my exercises and assignements for the course Probabilistic Graphical Models offered by Stanford University.

<p align="center">
 <img src="https://www.spsc.tugraz.at/collections/assets/pgm.png">
</p>

## Introduction 

Probabilistic graphical models (PGMs) are a rich framework for encoding probability distributions over complex domains: joint (multivariate) distributions over large numbers of random variables that interact with each other. These representations sit at the intersection of statistics and computer science, relying on concepts from probability theory, graph algorithms, machine learning, and more. They are the basis for the state-of-the-art methods in a wide variety of applications, such as medical diagnosis, image understanding, speech recognition, natural language processing, and many, many more. They are also a foundational tool in formulating many machine learning problems. 

## Disclaimer
-------------------
The reason I would like to create this repository is purely for academic use (in case for my future use).
I would be really glad if you can use it as a reference and happy to discuss with you about issues related with the course even further the specific course content.

## Content of the course

### 1. PGM Representation

The module describes the two basic PGM representations: Bayesian Networks, which rely on a directed graph; and Markov networks, which use an undirected graph. The course discusses both the theoretical properties of these representations as well as their use in practice. The (highly recommended) honors track contains several hands-on assignments on how to represent some real-world problems. The course also presents some important extensions beyond the basic PGM representation, which allow more complex models to be encoded compactly.

### 2. PGM Inference

Following the first course, which focused on representation, this course addresses the question of probabilistic inference: how a PGM can be used to answer questions. Even though a PGM generally describes a very high dimensional distribution, its structure is designed so as to allow questions to be answered efficiently. The course presents both exact and approximate algorithms for different types of inference tasks, and discusses where each could best be applied. The (highly recommended) honors track contains two hands-on programming assignments, in which key routines of the most commonly used exact and approximate algorithms are implemented and applied to a real-world problem.

### 3. PGM Learning

Following the first course, which focused on representation, and the second, which focused on inference, this course addresses the question of learning: how a PGM can be learned from a data set of examples. The course discusses the key problems of parameter estimation in both directed and undirected models, as well as the structure learning task for directed models. The (highly recommended) honors track contains two hands-on programming assignments, in which key routines of two commonly used learning algorithms are implemented and applied to a real-world problem.
