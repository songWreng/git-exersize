# <center>Git 学习笔记</center>

## 本地git仓库与远程仓库关联

1. 使用命令行创建一个新的仓库

   ```shell
   echo "# create a readme for the respository" >> README.md
   git init
   git add README.md
   git commit -m 'first commit'
   git branch -M main
   git remote add originorigin https://github.com/账号名/仓库名.git
   git push -u origin main
   ```

2. 使用命令行推送一个活跃的仓库

   ```
   git remote add origin https://github.com/账号名/仓库名.git
   git branch -M main
   git push -u origin main
   ```

   

   

