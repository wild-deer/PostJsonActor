# PostJson(Actor)

此actor的功能是通过传入映射和接口地址发送json格式的post请求

### 1.安装VaRest

在虚幻商城中安装VaRest

![image-20220714155758213](https://jeremy233.oss-cn-beijing.aliyuncs.com/img1image-20220714155758213.png)

将actor拖入到场景中，并在关卡蓝图中创建引用

![image-20220714160952559](https://jeremy233.oss-cn-beijing.aliyuncs.com/img1image-20220714160952559.png)

### 2.Input

![image-20220714160045505](https://jeremy233.oss-cn-beijing.aliyuncs.com/img1image-20220714160045505.png)



| Parameter | describe          |
| --------- | ----------------- |
| Target    | postjson对象引用  |
| Map       | 需要传递的map映射 |
| URL       | 发送地址          |

### 3.OutPut

![image-20220714160504787](https://jeremy233.oss-cn-beijing.aliyuncs.com/img1image-20220714160504787.png)

| Parameter                      | describe                  |
| ------------------------------ | ------------------------- |
| Target                         | PostJson对象引用          |
| Bind Event To Post Json Result | 绑定事件                  |
| custom event                   | 绑定的用户自定义事件      |
| Result                         | VaRestJson Object对象引用 |

根据接口返回的json进行相应的解析即可