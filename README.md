# 基于LSH的局部敏感hash模型

## 环境配置

```
conda create -n imageretrieval_lsh python=3.8 -y
conda activate imageretrieval_lsh

pip install torch==2.4.1 torchvision==0.19.1 torchaudio==2.4.1 --index-url https://download.pytorch.org/whl/cu121

pip install -r requirements.txt
```

## 数据和模型
模型下载路径：
http://cmp.felk.cvut.cz/cnnimageretrieval/data/networks/gl18/gl18-tl-resnet50-gem-w-83fdc30.pth

模型放置路径为weights文件夹下即可（自行创建）

数据下载路径：
https://www.kaggle.com/datasets/dansbecker/food-101

其中数据集中含有训练集和测试集描述，如果内存足够可选择全部数据集，不够的话可选择部分数据集（训练集为索引数据库，测试集为待索引图像即可）


## 运行

参考

```
python demo.py
```
