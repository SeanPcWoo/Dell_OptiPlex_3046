# Dell_OptiPlex_3046
 黑苹果efi
 
使用方法：
1、使用黑果小兵的10.14.5 MACOS 镜像来安装系统；
2、安装完成之后，使用 grubshell 进行更改 DVMT， 更改方法：
	进入 grubshell ，输入：setup_var 0xx350 0x3  // 0x3 指的是改为 96M
3、此时进入系统之后，使用本 github 提供的 efi 覆盖硬盘的 efi 即可


