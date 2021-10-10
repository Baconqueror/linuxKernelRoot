	项目说明：
	1.【find_kernel_func】 自动寻找内核函数位置
	2.【ida_patch_cmd_creator】 根据内核函数位置自动生成IDA补丁代码
	3.【testRoot】 演示全部ROOT功能的调用方法
	4.【su】 授予ROOT到第三方进程的演示
	5.【suTest】模拟第三方进程获取ROOT权限的APP
	6.【PermissionManager】以APP形式演示全部ROOT功能的调用方法
	
	printf(
		"======================================================\n"
		"本工具名称: Linux ARM64 完美隐藏ROOT演示\n"
		"本工具功能列表：\n"
		"\t1.显示自身权限信息\n"
		"\t2.获取ROOT权限\n"
		"\t3.绕过SELinux\n"
		"\t4.还原SELinux\n"
		"\t5.执行ROOT命令\n"
		"\t6.执行ADB Shell命令\n"
		"\t7.赋予ADB最高级别权限\n"
		"\t8.授予ROOT到其他进程\n"
		"\t新一代root，跟面具完全不同思路，摆脱面具被检测的弱点，完美隐藏root功能（免root级别），兼容安卓APP直接JNI稳定调用。\n"
		"======================================================\n"
	);