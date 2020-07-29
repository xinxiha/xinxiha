# GitHub与本地仓库交互-基于http协议
 - 提交本地仓库到线上
   - 第一步：创建版本库，新建文件并提交至版本区
   ```
   $ mkdir gitFile
   $ cd gitFile
   $ git init
   $ vi README.md
   $ git add *
   $ git commit -m 'NO.1 commit README.md'
   ```
   - 第二步：提交到线上仓库
   ```
   //:给线上仓库地址添加一个关联别名，origin可以是任意名称
   $ git remote add origin https://github.com/xinxiha/xinxiha.git
   $ git push -u origin master
   ```

