# reinforce-actor-critic-implementation

Implemneted two RL algorithms listed as follows:

-	Reinforce
-	Actor-Critic (A2C)

Reinforce algorithm is one of the first policy gradient algorithms in reinforcement learning. 
In this algorithm the main difference is in the policy gradients. 
Unlike Q-learning algorithm in this algorithm policy gradient learns a parameterized policy instead of estimating values of state-action pairs. 
So, policy output is represented as a probability distribution over actions.

In Actor-critic online methods the agent updates its parameters after each step in the environment. 
It uses a critic that estimates the value function and whose appraisal is equal to the TD error. 
Thus, in actor-critic algorithm, “Critic” is used to estimate the value function i.e. equivalent 
to Q value of V value and “Actor’ is used to update the policy distribution in the direction suggested 
by the Critic i.e. policy gradient. Thus, it is the temporal difference for the both and thus results in 
low variance in comparison to reinforce algorithm. 

Used MuJoCo environments i.e. Half Cheetah and Inverted Pendulum) to compare these RL algorithms.

