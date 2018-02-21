# chineseEL-datasets
This is the revised NLPCC dataset for Chinese entity linking (re-annotated to Chinese wikipedia dump on 12-01-2017). 

The original datasets can be retrieved from http://tcci.ccf.org.cn/conference/2013/pages/page04_tdata.html (NLPCC 2013); http://tcci.ccf.org.cn/conference/2014/pages/page04_tdata.html (NLPCC 2014). After downloading the files, there ought to be the following files:
(NLPCC 2013)
query.txt.withNIL: evaluation answer with annotation to the local knowledge base
query_0525_ALL.txt: evaluation samples without answer
query_0501.txt: training data
KB_BD_nomerge_nolink.xml: local knowledge base

(NLPCC 2014)
EL_annotation.txt: evaluation answer with annotation to the local knowledge base
weiboAutoTag_6.txt: evaluation samples without answer
sample_query_2014.txt: training data
PKBase_zhwiki_1_small.xml: local knowledge base

As is pointed out in our paper, the local knowledge bases used in the datasets are partial and out-dated, thereby might restrain the development of EL techniques. We re-annotated the in-KB parts to the Chinese wikipedia. Note that not all the mentions need to be re-annotated since we identify each entity by its name instead of id or other things. Chances are that the true entity name for some mentions share the same name with the corresponding entities in Chinese wikipedia. Thereby, we merely offers the modification files here, which includes mentions whose true entity name has changed during the re-annotating process.

The modification files may conform to the following form:


We have found some errors in the revised datasets. They will be uploaded as soon as possible.
