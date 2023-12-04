# Reinforcement-Learning

This repository is to understand the basics of reinforcement learning. I believe RL plays a crucial role in the development of Artificial General Intelligence (AGI), and its importance lies in its ability to enable systems to learn and make decisions in complex, dynamic environments. RL offers a different paradigm that is particularly relevant for achieving AGI.
We will try to learn concepts like:
  
  <b>* Agent:</b> The entity or system that takes actions within an environment.  
  <b>* Environment:</b> The external system or context in which the agent operates and interacts.  
  <b>* State:</b> A representation of the current situation or configuration of the environment.  
  <b>* Action:</b> The set of possible moves or decisions an agent can make in a given state.  
  <b>* Reward:</b> A numerical value that the environment provides to the agent as feedback based on the agent's action in a particular state.  
  <b>* Policy:</b> The strategy or set of rules that the agent uses to determine its actions in different states.  
  <b>* Value Function:</b> A function that estimates the expected cumulative reward an agent can obtain from a given state (or state-action pair) under a certain policy.  
  <b>* Model:</b> In the context of RL, a model represents the agent's understanding or approximation of the environment, including how it responds to the agent's actions.  
  <b>* Markov property: </b> The Markov property states that, in a stochastic process, the future state depends only on the current state and is independent of the past states, making the sequence of events a memoryless process. This property is fundamental in Markov Decision Processes (MDPs) for modeling and solving problems in reinforcement learning.  
  <b>* State Transition Matrix:</b> A matrix that describes the probabilities of transitioning from one state to another given a particular action.  
  <b>* Markov Decision Process (MDP):</b> A mathematical framework used to model decision-making in situations where an agent makes decisions in an environment. It satisfies the Markov property, meaning the future state depends only on the current state and action, not on the sequence of events that preceded it.  
  <b>* Q-Value (Action-Value Function):</b> The expected cumulative reward of taking a particular action in a given state and following a specific policy.  
  <b>* Q-Learning:</b> A model-free RL algorithm that learns the optimal action-value function without requiring a model of the environment. It uses a Q-table to store and update Q-values.  
  <b>* Policy Iteration:</b> An iterative method for finding an optimal policy in RL by alternating between policy evaluation (estimating the value function of a policy) and policy improvement (selecting actions that improve the policy).  
  <b>* Exploration vs. Exploitation:</b> The trade-off between trying new actions to discover their effects (exploration) and choosing known actions for immediate reward (exploitation).  
  <b>* Deep Q-Learning (DQN):</b> An extension of Q-learning that uses a deep neural network to approximate the Q-function, allowing it to handle high-dimensional state spaces.  
  <b>* Replay Buffer:</b> A mechanism used in DQN to store and randomly sample past experiences, helping to break temporal correlations in the data and improve learning stability.  
  <b>* Temporal Difference (TD) Error:</b> The difference between the predicted value of a state (or state-action pair) and the actual observed value, is used in many RL algorithms for updating value functions.  

In reinforcement learning, environments are often categorized based on the nature of the tasks and the structure of the interactions between the agent and the environment. Two primary categories are:
  
  <b>* Episodic Environment:</b> In episodic environments, tasks are divided into self-contained episodes, each with a distinct beginning and end. These episodes represent specific, task-oriented interactions, such as completing a level in a game or solving a puzzle.  
  <b>* Non-Episodic Environment:</b> In non-episodic or continuing environments, no clear episodes or defined start/end points exist. Interactions persist indefinitely, and the agent's goal is often to maximize cumulative rewards over time. Examples include ongoing decision-making scenarios or tasks like continuous control and online portfolio management.  

<b>These concepts form the foundation of reinforcement learning and are essential for understanding and developing algorithms for decision-making in dynamic environments.</b> 
