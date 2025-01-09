# FDI-attack-detection

 The training data file comprises a .mat file with 4 matrices There are training_x, training_y, testing_x, and testing_y.
The training data is generated as follows:
•	By extending the real-world data by creating loads on each bus with a normal distribution, we first create 110000 sets of base load data.
•	To implement an FDI attack, we choose randomly 10,000 sets of loads of data.
•	We choose a set of target state parameters for compromise randomly for every assault. Specifically, the indices of target state variables are uniformly selected from all state variables, and the total number of target state parameters is uniformly distributed between 2 and 5.
•	We additionally add random Gaussian noises to both uncompromised and compromised data due to the dynamic measurement noise.
Following the creation of the training data, the aforementioned procedure is repeated ten times to produce IEEE 14 bus and IEEE 118 bus separate testing data sets, which inevitably results in validation variability.
