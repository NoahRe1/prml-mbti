# 【PRML2024】通过类别平衡与特征融合提升人格预测性能

**作者**：莫繁滨

**学号**：2024111109号

# 文件说明

- prml_mbti.ipynb（代码）
- youtube_video_info.json（爬取的 YouTube URL 与视频标题的映射关系）
- bert_feature.npy（数据集中每个样本经过 BERT* 提取出的类别标签的归一化结果）

*此处使用的 BERT 为经过情感分析微调的版本：https://huggingface.co/bhadresh-savani/bert-base-uncased-emotion

# 环境

- scikit-learn 1.2.2
- nltk 3.2.4
- pandas 2.1.4
- numpy 1.26.4
- torch 2.4.1+cu121
- transformers 4.44.2

# 数据集

使用了课程指定的 MBTI 数据集：https://www.kaggle.com/datasets/datasnaek/mbti-type

