# GDS_Proj_Group8 - ML Techniques on Bibliographic Dataset Using Graph-Based Approaches
Repo for our Project for the Course Graph Data Science (CS343), Spring 2025

# Use-cases for ML Techniques:
1. Node Classification - Author Classification: Predict the research domain or expertise of an author based on their co-authorship network.
2. Link Prediction - Citation Recommendation: Suggest relevant citations for a research paper by predicting possible citation links.

# Result Reproduction Instructions:
Our results can be reproduced by the following steps:

1. Download the raw data files from the repository, https://github.com/habib-university/cs343-project
2. Run our data cleaning and preprocessing scripts provided in this repo.
3. Create a new project in Neo4j and place the cleaned CSV files in the import directory. Make sure to install GDS Library Plugin as well.
4. Before starting data loading, edit the Graph DB settings to increase heap sizes for data loading. Add/Change the following:
    dbms.memory.heap.initial_size=2G
    dbms.memory.heap.max_size=4G
    dbms.memory.pagecache.size=2G
5. Open Neo4j Browser and run the data loading script as instructed.
6. Run the Node Classification and Link Prediction scripts as instructed.
