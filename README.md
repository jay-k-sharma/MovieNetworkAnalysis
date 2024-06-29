Creating a detailed technical README for your project "Keywords: Network Analysis and Propagation Dynamics of the Most Successful Films" involves documenting various aspects of your research and methodology. Here's a structured outline for your README:

---

# Project Title: Network Analysis and Propagation Dynamics of the Most Successful Films

## Authors:
- Jay Sharma (jksharma@my.yorku.ca)
- Saiz Prasla (saiz2001@my.yorku.ca)
- Harsimran Saini (saini19@my.yorku.ca)
- Zuhair Siddiqi (zuhairs@my.yorku.ca)
  
**York University, Toronto, Ontario, Canada**

---

## Table of Contents

1. [Abstract](#abstract)
2. [Introduction](#introduction)
3. [Motivation / Problem Statement](#motivation--problem-statement)
4. [Related Work](#related-work)
5. [Methodology](#methodology)
   - [Dataset](#dataset)
   - [Mathematical Formulation of Node Weights](#mathematical-formulation-of-node-weights)
   - [Mathematical Formulation of Edge Weights](#mathematical-formulation-of-edge-weights)
   - [Algorithms Used](#algorithms-used)
6. [Experiments / Evaluation](#experiments--evaluation)
   - [The Network](#the-network)
   - [Evaluations](#evaluations)
7. [Analysis and Visualization](#analysis-and-visualization)
8. [Robustness and Challenges](#robustness-and-challenges)
9. [Conclusion](#conclusion)
10. [Future Work](#future-work)
11. [References](#references)

---

### Abstract<a name="abstract"></a>

The project explores network dynamics in films using shared actors as nodes and their collaborations as weighted edges. Utilizing data from TMDB on the top 9,400 highest-rated films, we employ network analysis techniques such as PageRank and Louvain community detection to uncover insights into successful film attributes.

### Introduction<a name="introduction"></a>

The study focuses on understanding the interconnectedness of successful films through actor collaborations, aiming to provide actionable insights for the film industry amidst changing market dynamics post-COVID-19.

### Motivation / Problem Statement<a name="motivation--problem-statement"></a>

In an era where theatrical releases are declining, the project aims to identify factors contributing to blockbuster success to guide strategic decision-making by filmmakers and producers.

### Related Work<a name="related-work"></a>

We build upon studies analyzing centrality and community structures in film networks, using methodologies similar to those exploring actor networks and production collaborations.

### Methodology<a name="methodology"></a>

#### Dataset<a name="dataset"></a>

We obtained data from TMDB API, focusing on the top 9,400 films by rating. Attributes considered include budget, revenue, genres, actors, production companies, and viewer ratings.

#### Mathematical Formulation of Node Weights<a name="mathematical-formulation-of-node-weights"></a>

We calculated a "success score" for each film based on normalized profit and viewer ratings, scaled to a 0-10 range to measure relative success.

#### Mathematical Formulation of Edge Weights<a name="mathematical-formulation-of-edge-weights"></a>

Edge weights were determined by the number of shared actors between films, emphasizing actor collaborations as significant indicators of network strength.

#### Algorithms Used<a name="algorithms-used"></a>

- **PageRank**: Used to rank films based on their success scores, adjusted with a personalized vector.
- **Louvain Algorithm**: Employed for community detection to identify clusters of films with strong internal connections.

### Experiments / Evaluation<a name="experiments--evaluation"></a>

#### The Network<a name="the-network"></a>

- **Nodes**: 5,755 films
- **Edges**: 13,998 weighted edges based on shared actor collaborations

#### Evaluations<a name="evaluations"></a>

Detailed analysis using PageRank, Node Degree Centrality, and Louvain Community Detection to identify influential films, genres, and production clusters within the network.

### Analysis and Visualization<a name="analysis-and-visualization"></a>

Graphical representations and community summaries highlight clusters such as "Marvel Cinematic Universe" and "Harry Potter," showcasing their influence and success factors.

### Robustness and Challenges<a name="robustness-and-challenges"></a>

Challenges include dataset scalability and API limitations (e.g., IMDb). Methodological refinements were made to ensure robust analysis and meaningful insights.

### Conclusion<a name="conclusion"></a>

The study provides insights into film network dynamics, emphasizing the role of actor collaborations and community structures in predicting film success.

### Future Work<a name="future-work"></a>

Future research could expand to include more nuanced factors like directorial influence and genre-specific analyses to enhance predictive models for film success.

### References<a name="references"></a>

Cite relevant studies and methodologies used for data collection, analysis, and algorithm implementations.

---

This README template provides a comprehensive structure to document your project's technical details, methodologies, and findings effectively. Adjust sections and subsections as per your specific project requirements and findings.
