
# DirectAdmin Enhanced/Evolution 简体中文语言包
  
我们从2007年开始提供DirectAdmin授权相关的服务  
语言包均为原创翻译  
原本仅提供给我们授权的客户内部使用的, 现在免费提供给公众客户使用

## 如果有需要购买DirectAdmin授权  
## 请在我们的官方网站[成立于2007年的主机软件官方网站购买](http://www.hostsoft.cn)


## 当前版本
* DirectAdmin 最新软件 版本  ![#f03c15](https://placehold.it/15/f03c15/000000?text=+) `1.604`  系列
* DirectAdmin 中文语言 版本  1.604 系列

我们会一直与官方同步  
最后更新 2020/05/13 
  
 ![](directadmin.png)

  
## 安装教程1 Git方式
```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang/
git clone https://github.com/ninetian/diretcadmin-chinese-lang cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```

## 安装教程2 zip方式
   注意替换版本号
```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang
da_langver=1.55
wget --no-check-certificate  -c https://github.com/ninetian/diretcadmin-chinese-lang/archive/${da_langver}.zip
unzip ${da_langver}.zip
rm -rf ${da_langver}.zip
mv diretcadmin-chinese-lang-${da_langver} cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```




