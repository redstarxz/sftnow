#乱码问题
#innerHTML用法
#wamp局域网不能访问 -> http://blog.sina.com.cn/s/blog_48e42dc90101jubj.html
					-> http://www.cnblogs.com/sbaicl/archive/2012/10/03/2710657.html
					-> http://www.poguanzi.net/item/32-wampserver-2-5
##
修改端口带来的影响 Y
融合界面 Y
git同步 Y
去掉调试界面 Y
js基础 
--js调试

##


#git clone push pemission denied 解决方案
pc@pc-PC MINGW32 /d/wamp/www/sftnow (master)
$ git remote rm origin

pc@pc-PC MINGW32 /d/wamp/www/sftnow (master)
$ git remote add origin git@github.com:xuweikang/sftnow.git


---------#1------------
##git add .  // 
##git commit -am 'tips...' //
##git push origin master //提交到自己的远程仓库
##git lg  //查看提交历史

-------------#2------------
## git remote add xwk-dev-origin git@github.com:hechao12/sftnow //建立fork源的联系 方便以后查看改动 同步本地
## git fetch xwk-dev-origin master    // 抓取远程库改动的地方 等待下一步merge 或者pull
##git pull  xwk-dev-origin master   /./ g跟新本地仓库 和主开发者保持一致
## ....继续开发中。。。
##  回到#1
 
 
 #<script src="https://gist.github.com/HeChao12/1a21a63a1b430a73806fdb57e7ee3230.js"></script>