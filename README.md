mercury-adfilter
================

mercury浏览器 去广告规则

前言：您的IOS设备必须已经越狱，IOS设备上已安装iFile 或者 PC端已安装 iTools 或者其他可以修改越狱文件系统的第三方软件
================
如何使用

安装 mercury pro 浏览器，PP助手或者其他提供越狱软件下载的第三方app进行安装，
安装完毕，进入mercury浏览器，打开 设置-->扩展-->广告拦截【开】

OK,您已经完成ios端的设置，请退出mercury浏览器，并且结束mercury后台进程。

本文以 iTools 为例作介绍，其他文件浏览器大同小异。
链接ios设备至安装有iTools的PC机，打开iTools，点击左侧 文件系统-->常用目录-->程序(用户)，找到 mercury，
双击打开，进入 /Library/Mercury目录，在该目录下，存在同名文件adFilter.json，请将该文件重命名为 adFilter.json.bak 
完成以上步骤之后，下载 https://raw.github.com/HuChundong/mercury-adfilter/master/adFilter.json
将该文件复制到adFilter.json.bak 相同目录，即 
/var/mobile/Applications/5F003983-D9EF-49BE-BD9D-989EBB853C92/Library/Mercury
此处 5F003983-D9EF-49BE-BD9D-989EBB853C92 所有设备均不同，但是iTools 会自动显示为app的名称，所以不用担心找不到正确目录。

到此，整个去广告规则文件已经替换成功。重新打开mercury浏览器即可享受无广告的网上冲浪了。

上文针对小白，有一定基础的朋友就直接看这句就行了：找到mercury浏览器的安装目录，替换/Library/Mercury下的adFilter.json文件，over。


