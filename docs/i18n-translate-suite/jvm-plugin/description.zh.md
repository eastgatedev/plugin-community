# i18n 翻译专业版：JVM

> 🌐 **Language / 语言**: [🇺🇸 English](description.md) | [🇨🇳 简体中文](description.zh.md)

通过**智能文本转 i18n**（Alt+Shift+]）革命化您的 i18n 工作流程 - 瞬间提取硬编码字符串并转换为正确的 MessageSource 调用。加上 AI 驱动的 200+ 语言翻译，全面支持 Kotlin 优先的 Java 区域设置。

## 📦 安装插件

[![JetBrains 插件](https://img.shields.io/jetbrains/plugin/v/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)
[![下载量](https://img.shields.io/jetbrains/plugin/d/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)

**[从 JetBrains 市场安装 →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**

## 📺 视频教程

观看我们的全面设置指南：[i18n 翻译插件设置指南](https://youtu.be/eUKpTmiWATU)

## 💡 相关产品

需要翻译 Web 框架的 JSON i18n 文件？请查看我们的配套插件 [i18n 翻译专业版：Web](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)，支持 React、Vue、Angular 和 Next.js！

## 🎯 智能文本转 i18n 教程

**在几秒钟内将硬编码字符串转换为专业的 i18n 代码！** 通过我们的综合教程掌握革命性的 Alt+Shift+] 功能：

**[📖 完整智能文本转 i18n 教程 →](smart-text-to-i18n-tutorial.zh.md)**

学习如何通过智能自动化、构造函数注入和区域设置处理，将手动字符串提取从 3 小时噩梦变成 30 秒魔法技巧。

## 主要功能

- **🎯 智能文本转 i18n** - 革命性的 Alt+Shift+] 快捷键，提取硬编码字符串并转换为 MessageSource 调用，具有智能自动化
- **支持 200+ Java 区域设置** - 全面覆盖所有 Java 区域设置，具有智能显示名称
- **检测未提交的更改** - 智能 VCS 集成，用户可选择新增或修改的键
- **可搜索的语言选择器** - 现代化 UI，可实时搜索语言名称、代码和国家
- **高级 LLM 配置** - 安全的 API 密钥管理，支持可见性切换、剪贴板集成和实时验证
- **智能区域设置检测** - 自动识别现有翻译文件（ms、MY、ms_MY 格式）
- **智能翻译选项** - 覆盖现有内容或仅添加缺失内容，保持文件命名
- **基础语言选择** - 选择源语言以获得更好的翻译上下文
- **项目级设置** - 每个项目的语言配置
- **高级文件处理** - 字母排序、重复键移除和顺序保持
- **速率限制和重试逻辑** - 3 次重试，指数退避（5 秒、15 秒、30 秒）实现稳健的 API 处理
- 具有实时批处理更新的高级进度跟踪
- 对所有生成文件的 UTF-8 编码支持
- 属性文件的上下文菜单集成

## 全面的区域设置支持

- **45+ 语言代码：** en、fr、de、ja、zh、ar、ms、hi、ko 等
- **60+ 国家代码：** US、GB、DE、FR、MY、CN、JP 等
- **100+ 语言-国家组合：** en_US、fr_FR、ms_MY、zh_CN 等
- **特殊区域设置：** ja_JP_u_ca_japanese、sr_Latn_BA 等

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
- 具有选项卡界面和基础语言选择的增强翻译对话框
- 全面的错误处理，具有详细的错误收集和摘要报告
- 团队友好操作，可选注释标头（默认禁用）
- 智能属性过滤 - 当禁用覆盖时仅翻译缺失的键
- 文件清理操作 - 移除不存在的键，自动处理重复项
- 项目级语言管理 - 独立的每个项目语言配置
- 批处理进度跟踪 - 具有批处理级信息的详细进度

## 常用语言示例

英语（en、en_US、en_GB）、中文（zh、zh_CN、zh_TW）、法语（fr、fr_FR、fr_CA）、阿拉伯语（ar、ar_SA、ar_EG）、马来语（ms、ms_MY、MY）等等！