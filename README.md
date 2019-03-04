# 本地仓库上传到git流程
1.建立本地仓库.git；
# （$ git init）
2.将需要提交的本地文件复制与到本地仓库所在文件夹，但不是.git内；
3.将要提交的本地文件添加到本地仓库；
# （$ git add .）
4.新建提交文件版本说明；
# （$ git commit -m "loading first time"）
5.提交本地文件到仓库步骤如下：
# 1）$ git remote add origin https://github.com/caohuiying/xiaobaiBk.git（链接到要提交的仓库）
# 2）$ git remote add origin https://github.com/caohuiying/xiaobaiBk（如果有分支，链接）
# 3）$ git push -u origin master（可直接在当前仓库提交）
