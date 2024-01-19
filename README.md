# MCCA
Conversational Recommender Systems (CRS) aim to provide high-quality items to
users in fewer conversation rounds using natural language. Despite various attempts
that have been made, there are still some issues being faced. First, User modeling
ignores items' tag information. Second, existing knowledge graphs are incomplete,
making it difficult to comprehensively integrate information. Third, the same item exists
information gap in different knowledge graphs. To address these issues and fully utilize
external knowledge, in this paper, we propose Multi-source Information Contrastive
Learning Collaborative Augmented Conversational Recommender Systems ( MCCA),
which aims to mine the potential tag preference of the user in conversation and, at the
same time, improve the accuracy of item representation and user preference modeling.
Specifically, we use the obtained items and their tag information to construct a new
knowledge graph and use the tag information in this knowledge graph to enhance the
user representation; we design a Multi-source Item Fusion mechanism (MIF) to
minimize the information gap of items in different knowledge graphs; and then we use
unsupervised contrastive learning to improve the item representation ability after MIF.
Additionally, a Multi-Tag Fusion mechanism (MTF) is designed to combine with userperceived information (i.e., tag information popularity) and keywords obtained from
reviews to co-enhance user representations through items and tags. Extensive
experiments on two baseline datasets demonstrate that our approach is significantly
better than previous approaches in terms of effectiveness.
