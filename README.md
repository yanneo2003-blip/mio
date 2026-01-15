🔮 灵喵 | DivineChat (Mio)<div align="center">
<img src="https://i.imgs.ovh/2026/01/15/yFdAQm.png" width="100" alt="Logo">
<h3>AI 驱动的沉浸式东方命理咨询终端</h3>
<p>紫微斗数 · 子平八字 · 真太阳时 · 多维人格咨询</p>
</div>📖 项目简介灵喵 (DivineChat) 是一款基于 Web 的单文件轻量级命理咨询应用。它将传统东方玄学（紫微斗数、子平八字）的严谨算法与现代 LLM（大语言模型）的自然语言能力相结合，创造了一个既专业又富有温度的 AI 算命体验。不同于传统的算命软件，灵喵更像是一个“通灵终端”。它运行在您的浏览器中，排盘计算完全在本地完成，仅将必要的脱敏上下文发送给 AI，极大程度地保护了您的隐私。

✨ 核心特性🌌 双核排盘引擎：集成 lunar-javascript 与 iztro，支持精确到真太阳时的八字排盘与紫微斗数排盘。内置中国主要城市经纬度数据，自动校正出生时间偏差。🎭 多维 AI 人格矩阵：内置 7 位风格迥异的咨询师人格，包括道家高人、盲派宗师、现代心理学家、纵横家等。支持**“诸仙会审”**模式，让不同流派的 AI 大师为您联合推演，从不同角度辩证分析。

🎨 Apple Design 风格 UI：极致的响应式设计，在移动端和桌面端均有完美表现。支持深色/浅色模式无缝切换，界面优雅、克制、无干扰。

🔒 隐私优先：所有聊天记录和用户设置均存储在浏览器 localStorage 中。排盘算法纯前端运行，不依赖后端数据库。

🛠️ 高度可配置：支持自定义 OpenAI 格式的 API Endpoint (Base URL)。支持自定义模型名称 (Model Name) 和 API Key。

🛠️ 技术栈本项目采用单文件组件 (Single File Component) 思想，无需复杂的构建流程，开箱即用。Core: Vue.js 3 (CDN 引入)UI/Styling: Tailwind CSS (CDN 引入)Metaphysics:lunar-javascript (历法与八字)iztro (紫微斗数排盘)Markdown: markdown-itIcons: FontAwesome 6

🚀 快速开始
1. 获取代码直接克隆本仓库或下载 index.html 文件。git clone [https://github.com/yourusername/divine-chat.git](https://github.com/yourusername/divine-chat.git)
2. 运行项目由于本项目是纯静态的单文件应用，您可以：直接打开：双击 index.html 在浏览器中运行。本地服务：使用 Live Server (VS Code 插件) 或 python -m http.server 启动（推荐，可避免部分浏览器跨域限制）。
3. 配置 AI点击页面右上角的 设置 (Sliders Icon) 按钮。输入您的 API 服务商提供的 Base URL (例如 https://api.openai.com/v1)。输入 API Key。输入 Model Name (例如 gpt-4o, deepseek-chat 等)。点击“保存配置”。
4. 📖 使用指南输入信息：在首页填写您的姓名、性别、公历生日、出生时辰及出生地。系统会自动根据出生地经度计算真太阳时。开始推演：点击“开始推演”，系统将生成您的命盘概览。
5. 切换大师：在聊天界面的顶部栏，点击不同的大师标签（如“清虚道长”、“铁口刘”）切换当前对话的 AI 人格。
6. 提问互动：在底部输入框发送您的问题，AI 将结合当前的命盘数据为您解答。📂 项目结构divine-chat/

└── index.html  # 核心文件，包含所有 HTML/CSS/JS 逻辑

🤝 贡献欢迎提交 Issue 或 Pull Request！由于本项目保持“单文件”特性以便于分发，请尽量保持代码的紧凑性。📄 许可证本项目采用 MIT License 开源。<div align="center"> Designed with ❤️ by Mio </div>
