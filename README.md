# Circadian-and-Immunity
The following instructions will guide you to generate the logical parameters, the GINsim model, the Petri net model, and to obtain the simulation results. 

1.	In the first step, SMBioNet is used to generate the set of logical parameters using the BRN (an abstract representation of the pathway) and the CTL formula (representing biological observations). This information is provided to SMBioNet as input file. The input file of SMBioNet consists of three sections: the first section delineates the set of nodes given in the BRN and their potential values, the second section consists of all the interactions between nodes, and the third section specifies the biological insights using CTL formulas. SMBioNet generates the selected set of parameters that satisfy the CTL formulae as output file.
2.	To construct the qualitative model, use the BRN and the verified set of parameters using GINsim tool. Our constructed model is available here as “GINsim model.zginml”, which can be opened directly. 
3.	To generate the state graph of the model chose “Run simulation” from the Tools menu in the GINsim tool. 
4.	To convert the GINsim model to Petri net model first export the GINsim model to pnml file. Then import the pnml file into Snoopy tool to create the Timed Hybrid Petri net model. We have provided our various Petri net models here, which can be opened directly in snoopy.  
5.	To obtain the simulation results of the Petri net model select “Start Simulation-mode” from the View menu. To introduce various jet lag effects in the model chose among “Normal”, “Mild”, and “Chronic” from the “Model Configuration” dialogue box. 
 
