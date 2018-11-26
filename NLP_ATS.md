**自动文本摘要（Automatic text summarization）** 是自然语言处理的重要研究领域，旨在针对原始的长文本或多个文本生成一段短文本。

一段好的摘要满足两个条件：
  - 保留文本或文本集合中重要的信息
  - 无冗余、连贯且语法可读

## 综述
||论文题目|作者|发表年份|期刊或会议|论文链接|注释|
|-|------|----|-------|----------|-------|---|
|1 |Recent advances in document summarization|Jin-ge Yao, Xiaojun Wan ,Jianguo Xiao|2017|Knowledge and Information Systems（三区）|[paper](http://59.108.48.12/lcwm/wanxj/files/summ_survey_draft.pdf)||
|2 |Recent automatic text summarization techniques: a survey|Mahak Gambhir, Vishal Gupta|2017|Artificial Intelligence Review(三区)|[paper](https://link.springer.com/article/10.1007/s10462-016-9475-9)||
|3 |A survey of text summarization techniques.|Ani Nenkova, Kathleen McKeown|2012|Mining text data（四区）|[paper](https://www.cs.bgu.ac.il/~elhadad/nlp16/nenkova-mckeown.pdf)||
|4 |Automatic summarization.|Nenkova A, McKeown K|2011|Foundations and Trends® in Information Retrieval（三区）|[paper](https://www.nowpublishers.com/article/Details/INR-015)||

## 相关论文
||论文题目|作者|发表年份|期刊或会议|论文链接|注释|
|-|------|----|-------|----------|-------|---|
|1|LCSTS: A Large Scale Chinese Short Text Summarization Dataset|Baotian Hu Qingcai Chen Fangze Zhu|2015|EMNLP|[paper](http://aclweb.org/anthology/D15-1229)|基于新浪数据贡献大规模中文数据集|
|2|A repository of state of the art and competitive baseline summaries for generic news summarization.|Hong K, Conroy J, Favre B, Kulesza A, Lin H, Nenkova A|2014|LREC|[paper](http://www.lrec-conf.org/proceedings/lrec2014/pdf/1093_Paper.pdf)|在DUC数据集上多种extractice方法对比|
|3|A Novel Feature-based Bayesian Model for Query Focused Multi-document Summarization |Jiwei Li, Sujian Li|2013|ACL|[paper](https://transacl.org/ojs/index.php/tacl/article/view/80/6)|基于topic增强连贯性|
|4|Discovery of Topically Coherent Sentences for Extractive Summarization|Asli Celikyilmaz, Dilek Hakkani-Tur|2011|ACL|[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.482.1376&rep=rep1&type=pdf)|基于topic增强连贯性|
|5|Learning Summary Prior Representation for Extractive Summarization|Ziqiang Cao, Furu Wei, Sujian Li, Wenjie Li|2015|ACL|[paper](http://www.aclweb.org/anthology/P15-2136)|extractive模型＋CNN|
|6|AttSum: Joint Learning of Focusing and Summarization with Neural|Ziqiang Cao, Wenjie Li, Sujian Li|2016|COLING|[paper](http://www.aclweb.org/anthology/C16-1053)|extractive模型＋Attention+DUC|
|7|Fear the REAPER: A System for Automatic Multi-Document Summarization with Reinforcement Learning|Cody Rioux, Sadid A. Hasan|2014|ACL|[paper](http://anthology.aclweb.org/D/D14/D14-1075.pdf)|extractive模型＋强化学习+Multi-Document|
|8|Real-Time Web Scale Event Summarization Using Sequential Decision Making||2016|arXiv|[paper](https://arxiv.org/pdf/1605.03664.pdf)|TREC数据集|
|9|A Sentence Compression Based Framework to Query-Focused Multi-Document Summarization|Lu Wang, Claire Cardie|2013|ACL|[paper](https://www.cs.cornell.edu/home/cardie/papers/acl13-Sentence.pdf)|结合多个特定打分器构造打分函数+句子压缩+query+Multi-document|
|10 |Jointly Learning to Extract and Compress|Taylor Berg-Kirkpatrick Dan Gillick Dan Klein|2011|ACL|[paper](http://nlp.cs.berkeley.edu/pubs/BergKirkpatrick-Gillick-Klein_2011_Summary_paper.pdf)|Mlti-task+压缩句子|
|11|Fast and robust compressive summarization with dual decomposition and multi-task learning.|Miguel B. Almeida|2013|ACL|[paper](https://pdfs.semanticscholar.org/6401/9361de1d4fa54a7fc5949f3c4f568a6f334c.pdf)|改ILP框架为AD3，运行快+multi-task框架|
|12|Single Document Summarization based on Nested Tree Structure|Yuta Kikuchi, Tsutomu Hirao|2014|ACL|[paper](http://www.aclweb.org/anthology/P14-2052)|句子间依赖关系+词间依赖关系+句子压缩|
|13|Learning-based single-document summarization with compression and anaphoricity constraints|Greg Durrett，Taylor Berg-Kirkpatrick|2016|ACL|[paper](https://arxiv.org/pdf/1603.08887.pdf)|句子压缩+结构约束（代词）两种约束|
|14|Multi-Document Abstractive Summarization Using ILP based Multi-Sentence Compression|Banerjee S, Mitra P, Sugiyama K|2015|IJCAI|[paper](https://arxiv.org/pdf/1609.07034.pdf)|生成式摘要+word图最小路径|
|15|Toward abstractive summarization using semantic representations|Fei Liu， Jeffrey Flanigan Samh|2015|ACL|[paper](https://www.aclweb.org/anthology/N15-1114)|生成式摘要+Abstract Meaning Representation+图|
|16|Multi-document abstractive summarization using ilp based multi-sentence compression|Siddhartha Banerjee, Kazunari Sugiyama|2015|IJCAL|[paper](https://www.comp.nus.edu.sg/~sugiyama/papers/IJCAI15-174.pdf)|生成式摘要+multi-document+word-graph+最短路径|
|17|Abstractive multi-document summarization via phrase selection and merging|Lidong Bing, Piji Li, Yi Liao|2015|ACL|[paper](https://www.cs.cmu.edu/~lbing/pub/acl2015-bing.pdf)|生成式摘要+phrase细粒度|
|18|Improving Argument Overlap for Proposition-Based Summarisation|Yimai Fang, Simone Teufel|2016|ACL|[paper](http://www.aclweb.org/anthology/P16-2078)|生成式摘要+proposition-based|
|19|Multi-Sentence Compression: Finding Shortest Paths in Word Graphs|Katja Filippova|2010|Coling|[paper](http://www.aclweb.org/anthology/C10-1037)|最短路径|
|20|Unsupervised Sentence Enhancement for Automatic Summarization|Jackie Chi Kit Cheung|2014|EMNLP|[paper](http://www.aclweb.org/anthology/D14-1085)|引入外部资源作为sentence-enhencement|
|21|HEADY: News headline abstraction through event pattern clustering|Enrique Alfonseca,Daniele Pighin|2013|ACL|[paper](http://www.aclweb.org/anthology/P13-1122)|新闻标题|
|22|Modelling events through memory-based, openie patterns for abstractive summarization.|Pighin D, Cornolti M, Alfonseca E, Filippova K|2014|ACL|[paper](http://www.aclweb.org/anthology/P14-1084)|新闻标题|
|23|Abstractive summarization of product reviews using discourse structure|Shima Gerani, Yashar Mehdad|2014|EMNLP|[paper](http://emnlp2014.org/papers/pdf/EMNLP2014168.pdf)|discourse结构+template-bsed框架|
|24|Opinosis: A Graph-Based Approach to Abstractive Summarization of Highly Redundant Opinions|Kavita Ganesan and ChengXiang Zhai and Jiawei Han|2010|COLING|[paper](http://aclweb.org/anthology/C10-1039)|基于graph+用户review摘要|
|25|**Abstractive sentence summarization with attentive recurrent neural networks**|Sumit Chopra, Michael Auli|2016|NAACL|[paper](http://www.aclweb.org/anthology/N16-1012)|生成式摘要+RNN+Attention|
|26|**Abstractive Text Summarization using Sequence-to-sequence RNNs and Beyond**|Ramesh Nallapati, Bowen Zhou|2016|CoNLL|[paper](http://www.aclweb.org/anthology/K16-1028)|Attention+RNN+生成式摘要|
|27|Incorporating Copying Mechanism in Sequence-to-Sequence Learning|Jiatao Gu， Zhengdong Lu|2016|ACL|[paper](http://aclweb.org/anthology/P16-1154)|copy机制+Seq2Seq|
|28|Pointing the Unknown Words|Caglar Gulcehre|2016|ACL|[paper](http://www.aclweb.org/anthology/P16-1014)|未知词在摘要生成中的作用|
|29|**SEQUENCE LEVEL TRAINING WITH RECURRENT NEURAL NETWORKS**|Marc’Aurelio Ranzato, Sumit Chopra, Michael Auli, Wojciech Zaremba|2016|ICLR|[paper](https://arxiv.org/pdf/1511.06732.pdf)||
|30|Neural summarization by extracting sentences and words.|Cheng J, Lapata M|2016|ACL|[paper](https://arxiv.org/pdf/1603.07252.pdf)|hierarchical + Attention|
|31|A Dataset and Evaluation Metrics for Abstractive Compression of Sentences and Short Paragraphs|Toutanova K, Brockett C, Tran KM, Amershi S|2016|EMNLP|[paper](https://aclweb.org/anthology/D/D16/D16-1033.pdf)|Multi-reference|
|32|Neural network-based abstract generation for opinions and arguments. |Wang L, Ling W|2016|NAACL|[paper](http://www.aclweb.org/anthology/N16-1007)|电影评价等文本中生成摘要|
|33|Predicting salient updates for disaster summarization.|Kedzie C, McKeown K, Diaz F|2015|ACL|[paper](http://www.aclweb.org/anthology/P15-1155)|动态|
|34|Evolutionary Timeline Summarization: a Balanced Optimization Framework via Iterative Substitution|Rui Yan,Xiaojun Wan|2011|SIGIR|[paper](http://www.cis.pku.edu.cn/faculty/system/zhangyan/papers/SIGIR2011-yanrui.pdf)|动态演化|
|35|Comparative document summarization via discriminative sentence selection|Dingding Wang|2013|TKDD|[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.172.5258&rep=rep1&type=pdf)|总结文本区别的摘要|
|36|Update summarization based on co-ranking with constraints|Xiaojun Wan|2012|COLING|[paper](https://pdfs.semanticscholar.org/21c2/30d55c44f75e2c7cf4d57f1bf3df513bdfef.pdf)|动态文本摘要|
|37|Domain-independent abstract generation for focused meeting summarization|Lu Wang|2013|ACL|[paper](https://www.cs.cornell.edu/home/cardie/papers/acl13-Domain.pdf)|会议演讲摘要|
|38|Neural Network-Based Abstract Generation for Opinions and Arguments|Lu Wang, Wang Ling|2016|NAACL|[paper](http://www.aclweb.org/anthology/N16-1007)|评价/意见摘要+RNN|
|39|Opinosis: a graph based approach to abstractive summarization of highly redundant opinions.|Kavita Ganesan, Jiawei Han|2010|COLING|[paper](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.231.6542&rep=rep1&type=pdf)|评价摘要+Graph|
|40|Summarizing entity descriptions for effective and efficient human-centered entity linking. ||2015|WWW|[paper](https://dl.acm.org/citation.cfm?id=2741094)|知识图谱描述摘要|
|41| Summarizing source code using a neural attention model.||2016|ACL|[paper](https://aclweb.org/anthology/P/P16/P16-1195.pdf)|源代码描述摘要|
|42|Exploiting category-specific information for multidocument summarization||2012|COLING|[paper](http://www.aclweb.org/anthology/C12-1128)|guidence + multi-document|
|43|**A hierarchical neural autoencoder for paragraphs and documents.** ||2015|ACL|[paper](https://nlp.stanford.edu/pubs/acl2015_jiwei.pdf)|长文本+hierarchical LSTM|
|44|A latent variable recurrent neural network for discourse-driven language models|Yangfeng Ji, Jacob Eisenstein|NAACL|2016|[paper](http://www.aclweb.org/anthology/N16-1037)|RNN + 句子间discourse|


## 参考论文
||论文题目|作者|发表年份|期刊或会议|论文链接|注释|
|-|------|----|-------|----------|-------|---|
|1|End-to-end memory networks.||NIPS|2015|[paper](https://arxiv.org/pdf/1503.08895.pdf)||

##相关研究团队
1.[xusun, Peking University](https://xusun.org/)
2.[xiaojun wan, Peking University](http://www.icst.pku.edu.cn/lcwm/index.php?title=%E9%A6%96%E9%A1%B5)
