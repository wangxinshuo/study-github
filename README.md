# study-github
just study git, nothing.

0.git配置，生成公钥并添加
  ssh-keygen -t rsa -C '123456789@mail.com'
  cd ~/.ssh  ||  cat  id_rsa.pub

1.new repository #新建仓库 

2.git clone newRepository.git #克隆仓库到本地 

3.coding && git status #写代码，查看代码状态

4.git add youCodeFile.ext #预添加

5.git commit -m "what are you doing"  #预提交

6.git push origin master  #提交到远程仓库

————————————————————————————————————————————————————————————————————
git常用命令

$ git config --list

$ git config --global user.name "John Doe"
$ git config --global user.email johndoe@example.co
