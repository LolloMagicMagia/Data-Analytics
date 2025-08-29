# Data-Analytics
Tasks and projects for the data analytics course:

### TASK 1
In this task, we analyzed the structure of interconnected networks by examining their attributes and relationships using the igraph library. Our objective was to explore various network models applicable to different contexts, evaluating their structure and behavior. As part of the analysis, we employed multiple centrality measures—such as betweenness, eigenvector centrality, PageRank, and degree centrality—to identify the main nodes within each network. By doing so, we were able to make hypotheses regarding the reasons why certain nodes exhibit high centrality values, thereby gaining insights into their significance and role within the overall network.

### TASK 2
In this task, we focused on community detection by applying various approaches to identify meaningful subgroups within the network. Specifically, we utilized methods such as edge betweenness, modularity-based community detection, the Louvain algorithm, and the leading eigenvector method. These techniques allowed us to uncover different community structures and analyze how nodes cluster together based on their connectivity. Subsequently, we applied the chosen algorithms to a new dataset in order to detect communities within it and formulate hypotheses regarding their structure and significance. Our interpretations were also guided by the insights obtained in Task 1, particularly in relation to centrality measures and the roles of key nodes within the network.

### TASK 3 
In Task 3, we conducted a sentiment analysis exercise. Although the approach we adopted is somewhat traditional compared to more recent methodologies, it serves as a valuable foundation for future, more in-depth studies. In this task, we focused on a lexicon-based approach, accompanied by essential preprocessing steps such as stopword removal, punctuation filtering, stemming, and word visualization. The initial method followed the principles provided by the NLTK (Natural Language Toolkit) framework. Through this process, we aimed to understand how the occurrence and distribution of certain words can be leveraged to infer sentiment and meaning within textual data.

### TASK 4
This task will be presented through two separate files. The first file provides a brief overview of Transformer architectures and illustrates how dimensionality reduction techniques such as PCA and t-SNE can be leveraged to project high-dimensional data into a lower-dimensional space. This transformation enhances the interpretability and visual representation of the data, making it easier for users to analyze and understand.

Following this, we will include a concise recap of why Transformer models have significantly outperformed traditional word embedding methods like Word2Vec. In particular, we will focus on the BERT model (Bidirectional Encoder Representations from Transformers), which will serve as the core tool for the subsequent sentiment analysis.

In the second part, we will apply BERT to a sentiment analysis task, making use of a pre-trained model and fine-tuning it on a specific dataset. This approach allows us to leverage the rich contextual understanding that BERT provides, yielding more accurate and context-aware sentiment classification results.

In the second file, we will demonstrate how to apply model explainability techniques—such as SHAP, gradient-based, and value-based methods—in order to understand how a model makes decisions. These tools allow us to interpret the model's reasoning process, identify possible errors, and gain insights into its internal logic and decision boundaries.

Following this explainability section, we will explore two additional applications of the BERT model: machine translation and question answering. Although these implementations will be carried out in a simplified manner, they serve as practical examples of how powerful and versatile Transformer-based models like BERT can be across a variety of natural language processing tasks.


### Sentiment Analysis and Network Analysis on Amazon Italy products
More info in the folder Projects.
