MGPicker_Program目录内的所有文件&文件夹都是程序自带的，请不要改变他们，
如果您要添加用户文件，比如自动加载的文件或转换器等，请放置到MGPicker_UserConfig的相关目录内。

AutoSourced:	内置的随MG-Picker工作室启动而自动中载的一些脚本。

CodeSnippets:	内置的代码片段的脚本。这些脚本的内容，将来被使用时将会被插入到当前代码编辑器的鼠标位置。

CommandButtonPresets:	内置的命令按钮预设。有了这些预设，用户就可以快速创建命令按钮且无需再敲代码。
		这些脚本的内容将会是被创建的命令按钮的command，
		脚本的文件名将会是被创建的命令按钮的标签，并且文件名中所有的"_"字符将被替换成空格。
		比如使用了"Reset_Selection.mel"这个预设文件创建的命令按钮，其标签是"Reset Selection"。			
			
Converters:	内置的picker转换器脚本.
		这些转换器用来读取其它picker程序的picker节点或文件。

Icons: 	MG-PickerStudio使用的图标. 

Installer: MG-PickerStudio安装器，里面的安装mel可以用来将工具装到其它不同的maya版本。

LanguageRes: 	MG-Picker工作室内置的语言文件。目前只有英文，简体中文，繁体中文。
		如果你有除英文中文外的语言翻译文件，请邮件到mgpickerstudio@gmail.com，以便将来这个语言资源被正式发布到程序目录里。

Plug-ins: 	MG-Picker工作室的插件文件. 

SnapshotStyles: 内置的图片处理风格预设，主要用来截图等的自动处理。
		所有的预设文件均以~字符开头，以显示这些预设是内置预设。
		不以"~"字符开头的预设文件将被忽略。

Templates: 内置的Picker模板，你可以基于这些模板快速创建picker.
	   同时这些模板picker也可以被用做picker例子，从中了解如何用MG-Picker工作室创建picker.

Terms:	MG-Picker工作室的程序用户协议及条款，请不要更动里面内容。  	

MGPicker.ver: 	MG-Picker工作室的当前版本数值，请不要更动里面内容。

MGPicker_WrittenByMiguel.mel: 	MG-Picker工作室加载用mel，它也提供了工具不可或缺的脚本支持，请不要更动里面内容。