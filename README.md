# DirectAdmin 最新版 中文语言包

我们从2007年开始提供DirectAdmin授权相关的服务,语言包均为原创翻译
原本仅提供给我们授权的客户内部使用的, 现在免费提供给公众客户使用

我们会一直与官方同步

### 当前版本
* DirectAdmin 最新软件 版本  1.5.0
* DirectAdmin 中文语言 版本  1.5.0

### 安装教程1 Git方式
```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang/
git clone https://github.com/ninetian/diretcadmin-chinese-lang cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```

### 安装教程2 zip方式
   注意替换版本号
```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang
wget --no-check-certificate  -c https://github.com/ninetian/diretcadmin-chinese-lang/archive/1.5.0.zip
unzip 1.5.0.zip
rm -rf 1.5.0.zip
mv diretcadmin-chinese-lang-1.5.0 cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```


# DiretcAdmin Chinese Language Pack by Hostsoft.cn

Current began offering free, All are original translation by us

how to install?


```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang/
git clone https://github.com/ninetian/diretcadmin-chinese-lang cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```


