# AdvancedNLP (ongoing)

个人整理nlp基本操作，方便后续快速实现各种模型算法idea：

0.NLPBasic.ipynb：分词、词性标注、句法分析、话题模型（LSA/LDA）、word2vec、爬虫、trie前缀树。

1.EntityRelationKG.ipynb：命名实体识别模型（包括CRF、BiLSTM-CRF）和联合识别模型Bert+CasRel、py2neo操作neo4j知识库操作、kg表示学习推理模型TransE等。

2.Search.ipynb：ElasticSearch结构化文本搜索引擎的建立索引、查询、更新、删除等操作，Faiss向量检索引擎的各种索引方式及建立索引和检索效率对比。互联网公司召回模型通常采用双塔模型，这时候可以用faiss进行相似性向量检索，用user embedding从item embedding的faiss向量检索库中检索top-k个（其数值通常为数百或上千）物品向量，实现快速召回。

3.huggingface_transformers_notebook.ipynb：利用huggingface transformers库来完成各项NLP任务，包括文本分类（情感分类等）、文本匹配（相似度、阅读理解等）、文本回归生成（对话问答等）、序列标注、掩码模型和自回归模型。
