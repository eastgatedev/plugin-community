# Release Notes - i18n Translate Pro: JVM

> 🌐 **Language / 语言**: [🇺🇸 English](release-notes.md) | [🇨🇳 简体中文](release-notes.zh.md)

## Version 2025.1.5 <small>(2025-08-29)</small>

- **✅ Commit Panel Integration:** Right-click translate directly in commit view with seamless development workflow during commit preparation
- **🤖 LLM Provider Expansion:** Added 6 new providers (Google Gemini, DeepSeek, Azure OpenAI, Ollama, OpenRouter, Custom) - now 8 total providers with 60+ models
- **⭐ Google Gemini Default:** Gemini 2.5 Flash now recommended default with free daily usage limits - perfect for regular development
- **🚀 Professional Workflow:** Context menu available at end of commit panel for in-context translation
- **🆓 Free Usage Option:** Google Gemini provides free daily usage limits for regular development needs
- **🏢 Enterprise Compliance:** Azure OpenAI support for enterprise environments
- **💻 Local Inference:** Ollama support for offline translation capabilities

**Revolutionary LLM Integration:** Transform your translation workflow with 8 AI providers and 60+ models! Google Gemini's free daily usage makes professional translation accessible to everyone!

## Version 2025.1.4 <small>(2025-08-17)</small>

- **🎯 Smart Text to i18n:** Revolutionary new feature to extract hardcoded strings and convert them to i18n method calls with keyboard shortcut Alt+Shift+]
- **⚡ Instant Code Transformation:** Automatically detects string literals and generates Spring MessageSource integration with preview dialog
- **🔧 Intelligent Code Enhancement:** Auto-injects messageSource and locale parameters when missing from methods
- **📝 Developer Productivity:** Eliminate hardcoded strings instantly - select text or position cursor and press Alt+Shift+] for immediate i18n conversion
- **🚀 IntelliJ IDEA 2025.1+ Support:** Minimum required platform version upgraded to 2025.1
- **⚡ K2 Kotlin Compiler Mode:** Full support for Kotlin's new K2 compiler with enhanced performance and stability
- **🔍 Improved Inspections:** Access to 100+ enhanced code inspections and intentions from K2 mode
- **🛠️ Platform Modernization:** Leverages latest IntelliJ platform APIs for better compatibility

**Smart Text to i18n Revolution:** Transform your i18n workflow! No more manual string extraction - just press Alt+Shift+] and watch hardcoded text become proper i18n method calls with automatic MessageSource integration!

## Version 2025.1.3 <small>(2025-07-28)</small>

- **🔍 VCS Integration:** Smart detection of uncommitted changes with intelligent user choice for new vs modified keys
- **📋 Enhanced User Control:** Clear prompts for modified keys with old/new value preview and confirmation dialogs
- **🎯 Selective Translation:** Automatically processes new keys while giving users explicit control over modified key translations
- **🛡️ Data Protection:** Prevents accidental overwriting of existing translations without user approval
- **⚡ Workflow Optimization:** Streamlined translation process focusing only on relevant changes

**Intelligent Change Detection:** Now analyzes Git/VCS changes to translate only what matters - new keys automatically, modified keys with your permission!

## Version 2025.1.2 <small>(2025-07-19)</small>

- **🚀 Performance Improvements:** Significantly faster translations with parallel language processing and optimized batch sizes
- **📱 Platform Compatibility:** Added support for IntelliJ Platform 2024.1+
- **⚡ Parallel Processing:** Now processes 2 languages concurrently instead of sequentially
- **📦 Optimized Batching:** Improved batch size (150 keys) for better balance between speed and reliability
- **🎯 Reduced Delays:** Minimized artificial delays between language chunks for faster workflow
- **📺 Video Tutorial:** Added comprehensive setup guide link in plugin description
- **🛠️ Enhanced Error Handling:** Improved robustness with better concurrent processing error management

**Performance Impact:** Users can expect 50-70% faster translation times compared to previous versions!

## Version 2025.1.1 <small>(2025-07-10)</small>

- **🚀 Initial Commercial Release:** First stable release of the professional translation plugin
- **🌍 200+ Locale Support:** Complete Java locale coverage with intelligent display names
- **🤖 Multi-LLM Support:** OpenAI and Anthropic integration with model selection
- **⚙️ Advanced Configuration:** Secure API key management and project-level settings
- **📊 Progress Tracking:** Real-time translation progress with detailed batch information
- **🛡️ Error Recovery:** Robust retry logic with exponential backoff
- **📁 File Management:** UTF-8 encoding, duplicate removal, and alphabetical sorting
- **🔧 Context Menu Integration:** Direct translation from project tree
- **📋 Professional UI:** Modern language picker with search functionality

**Foundation Release:** Establishing the core functionality for professional Java i18n translation workflows!
