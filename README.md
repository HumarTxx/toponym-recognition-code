# 主要库的版本

本项目是基于keras（Using TensorFlow backend）以下是主要库的版本

- python = 3.6.8



- keras == 2.2.4
- keras_contrib == 0.0.2
- keras_bert == 0.80.0
- tensorflow == 1.14.0



# 项目目录结构

- data 数据目录
  - 具体请查看数据目录文件夹下的README文件
- DataProcess 数据处理文件夹
  - 具体请查看数据处理文件夹下的README文件
- Pubilc 公共工具
  - path 定义文件（文件夹）的路径
  - utils 工具
    - 创建log
    - keras的callback调类
- Model 模型（总共定义了5个模型，具体结构请查看Model文件夹下的README文件）
  - BERT+BILST+CRF
  - BILSTM+Attention+CRF
  - BILSTM+CRF
  - IDCNN+CRF（1）
  - IDCNN+CRF（2）
- log 记录数据

