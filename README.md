# 010editor  lichao890427

## macho.bt
		  该脚本用于识别arm/arm64/x86/x64架构的mac可执行文件格式macho
		  This script is for mach-o format; there is many bugs in origin script in official website,
		so I fix them and add features to ease use
		特点：
		1.修复之前某些command无法识别的bug及一些语法错误
		2.load_dylib等command直接显示路径
![image](https://github.com/lichao890427/010editor_script/blob/master/screenshots/macho_ext.png)

## AndroidResource.bt
		  该脚本用于识别android二进制xml文件，包括res/*.xml AndoidManifest.xml resource.arsc等，已收入官网
		  This script is for android binary xml file format, can deal with resource.arsc/AndroidManifest.xml
		and other binary xml
		特点：
		1.显示嵌套层数
		2.解析常量属性
		3.使用Android官方原生结构体定义

如图是解析ARSC：
![image](https://github.com/lichao890427/010editor_script/blob/master/screenshots/arsc.png)

如图是解析AXML：
![image](https://github.com/lichao890427/010editor_script/blob/master/screenshots/axml.png)

## AndroidManifest.bt
		  该脚本用于识别android二进制AndoidManifest.xml
		  This script is for android binary AndoidManifest.xml file format.
		特点：
		1.显示嵌套层数
		2.显示XML节点名称
		3.使用Android官方原生结构体定义

如图是解析AXML：
![image](https://github.com/lichao890427/010editor_script/blob/master/screenshots/axml2.png)
