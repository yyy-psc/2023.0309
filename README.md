# 2023.0309
# 服务器看显卡：
# watch -n 0.5 nvidia-smi  : 0.5s刷新一次显卡(nvidia-smi:刷新显卡)
![](https://github.com/yyy-psc/2023.0309/blob/main/photos/1.png)


# kill -9 （PID）：杀死显卡
![](https://github.com/yyy-psc/2023.0309/blob/main/photos/2.png)

# 跑训练模型：
default=false

![](https://github.com/yyy-psc/2023.0309/blob/main/photos/3.png)

# 跑验证模型：
Default=True

![](https://github.com/yyy-psc/2023.0309/blob/main/photos/4.jpg)

# 代码跑训练好的模型的循环：
![](https://github.com/yyy-psc/2023.0309/blob/main/photos/5.jpg)

# 训练的第一个模型：
![](https://github.com/yyy-psc/2023.0309/blob/main/photos/6.jpg)

# 遇到the following arguments are required：XXX
![](https://github.com/yyy-psc/2023.0309/blob/main/photos/7.jpg)

找不到文件的路径了。
解决办法1：

![](https://github.com/yyy-psc/2023.0309/blob/main/photos/8.jpg)

自己在default上加上：（记得连服务器还要再次上传一下服务器）

解决办法2：

![](https://github.com/yyy-psc/2023.0309/blob/main/photos/9.jpg)

在参数那边写上去，就会按照参数上面的路径来走

# 服务器使用显卡：

![](https://github.com/yyy-psc/2023.0309/blob/main/photos/10.jpg)

CUDA_VISIBLE_DEVICES=2，代表在2号显卡上跑代码（即第三章显卡）
