 模仿美团  
 
 npm i
 
 npm run dev
 1.采用nuxt ssr，路由有点问题，不太了解底层实现，解决只能通过location.href，
 
 2.但每次加载了新的页面，vuex 什么的都会不在，切换城市页面正常运行放到vuex，尽力做得到真实化数据，
 
 3.做了简单的登录和注册功能，注册用了smtp服务发送邮件。
 
 
4.爬了一些美团的数据放到数据库，数据不全，只有部分


5.引入的pinyin.js库有BUG，很多汉字不能正常解析成拼音


6.数据库放在dbs文件夹下面，导入到自己本地mongodb
