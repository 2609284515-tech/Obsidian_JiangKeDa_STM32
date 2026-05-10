打开安装程序
在根目录建一个文件夹给Core
安装器件支持包
	直接安装现成的包
	或在线安装
		点三色骰子
		在左侧Device找STMicroelectronics
		选中想要的Series
		在右表Pack找后缀为DFP的下载

破解
	管理员模式打开
	File->License Management，复制CID
	keygen输入CID，Target选ARM，Generate码复制
	粘贴到License Management的New License ID Code
	Add LIC

安装STLINK驱动
	插上STLink
	如果插上后在设备管理器有感叹号则需要安装
	在Core\ARM\STLink\USBDriver\dpinst_xx，amd64是64位系统的，x86是32位的
	另外，Core\ARM\Segger有JLink驱动

安装USB转串口驱动
	插上USB转串口
	设备管理器有感叹号则需要安装
	安装包在工具软件里

下一步[[初始设置]]