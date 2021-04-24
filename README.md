# profiledatascrapping
This is a sample code for clustering the profile data from freelancer.in website
Dataset containing user profiles that is scraped data from freelancer.in, Scraped data containing Users_profile.csv file, That was containing columns Name, Title, location ,skills ,Hourly rate. 
In this clustering based on their location and their skills. 
Location and skills are encoded into 1-0 format, that dataset containing file is  New_dataset_cluster.csv 
Then choose the K-means cluster algorithm, and clustering into 3 clusters. 
Then analysis using two methods that is PCA and T-SNE. 
The T-SNE algorithm did a fairly decent job in visualizing the clusters, too. But, there were a few  noticeable differences when comparing it's resulting plots to PCA's resulting plots. 
One major difference between the plots produced by PCA and T-SNE is that T-SNE's plots seemed to  have it's clusters overlapping with each other more so than in PCA's plots. For example, if you look at  the 2-D plot formed from PCA, you see three distinct sections of the data-points with strict, visible  borders separating each colour into groups. Whereas, if you look at the 2-D plot formed from T-SNE,  you, again, see three sections formed within the data-points, but this time, datapoints between each  cluster seem to 'intermingle' and overlap more. 
The other major difference between the plots created by PCA and the plots created by T-SNE, is the  shape. Because both PCA and T-SNE perform dimensionality reduction in very different ways (and  with different objectives), the resulting shape or distribution of the points produced by the  algorithms will almost always be very different. 
Bear in mind that the plots resulting from the T-SNE algorithm are quite variable, in that they  depend very heavily on the value chosen for perplexity.
