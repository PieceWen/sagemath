# 安装sagemath(如果速度慢，可选择换为阿里源)
```shell
sudo apt install sagemath-jupyter
```

# Ubuntu apt更换为阿里源
apt源配置在 /etc/apt/sources.list，首先备份一下：
```shell
cd /etc/apt/
cp sources.list sources.list.bp
```
然后修改为附件的sources.list，最后更新一下软件列表
```shell
sudo apt-get update
```

