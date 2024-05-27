# text2graph
Text2graph workflow using LLMGraphTransformer. 

This Jupyter notebook uses Langchain's LLMGraphTransformer to take a text input and form it into a knowledge graph. The knowledge graph is then used to train a Graph Neural Network (GNN) that classifies nodes into clusters. This allows the GNN to then detect any anomaly nodes in the knowledge graph (Example: a cluster with 1 node is likely to be a anomaly and an error in the input text).
