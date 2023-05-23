# Spotify Music Insights and Comparative Analysis

> Repository for CSL4050 - Data Visualization Course Mini Project

Here, we used concepts from The course Data Visualization course where various topics in Data analysis and data visualization.

All the Visualizations are Interactive in nature.

Some of the concepts used are listed below:

-   Data preparation techniques
-   Exploratory Data Analysis
-   Storytelling
-   Interactive visualizations
-   Many many more

## Repo Structure

### **History Analysis**

> This data was requested from spotify website which included StreamingHistory, Playlist information and some personal data.

-   Data Preparation
-   **Unique Artist** -> What percent of unique artists do you listen to (Do you listen some artists repeatedly or listen to varied number of artists?)
-   Top 10 Favoriate artists based on
    -   Hours listened
    -   Number of times listened
-   **Unique Songs** -> What percent of unique songs do you listen to (Do you listen some songs repeatedly or listen to varied number of songs?)
-   Top 10 Favoriate songs based on
    -   Hours listened
    -   Number of times listened
-   Day wise split of spotify listening
-   Hour wise split of spotify listening
-   Month wise split of spotify listening
-   Percent of hours spent on spotify
-   Count plot on number of songs listened on each day (for outlier detection)
-   Word Cloud based on:
    -   Artists
    -   Songs
-   Heatmap on Hour v/s Day

### **Music Taste Analyser**

> We made an python script using `spotipy` library that created a dataset for each unique song features (which is provided by spotify itself).

-   Box Plots based on song features
-   Pairplots
-   Correlation Plots
-   Closeness and distintiveness analysis -> based on the features, we found songs which were similar and songs which were mostly dissimilar to determined the range of songs a person is listening.
-   Distplots
-   **TSNE Plots (3D and 2D)**

### **Comparative Analysis**

> We used those spotify audio features of Jaimin and Mukul to perform an comparative analysis of songs tastes of them.

-   Bar plots from Mean Values of those features.
-   How diversified are the lists?
-   `Histograms`
