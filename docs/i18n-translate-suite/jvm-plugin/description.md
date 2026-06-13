# i18n Translate Pro: JVM

> 🌐 **Language / 语言**: [🇺🇸 English](description.md) | [🇨🇳 简体中文](description.zh.md)

Revolutionize your i18n workflow with **Smart Text to i18n** (Alt+Shift+]) - instantly extract hardcoded strings and convert them to proper MessageSource calls. Plus AI-powered translation to 200+ languages with comprehensive Kotlin-first Java locale support.

## 🤔 When Should You Use i18n Translate Pro?

We'd rather be honest than oversell:

- **Small project (1–2 languages):** You probably don't need this plugin. A general AI assistant — Claude Code, Codex, Antigravity, or Cursor — can handle occasional translation just fine.
- **Medium-to-large project (3+ languages, hundreds of strings — think 500+ translations):** Yes. This is where batch processing and multi-language automation pay off.
- **Frequent changes / continuously updating existing translations:** Yes. VCS-aware change detection translates only what changed, saving hours of manual effort.

Try it with a **30-day Pro trial**, or use the **free tier** — translate one language file per run, and repeat for each additional language.

## 📦 Install Plugin

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/27856-i18n-translate-pro-jvm.svg)](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)

**[Install from JetBrains Marketplace →](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm)**

## 📺 Video Tutorial

Watch our comprehensive setup guide: [i18n Translate Plugin Setup Guide](https://youtu.be/eUKpTmiWATU)

## 💡 Also Available

Need to translate JSON i18n files for web frameworks? Check out our companion plugin [i18n Translate Pro: Web](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web) for React, Vue, Angular, and Next.js support!

## 🎯 Smart Text to i18n Tutorial

**Transform hardcoded strings into professional i18n code in seconds!** Master the revolutionary Alt+Shift+] feature with our comprehensive tutorial:

**[📖 Complete Smart Text to i18n Tutorial →](smart-text-to-i18n-tutorial.md)**

Learn how to turn manual string extraction from a 3-hour nightmare into a 30-second magic trick with intelligent automation, constructor injection, and locale handling.

## Key Features

- **🎯 Smart Text to i18n** - Revolutionary Alt+Shift+] shortcut to extract hardcoded strings and convert to MessageSource calls with intelligent automation
- **200+ Java Supported Locales** - Complete coverage of all Java locales with intelligent display names
- **Detecting Uncommitted Changes** - Smart VCS integration with user choice for new vs modified keys
- **Searchable Language Picker** - Modern UI with real-time search across language names, codes, and countries
- **Advanced LLM Configuration** - Secure API key management with visibility toggle, clipboard integration, and real-time validation
- **Intelligent Locale Detection** - Auto-recognizes existing translation files (ms, MY, ms_MY formats)
- **Smart Translation Options** - Overwrite existing or add missing only, with file naming preservation
- **Base Language Selection** - Choose source language for better translation context
- **Project-Level Settings** - Per-project language configuration
- **Advanced File Processing** - Alphabetical sorting, duplicate key removal, and order preservation
- **Rate Limiting & Retry Logic** - 3-attempt retry with exponential backoff (5s, 15s, 30s) for robust API handling
- Advanced progress tracking with real-time batch updates
- UTF-8 encoding support for all generated files
- Context menu integration for properties files

## Comprehensive Locale Support

- **45+ Language codes:** en, fr, de, ja, zh, ar, ms, hi, ko, etc.
- **60+ Country codes:** US, GB, DE, FR, MY, CN, JP, etc.
- **100+ Language-Country combinations:** en_US, fr_FR, ms_MY, zh_CN, etc.
- **Special locales:** ja_JP_u_ca_japanese, sr_Latn_BA, etc.

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
- Enhanced Translation Dialog with tabbed interface and base language selection
- Comprehensive error handling with detailed error collection and summary reporting
- Team-friendly operation with optional comment headers (disabled by default)
- Smart Property Filtering - only translates missing keys when overwrite is disabled
- File Cleanup Operations - remove non-existent keys, handle duplicates automatically
- Project-Level Language Management - isolated per-project language configuration
- Batch Progress Tracking - detailed progress with batch-level information

## Popular Language Examples

English (en, en_US, en_GB), Chinese (zh, zh_CN, zh_TW), French (fr, fr_FR, fr_CA), Arabic (ar, ar_SA, ar_EG), Malay (ms, ms_MY, MY), and many more!