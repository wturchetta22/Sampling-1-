## 



## From Willie

Here's how everything works
1. The 5%, 10%, 15%, and 20% contain folders that say RN, RNE, RW, and FF (Random Node, Random Node Edge, Random Walk, and Forest Fire) which in turn hold 5 different samples for each sampling method
2. The notebooks are self explanatory but for sake of completeness: Random_Node, Random_Walk, Random_Node_Edge, and Forest_Fire contain the sampling code
3. In_Degree_Out_Degree_WCC_SCC contains code for how to get the those four statistics, Hop_Plot describes how to get hop plot, as does Hop_Plot_WCC, and Clustering_Coefficient
4. All_Stats_Together is a quick (and I say quick meaning efficient in that you only have to press a few buttons to get all the stats for every single dataset) way to get all the stats. Would suggest looking into this and understanding before you press play as there are a couple of caveats.
5. Final_Stats contains the statistics run on web-Stanford-txt. Couple notes on this: In order the statistics are: D-Statistics for: In degree, out degree, wcc, and scc then just numbers for: hop plot, hop plot wcc, and clustering coefficient as these "statistics" output numbers rather than lists as the first four  output lists that can be compmared using d-stastistics.
6. Also if you actually want to run code you need to change the .txt file to say "FromNode" and "ToNode" so that those will be the headers of the two columns when converted to a dataframe

Here's what we still need:
1. The actual write up!

Hope this all makes some sense!
