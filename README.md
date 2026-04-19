BlenderDeepSeek
Blender 支持使用 Python 程序脚本进行操控。如今以深度求索（DeepSeek）为代表的大语言模型，可以根据简单的自然语言生成这些 Python 脚本并执行。本插件提供了简洁易用的交互界面，将 DeepSeek 大模型直接集成到 Blender 软件界面中，你只需使用自然语言指令，即可操控 Blender。
注意事项
本插件内使用 DeepSeek 模型无额外等待申请门槛，直接使用 DeepSeek API 密钥即可调用。
插件仅支持通过 DeepSeek 官方 API 接口调用模型，你需要前往 DeepSeek 开放平台申请属于自己的 API Key 来使用全部功能。
安装教程
在 GitHub 页面点击 Code > Download ZIP 下载本项目压缩包
打开 Blender，依次进入 编辑 > 偏好设置 > 附加组件 > 安装
选中下载好的 ZIP 压缩包，点击 安装附加组件
勾选 DeepSeek Blender 助手 复选框，启用该插件
在插件偏好设置界面中粘贴你的 DeepSeek API 密钥
想要实时查看生成的代码，可打开 窗口 > 切换系统控制台
使用方法
在 3D 视图界面，打开侧边栏（若未显示可按快捷键 N），找到 DeepSeek 助手 选项卡
在输入框中输入自然语言指令，例如：在坐标原点创建一个立方体
点击 执行 按钮，插件将自动生成 Blender Python 代码并运行
运行要求
Blender 3.1 及以上版本
DeepSeek API 密钥（可在 https://platform.deepseek.com/api_keys 获取）
演示视频
https://user-images.githubusercontent.com/63528145/227158577-d92c6e8d-df21-4461-a69b-9e7cde8c8dcf.mov
