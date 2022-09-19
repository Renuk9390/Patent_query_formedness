#### Query_formedness_PQAI

This repository contains the abstract, code and data relating to the paper as shown below:
## "Is Your Search Query Well Formed? A Natural Query Understanding for Patent Prior Art Search"


The eternal focus of search engines in finding relevant documents to the query remains the
same, however, domain-specific nuances play a critical role in obtaining the desired results. Patent
prior art search is one such domain, where search results depend on the style, expressions, and
grammar of the search query. Small variations can cause significant differences in retrieved results.
Recent advances in Deep Learning based prior art search has enabled the development of easy-to-use
prior art search engines that accept natural language search queries and provide improved search
performance. However, unlike conventional keyword-based techniques where the results are readily
interpreted by the presence of queried keywords, Deep Learning based techniques act like a black box.
As a result, it is difficult for users to articulate their information in order to obtain optimal results. In
this paper, we share insights on query formedness from extensive experimentation with PQAI, an open
source Deep Learning based prior-art search engine. We study the effects of various query parameters
such as grammar, specificity, and verbosity on the search results and show that ill-formed queries
containing grammatical errors, non-essential content, and broad terminology adversely affect the
relevance of search results. We also develop and benchmark a number of Machine Learning models,
viz. Grammatical Error Detection Model (GEDM), Query Specificity Model (QSM), and Query
Verbosity Model (QVM), to identify and mitigate commonly encountered issues with ill-formed
queries. The data and code5 relating to this work are released to the community for further research in
this direction
