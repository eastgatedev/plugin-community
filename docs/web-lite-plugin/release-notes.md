# Release Notes - i18n Translate Pro: Web

> 🌐 **Language / 语言**: [🇺🇸 English](release-notes.md) | [🇨🇳 简体中文](release-notes.zh.md)

## Version 2025.1.3 <small>(2025-08-29)</small>

- **✅ Commit Panel Integration:** Right-click translate directly in commit view with seamless development workflow during commit preparation
- **🤖 LLM Provider Expansion:** Added 6 new providers (Google Gemini, DeepSeek, Azure OpenAI, Ollama, OpenRouter, Custom) - now 8 total providers with 60+ models
- **⭐ Google Gemini Default:** Gemini 2.5 Flash now recommended default with free daily usage limits - perfect for regular development
- **🚀 Professional Workflow:** Context menu available at end of commit panel for in-context translation
- **🆓 Free Usage Option:** Google Gemini provides free daily usage limits for regular development needs
- **🏢 Enterprise Compliance:** Azure OpenAI support for enterprise environments
- **💻 Local Inference:** Ollama support for offline translation capabilities

**Revolutionary LLM Integration:** Transform your translation workflow with 8 AI providers and 60+ models! Google Gemini's free daily usage makes professional translation accessible to everyone!

## Version 2025.1.2 <small>(2025-08-17)</small>

- **🎯 Smart Text to i18n Revolution:** Revolutionary new feature to extract hardcoded strings and convert them to framework-specific i18n calls with keyboard shortcut Alt+Shift+]
- **⚡ Instant Code Transformation:** Automatically detects string literals and generates React/Vue/Angular/Next.js integration with preview dialog
- **🔧 Intelligent Framework Integration:** Auto-injects useTranslation, $t, translate pipe imports when missing from components
- **📝 Developer Productivity:** Eliminate hardcoded strings instantly - select text or position cursor and press Alt+Shift+] for immediate i18n conversion
- **🚀 IntelliJ IDEA 2025.1+ Support:** Minimum required platform version upgraded to 2025.1
- **⚡ Framework Intelligence:** Auto-detects React, Vue, Angular, Next.js projects with intelligent import handling
- **🛠️ Architecture Alignment:** Package structure now matches JVM plugin for consistency

**Smart Text to i18n Revolution:** Transform your frontend i18n workflow! No more manual string extraction - just press Alt+Shift+] and watch hardcoded text become proper framework-specific i18n calls with automatic JSON file updates!

## Version 2025.1.1 <small>(2025-07-31)</small>

### New Features:
- **🔍 VCS Integration:** Smart detection of uncommitted changes with intelligent user choice for new vs modified keys
- **📋 Enhanced User Control:** Clear prompts for modified keys with old/new value preview and confirmation dialogs
- **🎯 Selective Translation:** Automatically processes new keys while giving users explicit control over modified key translations
- **🛡️ Data Protection:** Prevents accidental overwriting of existing translations without user approval
- **⚡ Workflow Optimization:** Streamlined translation process focusing only on relevant changes

### Bug Fixes:
- **🔧 Non-Existent Keys Fix:** Fixed critical bug where "Remove non-existent keys" checkbox was being ignored
- **🎯 Nested Structure Preservation:** Now properly preserves extra keys within deeply nested JSON structures
- **🔄 Recursive Merging:** Enhanced JSON merging algorithm to handle unlimited nesting levels safely
- **📊 Structure Integrity:** Extra keys maintain their proper nested hierarchy instead of becoming empty objects

**Intelligent Change Detection:** Now analyzes Git/VCS changes to translate only what matters - new keys automatically, modified keys with your permission!

**Key Preservation Fix:** Now correctly honors the "Remove non-existent keys" setting - when unchecked, extra keys from target files are preserved with their nested structure intact!

## Version 2025.1.0 <small>(2025-07-25)</small>

- **🚀 Initial Release:** Comprehensive web framework translation support for JSON i18n files
- **🌐 Multi-Framework Support:** React, Vue, Angular, Next.js, Nuxt.js automatic detection
- **📱 Smart Pattern Detection:** Automatically detects framework-specific i18n file patterns
- **🔍 Nested JSON Support:** Handles complex nested structures with intelligent flattening
- **⚡ Parallel Processing:** Processes multiple languages concurrently for faster translations
- **🎯 XLF Support:** Angular XLIFF file translation support
- **🛠️ Advanced Configuration:** Framework-specific settings and path detection
- **📊 Progress Tracking:** Real-time translation progress with detailed batch information

**Perfect for:** Frontend developers working with modern web frameworks requiring fast, accurate i18n translations!