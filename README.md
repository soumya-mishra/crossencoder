# Crossencoder 
- Given a search query, we first use a retrieval system that retrieves a large list of documents
- However, the retrieval system might retrieve documents that are not that relevant for the search query.
- Hence, in a second stage, we use a re-ranker based on a cross-encoder that scores the relevancy of all candidates for the given search query.
![image](https://github.com/soumya-mishra/crossencoder/assets/39845943/9b977c20-ddde-48a5-af10-30c606174915)

- A re-ranker based on a Cross-Encoder can substantially improve the final results for the user. The query and a possible document is passed simultaneously to transformer network, which then outputs a single score between 0 and 1 indicating how relevant the document is for the given query.

![image](https://github.com/soumya-mishra/crossencoder/assets/39845943/0a549321-8964-4f46-9419-f3133f80f7f1)

- Continue
