# Android编译
部署完服务后就可以开始客户端的编译。客户端提供源码，从[这里](http://www.baidu.com)下载最新的源码。

## 修改配置
找到Config.java文件，修改```IM_SERVER_HOST```和```IM_SERVER_HOST```为你的服务器地址，比如```192.168.1.100```。修改```IM_SERVER_PORT```为```80```, 修改```APP_SERVER_PORT```为```8888```。

## 运行
编译运行，填入您的手机号码，验证码填写服务器部署时指定的superCode ```66666```。