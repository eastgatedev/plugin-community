# i18n Translate Pro: Web

> 🌐 **Language / 语言**: [🇺🇸 English](description.md) | [🇨🇳 简体中文](description.zh.md)

Revolutionize your frontend i18n workflow with **Smart Text to i18n** (Alt+Shift+]) - instantly extract hardcoded strings and convert them to framework-specific i18n calls. Plus AI-powered translation for React, Vue, Angular, and Next.js JSON files to 200+ languages.

## 🤔 When Should You Use i18n Translate Pro?

We'd rather be honest than oversell:

- **Small project (1–2 languages):** You probably don't need this plugin. A general AI assistant — Claude Code, Codex, Antigravity, or Cursor — can handle occasional translation just fine.
- **Medium-to-large project (3+ languages, hundreds of strings — think 500+ translations):** Yes. This is where batch processing and multi-language automation pay off.
- **Frequent changes / continuously updating existing translations:** Yes. VCS-aware change detection translates only what changed, saving hours of manual effort.

Try it with a **30-day Pro trial**, or use the **free tier** — translate one language file per run, and repeat for each additional language.

## 📦 Install Plugin

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/28020-i18n-translate-pro-web.svg)](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)

**[Install from JetBrains Marketplace →](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web)**

## 📺 Video Tutorial

Watch our comprehensive setup guide: [i18n Translate Web Plugin Setup Guide](https://www.youtube.com/watch?v=Uj9GH283Wdw)

## 💡 Also Available

Need to translate Java properties files? Check out our companion plugin [i18n Translate Pro: JVM](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm) for Spring Boot projects!

## 🎯 Smart Text to i18n Tutorial

**Transform hardcoded strings into framework-specific i18n code in seconds!** Master the revolutionary Alt+Shift+] feature with our comprehensive tutorial:

**[📖 Complete Smart Text to i18n Tutorial →](smart-text-to-i18n-tutorial.md)**

Learn how to turn manual string extraction from a 3-hour nightmare into a 30-second magic trick with intelligent framework detection, automatic import handling, and JSON file updates.

## Web Framework Support

- **React.js** - react-i18next, react-intl integration
- **Next.js** - next-i18next, next-intl support
- **Vue.js** - vue-i18n integration
- **Angular** - Built-in i18n support
- **Nuxt.js** - Nuxt i18n module support
- **Generic** - Any web framework using JSON i18n files

## Key Features

- **🎯 Smart Text to i18n** - Revolutionary Alt+Shift+] shortcut to extract hardcoded strings and convert to framework-specific i18n calls with intelligent automation
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

## Supported LLM Providers (120+ Models Across 8 Providers)

- **Google Gemini** - gemini-3.1-flash-lite (default), gemini-3.5-flash, gemini-2.5-pro/flash/flash-lite (free tier available)
- **OpenAI** - GPT-5.5, GPT-5.4 series, GPT-5 series (Nano/Mini/Pro), GPT-4.1, GPT-4o
- **Anthropic** - Claude Opus 4.8/4.7/4.6, Claude Sonnet 4.6, Claude Haiku 4.5
- **DeepSeek** - DeepSeek R1, deepseek-chat, deepseek-reasoner
- **Azure OpenAI** - Enterprise-grade access to all OpenAI models
- **OpenRouter** - 50+ additional models through unified API
- **Ollama** - Local inference for offline translation
- **Custom Providers** - Any OpenAI-compatible endpoint

**Smart Cost Optimization:** Intelligent legacy model detection alerts you to upgrade opportunities - save up to 99.6% on translation costs (e.g., GPT-4 → GPT-5 Nano: $40.00 → $0.17 per 1M tokens).

## Advanced Features

- **134+ LLM Models** - Latest GPT-5.5, Claude Opus 4.8, Gemini 3.5 with smart legacy detection and cost optimization alerts
- **Legacy Model Detection** - Automatic outdated model alerts with smart upgrade recommendations
- **Cost Optimization Intelligence** - Pricing comparison dashboard showing savings up to 99.6%
- Modern searchable language picker with real-time filtering
- Intelligent display names (en-US → "English (United States)")
- Framework-specific configuration templates
- Automatic project type detection via package.json analysis
- Context menu integration for JSON files
- UTF-8 encoding support with proper JSON formatting
- Batch processing with parallel language translation
- Comprehensive error collection and reporting

**Perfect for:** Frontend developers, full-stack teams, agencies working with modern web frameworks and requiring fast, accurate i18n translations!