Yaf框架学习
===========

git在windows/linux上配置ssh公钥
-------------------------

>设置git的username和email

    $ git config --global user.name "username"
    $ git config --global user.email "email"

>生成密钥

    ssh-keygen -t rsa -C "email"

>.ssh下面将id_rsa.pub里的内容复制出来粘贴到github个人中心的账户设置的ssh key里面