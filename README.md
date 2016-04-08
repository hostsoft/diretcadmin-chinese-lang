# DiretcAdmin Chinese Language Pack by Hostsoft.cn

Current began offering free, All are original translation by us


how to install?


```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang/
git clone https://github.com/ninetian/diretcadmin-lang cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```


