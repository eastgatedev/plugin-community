# Additional Information - i18n Translate Pro: JVM

> 🌐 **Language / 语言**: [🇺🇸 English](additional-information.md) | [🇨🇳 简体中文](additional-information.zh.md)

## 🚀 Java Properties File Translation

### 🎯 Properties File Support
- **Standard Properties:** Classic Java `.properties` files with key=value format
- **Resource Bundles:** Complete support for Java ResourceBundle conventions
- **UTF-8 Encoding:** Full Unicode character support for international text
- **Comment Preservation:** Maintains comments and file structure during translation
- **File Naming Conventions:** Generates standard locale-specific filenames (`messages_fr.properties`)
- **Key Order Preservation:** Maintains original key ordering or applies alphabetical sorting

### 📁 File Structure Examples
```properties
# Base file: messages.properties
welcome.title=Welcome to our application
user.login.button=Login
user.logout.button=Logout
navigation.home=Home

# Generated: messages_fr.properties
welcome.title=Bienvenue dans notre application
user.login.button=Connexion
user.logout.button=Déconnexion
navigation.home=Accueil
```

## ⚡ Advanced Technical Features

### 🔧 Smart Properties Processing
- **Batch Processing:** Optimized batch sizes (150 keys) for efficient LLM processing
- **Parallel Language Processing:** Processes 2 languages concurrently for faster translation
- **Selective Translation:** Only processes missing keys when overwrite is disabled
- **VCS Integration:** Intelligent detection of uncommitted changes with user choice for modified keys
- **Change Analysis:** Compares before/after content to identify new and modified keys automatically
- **Key Validation:** Pre-translation validation to ensure proper property format
- **Duplicate Detection:** Advanced duplicate key detection and removal
- **Order Management:** Configurable key sorting with alphabetical or natural ordering

### 🚀 Performance & Optimization
- **Memory Efficient:** Streams large property files without loading everything into memory
- **Background Processing:** Non-blocking UI with real-time progress updates
- **File System Integration:** Automatic IDE refresh and project tree updates
- **Reduced Processing Delays:** Minimized delays between batches for faster workflow
- **Concurrent Language Processing:** 50-70% faster translation times compared to sequential processing
- **Resource Cleanup:** Automatic cleanup of temporary files and memory

### 🌍 Comprehensive Java Locale Support
- **200+ Java Locales:** Complete coverage of all Java 17 supported locales
- **Language Codes:** 45+ languages (en, fr, de, ja, zh, ar, ms, hi, ko, etc.)
- **Country Codes:** 60+ countries (US, GB, DE, FR, MY, CN, JP, etc.)
- **Language-Country Combinations:** 100+ combinations (en_US, fr_FR, ms_MY, zh_CN, etc.)
- **Special Locales:** Advanced locales like ja_JP_u_ca_japanese, sr_Latn_BA
- **Intelligent Display Names:** "Malay (Malaysia) (ms_MY)" format for clear identification
- **Smart Search & Filtering:** Search by language name, locale code, or country

### 🛡️ Reliability & Error Handling
- **Robust Error Recovery:** Continues processing other languages if one translation fails
- **Rate Limit Handling:** Automatic retry with exponential backoff (5s, 15s, 30s)
- **Comprehensive Error Collection:** Detailed error reporting with categorization
- **API Key Validation:** Real-time verification with secure storage via IntelliJ PasswordSafe
- **Properties Validation:** Pre-translation validation to catch syntax errors
- **Backup & Recovery:** Safe file operations with rollback capabilities

## 🔧 Configuration & Customization

### 📊 Advanced Translation Settings
- **Base Language Selection:** Choose source language for enhanced translation context
- **Remove non-existent keys:** Automatically clean up orphaned translations
- **Add generation comments:** Optional timestamp headers (disabled by default to prevent merge conflicts)
- **Key sorting strategies:** Alphabetical, natural ordering, or preserve original order
- **Duplicate handling:** Advanced duplicate detection and removal with configurable strategies
- **UTF-8 encoding:** Proper international character support with BOM handling
- **Comment preservation:** Maintains existing comments during translation

### 🤖 LLM Provider Configuration (8 Providers, 60+ Models)
- **Google Gemini (⭐ Recommended):** gemini-2.5-pro, gemini-2.5-flash (default), gemini-2.5-flash-lite with free daily usage limits - perfect for regular development
- **OpenAI Models:** GPT-4o, GPT-4o-mini, GPT-4-Turbo, GPT-4, GPT-3.5-Turbo, o1, o1-mini
- **Anthropic Models:** Claude-3.5-Sonnet, Claude-3.5-Haiku, Claude-3-Opus, Claude-3-Sonnet, Claude-3-Haiku
- **DeepSeek Models:** deepseek-chat, deepseek-reasoner
- **Azure OpenAI:** Enterprise compliance with all OpenAI models through Azure infrastructure
- **Ollama (Local):** Local inference with llama3.2, mistral, codellama for offline translation
- **OpenRouter:** Access to 50+ additional models through unified API
- **Custom Provider:** Any OpenAI-compatible endpoint for specialized setups
- **API Key Management:** Secure storage with visibility toggle and clipboard integration
- **Real-time Verification:** Test API connectivity and model access before translation
- **Rate Limiting Awareness:** Intelligent handling of provider-specific limits
- **Free Usage Option:** Google Gemini provides free daily usage, making professional translation accessible

### 🎯 Project-Level Management
- **Per-Project Configuration:** Isolated language settings for each project
- **Language Detection:** Automatic scanning of existing translation files
- **Custom Language Management:** Add specialized locales or custom language codes
- **Settings Inheritance:** Global settings with project-specific overrides
- **Team Collaboration:** Shared configuration files for consistent team workflows

## 🛠️ Troubleshooting & Best Practices

### 🚨 Common Issues & Solutions
- **API Key Issues:** Verify API key validity, sufficient credits, and correct provider selection
- **Encoding Problems:** Ensure UTF-8 encoding is set for project and properties files
- **File Path Issues:** Check that base properties files are accessible and properly formatted
- **Missing Translations:** Verify "Overwrite existing" setting and check if target keys already exist
- **Rate Limit Errors:** Plugin automatically handles rate limiting, but verify API account status
- **Properties Format Errors:** Validate properties file syntax before translation
- **Performance Issues:** For very large files (1000+ keys), consider breaking into smaller modules

### 💡 Professional Tips & Best Practices
- **Model Selection:** Use gpt-3.5-turbo for simple UI text, gpt-4 for complex content requiring nuance
- **Base Language Strategy:** Choose a well-supported language (English, Spanish, French) as source for better context
- **File Organization:** Use modular properties files for better maintainability (messages.properties, labels.properties, errors.properties)
- **Testing Workflow:** Start with small test files to verify LLM configuration before bulk translation
- **Project Management:** Enable "Remove duplicate keys" and "Remove non-existent keys" for cleaner codebases
- **Development Testing:** Use mock API keys for development without consuming API credits
- **Version Control:** Keep generation comments disabled to prevent unnecessary merge conflicts
- **VCS Workflow:** Use the intelligent change detection to focus translations on what actually changed
- **Change Management:** Review modified keys carefully before confirming translation to prevent data loss
- **Resource Bundle Naming:** Follow Java conventions: messages.properties, messages_fr.properties, messages_es.properties

### 📈 Locale Examples & Patterns
```properties
# Language-only codes
en → English
fr → French
de → German
ja → Japanese
zh → Chinese

# Country-specific variants
en_US → English (United States)
en_GB → English (United Kingdom)
fr_FR → French (France)
fr_CA → French (Canada)

# Regional variants
zh_CN → Chinese (China) - Simplified
zh_TW → Chinese (Taiwan) - Traditional
pt_BR → Portuguese (Brazil)
pt_PT → Portuguese (Portugal)
```

## 💰 Pricing & Value Proposition

### 🚀 Exceptional ROI for Heavy Users
- **Heavy User Economics:** Total annual cost ~$50-100 (plugin + API usage) vs $500+ freelancer or $1000+ developer time
- **10x+ Return on Investment:** Save thousands in manual translation costs for just hundreds in tool costs
- **Scale-friendly Pricing:** Pay only for API usage when you translate - no fixed monthly fees
- **Time Multiplication:** Translate 1000+ keys in minutes vs days of manual work
- **Quality Consistency:** Professional-grade translations with context awareness and terminology consistency

### 💡 Value Realization Examples
- **Enterprise Application:** 2000 keys × 10 languages = 18,000 translations in 2 hours vs 2 weeks manual work
- **SaaS Platform:** Monthly feature updates translated instantly across all supported languages
- **E-commerce Site:** Product catalogs and UI elements translated with cultural context and consistency
- **Multi-tenant Applications:** Customer-specific localizations managed efficiently at scale

### 🎯 Perfect for Heavy Users
- **Large Internationalization Projects:** 10+ languages with complex property structures
- **Frequent Updates:** Regular feature releases requiring translation updates
- **Enterprise Applications:** Mission-critical software with quality translation requirements
- **Global SaaS Products:** Multi-language support as a core business requirement

## 📞 Support & Resources

### 🆘 Getting Help
- **Technical Support:** eastgate3194@gmail.com
- **Documentation:** [GitHub Community Repository](https://github.com/eastgatedev/i18n-translate-community)
- **Video Tutorial:** [Setup Guide on YouTube](https://youtu.be/eUKpTmiWATU)
- **Feature Requests:** Submit via email with detailed use case descriptions
- **Bug Reports:** Include IDE version, plugin version, and reproduction steps

### 🔗 Related Plugins
- **Web JSON Files:** [i18n Translate Pro: Web](https://plugins.jetbrains.com/plugin/28020-i18n-translate-pro-web) - For translating JSON i18n files in web projects
- **Plugin Compatibility:** Both plugins can be installed simultaneously for full-stack Java/web projects

### 🎯 Performance Metrics
- **Translation Speed:** 50-70% faster than previous versions with parallel processing
- **Memory Usage:** Optimized for large files with streaming processing
- **Batch Size:** 150 keys per batch for optimal speed/reliability balance
- **Concurrent Languages:** 2 languages processed simultaneously
- **Error Recovery:** 3-attempt retry with exponential backoff