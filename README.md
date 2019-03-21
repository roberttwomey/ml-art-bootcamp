# Machine Learning for the Arts Bootcamp

UC San Diego - Spring 2019 - https://github.com/roberttwomey/ml-art-bootcamp

## Description

This bootcamp is a one day intensive introduction to Art and Machine Learning (ML), in advance of the Special Topics course offered through ECE. The goal is to introduce both the technical software tools and the conceptual application domain of ML and Art. Students who thrive in this bootcamp workshop will enjoy the quarter-long course.

ECE 16 is a prerequisite for this course, or equivalent experience with python and/or ML.

## Details

- **Instructor**: Robert Twomey - rtwomey@ucsd.edu - http://roberttwomey.com
- **Date**: Thursday 5/21 
- **Time**: 10am-3pm
- **Location**: Qualcomm Conference Center, Jacobs School of Engineering.

**Topics**:
- Generative Methods in the Arts
- Neural Style Transfer
- MNIST Style Recognition
- Text Generation with RNNs
- GAN Latent Space Exploration

**Work Environment**:
- Kubernetes (datahub.ucsd.edu)
- Jupyterhub (cuda, python, etc. all pre-installed)
- TensorFlow
- Participant-contributed ideas + data (images, text, etc.)

## Schedule
| Time | Activity |
| --- | --- |
| 10:00-10:30 | Lecture: Introduction and Motivation ("Generative Machines") |
| 10:30-11:15 | Style transfer activity with online tools. Discussion |
| 11:15-11:30 | Hands on with Python and Tensorflow in Jupyterhub |
| 11:30-12:00 | Notebook 1: Style Transfer in Python |
| 12:00-12:30 | LUNCH BREAK |
| 12:45-1:00 | Generative vs. Perceptive ML |
| 1:00-1:30 | Notebook 2: Fashion MNIST |
| 1:30-2:00 | Notebook 3: Text Generation with LSTMs |
| 2:00-2:30 | Notebook 4: GAN Latent Space Exploration |
| 2:30-3:00 | Closing Discussion. Sign up for class |

## Schedule Description

**10:00-10:30 - Lecture** - For the first half hour the instructor will briefly survey generative methods in the arts, and describe some contemporary ML and generative tools.

**10:30-11:00 - Style Transfer Activity** - The instructor will briefly introduce neural style transfer, and demonstrate online tools to accomplish style transfers. In a quick “sketching” exercise, students will have 20 minutes to experiment with style transfer software. They will select both the source style images and target images, and are asked to consider the meanings and aesthetics of their decisions, implementing one of the following:

1. Content and Style that are Incongruous
2. Content and Style that Amplify Each Other 
3. Style that adds an emotional charge to the content

**11:00-11:15 - Style Transfer Discussion** - Compare results in small groups, and choose one output to share with the class. 

**11:15-11:30 - Hands on with Python and Tensorflow in jupyterhub** - Instructor will introduce our ML software development environment. We will use the TensorFlow framework through python notebooks running in jupyterhub. For the bootcamp, these resources are pre-configured as virtual machine images running on Kubernetes, to skip time consuming software install processes. 

1. Log-on to [datahub.ucsd.edu](http://datahub.ucsd.edu)
2. Select `ECE188_SP19_A00: Scientific Python + Machine Learning Tools (1 GPU, 2 CPU, 16GB RAM)`
3. Spawn. 
4. Clone this repository into your account.

Switch to this: [0_Schedule.ipynb](0_Schedule.ipynb)

**11:30-12:00 - Notebook 1: Style Transfer in Python** - Students will work with a provided partial implementation of neural style transfer in TensorFlow, completing the implementation, and experimenting with their own style transfer function to produce new images. 

**12:00-12:30 - Lunch Break -**

**12:45-1:00 - Discuss Generative vs Perceptive ML**

**1:00-1:30 - Notebook 3: MNIST Activity** - Students will work through a provided MNIST Fashion recognition example in TensorFlow, training a recognition model, and then running it on photos of fashion samples they capture with their cellphones to explore the inferential capabilities and limitations of their model.

**1:30-2:00 - Notebook 3: Text Generation with RNNs** - 

**2:00-2:30 - Notebook 4: GAN Latent Space Exploration** - Instructor will introduce advanced generative methods for images, including Generative Adversarial Networks (GANs). Students will work with provided code to experiment with a GAN. 

**2:30-3:00 - Closing Discussion** - Students will briefly share their progress from the GAN activity and we will have a closing discussion. Instructor will answer questions about the course, and students will sign up for course if interested. 
