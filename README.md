# Vulnerability Analysis of Autonomous Cars using Hacking Techniques

Google Developer Student Clubs Solution Challenge 2021 repo

## Introduction

We all know that autonomous and electric vehicle technology will soon be a reality thanks to people like Elon Musk. However, we felt that there is minimal scientific literature available which has deeply explored the security aspect. That is why we wanted to try and explore the safety component of connected technology like autonomous cars and see what are the possible Vulnerabilities in its design.

## Simulation

We used AWS Sagemaker and AWS Robomaker for simulating an environment inside an AWS EC2 G4dN instance. We were able to make the environment as close to the actual AWS DeepRace console as possible. After that we trained the model in the environment using RL.

## Prototyping

We have completed most of the prototyping for the project. We have a model ready which can drive and over which we have done some attacks on the model. However, we wish to do some modifications which will allow us to stretch the possiblities of our research even more.

## Future Scope

We want to make this into an overall framework which should prove to be really helpful for companies that are into making electric and autonomous cars. They can have a better assessment of the security of their design and they can use our research to build better and safer cars for everyone.

## Want to contribute?

You can clone this repo into AI Platform to get started. Once you have an AI Platform instance, you can use git clone to copy the contents of this repo

`git clone https://github.com/APratham/edith.git`

Now you will have to go into the appropriate directory to access the Jupyter Notebooks

`cd edith\src\gcp\gcp-ai-platform\notebooks\deepracer-analysis`

Here you will find the notebooks along with the training simtrace and a few more helper files which will help you to run this repo
