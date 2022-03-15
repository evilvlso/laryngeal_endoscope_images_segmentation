# Laryngeal Endoscope Images Segmentation
This repo contains laryngeal endoscope images segmentation datasets

---

## The dataset

![image-20220315164739553](https://raw.githubusercontent.com/evilvlso/picsbed/master/image-20220315164739553.png)

数据集来源于西安某三甲医院耳鼻喉科, 通过视频采集卡直接从电子内窥镜工作站拉取视频流作为原始数据, 采集周期1个月, 共采集来自不同患者的350份视频数据, 每份视频时长2~5 min不等.本数据集标签包含4种器官类别. 其中声带分声带开和声带闭两种形态, 方便后续自动诊断. 类别标签分别为**会厌、梨状窝、喉部、声带(开)、声带(闭), 其类别索引为{1,2,3,4,5}**. **img**目录下是喉镜图像, **annot**目录下是标注结果. **label_viz**目录下标注后的可视化. 采用VIA图像标注工具对训练样本进行标注. 您可以从这里下载数据集中包含的不同类型的一些样本. img目录下文件名和annot目录下文件名相匹配. 要获得对数据集完全下载权限, 请向下面的电子邮件联系人发送请求.

## Publication

## Contact

[panxiaoying@xupt.edu.cn](panxiaoying@xupt.edu.cn)

[bwdtango@stu.xupt.deu.cn](bwdtango@stu.xupt.deu.cn) 

