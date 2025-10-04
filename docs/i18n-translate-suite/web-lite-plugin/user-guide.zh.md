# 用户指南 - i18n 翻译精简版：Web

> 🌐 **Language / 语言**: [🇺🇸 English](user-guide.md) | [🇨🇳 简体中文](user-guide.zh.md)

## 📦 安装

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)

**[从 JetBrains 市场安装 →](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)**

本指南将帮助您开始使用适用于 IntelliJ IDEA 的 **i18n 翻译精简版：Web** 插件。此插件使用 LLM 集成自动翻译现代 Web 框架的 JSON i18n 文件。

## 🚀 安装

### 📺 视频教程
观看我们的全面设置教程：[i18n 翻译专业版：Web 插件设置指南](https://www.youtube.com/watch?v=Uj9GH283Wdw)

### 步骤 1：安装插件
1. 启动您的 IntelliJ IDEA，通过 `文件 → 设置 → 插件`（Windows/Linux）或 `IntelliJ IDEA → 首选项 → 插件`（macOS）打开插件设置
2. 在市场中搜索 **"i18n Translate Lite: Web"**
3. 点击安装，提示时重新启动您的 IDE

### 步骤 2：配置文件编码
确保您的项目使用 UTF-8 编码以获得正确的字符支持：
1. 转到 `文件 → 设置 → 编辑器 → 文件编码`
2. 将 **全局编码** 设置为 `UTF-8`
3. 将 **项目编码** 设置为 `UTF-8`
4. 将 **属性文件的默认编码** 设置为 `UTF-8`

## ⚙️ 首次设置

### 步骤 3：访问翻译功能
1. 在项目中右键单击任何 JSON i18n 文件（例如，`en.json`、`common.json`）
2. 从上下文菜单中选择 **"翻译为多种语言 (Web)"**
3. 或使用工具栏：**i18n 翻译 Web → 翻译 JSON i18n 文件**

### 步骤 4：配置 LLM 提供商
首次使用时，您需要配置 LLM 提供商以获取翻译服务：

1. **创建 OpenAI 账户：** 在 [platform.openai.com](https://platform.openai.com/) 注册
2. **向 OpenAI 账户添加信用：** OpenAI 需要最少充值 5 美元才能使用 API。通过计费部分添加信用。
3. **生成 API 密钥：** 导航到 API 密钥部分并创建新的密钥
4. **在插件中配置：**
   - 选择 **提供商：** OpenAI（推荐）或 Anthropic
   - 在安全字段中粘贴您的 API 密钥
   - 选择 **模型：** gpt-3.5-turbo（经济实惠）或 gpt-4（更高质量）
   - 点击验证来测试您的配置
5. 点击保存以安全存储您的设置

## 🎯 基本用法

### 步骤 5：选择目标语言
选择您要生成翻译的语言：
- **全选：** 选择所有可用语言（支持 200+ 种）
- **全不选：** 清除所有选择
- **扫描：** 自动检测项目中现有的翻译文件
- **管理语言：** 添加或删除自定义语言配置

### 步骤 6：配置基本选项
通过"项目设置"标签自定义翻译设置：
- **基础语言：** 选择翻译上下文的源语言（例如，英语）
- **覆盖现有翻译：** 替换现有翻译（默认禁用）
- **按字母顺序排序键：** 按字母顺序组织 JSON 键
- **删除重复键：** 清理重复条目（推荐）

### 步骤 7：了解 VCS 变更检测
插件智能检测您的 JSON i18n 文件中未提交的更改：
- **新键：** 自动包含在翻译中
- **修改的键：** 系统会提示您新旧值以进行确认
- **用户选择：** 对是否翻译修改的键的明确控制
- **数据保护：** 防止意外覆盖现有翻译

### 步骤 8：开始翻译
1. 查看您的语言选择和设置
2. 点击翻译开始流程
3. 如果检测到未提交的更改，请查看更改摘要对话框
4. 确认要翻译哪些修改的键（新键会自动处理）
5. 监控显示当前语言和批处理进度的进度对话框
6. 翻译文件将在您项目的框架特定目录中生成

### 步骤 9：智能文本转 i18n - 提取硬编码字符串

通过单个键盘快捷键将硬编码字符串转换为框架特定的 i18n 代码！

**革命性的 Alt+Shift+] 功能：**
1. **打开任何 React/Vue/Angular/Next.js 文件**，其中包含硬编码字符串，如 `"欢迎来到我们的平台"`
2. **将光标定位**在字符串字面量内的任意位置
3. **按 Alt+Shift+]** 调用智能文本转 i18n 魔法
4. **查看预览对话框**显示：
   - 原始硬编码字符串
   - 生成的 i18n 键（例如，`welcomeToOurPlatform`）
   - 框架特定的替换（useTranslation、$t、translate 管道）
   - 自动添加的导入和翻译钩子
5. **点击应用**自动：
   - 将键值对添加到您的 JSON 翻译文件
   - 用框架特定的 i18n 调用替换硬编码字符串
   - 注入所需的导入和翻译钩子
   - 使用正确的结构更新 JSON 文件

**配置：** 右键点击 JSON 文件 → 项目设置 → 智能文本转 i18n

**了解更多：** [📖 完整智能文本转 i18n 教程](smart-text-to-i18n-tutorial.zh.md)

**专业技巧：**
- 在预览对话框中编辑生成的键然后再应用
- 支持 React、Vue、Angular、Next.js 自动检测
- 保持现有 JSON 结构和格式

## 📁 快速框架示例

### 常见文件模式：
- **Next.js：** `src/messages/en.json` → `src/messages/fr.json`
- **Vue.js：** `src/locales/en.json` → `src/locales/fr.json`
- **Angular：** `src/assets/i18n/en.json` → `src/assets/i18n/fr.json`
- **React：** `public/locales/en.json` → `public/locales/fr.json`

**下一步：** 有关框架特定配置、高级功能、故障排除和详细技术信息，请参阅我们的[综合文档](additional-information.zh.md)。