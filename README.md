# AI 作文助手 (AI Essay Assistant)

一款基于 DeepSeek AI 的高考议论文写作辅助工具，专为高中生打造。支持一键生成高质量论据素材和完整范文，帮助学生拓展写作思路。

## ✨ 主要功能

*   **智能生成论据**：根据主题和关键词，生成包含素材、分析、适用论点和出处的结构化论据。
*   **一键生成范文**：生成 800 字左右的标准高考议论文范文，包含标题、正文和素材来源。
*   **深色/浅色模式**：内置舒适的淡紫色浅色主题和深沉的暗夜模式，支持炫酷的圆形扩散切换动画。
*   **响应式设计**：完美适配手机、平板和桌面端浏览器。

## 🚀 快速开始

本项目是一个纯静态的 HTML 应用，无需复杂的后端环境配置。

### 1. 获取代码
下载本项目中的 `index.html` 文件到你的本地电脑。

### 2. 配置 API 密钥 (重要)
为了保护隐私，上传的代码中已移除 API 密钥。你需要使用自己的 DeepSeek API Key。

1.  使用文本编辑器（如 VS Code, Notepad++, 记事本）打开 `index.html`。
2.  搜索代码中的 `const API_KEY`。
3.  将 `"YOUR_API_KEY_HERE"` 替换为你实际的 DeepSeek API 密钥。

```javascript
// 修改前
const API_KEY = "YOUR_API_KEY_HERE";

// 修改后 (示例)
const API_KEY = "sk-xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx";
```

### 3. 运行应用
直接双击打开修改后的 `index.html` 文件，即可在浏览器中使用。

## 🛠️ 技术栈

*   **HTML5 / CSS3**: 原生构建，无第三方 UI 框架依赖。
*   **JavaScript (ES6+)**: 处理 API 请求和页面交互。
*   **DeepSeek API**: 提供强大的 AI 文本生成能力。
*   **View Transitions API**: 实现丝滑的主题切换动画。

## 🔒 安全提示

*   本项目的 API Key 存储在前端代码中。
*   **请勿** 将包含真实 Key 的代码发布到公共网络或 GitHub 仓库。
*   仅建议在个人本地环境中使用。

## 📄 许可证

MIT License
