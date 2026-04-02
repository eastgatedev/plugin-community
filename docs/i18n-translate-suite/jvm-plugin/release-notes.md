# Release Notes - i18n Translate Pro: JVM

> 🌐 **Language / 语言**: [🇺🇸 English](release-notes.md) | [🇨🇳 简体中文](release-notes.zh.md)

## Version 2025.1.11 <small>(2026-04-02)</small>

### 🐛 Bug Fixes
- Fixed misleading translation failure messages caused by OkHttp double-reading the error body in provider error paths
- Improved response parsing to handle wrapped, fenced, or noisy LLM JSON output reliably
- Fixed VFS write-safety violations during properties file save and refresh cycles
- Fixed TransactionGuard warnings triggered by the translation progress dialog

### 🤖 New LLM Models
- **OpenAI:** Added GPT-5.4 family (gpt-5.4, gpt-5.4-mini, gpt-5.4-nano, gpt-5.4-pro)
- **Anthropic:** Added Claude 4.6 family (claude-opus-4-6, claude-sonnet-4-6)

### ⚡ Token Usage Optimization
- Added compact internal key aliasing: long source keys are converted to short IDs (e.g. a00001) before sending to the LLM and restored after parsing, reducing prompt token usage for projects with long translation keys

## Version 2025.1.10 <small>(2026-01-07)</small>

### 🌐 Plugin UI Internationalization
- **Multi-Language Support:** Plugin UI now available in Chinese Simplified, Korean, Japanese, and Indonesian
- **Automatic Detection:** Follows your IDE's language setting automatically
- **Complete Coverage:** All dialogs, messages, tooltips, and model display names are localized

### 🤖 Latest LLM Models
- **OpenAI:** Added GPT-5.2, GPT-5.2 Pro (Premium), O3 (Reasoning)
- **Anthropic:** Added Claude Opus 4.5 (Most Capable), Claude Opus 4, Claude Sonnet 4, Claude Haiku 3.5 (Most Cost-Efficient)
- **New Default:** Changed Anthropic default model to claude-haiku-3-5 for 20% cost savings

### 🐛 Bug Fixes
- Minor bug fixes and improvements

## Version 2025.1.9 <small>(2025-11-20)</small>

### 🤖 GPT-5/5.1 Complete Support
- **GPT-5.1 Model Added:** Full API compatibility with OpenAI GPT-5.1 (zero reasoning tokens - best for translation)
- **Enhanced Translation Quality:** Improved system and user prompts across ALL providers to prevent "talkativeness" and ensure concise, accurate translations
- **Reasoning Token Optimization:** Smart reasoning_effort configuration - GPT-5.1 uses "none" (0 tokens), GPT-5 uses "minimal" (~100-200 tokens)
- **API Compatibility Fixes:** Updated to use max_completion_tokens and proper temperature handling for GPT-5 series
- **Cost Optimization:** GPT-5.1 provides 60% cost savings compared to default GPT-5 settings through reasoning token elimination

### 🔧 Technical Improvements
- **Increased Token Limits:** GPT-5 series now uses 16,000 max_completion_tokens to prevent translation cutoff for large batches
- **Model-Specific Configuration:** Intelligent parameter configuration based on model capabilities
- **Hindi Translation Fix:** Resolved issue where GPT-5 consumed all output tokens for internal reasoning, leaving no space for translation

## Version 2025.1.8 <small>(2025-11-17)</small>

### 🤖 LLM Model Updates
- **21 New Models Added:** GPT-5 series (Nano/Mini), GPT-4.1 series, Claude 4.5 (Sonnet/Haiku), Claude Opus 4.1, DeepSeek R1, Phi4, and more across all 8 providers
- **120+ Total Models:** Comprehensive model coverage from Google Gemini 2.5, OpenAI GPT-5, Anthropic Claude 4.5, DeepSeek, Azure OpenAI, OpenRouter, Ollama, and Custom providers
- **Smart Cost Optimization:** New models provide better performance at lower costs - GPT-5 Nano offers best value proposition

### 💰 Legacy Model Detection
- **Automatic Outdated Model Alerts:** Plugin now detects when you're using legacy models and provides smart upgrade recommendations
- **Cost-Saving Intelligence:** Shows pricing comparisons to help save up to 99.6% on translation costs (e.g., GPT-4 → GPT-5 Nano: $40.00 → $0.17 per 1M tokens)
- **Pricing Comparison Dashboard:** View current model costs vs. recommended alternatives with detailed savings analysis
- **Version-based Dismissal:** Dialog won't show again until next plugin update with new model recommendations

### 🔍 OpenRouter Model Browser
- **300+ Models at Your Fingertips:** New dialog to browse and compare all available OpenRouter models
- **Real-time Search & Filtering:** Find models by name, provider, or capabilities with instant results
- **Pricing Intelligence:** Compare input/output token costs across different models
- **Context Window Info:** View maximum context window sizes for each model
- **Smart Recommendations:** Models sorted by popularity and value proposition

### ⚡ API Key Setup Improvements
- **Redesigned Provider Selection:** Clear comparison between free (Gemini) and premium options
- **Single-Click Setup:** Streamlined workflow with "Setup" button that defaults to recommended Gemini provider
- **Visual Provider Comparison:** Side-by-side comparison boxes showing features and benefits
- **All Providers Listed:** Complete list of 8 supported LLM providers displayed upfront

### 🐛 Bug Fixes
- **Spring Dependencies Panel:** Fixed issue where Spring Dependencies panel was not displaying in extraction dialog
- **LLM Translation Reliability:** Improved error handling and retry logic for more stable translation operations
- **Configuration Persistence:** Better handling of API key and provider settings across IDE restarts

**Professional Pricing Intelligence:** Stay ahead with automatic legacy model detection! The plugin now alerts you when using outdated models and recommends modern alternatives that can save up to 99.6% on costs while delivering better performance!

## Version 2025.1.6 <small>(2025-09-08)</small>

- **🎯 Smart Text to i18n Enhancement:** Better support for Spring Boot framework with improved string detection and code generation
- **🔄 Auto-Downgrade Feature:** Seamless transition from Pro to Lite functionality after trial expiration - no reinstallation needed
- **⚡ UI Improvements:** Enhanced user interface with better visual feedback and smoother workflows
- **🐛 Bug Fixes:** Resolved various issues for improved stability and performance
- **📝 Enhanced Code Generation:** More accurate MessageSource integration for complex string patterns
- **🚀 Framework Detection:** Improved Spring Boot configuration detection and handling

**Auto-Downgrade Revolution:** No more forced uninstalls! When your trial expires, the plugin seamlessly transitions to Lite functionality - translate one language at a time while keeping all your settings intact!

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
