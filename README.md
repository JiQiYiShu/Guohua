# Guohua 国画
Guohua: Traditional Chinese painting,  Landscape painting flower &amp; bird painting

首期：国画（山水画 & 花鸟画）

<a href='https://www.JiQiYiShu.com'>机器艺术</a>出品

### 1.定位: 
机器艺术：探索人工智能艺术与设计，展现中国元素

### 2.为什么做这个：
随着人工智能的发展，艺术结合的领域效果越来越好，应用场景丰富；但缺乏结合中国元素的应用

### 3.怎么做的：
原理：使用对抗生成网络，结合最新的技术，采用少量样本训练得到国画-山水画。

基于强大的高清人脸预训练模型，在16G GPU单卡上训练，使用自适应数据增强的StyleGan2-ada网络, 在1700张山水画上训练12个小时、3000张花鸟画训练30个小时得到。

### 4. 现在有什么？
一期国画，已经覆盖国画中的重点题材：山水画、花鸟画。

### 5.效果图
##### 5.1 生成的山水画效果图(多图、单图)

##### 多图效果：

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-ss-duotu-001-watered1.jpg"  width="65%" height="65%" />


##### 单图：

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-ss-73.jpg"  width="65%" height="65%" />

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-ss-16.jpg"  width="65%" height="65%" />


##### 5.2 生成的花鸟画效果图(多图、单图)

##### 多图：

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-fb-duotu-0011.jpg"  width="65%" height="65%" />

##### 单图：

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-fb-45.jpg"  width="65%" height="65%" />

<img src="https://github.com/JiQiYiShu/Guohua/blob/main/resources/images/jqys-fb-56.jpg"  width="65%" height="65%" />


### 5.团队：机器艺术社区(JiQiYiShu)  |  About Team
机器艺术社是开源协助组织，由国内外AI产业界和学术界同仁共同发起，探索人工智能艺术与设计，并展现中国元素。


### 6.目前还有什么问题或课题  | Current Question and Research Topic
国画中的中文，目前生成的比较抽象，并不是具体的中文；
生成国画过程中，不仅生成高清晰艺术画，而且结合图像意境、带书法图字描述，是一个研究课题。


### 7.社区 | Community 
机器艺术社区，目前处于创始阶段，现招募创始会员。
有意探索机器艺术或对此项目感兴趣的朋友，请发送邮件联系: contact@JiQiYiShu.com

### 8.后续 | Release Plan
机器艺术社区，在2021年10月1号之前，将推出5-10个带有中国元素并结合最新AI技术的高质量的应用案例或场景，以及一些相关研究课题和发布相关论文。

### 9.网址 | Website
www.JiQiYiShu.com

### 10.机器艺术-国画数据集下载  | Downloads Images from JiQiYiShu
各约100幅

<a href='https://storage.googleapis.com/jiqiyishu/datasets/JiQiYiShu-HuaNiao100.zip'>机器艺术-山水画 下载</a>

<a href='https://storage.googleapis.com/jiqiyishu/datasets/JiQiYiShu-HuaNiao100.zip'>机器艺术-花鸟画下载</a> 


###  参考 Reference 
1.模型，StyleGan2-ada：https://github.com/NVlabs/stylegan2-ada

2.高清人脸数据集，Flickr-Faces-HQ Dataset (FFHQ), https://github.com/NVlabs/ffhq-dataset


