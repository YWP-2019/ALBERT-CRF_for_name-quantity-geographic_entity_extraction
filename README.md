# ALBERT-CRF
数据准备：标注数据，格式如“三类实体标注格式一览.png”所示

ALBERT配置：在“ALBERT配置（CSDN）”，用于如下代码
#albert配置
config_path = './bert_model/albert_large/albert_config.json'
checkpoint_path = './bert_model/albert_large/model.ckpt-best'
dict_path = './bert_model/albert_large/vocab_chinese.txt'

模型构建、训练与评估：model.py

模型应用：run_weights.py 
