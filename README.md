# Informed Agent in Vega CPFM

Code was designed to run in Google Colab - to run in another directory, comment out the first cell of any of the 'aaa' files.

All notebooks starting with 'aaa' are meant to be run by the user. Other notebooks organize the helper functions.

aaa_parameters : set up the parameters for the market and for the trained informed agent. This is done in a seperate step so that a record of the parameters used for training is always saved. Workflow for using this code is: set up parameters in aaa_parameters, train the agent in aaa_runtime and then evaluate results in aaa_analysis_draft or aaa_graphs_for_report
aaa_runtime : loads an agent from some parameters files and trains it for a desired number of epoch then saves the new state

aaa_graphs_for_report : code to generate all the graphs and data used in the report. Agent files loaded can be changed to analyse new agents. 
aaa_sampling : code used to load an agent and show their sampling distribution
aaa_analysis_draft : rough work. Load results from a simulation quickly to get some quick metrics

