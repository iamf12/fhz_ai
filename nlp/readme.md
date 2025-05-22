-modelscope
阿里大模型社区
-python notebook
-ipynb

nlp 机器学习
- python
nlp 第一语言
js 也挺好的

-引入pipeline模块
model中国第一大模型社区
魔塔
from modelscope.pipelines import pipe
from modelscope.utils.constant import Tasks
情感分析实例
semantic_cls = pipeline(Tasks.text_classification,'damo/nlp_structbert_sentiment-classification_chinese-base')
进行情感分析分类，进行打分label类
result = semantic_cls(input='遥遥领先，遥遥领先，遥遥领先')
print(result)