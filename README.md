# MSRN_paddle

ClassSR: Multi-scale Residual Network for Image Super-Resolution

[Paper]([Multi-scale Residual Network for Image Super-Resolution (thecvf.com)](https://openaccess.thecvf.com/content_ECCV_2018/papers/Juncheng_Li_Multi-scale_Residual_Network_ECCV_2018_paper.pdf))



Paddle 复现版本

## 数据集
DIV2K
https://data.vision.ee.ethz.ch/cvl/DIV2K/
Set5
https://drive.google.com/drive/folders/1pRmhEmmY-tPF7uH8DuVthfHoApZWJ1QU


## 训练模型

X2,X3,X4模型链接：链接：https://pan.baidu.com/s/1-0EU167AQYauOnPAzCOoZA 
提取码：MSRN 

## 训练步骤
### train sr
```bash
python train.py -opt config/train/train_MSRN.yml
```


## 测试步骤
```bash
python test.py -opt config/test/test_MSRN.yml
```





## 参考资料

- [Xiangtaokong/ClassSR](https://github.com/Xiangtaokong/ClassSR)
