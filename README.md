# git-linux

Multiple SSH Keys settings for different github account modify ./ssh/config

by default github use https 

if you want use ssh and ssh-key : git clone git@github.com:/zxf1111/github-linux

您的姓名和邮件地址基于登录名和主机名进行了自动设置。请检查它们正确
与否。您可以通过下面的命令对其进行明确地设置以免再出现本提示信息：

    git config --global user.name "Your Name"
    git config --global user.email you@example.com

设置完毕后，您可以用下面的命令来修正本次提交所使用的用户身份：

    git commit --amend --reset-author
#check ssh key

ssh -vvv git@github.com
