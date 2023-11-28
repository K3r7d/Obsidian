A two-stage stochastic programming framework for evacuation planning in disaster responses (By Li Wang)
1. INTRODUCTION: 
- Main idea of this  reference is using two-stage SLP and integer program (SMIP) to construct the most efficient plan for evacuating people when the disaster come. 
- This is an uncertain problem, we have to deal with randomness.
- This paper proposed a min-cost flow model based on two-stage stochastic programming
- Model is decomposed into two subproblems by means of Lagrangian relaxation approach. The two subproblems are respectively min-cost flow model and its time-dependent case
2. PROBLEM STATEMENT:
	1. Representation of the evacuation problem as a two-stage stochastic programming problem:
		-  At the first stage, the initial warning about the disaster to the resident, the government will provide the initial evacuation plan before the new information is informed.
		- In the second stage, depend on the initial result or surprising scenarios happen, they have to change the evacuation adaptively.
		- Example: 
			In this evacuation scenario, cars a, b, c, and d initially follow a pre-planned route from a disaster area (node 1) to a safe area (node 8). However, after a certain time threshold T, the plan may adapt based on accurate road information. Two scenarios are considered: in scenario 1, cars a and b follow path 1 2 3 4 7 8, and cars c and d follow path 1 3 5 6 8; in scenario 2, cars a and b follow path 1 2 3 4 6 8, car c follows path 1 3 5 6 8, and car d follows path 1 3 5 6 7 8. The goal is to create a robust initial evacuation plan that can adapt to different scenarios in the second stage.
			![[Pasted image 20231127232744.png]]
	2. Multiple sources and sinks conversion: 
		 ![[Pasted image 20231128081920.png]] ![[Pasted image 20231128081934.png]] ![[Pasted image 20231128081950.png]] 
	1. Description of the two-stage stochastic evacuation problem by the min-cost flow problem
2. MODEL FORMULATION