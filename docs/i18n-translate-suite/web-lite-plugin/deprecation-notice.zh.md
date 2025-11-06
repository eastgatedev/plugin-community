# Web Lite 插件弃用通知

## 重要更新

**i18n Translate Lite: Web 插件已于 2025 年 11 月弃用。**

Lite 版本将不再提供更新或错误修复。我们强烈建议迁移到新的 **i18n Translate Pro: Web** 插件，该插件现在包含一个**免费层级**，提供 Lite 版本中所有以前可用的功能。

## 为什么要做此更改？

我们已转向**免费增值模式**，提供：

- **免费层级**：所有 Lite 功能（智能文本到 i18n + 单语言翻译）免费提供
- **Pro 层级**：无限语言和高级工作流功能
- **更好的支持**：一个平台上的所有用户都能获得更新和改进
- **简化的生态系统**：一个插件而不是两个独立版本

## 这对您意味着什么

### 当前 Lite 用户

您可以继续按原样使用 Lite 插件，但：
- ❌ 不会添加新功能
- ❌ 不会提供错误修复
- ❌ 不会为未来的 IntelliJ/WebStorm 版本提供兼容性更新
- ✅ 该插件将继续在当前支持的 IDE 版本上工作

### 建议操作

**切换到 i18n Translate Pro: Web** 以享受：
- ✅ 您当前的所有 Lite 功能永久免费
- ✅ 定期更新和错误修复
- ✅ 未来 IDE 版本兼容性（IntelliJ Ultimate、WebStorm）
- ✅ 可选择升级到 Pro 层级以获得无限语言

## 迁移步骤

### 1. 安装 Pro 插件

访问 [JetBrains 市场](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web) 并安装 **i18n Translate Pro: Web**。

### 2. 卸载 Lite 插件

转到 **设置 → 插件**，找到 **i18n Translate Lite: Web** 并卸载它。

### 3. 重新配置设置

**重要**：迁移期间设置和 API 密钥将不会保留。

安装 Pro 插件后：
- 在 **设置 → 工具 → i18n Translate Pro: Web** 中重新输入您的 OpenAI/Anthropic API 密钥
- 重新配置任何自定义设置（模型选择、温度等）

### 4. 重启 IDE

重启您的 IDE（IntelliJ Ultimate 或 WebStorm）以完成迁移。

### 5. 享受免费功能

Pro 插件自动提供免费访问：
- 智能文本到 i18n 提取（完全功能）
- 使用您的 API 密钥进行完整的 LLM 翻译
- 单目标语言翻译
- 支持 Next.js、Vue i18n、Angular i18n 和通用 JSON 格式

要解锁无限语言和高级功能，您可以随时升级到 Pro 层级。

## 功能对比

| 功能 | Lite（已弃用） | Pro 免费版 | Pro 付费版 |
|---------|-------------------|----------|----------|
| 智能文本到 i18n | ✅ | ✅ | ✅ |
| LLM 翻译（您的 API 密钥） | ✅ | ✅ | ✅ |
| 目标语言 | 1 | 1 | 无限 |
| 框架支持（Next.js、Vue、Angular） | ✅ | ✅ | ✅ |
| 提交面板翻译 | ❌ | ❌ | ✅ |
| VCS 集成 | ❌ | ❌ | ✅ |
| 优先支持 | ❌ | ❌ | ✅ |
| 更新和错误修复 | ❌ | ✅ | ✅ |

## 替代访问方法

虽然提交面板翻译功能在免费层级中不可用，但您仍然可以通过以下方式访问所有核心翻译功能：

- **在项目视图中右键单击文件** → "翻译 JSON i18n 文件" 或 "翻译 Angular XLF i18n 文件"
- **工具菜单** → "i18n 翻译工具"
- 所有核心翻译功能正常工作

## 有疑问？

- **文档**：[完整文档](https://github.com/eastgatedev/plugin-community/tree/main/docs/i18n-translate-suite/web-plugin)
- **问题报告**：[报告问题](https://github.com/eastgatedev/plugin-community/issues)
- **市场**：[i18n Translate Pro: Web](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)

---

**感谢您使用 i18n Translate Lite: Web。我们期待通过新的免费增值 Pro 插件为您提供更好的服务！**
