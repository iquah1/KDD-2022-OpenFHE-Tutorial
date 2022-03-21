# An ML Practitioner's Guide to Encrypted Machine Learning With the OpenFHE library

A [hands-on tutorial](https://kdd.org/kdd2022/cfTutorial.html) for [KDD 2022](https://kdd.org/kdd2022/index.html).

## Abstract

The question of privacy in the age of big data is the subject of great interest as of late. On the one hand, the boom in progress made by machine learning algorithms can be attributed mainly to the increased availability of data; on the other hand, that increased data has come at a cost to the individual data owners in that their data and privacy is now in the hands of external entities. With regulations such as GDPR, PIPL, and CCPA, it is clear that governments are becoming increasingly concerned with how the data of their citizens are used. This tutorial discusses how to leverage homomorphic encryption to train machine learning models on encrypted data and perform inference on encrypted data via a trained in-the-clear model.

We cover three core areas: the main ideas behind homomorphic encryption, the PALISADE/OpenFHE library and its design principles, and finally, training a model in the PALISADE framework through the use of a python wrapper. We aim to give the attendees an intuitive understanding of the underlying concepts that will allow them to utilize any library implementing homomorphic encryption effectively. Additionally, we discuss the underlying design principles and motivation behind the OpenFHE library. Finally, we train an encrypted linear regression on encrypted data during the training portion, conduct encrypted inference via a linear SVM trained in-the-clear, and conduct some basic statistical tests to showcase the efficacy of the library.

A (non-exhaustive) preview of this tutorial can be viewed by reading these blog posts:

- [A Machine Learning Oriented Introduction to PALISADE, CKKS, and pTensor](https://ianq.ai/pTensor-and-palisade/) and the [associated code](https://github.com/IanQS/pTensor)

- [PALISADE: Python3 Demos](https://gitlab.com/palisade/palisade-python-demo)

## Requirements

The target audience for this tutorial are moderately skilled users who are comfortable writing code,
and familiar with basic statistical concepts. Attendees will need a laptop and should have the
provided docker image pulled.

## Tutorial Outline

1) We will begin by introducing privacy-preserving machine learning, as well as the motivation
behind such methods

2) We discuss the core concepts for homomorphic encryption to the level necessary for ML
practitioners to effectively leverage these libraries for encrypted machine learning.

3) We discuss OpenFHE, its motivation, its history, and its ties to various agencies.

4) We go in-depth into training an encrypted linear regression on some sample encrypted datasets

5) We go in-depth into loading a pre-trained linear SVM and using it for inference on an encrypted
dataset

6) We discuss methods for encrypted model-performance analysis

7) A live Q&A session

## Other information
The tutorial duration is 3 hours.

## Tutors

### [Ian Quah](https://github.com/ianqs)

Ian Quah is a software engineer at Duality Technologies and contributes to the OpenFHE repository as
part of his duties. After graduating with his B.Sc in Cognitive Science from Carnegie Mellon, Ian
worked as a machine learning engineer across various companies. In 2018, Ian was exposed to
privacy-preserving technologies and began contributing to open-source libraries in that space. Ian
eventually stumbled upon OpenFHE (PALISADE at the time) and decided to become a long-term
contributor working towards making private machine learning be the de-facto.



### [Matthew Triplett]()

Matt Triplett began as a contributor to the OpenFHE (then PALISADE) library while studying Computer
Science and Applied Mathematics at NJIT, and has continued to be a core contributor during his
tenure as a Software Engineer at Duality Technologies.

