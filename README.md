Contains code for Risk-Aware Bayesian Reinforcement Learning for Cautious Exploration

Experiments for each of the two scenarios (Bridge and Pacman) can be run using the 'run_experiments.sh' shell script found within the relevant folder. Results will be generated and stored in the relevant 'Results' folder. Edit the 'params.py' file to change the parameters of the experiment, such as the total number of episodes that the agent trains for, or the critical threshold. 

[This assumes you have a conda environment called 'minimal_ds' with the relevant packages. Otherwise, run the 'main.py' file with an integer as command-line input. This integer is the experiment number, used for keeping track of multiple experiments.]