# User Guide - i18n Translate Lite: Web

> 🌐 **Language / 语言**: [🇺🇸 English](user-guide.md) | [🇨🇳 简体中文](user-guide.zh.md)

## 📦 Installation

[![JetBrains Plugin](https://img.shields.io/jetbrains/plugin/v/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)
[![Downloads](https://img.shields.io/jetbrains/plugin/d/28325-i18n-translate-lite-web.svg)](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)

**[Install from JetBrains Marketplace →](https://plugins.jetbrains.com/plugin/28325-i18n-translate-lite-web)**

This guide will help you get started with the **i18n Translate Lite: Web** plugin for IntelliJ IDEA. This plugin automatically translates JSON i18n files for modern web frameworks using LLM integration.

## 🚀 Installation

### 📺 Video Tutorial
Watch our comprehensive setup tutorial: [i18n Translate Pro: Web Plugin Setup Guide](https://www.youtube.com/watch?v=Uj9GH283Wdw)

### Step 1: Install the Plugin
1. Launch your IntelliJ IDEA and open plugin settings via `File → Settings → Plugins` (Windows/Linux) or `IntelliJ IDEA → Preferences → Plugins` (macOS)
2. Search for **"i18n Translate Lite: Web"** in the marketplace
3. Click Install and restart your IDE when prompted

### Step 2: Configure File Encoding
Ensure your project uses UTF-8 encoding for proper character support:
1. Go to `File → Settings → Editor → File Encodings`
2. Set **Global Encoding** to `UTF-8`
3. Set **Project Encoding** to `UTF-8`
4. Set **Default encoding for properties files** to `UTF-8`

## ⚙️ First-Time Setup

### Step 3: Access Translation Feature
1. Right-click on any JSON i18n file in your project (e.g., `en.json`, `common.json`)
2. Select **"Translate to Multiple Languages (Web)"** from the context menu
3. Or use the toolbar: **i18n Translate Web → Translate JSON i18n File**

### Step 4: Configure LLM Provider
On first use, you'll need to configure your LLM provider for translation services:

1. **Create OpenAI Account:** Register at [platform.openai.com](https://platform.openai.com/)
2. **Add Credit to OpenAI Account:** OpenAI requires a minimum top-up of $5 to use the API. Add credit via the billing section.
3. **Generate API Key:** Navigate to API Keys section and create a new secret key
4. **Configure in Plugin:**
   - Select **Provider:** OpenAI (recommended) or Anthropic
   - Paste your API key in the secure field
   - Choose **Model:** gpt-3.5-turbo (cost-effective) or gpt-4 (higher quality)
   - Click Verify to test your configuration
5. Click Save to store your settings securely

## 🎯 Basic Usage

### Step 5: Select Target Languages
Choose which languages you want to generate translations for:
- **Select All:** Choose all available languages (200+ supported)
- **Select None:** Clear all selections
- **Scan:** Automatically detect existing translation files in your project
- **Manage Languages:** Add or remove custom language configurations

### Step 6: Configure Basic Options
Customize translation settings via the "Project Settings" tab:
- **Base Language:** Select source language for translation context (e.g., English)
- **Overwrite existing translations:** Replace existing translations (disabled by default)
- **Sort keys alphabetically:** Organize JSON keys in alphabetical order
- **Remove duplicate keys:** Clean up duplicate entries (recommended)

### Step 7: Understanding VCS Change Detection
The plugin intelligently detects uncommitted changes in your JSON i18n files:
- **New Keys:** Automatically included for translation
- **Modified Keys:** You'll be prompted with old/new values for confirmation
- **User Choice:** Explicit control over whether to translate modified keys
- **Data Protection:** Prevents accidental overwriting of existing translations

### Step 8: Start Translation
1. Review your language selections and settings
2. Click Translate to begin the process
3. If uncommitted changes are detected, review the change summary dialog
4. Confirm which modified keys to translate (new keys are processed automatically)
5. Monitor the progress dialog showing current language and batch progress
6. Translation files will be generated in your project's framework-specific directories

### Step 9: Smart Text to i18n - Extract Hardcoded Strings

Transform hardcoded strings into framework-specific i18n code with a single keyboard shortcut!

**Revolutionary Alt+Shift+] Feature:**
1. **Open any React/Vue/Angular/Next.js file** with hardcoded strings like `"Welcome to our platform"`
2. **Position cursor** anywhere within the string literal
3. **Press Alt+Shift+]** to invoke Smart Text to i18n magic
4. **Review the preview dialog** showing:
   - Original hardcoded string
   - Generated i18n key (e.g., `welcomeToOurPlatform`)
   - Framework-specific replacement (useTranslation, $t, translate pipe)
   - Auto-added imports and translation hooks
5. **Click Apply** to automatically:
   - Add the key-value pair to your JSON translation file
   - Replace hardcoded string with framework-specific i18n call
   - Inject required imports and translation hooks
   - Update JSON files with proper structure

**Configuration:** Right click JSON file → Project Settings → Smart Text to i18n

**Learn more:** [📖 Complete Smart Text to i18n Tutorial](smart-text-to-i18n-tutorial.md)

**Pro Tips:**
- Edit generated keys in preview dialog before applying
- Works with React, Vue, Angular, Next.js auto-detection
- Preserves existing JSON structure and formatting

## 📁 Quick Framework Examples

### Common File Patterns:
- **Next.js:** `src/messages/en.json` → `src/messages/fr.json`
- **Vue.js:** `src/locales/en.json` → `src/locales/fr.json`
- **Angular:** `src/assets/i18n/en.json` → `src/assets/i18n/fr.json`
- **React:** `public/locales/en.json` → `public/locales/fr.json`

**Next Steps:** For framework-specific configurations, advanced features, troubleshooting, and detailed technical information, see our [comprehensive documentation](additional-information.md).