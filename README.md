# Deciphering-the-Genetic-Foundations-of-Diseases
This project focuses on understanding the complex interplay between genes and diseases through network analysis, utilizing the "Diseasome" dataset. By mapping the relationships between genetic disorders and disease genes, we explore disease comorbidity and identify potential therapeutic targets.

Technologies Used:

    Python: Primary programming language for data manipulation and analysis.
    Gephi: Used for advanced network visualization to highlight key nodes and connections within the disease-genome network.
    NetworkX: Python library for the creation, manipulation, and study of complex networks.
    Matplotlib: Python library for creating static, animated, and interactive visualizations.

Dataset:

The "Diseasome" dataset forms a comprehensive bipartite graph, which is a pivotal resource in our analysis. It includes nodes representing both diseases and genes linked by edges denoting known genetic associations.

Features:

    Network Construction: Build a bipartite network using reduced and full versions of the "Diseasome" dataset.
    
    Statistical Analysis: Compute network statistics like degree distribution, clustering coefficient, modularity, and centrality measures.
    
    Visualization: Employ Gephi for graphical representation of the network, emphasizing significant nodes and connections.
    
    Community Detection: Implement algorithms to identify clusters within the network, highlighting the modular structure.
    
    Robustness Analysis: Perform gene knockout simulations to study the impact on network stability and disease associations.

Results:

The analysis reveals how specific genes contribute to multiple diseases, providing insights that are crucial for developing targeted therapies. Visualization in Gephi highlights the central genes and the intricate connections between diseases, offering a deeper understanding of genetic underpinnings.
