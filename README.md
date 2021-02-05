### DATASETS ###

Road Network Graph - roadNet-CA.txt
Road Network Graph random nodes used - file2.txt
Random Graph Generated - random_graph.txt
Random Graph Generated random nodes used - random_nodes.txt

### OUTPUTS ###

Task (a) and (b):
	Road Network Output - roadCA_taskAB.txt
	Random Graph Output - random_taskAB.txt
Task (c):
	Road Network Output - roadCA_c_k=2.txt
	Random Graph Output - random_c_k=2.txt
Task (d):
	Road Network Output - roadCA_d_k=4.txt
	Random Graph Output - random_d_k=4.txt

Empirical Study Graphs:
	Variable |H| Analysis - Variable_H_Analysis.png
	Variable k Analysis - Variable_K_Analysis.png

### SCRIPTS ###

GraphGenerator.ipynb - Run first three cells to generate a graph and store it. Change the
number of nodes, vertices, output file names and number of random nodes to generate as desired.

Hospitals.ipynb - Run all cells to generate the same results we obtained in our experiment. There is a
cell to input arbitrary graphs. To create them, there are two methods.
	1) Instantiate an empty NearestTargetGraph or KNearestTargetGraph. Call the add_edge method on the 
	   object to add a directed edge. An undirected graph requires an add_edge for both direction.
	2) Run the first 3 cells in GraphGenerator.ipynb. Customize num_nodes, num_vertices, num_random_nodes and file names as needed.
