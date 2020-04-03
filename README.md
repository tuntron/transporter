# transporter
解决appsstore transporter上传的时候一直卡在正在验证问题

···
解决办法就是 下载
下载com.apple.amp.itmstransporter 文件后，在里面的obr/2.0.0/repository.xml 打开文件，搜索Simpsons 然后替换你自己的电脑用户名，
然后把com.apple.amp.itmstransporter文件 去 覆盖 /Users/crespo/Library/Caches 目录下的 相同的文件 ，
再次再次运行transpoter 就可以上传了
···
