# 基于信息熵和凝聚度的新词发现
<p>测试！！！<p>

## 数据
* 全文存放在chapdics数据表中；
* 然后对文章进行分句（以所有标点符号为分割符）
## 方法
* 根据词频>5、凝聚度>30，信息熵>3，找出每篇小说的词，存入数据表worddic中
* 然后统计worddic中各个词出现的次数，发现每篇小说特有的词
