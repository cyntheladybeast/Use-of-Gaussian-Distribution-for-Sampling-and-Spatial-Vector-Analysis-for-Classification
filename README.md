This project uses RMarkdown to execute a range of data analysis and visualization tasks, integrating topic modeling, spatial data analysis, and clustering techniques. 
Analysis of a twitter dataset rdmTweets-201306.RData was cleaned by removing URLs, converting to lowercase, and filtering non-English characters.
Analyzed word frequencies for terms "data" and "mining" and visualized results using a word cloud.
Finally, the project applied a topic modeling algorithm to cluster tweets into 8 topics and extracted the top 6 frequent terms for each topic.

The project then tackled clustering for Stream Data whose objective was to compare clustering methods using Gaussian-distributed data points with 5% noise and 4 clusters.
Methods used include,
Reservoir Sampling: Sampled 200 points from a stream of 500 and clustered using K-means, evaluating performance with 100 additional points.
Windowing Method: Similar sampling and clustering process, comparing results.
D-Stream Clustering: Applied grid-based clustering on 500 points and evaluated performance.
Metrics: Precision, recall, and F1-score were used for comparison.

Similarly, Spatial Data Analysis in R was conducted and it included the following tasks,
Mapping Australia: Created a map with cities as dots, highlighting cities with populations over 1 million, displaying only country and state borders.
South Australia Mapping: Visualized statistical areas using a shapefile, highlighting SA4 areas with a color palette.
Greater Adelaide Aggregation: Aggregated polygons to display SA3-level borders.
Crime Data in Salisbury:
Processed spatial data from "crimeCounts.csv" to visualize crime counts in Salisbury.
Created a raster map, highlighting high-crime areas in red and labeling suburb names and borders.
Interactive Map: Designed a web-based map featuring the top 5 restaurants in Adelaide, including screenshots of the interactive visualization.
