## elasticsearch curator离线源码安装
### 1.安装setuptools
wget https://pypi.io/packages/source/s/setuptools/setuptools-33.1.1.zip

unzip setuptools-33.1.1.zip

cd setuptools-33.1.1

python setup.py install

### 2.安装urllib3
wget https://pypi.python.org/packages/source/u/urllib3/urllib3-1.20.tar.gz

tar -zxvf urllib3-1.20.tar.gz

cd urllib3-1.20

python setup.py install

### 3.安装click
wget https://pypi.python.org/packages/95/d9/c3336b6b5711c3ab9d1d3a80f1a3e2afeb9d8c02a7166462f6cc96570897/click-6.7.tar.gz#md5=fc4cc00c4863833230d3af92af48abd4

tar -zxvf click-6.7.tar.gz 

cd click-6.7

python setup.py install

### 4.安装certifi
wget https://github.com/certifi/python-certifi/archive/master.zip

unzip python-certifi-master.zip 

cd python-certifi-master

python setup.py install

### 5.安装PyYAML
wget http://pyyaml.org/download/pyyaml/PyYAML-3.12.tar.gz -O PyYAML-3.12.tar.gz

tar -zxvf PyYAML-3.12.tar.gz 

cd PyYAML-3.12

python setup.py install

### 6.安装voluptuous
wget https://github.com/alecthomas/voluptuous/archive/0.9.3.tar.gz

tar -zxvf 0.9.3.tar.gz

cd voluptuous-0.9.3/

python setup.py install

### 7.安装elasticsearch（python-module)
wget https://github.com/elastic/elasticsearch-py/archive/5.4.0.tar.gz -O elasticsearch-py.tar.gz

tar -zxvf elasticsearch-py.tar.gz 

cd elasticsearch-py-5.4.0/

python setup.py install

### 8.安装elasticsearch-curator（python-module)
wget https://github.com/elastic/curator/archive/v5.2.0.tar.gz -O elasticsearch-curator.tar.gz

tar -zxvf elasticsearch-curator.tar.gz

cd curator-5.2.0/

python setup.py install

### 9.验证
执行以下命令

curator_cli --help


技术分享离不开您的支持，您的支持是我源源不断的动力。

![微信](https://yuanyb.github.io/wxpay.png) ![支付宝](https://yuanyb.github.io/alipay.jpg)
