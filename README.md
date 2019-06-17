# ReservationSysyem 开发日志

1. 解决了Hbuilderx环境下scss编译错误的问题
```
错误原因
	由于D:\HBuilderX\plugins\compile-node-sass\node_modules\node-sass-china\vendor\win32-x64-64
下的binding.node文件的版本不对，导致出现报错
解决方法
	使用以下命令查看对应的版本，然后到https://github.com/sass/node-sass/releases下载对应的版本
	  ，注意需要把文件名称修改成binding.node
	node -p "[process.platform, process.arch, process.versions.modules].join('-')"  
```
2. 