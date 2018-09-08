# Hidden-Markov-Models
 ## What are hidden markov models?

The Hidden Markov Model (HMM) is a relatively simple way to model sequential data. 

A hidden Markov model implies that the Markov Model underlying the data is hidden or unknown to you. 

More specifically, you only know observational data and not information about the states. 
In other words, there’s a specific type of model that produces the data (a Markov Model) but you don’t know what processes are producing it. 

You basically use your knowledge of Markov Models to make an educated guess about the model’s structure.
## Hidden Markov models:
•	The Hidden Markov Model (HMM) is a relatively simple way to model sequential data. 
•	A hidden Markov model implies that the Markov Model underlying the data is hidden or unknown to you. 
•	More specifically, you only know observational data and not information about the states. 
•	In other words, there’s a specific type of model that produces the data (a Markov Model) but you don’t know what processes are producing it. 
•	You basically use your knowledge of Markov Models to make an educated guess about the model’s structure.
What is Markov chain?
•	A Markov chain is "a stochastic model describing a sequence of possible events in which the probability of each event depends only on the state attained in the previous event"
## What is a Markov Model?
•	A Markov model is a stochastic model which is used to model randomly changing systems.
•	Named after Russian mathematician Andrey Markov
•	It is assumed that future states depend only on the current state, not on the events that occurred before it
•	In the fields of predictive modelling and probabilistic forecasting, it is desirable for a given model to exhibit the Markov property.
## What is Markov Property?
•	Markov property refers to the memoryless property of a stochastic process
•	Hidden Markov model
o	A hidden Markov model is a Markov chain for which the state is only partially observable. 
o	In other words, observations are related to the state of the system, but they are typically insufficient to precisely determine the state. Several well-known algorithms for hidden Markov models exist.
	Viterbi algorithm
	Forward algorithm
	Baum–Welch algorithm
o	Use?
	One common use is for speech recognition, where the observed data is the speech audio waveform and the hidden state is the spoken text. In this example, the Viterbi algorithm finds the most likely sequence of spoken words given the speech audio.
•	Markov decision process
o	A Markov decision process is a Markov chain in which state transitions depend on the current state and an action vector that is applied to the system. 
o	Typically, a Markov decision process is used to compute a policy of actions that will maximize some utility with respect to expected rewards. 
o	It is closely related to reinforcement learning, and can be solved with value iteration and related methods
•	Partially observable Markov decision process
o	A partially observable Markov decision process (POMDP) is a Markov decision process in which the state of the system is only partially observed. 
o	POMDPs are known to be NP complete, but recent approximation techniques have made them useful for a variety of applications, such as controlling simple agents or robots
