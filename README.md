This project concerns a social network model that samples a complex graph to obtain a simpler graph with the greatest resemblance to original one, using methods based on random edge sampling and shortest path between two randomly chosen nodes.In this project, the goal is to achieve a smaller graph with the most similar behaviour to the original one.
The HYB algorithm was applied to random edge sampling, and the shortest path between two randomly chosen nodes useing Dijkstra algorithm.
Sampling is performed using scale-down and back-in-time approaches, and result for each approaches is evaluated with D-statistic index to measure the degree of resemblance. 
This project is executed on Google Colab using Python, with libraries such as NetworkX, pandas, matplotlib.pyplot and Little ball of fur is used.  
In this project, the dataset is a social network of LastFM users. 
For each sampling method, centrality and diffusion models such as Independent Cascade and Linear Threshold were assessed, and two sampled graphs were compered.
