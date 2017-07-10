# Git-Learn
Git-Learn

#生成SSH公钥
ssh-keygen -t rsa -C "361728793@qq.com" 

#测试SSH
ssh -T git@github.com 

git remove add git@github.com:LiYiHai/linux-2.6.39.4-notes.git 

配置账户
$ git config --global user.name “your_username”  #设置用户名
$ git config --global user.email “your_registered_github_Email”  #设置邮箱地址(建议用注册giuhub的邮箱)

151.101.44.249 github.global.ssl.fastly.net 

git config http.postBuffer 524288000

-----------------------------------------------------------------------------------------------------
#取消代理 Failed to connect to 127.0.0.1 port 1080: Connection refused
git config --global --unset http.proxy
