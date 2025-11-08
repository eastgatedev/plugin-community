# 用户指南 - i18n 翻译专业版：JVM

> 🌐 **Language / 语言**: [🇺🇸 English](user-guide.md) | [🇨🇳 简体中文](user-guide.zh.md)

## 📦 安装

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)

**[从 JetBrains 市场安装 →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**

本指南将帮助您开始使用适用于 IntelliJ IDEA 的 **i18n 翻译专业版：JVM** 插件。此插件使用 LLM 集成自动将 Java 属性文件翻译成多种语言。

## 🚀 安装

### 📺 视频教程
观看我们的全面设置教程：[i18n 翻译专业版：JVM 插件设置指南](https://youtu.be/eUKpTmiWATU)

### 步骤 1：安装插件
1. 启动您的 IntelliJ IDEA，通过 `文件 → 设置 → 插件`（Windows/Linux）或 `IntelliJ IDEA → 首选项 → 插件`（macOS）打开插件设置
2. 在市场中搜索 **"i18n Translate Pro: JVM"**
3. 点击安装，提示时重新启动您的 IDE

### 步骤 2：配置文件编码
确保您的项目使用 UTF-8 编码以获得正确的字符支持：
1. 转到 `文件 → 设置 → 编辑器 → 文件编码`
2. 将 **全局编码** 设置为 `UTF-8`
3. 将 **项目编码** 设置为 `UTF-8`
4. 将 **属性文件的默认编码** 设置为 `UTF-8`

## ⚙️ 首次设置

### 步骤 3：访问翻译功能
1. 在项目树中右键单击任何 `.properties` 文件
2. 从上下文菜单中选择 **"翻译为多种语言"**
3. 或使用工具栏：**i18n 翻译 → 翻译属性文件**

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

**💡 智能成本优化提示：**
- **推荐 GPT-5 Nano：** 最佳性价比，每百万 token $0.17 - 比 GPT-4 便宜 99.6%
- **免费层选项：** Google Gemini 为开发提供免费每日使用限制
- **旧模型警报：** 插件自动检测过时模型并建议升级
- **价格仪表板：** 访问 **设置 → i18n Translate Pro: JVM → LLM 配置** 来比较模型成本
- **120+ 模型可用：** 探索 8 个提供商，找到成本和质量的完美平衡

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
- **按字母顺序排序键：** 按字母顺序组织属性
- **删除重复键：** 清理重复条目（推荐）

### 步骤 7：了解 VCS 变更检测
插件智能检测您的属性文件中未提交的更改：
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
6. 翻译文件将生成为 `filename_locale.properties`

### 步骤 9：智能文本转 i18n - 提取硬编码字符串

通过单个键盘快捷键将硬编码字符串转换为正确的 i18n 代码！

**革命性的 Alt+Shift+] 功能：**
1. **打开任何 Kotlin/Java 文件**，其中包含硬编码字符串，如 `"用户创建成功"`
2. **将光标定位**在字符串字面量内的任意位置
3. **按 Alt+Shift+]** 调用智能文本转 i18n 魔法
4. **查看预览对话框**显示：
   - 原始硬编码字符串
   - 生成的 i18n 键（例如，`userCreatedSuccessfully`）
   - 使用 `messageSource.getMessage()` 调用的转换代码
   - 自动添加的导入、构造函数注入和区域设置处理
5. **点击应用**自动：
   - 将键值对添加到您的属性文件
   - 用正确的 i18n 调用替换硬编码字符串
   - 注入 MessageSource 和 Locale 参数
   - 自动添加所需的导入

**了解更多：** [📖 完整智能文本转 i18n 教程](smart-text-to-i18n-tutorial.zh.md)

**专业技巧：**
- 在预览对话框中编辑生成的键然后再应用
- 支持 Spring Boot 依赖注入模式
- 保持现有代码结构和格式

## 📁 快速示例

### 文件生成示例：
- **基础文件：** `messages.properties` → `messages_fr.properties`
- **基础文件：** `labels.properties` → `labels_es.properties`
- **基础文件：** `app.properties` → `app_zh_CN.properties`

**下一步：** 有关高级区域设置配置、批处理选项、故障排除和详细技术信息，请参阅我们的[综合文档](additional-information.zh.md)。