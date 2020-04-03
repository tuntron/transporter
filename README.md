# transporter
解决App Store transporter上传的时候一直卡在正在验证问题


1. 拉取代码
2. 打开文件obr/2.0.0/repository.xml，搜索Simpsons 然后全部替换成你自己的电脑用户名
3. 把com.apple.amp.itmstransporter文件夹 去 覆盖 /Users/xxx/Library/Caches 目录下的 相同的文件夹
4. 再次运行transpoter 就可以上传了
