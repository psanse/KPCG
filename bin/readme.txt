readme.txt
This folder contains a linux binary release for the algorithm CFS for the Knapsack problem with conflicts.

Date of release@29/12/2021
Compiled with Ubuntu 16.04.7 LTS

%%%%%%%%%%%%
%%
%% INSTRUCTIONS
%%
%%%%%%%%%%%

Run the binary with the name of the problem instance (in its specific format).

./CFS <filename> 

%%%%%%%%%%%%%%%%%%
%%
%% EXAMPLE
%%
%%%%%%%%%%%%%%%%%%

Running:

./CFS <path>C3/BPPC_1_0_10.txt_0.3   

ouptuts the following information in the console:

	  items killed at root: 0
	   w:[484,645]
	   
	   //...
	   
	  [w:570,1.94524s]
	  
	  
**********items in the optimal solution*********
118 119 116 113 109 108 98 97 92 90 88 84 82 81 79 71 70 60 59 54 50 49 46 44 35 26 25 23 12 3  [30]
************************************************
nSteps: 14080080
	  
The first two lines are concerned with pre-processing and provide information of the number of objects that can be removed and the lower (484 in the example) and upper (645) bounds for the optimal knapsack value. The last line in square brackets contains the optimal value (570) and the total time (1.94s). Finally the algorithm reports the items in the optimal solution and the number of steps (number of recursive calls).
