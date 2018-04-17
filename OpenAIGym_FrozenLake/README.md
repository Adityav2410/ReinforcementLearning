This file contains solution to OpenAI Gym, Frozen lake problem. <br>

The ipython notebook has two solutions/approach: <br>
<br>
1. Policy Iteration - Model based approach <br>
2. Qlearning - Model free learning - epsilon greedy approach is used for exploration <br>
<br>
For the model based learning: <br>
1. A model of the environment is created. Essentially Transition matrix T(s,a,s') and Reward Matrix(s,a,s') is first created by exploration. <br>
Once the environment model is created, Policy iteration is performed with the help of Bellman optimality condition. <br>
