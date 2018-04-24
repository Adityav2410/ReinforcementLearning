This file contains solution to OpenAI Gym, CartPole problem, implemented in TensorFlow. <br>

The ipython notebook has its solution implemented in Tensorflow <br>

* The solution implements double DQN network, with a DQN network and a target DQN network.

* The input to network is state, and it predicts value Q(s,a), for the two possible actions.

* The predicted value of targetDQN network is fed as target/truth to DQN network.

* The DQN network is trained for 50 episodes, and then the updated weights of DQN is copied to targetDQN. 


