# i18n 翻译专业版：Web

> 🌐 **Language / 语言**: [🇺🇸 English](description.md) | [🇨🇳 简体中文](description.zh.md)

通过**智能文本转 i18n**（Alt+Shift+]）革命化您的前端 i18n 工作流程 - 瞬间提取硬编码字符串并转换为框架特定的 i18n 调用。加上 AI 驱动的 React、Vue、Angular 和 Next.js JSON 文件翻译，支持 200+ 语言。

## 📦 安装插件

[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)
[![下载量](https://img.shields.io/jetbrains/plugin/d/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)

**[从 JetBrains 市场安装 →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

## 📺 视频教程

观看我们的全面设置指南：[i18n 翻译 Web 插件设置指南](https://www.youtube.com/watch?v=Uj9GH283Wdw)

## 💡 相关产品

需要翻译 Java 属性文件？请查看我们的配套插件 [i18n 翻译专业版：JVM](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm) 用于 Spring Boot 项目！

## 🎯 智能文本转 i18n 教程

**在几秒钟内将硬编码字符串转换为框架特定的 i18n 代码！** 通过我们的综合教程掌握革命性的 Alt+Shift+] 功能：

**[📖 完整智能文本转 i18n 教程 →](smart-text-to-i18n-tutorial.zh.md)**

学习如何通过智能框架检测、自动导入处理和 JSON 文件更新，将手动字符串提取从 3 小时噩梦变成 30 秒魔法技巧。

## Web 框架支持

- **React.js** - react-i18next、react-intl 集成
- **Next.js** - next-i18next、next-intl 支持
- **Vue.js** - vue-i18n 集成
- **Angular** - 内置 i18n 支持
- **Nuxt.js** - Nuxt i18n 模块支持
- **通用** - 使用 JSON i18n 文件的任何 Web 框架

## 主要功能

- **🎯 智能文本转 i18n** - 革命性的 Alt+Shift+] 快捷键，提取硬编码字符串并转换为框架特定的 i18n 调用，具有智能自动化
- **智能文件检测** - 自动检测常见路径中的 JSON i18n 文件
- **检测未提交的更改** - 智能 VCS 集成，用户可选择新增或修改的键
- **嵌套 JSON 支持** - 使用点记法处理复杂的嵌套结构
- **框架检测** - 识别 React、Vue、Angular、Next.js、Nuxt 项目
- **智能路径映射** - 知道每个框架存储 i18n 文件的位置
- **支持 200+ 区域设置** - 完整的语言和国家代码覆盖
- **安全 API 管理** - 使用 IntelliJ PasswordSafe 安全存储 API 密钥
- **基础语言选择** - 选择源语言以获得更好的上下文
- **覆盖控制** - 仅添加缺失键或覆盖现有键
- **进度跟踪** - 具有批处理更新的实时翻译进度
- **错误恢复** - 具有重试逻辑的稳健错误处理

## 支持的文件结构

- **React/Next.js:** public/locales/en/common.json, locales/en.json
- **Vue/Nuxt:** locales/en.json, static/locales/en.json
- **Angular:** src/assets/i18n/en.json, assets/i18n/en.json
- **通用:** src/locales/en.json, src/i18n/en.json

## JSON 结构示例

```json
{
  "homepage": {
    "title": "欢迎使用我们的应用",
    "buttons": {
      "login": "登录",
      "signup": "注册"
    }
  },
  "navigation": {
    "home": "首页",
    "about": "关于"
  }
}
```

## 支持的 LLM 提供商（8个提供商的120+模型）

- **Google Gemini** - gemini-2.5-pro、gemini-2.5-flash（免费层可用）
- **OpenAI** - GPT-5系列（Nano/Mini/Pro）、GPT-4.1、GPT-4o、GPT-4-Turbo、GPT-3.5-Turbo
- **Anthropic** - Claude 4.5（Sonnet/Haiku）、Claude Opus 4.1、Claude-3.5系列
- **DeepSeek** - DeepSeek R1、deepseek-chat、deepseek-reasoner
- **Azure OpenAI** - 企业级访问所有OpenAI模型
- **OpenRouter** - 通过统一API访问50+个额外模型
- **Ollama** - 离线翻译的本地推理
- **自定义提供商** - 任何OpenAI兼容的端点

**智能成本优化：** 智能旧模型检测会提醒您升级机会 - 最高可节省99.6%的翻译成本（例如：GPT-4 → GPT-5 Nano：每百万token从$40.00降至$0.17）。

## 高级功能

- **120+ LLM模型** - 最新的GPT-5、Claude 4.5、DeepSeek R1，具有智能旧模型检测和成本优化警报
- **旧模型检测** - 使用过时模型时自动警报，提供智能升级建议
- **成本优化智能** - 价格对比仪表板显示高达99.6%的节省
- 具有实时过滤的现代可搜索语言选择器
- 智能显示名称（en-US → "English (United States)"）
- 框架特定的配置模板
- 通过 package.json 分析自动检测项目类型
- JSON 文件的上下文菜单集成
- UTF-8 编码支持，正确的 JSON 格式化
- 并行语言翻译的批处理
- 全面的错误收集和报告

**完美适用于：** 前端开发者、全栈团队、使用现代 Web 框架并需要快速、准确的 i18n 翻译的代理机构！