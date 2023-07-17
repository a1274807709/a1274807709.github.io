# 安卓QQ 各类算法 8.9.30以上版本

## 合作项目

- [官网](https://qqxieyi.cn)
- [滑块地址](http://cr.qqxieyi.cn/register?dl=7)
- [开发文档](https://console-docs.apipost.cn/preview/5fab715e2dd2844a/5977bbc0502ddb6c)

## 使用

### 环境准备

 每次调用，务必需要先运行一次init初始化环境，为你创建独立算法环境，会返回给你  `appkey` 同时请你务必牢记


## 流程

- 初始化网址 http://127.0.0.1:9999/txapi/init?Card=MMD70AB77389D8F9A18B7760B8E95BAA&version=8.9.68  `Card    卡密`   `version QQ版本`
- [其余请点击开发文档](https://console-docs.apipost.cn/preview/5fab715e2dd2844a/5977bbc0502ddb6c)

# 544说明
get模式544 http://127.0.0.1:9999/txapi/encrypt_544?Card=&version=&data=&sms=&guid=&QQuin=&reqsms=&pass=&appkey=
### Data 如果看不懂建议使用post自行拼接
`810_f`,`810_9`,`810_2`,`810_7`,`812_a`,`812_6`,`812_a`,`812_6`,`812_5`

| 参数名      | 意义                                                                                         | 例子                               |
|----------|--------------------------------------------------------------------------------------------|----------------------------------|
| VERSION  | **注意！**这里的VERSION指的**是QQ的版本号，而是SDK Version**，可以在QQ安装包中找到此信息                                | 8.9.30-8.9.68                    
| UIN      | 操作的的QQ号                                                                                    | 80062（可以留空）                      |
| GUID     | 设备的GUID，为16个字节的16进制，需要删除全部空                                                                | ABCDABCDABCDABCDABCDABCDABCDABCD |
| DATA     | QQ登录发送544的CmdId和SubCmdId，例子中810是登陆CmdId，9是SubCmdId                                         | 810_9                            |
| DATA | 需要提供 guid,  版本号（8.9.30-8.9.68）                                                             | 810_f                            |
| DATA | 需要提供 guid,  版本号（8.9.30-8.9.68）                                                             | 810_a                            |
| DATA | 需要提供 guid,  版本号（8.9.30-8.9.68）                                                             | 810_9                            |
| DATA | 需要提供 guid,QQuin  版本号（8.9.30-8.9.68）                                                        | 810_2                            |
| DATA | 需要提供 guid,QQuin  版本号（8.9.30-8.9.68）                                                        | 810_7                            |
| DATA | 需要提供 version,sms(区号+手机号 86-18888888888)  版本号（8.9.30-8.9.68）                                | 812_a       |
| DATA | 需要提供 reqsms(注册手机回执`文本型`，不需要带入长度 8618888888888-86-1226787189 )  版本号（8.9.30-8.9.68）          | 812_6     |
| DATA | 需要提供 reqsms(注册手机回执`文本型`，不需要带入长度 8618888888888-86-1226787189 ) pass注册密码  版本号（8.9.30-8.9.68） | 812_5      |

## 一些设备参数
会打印的自行打印，不会打印的，查看：https://blog.csdn.net/weixin_38819889/article/details/118641961
