
# DirectAdmin Evolution Skin Simplified Chinese
This repo hosts the simplified Chinese (zh_Hans) language files for the new DirectAdmin Evolution skin.
Please refer to https://help.directadmin.com/item.php?id=704&in1=zh_Hans for installation instructions.

The translation is still WIP (about 91% translated). Many of the core features should have been translated, but areas such as mail, DNS, HTTPD configurations, etc. are still missing many of the translations. There are also other problems such as inconsistent use of half-width and full-width symbols, spacing, vocabularies, along with some ambiguous translations due to the use of polysemous words in the source language, and more :P. Some technical terms are remained as is (such as key, handler, etc.) because that's what I have been seeing most of the time. Feel free to send me a pull request if you want to improve this language file.

### Credit
Thanks to POEdit, I was able to import many of the translations from other contributors (contains machine translations). However, since the contributions are anonymous, I am not able to name them. I have translated the rest of the fields where no translation was available or the quality was not up to standard.

### Skin version
version=Latest


## DiretcAdmin Chinese Language Pack by Hostsoft.cn

Current began offering free, All are original translation by us  
how to install?  

```sh
rm -rf /usr/local/directadmin/data/skins/enhanced/lang/cn
cd /usr/local/directadmin/data/skins/enhanced/lang/
git clone https://github.com/ninetian/diretcadmin-chinese-lang cn
chown diradmin:diradmin -R cn
perl -pi -e 's/language=en/language=cn/' /usr/local/directadmin/data/users/*/user.conf
```
