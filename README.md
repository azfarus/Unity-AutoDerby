## AutoDerby- A simulation for 2v2 soccerbot trained through RL
This repository containes the trained models for the Soccerbot Environment. 
- The POCA and SAC models are compatible with the unity project.
- The PPO and A2C models can be demonstrated through the modelloader.ipynb file in the Builds folder. The filepaths of the executable and the models need to be changed to do that.
- Currently executing the executable  `builds/b6-uibuild/SoccerBot.exe` will display the POCA and SAC algorithms. To run the PPO and A2C the modelloader has to be run with the proper libraries setup.
- Training is done through Stable Baselines 3 python library. The file `Builds\sb3.ipynb` interacts with the serverbuild(b5) and executes training.  Comment the relevant parts in the ipynb to train with PPO or A2C algorithm. Necessary libraries are to be imported/installed through pip.
- The mlagents-learn executable was also used to execute training. It has to be setup from [here](https://github.com/Unity-Technologies/ml-agents/blob/develop/docs/Installation.md). We personally chose to setup it inside a python virtual environmnet (venv).
