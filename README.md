# SC21 Tutorial on Scientific Machine Learning

In this repository, you can find all the example notebooks used for SC21 full-day tutorial: _Scientific Machine Learning using HPC Servers on Cloud_


## Contents

- [Resources](#resources)
- [Target Audience](#target-audience)
- [Content Level](#content-level)
- [Prerequisites](#prerequisites)
- [Getting Started](#getting-started)
- [Frequently Asked Questions](#faq)

## Resources

- [Slack Invite](https://join.slack.com/t/sciml-workspace/shared_invite/zt-xfzyqf2u-zh4GRt7sRoh4RLSY9~yyJw)
- [Youtube Playlist](https://www.youtube.com/watch?v=ssZO8Y_TqxI&list=PLcK0exoS00ZTPdvhmh0IdyCIlVQ2lzjJ5)
- [RocketML support](mailto:rocketml@20230188.hubspot-inbox.com)
- [DeepXDE](https://github.com/lululxvi/deepxde)
- [DiffNet](https://github.com/adityabalu/DiffNet)


## Target Audience
Practitioners who use numerical simulations of Partial Differential Equations (PDEs) in analysis, optimization, design and control of complex engineered systems

## Content level
20% Beginner, 40 % Intermediate, 40% Advanced

## Prerequisites
Partial Differential Equations, Numerical methods, Machine Learning, Deep Learning, High Performance Computing, Python programming, Jupyter

## Getting Started

- If you registered for SC21 tutorial before October 29th then 
  1. Go to https://sciml.rocketml.net
  2. Enter your email address used for your registration and click on "Reset Password"
  3. Follow instructions in your password reset email
  
- If you registered after October 29th then email [RocketML](mailto:rocketml@20230188.hubspot-inbox.com) for a user account on [sciml.rocketml.net](https://sciml.rocketml.net). We will send you email instructions on how to log in. Don't worry this process should not take more than 10 minutes!  

- Log in to [sciml.rocketml.net](https://sciml.rocketml.net) using the instructions received from RocketML
<img width="1742" alt="Screen Shot 2021-11-14 at 2 05 29 PM" src="https://user-images.githubusercontent.com/7530528/141700438-070fb4ff-56b7-4733-b3ef-0988fd2e6b1b.png">

- Go through the onboarding screens

- You will see a list of tutorials that are ready to use

- Group by Topic to see _Beginner_, _Intermediate_, _Advanced_ tutorials
<img width="1750" alt="Screen Shot 2021-11-14 at 2 07 45 PM" src="https://user-images.githubusercontent.com/7530528/141700509-22f5ccdb-158f-4df9-8735-fd6c6b3b5e5a.png">

- Select a tutorial and wait for Jupyter Compute to start
<img width="1747" alt="Screen Shot 2021-11-14 at 2 10 24 PM" src="https://user-images.githubusercontent.com/7530528/141700568-5cc89727-87a4-45d6-9197-ff587abf1a88.png">

- Run the tutorial notebook one cell at a time. If you are not familiar with Jupyter notebook please google for a relevant [tutorial](https://www.youtube.com/watch?v=CwFq3YDU6_Y)
<img width="1751" alt="Screen Shot 2021-11-14 at 2 12 04 PM" src="https://user-images.githubusercontent.com/7530528/141700618-3b5f9de1-755f-496a-b47a-37757b9d99ac.png">

## FAQ

1. My tutorial screen is stuck at _Please Wait Jupyter Compute is not started yet_ for more than 5 minutes. What do I do?

This can happen due to following reasons:
- _When you log in for the first time. Resources like persistent disk space and Azure blob storage are being created for you to store the tutorials and for you to create new notebooks._

- _There is a delay in creating  containers when new nodes are being added to Azure Kubernetes cluster. A new node creation and downloading Docker images can take up to 10 minutes. If it takes more than 15 minutes, please ping us on slack._




