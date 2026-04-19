## BlenderDeepSeek




Blender 可以通过 Python 脚本进行程序控制。如今以 DeepSeek 为代表的大语言模型，能够根据简单的自然语言生成这些 Python 脚本并完成执行。

本插件提供了简易易用的交互界面，将 DeepSeek 模型直接集成到 Blender 软件界面中，你可以使用自然语言指令来操控 Blender。


## 注意事项
本插件调用 DeepSeek 模型无需等待名单申请，仅需使用对应的 DeepSeek API 密钥即可使用。

DeepSeek API 调用与网页端 DeepSeek 网页聊天账号不互通。本插件仅在你拥有自己的 DeepSeek API Key 密钥后才可正常使用全部功能。


## 安装方法
在 GitHub 页面点击 Code > Download ZIP 克隆并下载本仓库压缩包
打开 Blender，依次打开 编辑 > 偏好设置 > 附加组件 > 安装
选中下载好的 ZIP 文件，点击 安装附加组件
勾选 DeepSeek Blender 助手 对应的复选框，启用插件
在插件偏好设置界面，粘贴你的 DeepSeek API 密钥
如需实时查看代码生成过程，打开 窗口 > 切换系统控制台


## 使用方法
在 3D 视图界面打开侧边栏（未显示时按下快捷键 N），找到 DeepSeek 助手 选项卡
在输入框内输入自然语言指令，例如：在坐标原点创建一个立方体
点击 执行 按钮，插件将自动生成 Blender Python 代码并运行


## 运行要求
Blender 3.1 及以上版本
DeepSeek API 密钥（获取地址：https://platform.deepseek.com/api_keys）
