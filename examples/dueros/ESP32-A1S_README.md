# 前言
&nbsp; &nbsp; &nbsp; &nbsp; 本SDK新增了menuconfig-->Audio HAL..的ESP32-A1S-Audio-Kit V2.2板子，如果你的音频开发板是安信可的ESP32-A1S-Audio-Kit v2.2，可以直接配置使用本demo。
# 一、配置方式
&nbsp; &nbsp; &nbsp; &nbsp; idf.py menuconfig-->Audio HAL..-->ESP32-A1S-Audio-Kit V2.2
![在这里插入图片描述](https://img-blog.csdnimg.cn/20210603112917553.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxMTE0MDkyMDc0NQ==,size_16,color_FFFFFF,t_70)
# 二、按键说明
## 1.引入库


<font color=#999AAA >代码如下（示例）：



```c
import numpy as np
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
import  ssl
ssl._create_default_https_context = ssl._create_unverified_context
```

## 2.读入数据

- KEY1-->唤醒键，目前可以使用语音“Hi，乐鑫” 来唤醒；
- KEY2-->配网键，如果你想使用手机App配置网络连接，可以按这个件进入配网模式；
- KEY3-->模式按键，目前没有任何功能；
- KEY4-->播放按键，目前没有播放功能；
- KEY5-->增加音量；
- KEY6-->减小音量



