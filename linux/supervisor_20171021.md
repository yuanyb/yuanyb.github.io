## linux supervisor离线源码安装
### 1.安装meld
wget https://pypi.python.org/packages/45/a0/317c6422b26c12fe0161e936fc35f36552069ba8e6f7ecbd99bbffe32a5f/meld3-1.0.2.tar.gz#md5=3ccc78cd79cffd63a751ad7684c02c91
tar -zxvf meld3-1.0.2.tar.gz
cd meld3-1.0.2
python setup.py install

### 2.安装supervisor
wget https://pypi.python.org/packages/31/7e/788fc6566211e77c395ea272058eb71299c65cc5e55b6214d479c6c2ec9a/supervisor-3.3.3.tar.gz#md5=0fe86dfec4e5c5d98324d24c4cf944bd
tar -zxvf supervisor-3.3.3.tar.gz
cd supervisor-3.3.3
python setup.py install

### 3.验证安装是否成功
supervisorctl --help

下一期预告：使用守护进程supervisor管理logstash

技术分享离不开您的支持，您的支持是我源源不断的动力。

![微信](http://upload-images.jianshu.io/upload_images/7144180-f1c618ecdd1e78b7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)  ![支付宝](http://upload-images.jianshu.io/upload_images/7144180-592fa4773384df4e.jpg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)