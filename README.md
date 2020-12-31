### Project Description

In this project we train an agent to walk around an environment and collect bananas.

You get +1 for each yellow you collect and -1 for each blue one.  The goal is to get a score of >=13 over 100 consecutive episodes (note: we train to 15 because we're bananas for this project)

Copied from project description: The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.


### Getting Started

To run the code a unity environment is needed that can be downloaded as desribed below:

1. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    
    (For Windows users) Check out this link if you need help with determining if your computer is running a 32-bit version or 64-bit version of the Windows operating system.

    (For AWS) If you'd like to train the agent on AWS (and have not enabled a virtual screen), then please use this link to obtain the environment.

2. Update the line in `Navigation.ipynb` that starts with ```env = UnityEnvironment(``` to wherever you placed the env.

3. Dependencies: `pip install ` each of the following:
    * Pillow>=4.2.1
    * matplotlib
    * numpy>=1.11.0
    * jupyter
    * pytest>=3.2.2
    * docopt
    * pyyaml
    * protobuf==3.5.2
    * grpcio==1.11.0
    * torch==0.4.0
    * pandas
    * scipy
    * ipykernel
    * unityagents==0.4.0


### Instructions

Follow the instructions in `Navigation.ipynb` to get started with training your own agent!  

### Report
There is also a writeup of the algorithm used in `Report.md`