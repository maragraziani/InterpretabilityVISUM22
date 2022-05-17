[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

![Logo of the project](https://www.i-aida.org/wp-content/uploads/2022/02/visum2022.png)
# Interpretable AI at VISion Understanding and Machine intelligence (VISUM) Summer School 2022
On-site hand-on session for the track of Explainable AI led by Prof. Henning Müller

**Presented by:**

- Mara Graziani
    - Post-doc researcher at HES-SO Valais & IBM Research x ZHAW
    - mara.graziani@hevs.ch

Welcome to the hands-on session about **Explainable AI** of the **VISUM 2022 Summer School**. 
This tutorial is created with the purpose of showcasing multiple ways in which developers may interpret Deep Learning (DL) outcomes for vision tasks and build more reliable and transparent models than the existing ones. 

**Motivation**

Within the past decades the availability of annotated data has grown exponentially, and it has been followed by the physical improvement of computation possibilities. With the computing resources available now we can train complex deep learning models with billions of parameters in just a few hours. These models benefit from the availability of large datasets and are used for several tasks, from the prediction of animal species to the analysis of microscopy images. 
**It is important to keep in mind that these models, as other ML models, are only approximations of the true underlying phenomenon.**

And these approximations, as George Box said a long time ago, are never exactly true. How to estimate the usefulness and applicability of these approximations is a problem that depends on the context, the task and the risk involved in each application. 
Several proofs were given that deep learning models not always predict outcomes as we would expect, despite their impeccable performance on testing data. In a variety of situations we can observe performance drops, for example on shifted data, lack of robustness to samples that are engineered to trick the models and the incorporation of bias and discrimination within the learning procedure. 

An increasing number of researchers now claims that the evaluation of DL models by their **sole test performance is insufficient** and that we should drive the development towards building accurate and reliable models at the place of solely accurate models. So we need to keep the accuracy obviously, but we also want reliability. 

**Reliability is given by multiple desiderable factors, including the ability to generalise, to justify the decision making and, eventually, to show improvements of trust upon sustained use.**

In this hands-on session, I will present multiple ways of making black-boxes more transparent, of building gray-boxes and of testing the reliability and robustness of DL models. 

**Definition of Interpretability**
There is still quite some debate about the meaning of **interpretability**, with several papers disagreeing on the meaning of interpretable and explainable. Particularly there is a rupture point that I identified in my research work between the social and the technical sciences, with people from the social domain using very different definitions. 
In the context of the hands-on, we will adopt the following definition:

**“An AI system is interpretable
if it is possible to translate its work-
ing principles and outcomes in human-
understandable language without af-
fecting the validity of the system”**



Annotate your images: https://www.robots.ox.ac.uk/~vgg/software/via/via_demo.html

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/maragraziani/InterpretabilityVISUM22.svg?style=for-the-badge
[contributors-url]: https://github.com/maragraziani/InterpretabilityVISUM22/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/maragraziani/InterpretabilityVISUM22.svg?style=for-the-badge
[forks-url]: https://github.com/maragraziani/InterpretabilityVISUM22/network/members
[stars-shield]: https://img.shields.io/github/stars/maragraziani/InterpretabilityVISUM22.svg?style=for-the-badge
