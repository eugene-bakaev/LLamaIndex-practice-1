# LlamaIndex Practical - 1

This assessment will validate the learner's ability apply LlamaIndex

1. Loading CV Files: This involves reading CV files from
   https://www.kaggle.com/datasets/snehaanbhawal/resume-dataset
   You can choose up to 20-30 CVs.
2. Split CV into small meaningful chunks.
3. Generating Embeddings: Convert the parsed data into numerical representations
   (embeddings) that can be easily processed by machine learning algorithms. This typically
   involves using techniques like word embeddings or sentence embeddings.
4. Storing Embeddings in a Vector Database: Save the generated embeddings into a vector
   database. As a vector store, you can choose PostgreSQL, ChromaDB, FAISS, etc,
5. Retrieving Candidate Details: Extract and display specific information about each
   candidate, such as name, profession, and years of commercial experience.
6. Generating Experience Summary: Based on the parsed data and embeddings, generate a
   summary of each candidate’s strongest skills and professional highlights.

Important note:
The task should be done using LlamaIndex.

Expected outcome:
The repository contains a straightforward web application that lists candidates. Users can click on
any candidate to view detailed information and a summary of their profile.
