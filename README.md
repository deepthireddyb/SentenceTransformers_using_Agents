# SentenceTransformers_using_Agents
![image](https://github.com/user-attachments/assets/07f6329a-5639-446e-a745-8c4dbd819d1a)

Sentence Transformers (a.k.a. SBERT) is the go-to Python module for accessing, using, and training state-of-the-art text and image embedding models. It can be used to compute embeddings using Sentence Transformer models or to calculate similarity scores using Cross-Encoder models (quickstart). This unlocks a wide range of applications, including semantic search, semantic textual similarity, and paraphrase mining.

A quick comparison between Sentence Transformers vs RAG based system for question and answer problem statement.

![image](https://github.com/user-attachments/assets/fed02097-7523-4560-8fbe-db67742043d9)

Issues with RAG:
RAG models are primarily designed to work with unstructured text data. Product specifications, often stored in structured formats like tables or JSON, are not naturally suited for retrieval in RAG’s typical workflows. Key product attributes (e.g., dimensions, technical specifications, or compatibility) may be misinterpreted or ignored by the generative component, leading to irrelevant or incomplete recommendations.

Solutions found with Sentence Transformers:
Workflow:
Vectorization: Converts user queries and content descriptions into fixed-length vectors.
Similarity Search: Compares query and content vectors (e.g., cosine similarity) to identify relevant matches.

Strengths:
Efficiency: Fast similarity computations using vector indexes like FAISS or ANN search.
Customizability: Easy to fine-tune for specific recommendation domains.
Versatility: Works well for ranking and retrieval tasks in recommendation systems.

Use in Recommendation Systems:
Ideal for matching users with similar content or preferences based on semantic similarity.
Often used to power "users who liked this also liked" type of features.


