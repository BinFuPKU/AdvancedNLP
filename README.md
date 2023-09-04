# AdvancedNLP (ongoing)

个人整理实现nlp基本操作(mac m1环境, python 3.9)，作为方便后续快速实现各种模型算法的组件：

0.NLPBasic.ipynb：分词、词性标注、句法分析、话题模型（LSA/LDA）、word2vec、爬虫、trie前缀树（典型应用场景如Query Suggestion）等。

1.EntityRelationKG.ipynb：命名实体识别模型（包括CRF、BiLSTM-CRF）和联合识别模型Bert+CasRel、py2neo操作neo4j知识库操作、kg表示学习推理模型TransE等。

2.Search.ipynb：ElasticSearch结构化文本（包括文本、数值、term类型等）分布式搜索引擎的建立索引、查询、更新、删除等操作，Faiss向量检索单机引擎的各种索引方式及建立索引和检索效率对比。互联网公司（如我在boss直聘全职实习时候）召回模型通常采用双塔模型，这时候可以用faiss进行相似性向量检索，用user embedding从item embedding的faiss向量检索库（数亿级别）中检索top-k个（其数值通常为数百或上千）物品向量，实现快速召回（一般尽量控制在50ms内）。

3.huggingface_transformers_notebook.ipynb：利用huggingface transformers库来完成各项NLP任务，包括文本分类（情感分类等）、文本匹配（相似度、阅读理解等）、文本回归生成（对话问答等）、序列标注、掩码模型和自回归模型。这个库已经可以让人进行傻瓜操作，通过切换pipeline组件或底座模型即可。所以nlp的未来一定是落地应用或者分布式计算加速降低成本。
