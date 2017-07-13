# Artificial Curiosity
## Adaptive Reinforcement Learning of curious AI basketball agent
![](/robot.jpg?style=centerme)


A machine learning project of learning NBA shots success ratio based on  410,000 records of [NBA players shots stats](http://stats.nba.com).

The project implement various ML techniques in order to create a "Curious" AI agent, which learns success ratios and implements the knowledge in [**exploration-expoitaition**](http://www.indigosim.com/tutorials/exploration/t0s1.htm) game simulation enviroment.

## Part 1 - [Bayesian Inference and Information Gain](part1-bayes/cur_project_bayes.ipynb)
After a [EDA](https://en.wikipedia.org/wiki/Exploratory_data_analysis) and preprocessing of shot data into categorical features we implemented a [bayesian inference](https://en.wikipedia.org/wiki/Bayesian_inference) algorithm and evaluated the feature selection with Expected [Information Gain](https://en.wikipedia.org/wiki/Information_gain_ratio) criteria.


## Part 2 - [Neural Network Learning and Optimization](Part2-NN/cur_neural.ipynb)

Manual Neural Network implementation with numpy and SGD method. This part required new preprocess methods (to continous features) and network structure optimization improving [prediction AUC](https://en.wikipedia.org/wiki/Receiver_operating_characteristic#Area_under_the_curve) to 70%

### Extra:
  - [Genetic algorithm optimization](Part2-NN/Genetic.ipynb)
  
    Implementation of genetic algorithm for network structure optimization
    
  - [Random Forest, SVM and PCA methods](Part2-NN/Other_models.ipynb)
  
    Benchmark method for accuracy estimation and feature selection

## Part 3 - [Curiosity Loop with Adaptive Reinforcement Learning](/Part3-RL/Artificial_Curiosity_Loop.ipynb)
