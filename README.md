## Project Details

This is the first assignment of Udacity's Deep Reinforcement Learning Nanodegree. In this project, the agent has to navigate in a large square world. A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana. Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.

![Trained agent navigates in the environment](trained_agent.gif)

## Getting Started

1. After cloning the repository, download the custom Unity enviroment matching your operating system, then copy it to the root folder of this project.

   Download links: 
   - [Linux](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip) 
   - [MacOS](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip) 
   - [Windows 32-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip) 
   - [Windows 64-bit](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
   
1. Create and activate a new virtual Python environment
   ```
   python3 -m venv venv
   source venv/bin/activate
   ```
1. Install dependencies by running the command below from the root of this repository:
   ```
   pip install -r requirements.txt
   ```
1. To train the agent and see how it performs, run `jupyter notebook` from the root of this repository, then open `Navigation.ipynb`, and run the cells in the notebook.
