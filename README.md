# Google-Football-MADDPG
MADDPG application for the Google Football Research Environment

The main file to train the two players with MADDPG is MADDPG.ipynb. This implementation was from scratch and is not using Ray, but instead just using the bare bones of the football environment. This implementation assumes a Docker environment.

To run the training, run the first five cells. The fifth cell is where the actual training process happens. Configure at the beginning of that cell how many episodes to run training for. Running the rest of the cells will load the trained MADDPG agents, run them through 100 test episodes and then save the outputs of the metrics from the paper to csv. All of my charts in the paper were created using these csv's. 
