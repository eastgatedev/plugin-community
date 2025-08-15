# i18n Translate Pro: Web

> 🌐 **Language / 语言**: [🇺🇸 English](description.md) | [🇨🇳 简体中文](description.zh.md)

Automatically translate JSON i18n files for web frameworks (React, Vue, Angular, Next.js) using LLM integration with comprehensive language support.

## 📦 Install Plugin

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)

**[Install from JetBrains Marketplace →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

## 💡 Also Available

Need to translate Java properties files? Check out our companion plugin [i18n Translate Pro: JVM](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm) for .properties file translation!

## Web Framework Support

- **React.js** - react-i18next, react-intl integration
- **Next.js** - next-i18next, next-intl support
- **Vue.js** - vue-i18n integration
- **Angular** - Built-in i18n support
- **Nuxt.js** - Nuxt i18n module support
- **Generic** - Any web framework using JSON i18n files

## Key Features

- **Smart File Detection** - Automatically detects JSON i18n files in common paths
- **Detecting Uncommitted Changes** - Smart VCS integration with user choice for new vs modified keys
- **Nested JSON Support** - Handles complex nested structures with dot-notation
- **Framework Detection** - Recognizes React, Vue, Angular, Next.js, Nuxt projects
- **Intelligent Path Mapping** - Knows where each framework stores i18n files
- **200+ Supported Locales** - Complete language and country code coverage
- **Secure API Management** - Safe API key storage with IntelliJ PasswordSafe
- **Base Language Selection** - Choose source language for better context
- **Overwrite Control** - Add missing keys only or overwrite existing
- **Progress Tracking** - Real-time translation progress with batch updates
- **Error Recovery** - Robust error handling with retry logic

## Supported File Structures

- **React/Next.js:** public/locales/en/common.json, locales/en.json
- **Vue/Nuxt:** locales/en.json, static/locales/en.json
- **Angular:** src/assets/i18n/en.json, assets/i18n/en.json
- **Generic:** src/locales/en.json, src/i18n/en.json

## JSON Structure Examples

```json
{
  "homepage": {
    "title": "Welcome to our app",
    "buttons": {
      "login": "Login",
      "signup": "Sign Up"
    }
  },
  "navigation": {
    "home": "Home",
    "about": "About"
  }
}
```

## Supported LLM Providers

- OpenAI (GPT-3.5-Turbo, GPT-4, GPT-4o, GPT-4-Turbo)
- Anthropic (Claude-3-Haiku, Claude-3-Sonnet, Claude-3-Opus)

## Advanced Features

- Modern searchable language picker with real-time filtering
- Intelligent display names (en-US → "English (United States)")
- Framework-specific configuration templates
- Automatic project type detection via package.json analysis
- Context menu integration for JSON files
- UTF-8 encoding support with proper JSON formatting
- Batch processing with parallel language translation
- Comprehensive error collection and reporting

**Perfect for:** Frontend developers, full-stack teams, agencies working with modern web frameworks and requiring fast, accurate i18n translations!