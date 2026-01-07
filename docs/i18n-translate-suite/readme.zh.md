<!--
SEO 中文元标签 - 搜索引擎和社交媒体优化
标题: i18n 翻译 - IntelliJ IDEA 国际化翻译插件
描述: IntelliJ IDEA AI 驱动的国际化插件。自动翻译 Java 属性文件和 JSON i18n 文件，使用 OpenAI/Anthropic LLM。支持 React、Vue、Angular、Next.js，200+ 语言支持。
关键词: IntelliJ IDEA, 国际化, 翻译插件, Java, 属性文件, JSON, React, Vue, Angular, Next.js, AI, OpenAI, Anthropic, LLM, 本地化, 多语言
-->

# i18n 翻译社区中心 | IntelliJ IDEA 国际化翻译插件

> 🌐 **Language / 语言**: [🇺🇸 English](readme.md) | [🇨🇳 简体中文](readme.zh.md)

<!-- SEO 中文关键词信息 -->
**关键词**: IntelliJ IDEA 国际化翻译, 翻译插件, AI 翻译, Java 属性文件, JSON 本地化, React Vue Angular Next.js, OpenAI Anthropic LLM, 多语言开发

**i18n Translate** **IntelliJ IDEA 插件套件**的官方社区中心。先进的 **AI 驱动翻译工具**，支持 Java 属性文件和 JSON i18n 文件翻译，完美支持 **React、Vue、Angular 和 Next.js** 框架。

使用 **OpenAI 和 Anthropic LLM** 转变您的国际化工作流程，支持 **200+ 语言**的智能上下文感知自动翻译。

---

## 🚀 以 Kotlin 为优先的 i18n 生态系统

**i18n Translate** 以 **Kotlin 作为翻译生态系统中的最高优先级语言**设计，为现代 JVM 开发提供最佳体验，同时为现有项目维护全面的 Java 支持。

### 为什么 Kotlin 优先？
- **🎯 现代开发**: Kotlin 代表 Spring Boot 和 JVM 开发的未来
- **⚡ 增强体验**: 专为 Kotlin 的简洁语法和类型安全而定制
- **🔄 无缝集成**: 与 Kotlin 的空安全和函数式编程功能完美集成
- **☕ Java 兼容性**: 完整的 Spring Boot Java 支持确保不遗留任何项目

**结果**: 为现代 JVM 生态系统设计的翻译体验，优先考虑 Kotlin 同时欢迎 Java 开发者。

---

## 🎉 免费增值模式 - 免费开始，随时升级！

**自 2025 年 11 月起**，**JVM 专业版**和 **Web 专业版**插件现在提供**免费增值模式**：

- **🆓 永久免费：** 每次翻译一种语言 + 完整的智能文本转 i18n 功能（Alt+Shift+]）
- **✨ 无试用期：** 免费版永久有效，无时间限制
- **🔄 无缝升级：** 随时激活专业版功能，获得无限语言和批量翻译
- **🚀 无需重新安装：** 即时升级，无需更换插件

**精简版插件已弃用：** 独立的精简版插件不再支持。请使用专业版免费增值版本，其中包含所有精简版功能的免费版。

**[安装 JVM 专业版（免费增值） →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)** | **[安装 Web 专业版（免费增值） →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

---

## ✨ 高级 IntelliJ 翻译功能

*   **🎯 智能文本转 i18n：** 革命性功能，通过键盘快捷键 **Alt+Shift+]** **提取硬编码字符串**并转换为 i18n 方法调用 - 瞬间改变您的开发工作流程。
    - **[📖 JVM 插件教程 →](docs/jvm-plugin/smart-text-to-i18n-tutorial.zh.md)** - 将 Spring Boot 硬编码字符串转换为 MessageSource 调用
    - **[📖 Web 插件教程 →](docs/web-plugin/smart-text-to-i18n-tutorial.zh.md)** - 将 React/Vue/Angular 字符串转换为框架特定的 i18n 调用
*   **🤖 AI 驱动的翻译：** 利用领先的 **OpenAI GPT** 和 **Anthropic Claude** 模型，通过上下文感知即时翻译您的 i18n 资源文件
*   **🚀 Kotlin 优先属性支持：** 完整的 **Kotlin .properties 文件翻译**，支持 Spring Boot，并全面兼容 Java
*   **🌐 JSON 和 XLF i18n 翻译：** 高级 **React、Vue、Angular、Next.js** JSON 和 XLF 国际化文件处理，保持嵌套结构
*   **🔧 IntelliJ IDE 集成：** 原生 **JetBrains 插件**，带有上下文菜单翻译、进度跟踪和 VCS 集成
*   **📋 批量处理：** 高效的 **批量翻译**，包含速率限制、重试逻辑和全面错误处理
*   **🎯 智能检测：** 自动识别 **未提交的更改**，并选择性翻译新增与修改的键值

## 🎯 最新功能与成本优化

### 🌐 插件界面国际化（全新！）
**插件界面现已支持多语言** - 自动跟随您的 IDE 语言设置：
- **简体中文** (Chinese Simplified)
- **韩语** (한국어)
- **日语** (日本語)
- **印尼语** (Bahasa Indonesia)

所有对话框、消息、工具提示和模型显示名称均已本地化。无需手动配置！

### 跨 8 个提供商的 120+ LLM 模型
通过我们扩展的模型支持，包括 GPT-5.2、Claude Opus 4.5 等，**最高可节省 99.6% 的翻译成本**。

**最新模型（2026 年 1 月）：**
- **OpenAI：** GPT-5.2、GPT-5.2 Pro、O3、GPT-5.1、GPT-5 Nano/Mini/Pro
- **Anthropic：** Claude Opus 4.5（最强大）、Claude Opus 4、Claude Sonnet 4、Claude Haiku 3.5（最具成本效益）
- **Google Gemini：** Gemini 2.5 Flash（免费）、Gemini 2.5 Pro
- **智能旧模型检测：** 使用过时模型时自动警报，提供智能升级建议
- **成本智能仪表板：** 查看价格对比，显示高达 99.6% 的潜在节省
- **最佳性价比：GPT-5 Nano** - 每百万 token $0.17 的专业翻译，而 GPT-4 为 $40.00

**10 种语言 × 1000 个键的节省示例：**
- 传统 GPT-4：每次翻译运行约 $8.00
- 优化后的 GPT-5 Nano：每次翻译运行约 $0.03
- **年度节省：** 频繁更新的团队可节省 $1000+

**了解更多：** 在设置 → i18n Translate Pro → LLM 配置中查看您当前的模型成本

## 🚀 IntelliJ 翻译快速入门指南

初次使用 **IntelliJ IDEA i18n 翻译**？选择您的开发技术栈：

- **☕ JVM 插件安装指南（[专业版](docs/jvm-plugin/user-guide.zh.md) / [精简版](docs/jvm-lite-plugin/user-guide.zh.md)）** - **Java 属性文件翻译** (.properties) 支持 Spring Boot
- **🌐 Web 插件安装指南（[专业版](docs/web-plugin/user-guide.zh.md) / [精简版](docs/web-lite-plugin/user-guide.zh.md)）** - **JSON i18n 文件翻译**，支持 React、Vue、Angular 和 Next.js 项目

每个详细指南包含 **IntelliJ 插件安装**、**API 密钥配置** 和 **自动翻译** 设置 - 在几分钟内完成您的第一个 **多语言项目**。

## 📺 视频教程与频道

订阅我们的 **[YouTube 频道](https://www.youtube.com/@eastgate3194)** 获取全面的教程、技巧和更新！

- 🎥 插件安装指南
- 🛠️ 高级配置教程  
- 💡 i18n 最佳实践和工作流程
- 🆕 新功能发布公告

**精选视频：**
- [节省时间！在 IntelliJ 中一键翻译您的 Properties 文件](https://youtu.be/eUKpTmiWATU)
- [别再浪费时间做网页应用的人工翻译](https://youtu.be/eUKpTmiWATU)
- [高级翻译工作流程](https://www.youtube.com/@eastgate3194) _(订阅获取更多内容!)_

## 📦 安装 IntelliJ 翻译插件

准备 **自动化您的 i18n 翻译工作流程**？直接从 **JetBrains 市场** 安装：

### ☕ i18n 翻译专业版：JVM 插件
[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)
[![下载量](https://img.shields.io/jetbrains/plugin/d/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)

**[安装 JVM 插件 →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**

### 🌐 i18n 翻译专业版：Web 插件
[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)
[![下载量](https://img.shields.io/jetbrains/plugin/d/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)

**[安装 Web 插件 →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

### ☕ i18n 翻译精简版：JVM 插件（免费） - ⚠️ 已弃用
[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/28324-i18n-translate-lite-jvm.svg)](https://plugins.jetbrains.com/plugin/28324-i18n-translate-lite-jvm)
[![下载量](https://img.shields.io/jetbrains/plugin/d/28324-i18n-translate-lite-jvm.svg)](https://plugins.jetbrains.com/plugin/28324-i18n-translate-lite-jvm)

> **⚠️ 已弃用：** 此插件不再支持。请切换到 **[JVM 专业版（免费增值）](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**，其中免费包含所有精简版功能。

**[~~安装 JVM 精简版插件~~](https://plugins.jetbrains.com/plugin/28324-i18n-translate-lite-jvm)** → **[切换到 JVM 专业版（免费增值） →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**

### 🌐 i18n 翻译精简版：Web 插件（免费） - ⚠️ 已弃用
[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)
[![下载量](https://img.shields.io/jetbrains/plugin/d/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)

> **⚠️ 已弃用：** 此插件不再支持。请切换到 **[Web 专业版（免费增值）](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**，其中免费包含所有精简版功能。

**[~~安装 Web 精简版插件~~](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)** → **[切换到 Web 专业版（免费增值） →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

## 🔍 插件比较指南

| 功能 | 🍃 JVM 插件 | 🌐 Web 插件 |
|---------|---------------|---------------|
| **文件类型** | Java .properties | JSON i18n 文件 |
| **框架支持** | Spring Boot | React, Vue, Angular, Next.js |
| **语言支持** | 200+ Java 语言环境 | 200+ 语言 |
| **文件结构** | 扁平键值对 | 嵌套 JSON 对象 |
| **IDE 支持** | 所有 JetBrains IDE | WebStorm, IntelliJ IDEA |
| **使用场景** | 后端 Java 应用 | 前端 Web 应用 |

### 我需要哪个插件？
- **Java/Spring Boot 开发者** → 选择 JVM 插件
- **React/Vue/Angular 开发者** → 选择 Web 插件  
- **全栈团队** → 安装两个插件获得完整覆盖

## 功能比较：免费版 vs 专业版

### 功能比较矩阵

| 功能 | 免费版 | 专业版 |
|---------|--------------|-------------|
| **翻译语言** | 🔒 **最多 1 种目标语言** | ✅ **无限制** |
| **LLM 模型可用** | ✅ **120+ 模型**（8 个提供商） | ✅ **120+ 模型**（8 个提供商） |
| **旧模型检测** | ✅ **自动警报** | ✅ **自动警报** |
| **成本智能** | ✅ **节省高达 99.6%** | ✅ **节省高达 99.6%** |
| **智能文本转 i18n** | ✅ **完全启用** | ✅ **完全启用** |
| **基础翻译** | ✅ **已启用** | ✅ **已启用** |
| **提交面板翻译** | ❌ **不可用** | ✅ **已启用** |
| **批量处理** | ✅ **无大小限制** | ✅ **无大小限制** |
| **键值排序** | ❌ **已禁用** | ✅ **已启用** |
| **重复删除** | ❌ **已禁用** | ✅ **已启用** |
| **VCS 集成** | ⚠️ **部分** （仅新键） | ✅ **完整** （修改 + 新增） |
| **翻译对话框按钮** | ⚠️ **有限** | ✅ **全部启用** |
| **项目设置** | ✅ **所有选项** | ✅ **所有选项** |
| **时间限制** | ✅ **永久免费** | N/A |
| **许可证** | 免费 | 付费 |

### 共享功能（免费版和专业版均可用）
- **120+ LLM 模型**跨 8 个提供商（Gemini、OpenAI、Anthropic、DeepSeek、Azure、OpenRouter、Ollama、自定义）
- **旧模型检测**，自动升级建议
- **成本智能仪表板**，显示高达 99.6% 的节省
- **智能文本转 i18n**，提取硬编码字符串
- **批量处理**，无大小限制
- **项目设置**，可自定义

### 主要升级优势

#### 🆓 免费版非常适合：
- **个人开发者**学习 i18n 工作流程
- **小型项目**，单语言需求
- **测试和评估**插件功能
- **智能文本提取**，无需翻译

#### 💎 专业版必备：
- **多语言应用程序**
- **专业开发团队**需要无缝提交工作流程
- **复杂工作流程要求**，提交面板集成
- **生产应用程序**，现有 i18n 键
- **企业项目**需要高级功能
- **效率优先团队**，在提交过程中上下文翻译

### 专业版独家功能
- **无限目标语言**
- **完整 VCS 集成**，修改键处理
- **提交面板集成**：在提交视图中右键直接翻译
- **高级处理功能**：键值排序和重复删除
- **所有对话框按钮启用**

## 💰 价格与许可

### 🆓 **免费版（专业版插件包含）**
- **JVM 专业版 & Web 专业版**：免费版包含每次 1 种语言 + 智能文本转 i18n
- 非常适合个人开发者和小型项目
- 无时间限制，永久免费
- 随时升级到专业版，获得无限语言

### 💎 **专业版升级（商业）**
- 随时激活专业版功能 - 无需重新安装
- **个人/组织许可证**：在 JetBrains 市场查看当前价格
- 简单的应用内激活

### 📋 **专业版许可证优势**
- ✅ 无限翻译语言
- ✅ 提交面板集成
- ✅ 高级 VCS 功能
- ✅ 优先电子邮件支持
- ✅ 包含所有未来更新
- ✅ 商业使用权
- ✅ 团队协作功能

### ⚠️ **精简版插件已弃用**
独立的精简版插件（JVM 精简版 & Web 精简版）自 2025 年 11 月起不再支持。所有精简版功能现在都包含在专业版免费增值版本中。请迁移到专业版插件以获得持续支持和更新。

**迁移指南：** 查看发布说明 [JVM 精简版](docs/jvm-lite-plugin/release-notes.zh.md) | [Web 精简版](docs/web-lite-plugin/release-notes.zh.md)

## 📚 文档

### 插件文档

| **JVM 专业版**（Java 属性文件） | **JVM 精简版**（Java 属性文件 - 免费） |
|----------------------------|------------------------------|
| • **[插件描述](docs/jvm-plugin/description.zh.md)** \| **[Plugin Description](docs/jvm-plugin/description.md)** | • **[插件描述](docs/jvm-lite-plugin/description.zh.md)** \| **[Plugin Description](docs/jvm-lite-plugin/description.md)** |
| • **[用户指南](docs/jvm-plugin/user-guide.zh.md)** \| **[User Guide](docs/jvm-plugin/user-guide.md)** | • **[用户指南](docs/jvm-lite-plugin/user-guide.zh.md)** \| **[User Guide](docs/jvm-lite-plugin/user-guide.md)** |
| • **[🎯 智能文本转 i18n 教程](docs/jvm-plugin/smart-text-to-i18n-tutorial.zh.md)** \| **[🎯 Smart Text to i18n Tutorial](docs/jvm-plugin/smart-text-to-i18n-tutorial.md)** | • **[🎯 智能文本转 i18n 教程](docs/jvm-lite-plugin/smart-text-to-i18n-tutorial.zh.md)** \| **[🎯 Smart Text to i18n Tutorial](docs/jvm-lite-plugin/smart-text-to-i18n-tutorial.md)** |
| • **[附加信息](docs/jvm-plugin/additional-information.zh.md)** \| **[Additional Information](docs/jvm-plugin/additional-information.md)** | • **[附加信息](docs/jvm-lite-plugin/additional-information.zh.md)** \| **[Additional Information](docs/jvm-lite-plugin/additional-information.md)** |
| • **[发布说明](docs/jvm-plugin/release-notes.zh.md)** \| **[Release Notes](docs/jvm-plugin/release-notes.md)** | • **[发布说明](docs/jvm-lite-plugin/release-notes.zh.md)** \| **[Release Notes](docs/jvm-lite-plugin/release-notes.md)** |

| **Web 专业版**（JSON i18n 文件） | **Web 精简版**（JSON i18n 文件 - 免费） |
|----------------------------|------------------------------|
| • **[插件描述](docs/web-plugin/description.zh.md)** \| **[Plugin Description](docs/web-plugin/description.md)** | • **[插件描述](docs/web-lite-plugin/description.zh.md)** \| **[Plugin Description](docs/web-lite-plugin/description.md)** |
| • **[用户指南](docs/web-plugin/user-guide.zh.md)** \| **[User Guide](docs/web-plugin/user-guide.md)** | • **[用户指南](docs/web-lite-plugin/user-guide.zh.md)** \| **[User Guide](docs/web-lite-plugin/user-guide.md)** |
| • **[🎯 智能文本转换教程](docs/web-plugin/smart-text-to-i18n-tutorial.zh.md)** \| **[🎯 Smart Text to i18n Tutorial](docs/web-plugin/smart-text-to-i18n-tutorial.md)** | • **[🎯 智能文本转换教程](docs/web-lite-plugin/smart-text-to-i18n-tutorial.zh.md)** \| **[🎯 Smart Text to i18n Tutorial](docs/web-lite-plugin/smart-text-to-i18n-tutorial.md)** |
| • **[附加信息](docs/web-plugin/additional-information.zh.md)** \| **[Additional Information](docs/web-plugin/additional-information.md)** | • **[附加信息](docs/web-lite-plugin/additional-information.zh.md)** \| **[Additional Information](docs/web-lite-plugin/additional-information.md)** |
| • **[发布说明](docs/web-plugin/release-notes.zh.md)** \| **[Release Notes](docs/web-plugin/release-notes.md)** | • **[发布说明](docs/web-lite-plugin/release-notes.zh.md)** \| **[Release Notes](docs/web-lite-plugin/release-notes.md)** |

### 通用文档

有关其他信息，请访问我们的 **[官方文档 Wiki](https://github.com/eastgatedev/i18n-translate-community/wiki)**。

## 🗺️ 公开路线图

想了解接下来会有什么？查看我们的 **[公开路线图](roadmap.zh.md)** | **[Public Roadmap](roadmap.md)** 以了解我们对未来平台、功能和改进的计划。

## 💬 社区和支持

有问题需要咨询、错误需要报告或新功能的想法？这里就是合适的地方！

*   **[报告错误](https://github.com/eastgatedev/i18n-translate-community/issues/new?template=bug_report.md&labels=bug)：** 通过报告您遇到的任何问题帮助我们改进。
*   **[请求功能](https://github.com/eastgatedev/i18n-translate-community/issues/new?template=feature_request.md&labels=enhancement)：** 分享您对新功能和改进的想法。
*   **[提问](https://github.com/eastgatedev/i18n-translate-community/issues/new)：** 如果有任何不清楚的地方，请不要犹豫提问。

如有许可证或其他私人咨询，请联系我们：**eastgate3194@gmail.com**。

## 📄 许可证

此仓库中的内容（文档、示例等）根据 [MIT 许可证](LICENSE) 授权。i18n Translate 插件本身是商业产品，单独授权。
