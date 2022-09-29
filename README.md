# Quantile-graphs-for-EEG-based-diagnosis-of-Alzheimer-s-disease-article
this project related to the article https://www.semanticscholar.org/paper/Quantile-graphs-for-EEG-based-diagnosis-of-disease-Pineda-Ramos/95d5e66e95d23e4b33de8013405c4f28419fa4a0
Here are some notes for this project:

 - platform: The Jupyter Notebook is based on python.
 
 - Data from channel F7 were selected in the simulations as performed in the purposed paper.
 
 - The CC(k), Δ(k), BC(k), Mo(k), and LEE(k), were computed for two sample segments each, for groups A, and D.
 
 - The output data for most matrices and measures are attached in two text files (quantile_graph_output Group A.js, and quantile_graph_output Group D.js).
   Please use any text editor to open these files such as Notepad++:
   (Link: https://github.com/notepad-plus-plus/notepad-plus-plus/releases/download/v8.4.4/npp.8.4.4.Installer.x64.exe))
   
 - We visualized 25 network graphs and created the two Html files(Ploting_Outpots_For_GroupA, and Ploting_Outpots_For_GroupD ) to display output plotting.
 - We plotted the Scalp activities based on shortest path length and laplacian_matrix.
This paper maps the time series of length T=1024 into complex network g={ N,A}∈G. Where N is a set of vertices or nodes in g that are connected by a set of weighted arcs A. Firstly, the time series X(t) is split into 20 Quantiles (represent the colored shading.), in which, each quantile q_i is assigned to the corresponding node n_i.  Two nodes n_i and n_j in g are connected by the weighted arc (n_i,n_j,w_ij).  This representation will give a weighted adjacency matrix W. when W is normalized with Markov transition the resulting time series is as continuously smooth as possible. The resulted matrix W feds as input to five matrices that extract key features of time series (e.g., clustering coefficient, mean jump length, betweenness centrality, modularity, and Laplacian Estrada index matrices). The five output matrices fid into the SVM classifier. The SVM classifies two states: healthy elderly subjects and patients with AD.

