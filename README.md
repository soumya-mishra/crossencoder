# crossencoder
- Given a search query, we first use a retrieval system that retrieves a large list of documents
- However, the retrieval system might retrieve documents that are not that relevant for the search query.
- Hence, in a second stage, we use a re-ranker based on a cross-encoder that scores the relevancy of all candidates for the given search query.
