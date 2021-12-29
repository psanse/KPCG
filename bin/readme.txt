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

./CFS <path>BPPC_1_0_10.txt_0.3   

ouptuts the following information in the console:

	  items killed at root: 0
	   w:[484,645]
	  [w:570,1.94524s]
	  
The first two lines are concerned with pre-processing and provide information of the number of objects that can be removed and the lower (484 in the example) and upper (645) bounds for the optimal knapsack value. The last line in square brackets contains the optimal value (570) and the total time (1.94s).
