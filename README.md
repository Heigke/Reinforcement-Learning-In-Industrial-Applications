# Reinforcement-Learning-In-Industrial-Applications
In this repository we find the algorithm Proximal Policy Optimisation (PPO) applied to the Tennessee Eastman challenge process (http://users.abo.fi/khaggblo/RS/Downs.pdf).
The PPO algorithm is originally implemented by Nikolay Goodger and can be found in his repository (https://gitlab.com/ngoodger/ppo_lstm/-/blob/master/recurrent_ppo.ipynb) and an astounding description of his work is given in the article Proximal Policy Optimisation with PyTorch using Recurrent models at Medium. Alterations of Nikolaj Goodgers code was done by Eric Bergvall to make it interact with the Tennessee Eastman simulation. The implementation of the Tennessee Eastman challenge process was done by Niklas Kotarsky and Johan Grönqvist (Lund University). A compiled version of the original Fortran code is included (A.out) in the repository but if one want to recompile for some version you need to use the original Fortran code (teprob.f).


# Setup for PPO
(Start the file PPO_BIG_TE_constraints.ipynb with for example jupyter notebook)
To setup just make sure that python 3.8.2 or above is installed with the needed libraries (run the import statements in the notebook and see).
In case they are not installed just install them with pip and retry. (I needed to install dotmap and tensorboard with pip)

There are several hyperparameters to set for training which can be found under the section hyperparameters in the notebook. We suggest you just run the script as it is to start investigating by yourself.
