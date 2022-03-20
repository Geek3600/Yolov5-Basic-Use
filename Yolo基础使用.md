# Yolo_Notes

yolo源码下载地址：https://github.com/ultralytics/yolov5

* 利用Anaconda创建Python3.8的虚拟环境，之后在虚拟环境中配置yolo![image-20220319230411143](https://github.com/Geek3600/Pictures/blob/main/image-20220319230411143.png)

* clone之后需先安装依赖 —— requestments.txt文件（其中可能有些包的下载需要梯子）![image-20220319230229443](https://github.com/Geek3600/Pictures/blob/main/image-20220319230229443.png)

## Pytorch安装

Pytorch官网：https://pytorch.org/

无Nvidia显卡则选择CPU版本：![image-20220319230805182](https://github.com/Geek3600/Pictures/blob/main/image-20220319230805182.png)

在虚拟环境中执行安装指令即可

## yolo文件目录结构   

![image-20220319204513388](https://github.com/Geek3600/Pictures/blob/main/image-20220319204513388.png)

* data: 用于存放**待识别的数据**，我们可以在data中将不同类数据再整理为不同的文件夹，最后只需修改detect.py文件中的source参数即可。
* runs: 存放运行结果，无论是训练或是推理

## detect.py中的run()参数

![image-20220319204557097](https://github.com/Geek3600/Pictures/blob/main/image-20220319204557097.png)

## 自训练

### labelImg数据标记工具

github源码地址：https://github.com/tzutalin/labelImg

安装之后，初次执行可能会遇到 No module named ‘libs.resources‘的报错，解决方法：https://blog.csdn.net/qq_62018762/article/details/123601218

