# Additional Information - i18n Translate Pro: Web

> 🌐 **Language / 语言**: [🇺🇸 English](additional-information.md) | [🇨🇳 简体中文](additional-information.zh.md)

## 🚀 Framework Support & Detection

### 🎯 Supported Web Frameworks
- **Next.js** - Supports both next-intl and next-i18next libraries with automatic pattern detection
- **React.js** - Compatible with react-i18next, react-intl, and custom JSON i18n implementations
- **Vue.js** - Full vue-i18n support including flat and nested JSON structures
- **Angular** - Built-in i18n support with JSON and XLIFF (XLF) file translation
- **Nuxt.js** - Nuxt i18n module integration with automatic directory detection
- **Generic Web** - Any web framework using JSON i18n files with custom configurations

### 🔍 Intelligent Pattern Detection
- **Automatic Framework Detection:** Analyzes package.json dependencies to identify your framework
- **Smart Path Recognition:** Knows where each framework typically stores i18n files
- **Pattern Prioritization:** Selects optimal patterns based on project structure
- **Custom Pattern Support:** Fallback detection for non-standard configurations

### 📁 Complete File Pattern Reference
- **Next.js (next-intl):** `src/messages/{lang}.json` - Flat structure optimized for next-intl
- **Next.js (next-i18next):** `public/locales/{lang}/{namespace}.json` - Hierarchical namespace structure
- **Vue.js (flat):** `src/locales/{lang}.json` - Simple flat key-value structure
- **Vue.js (nested):** `src/locales/{lang}/{namespace}.json` - Organized by feature namespaces
- **Angular (JSON):** `src/assets/i18n/{lang}.json` - Standard Angular i18n structure
- **Angular (XLF):** `src/assets/i18n/{lang}.xlf` - XLIFF translation format
- **React (common):** `src/locales/{lang}.json`, `public/locales/{lang}.json`
- **Nuxt.js:** `locales/{lang}.json`, `static/locales/{lang}.json`
- **Generic patterns:** `src/i18n/{lang}.json`, `assets/i18n/{lang}.json`

## ⚡ Advanced Technical Features

### 🔧 Smart JSON Processing
- **Batch Processing:** Optimized batch sizes (150 keys) for efficient LLM processing
- **Parallel Language Processing:** Processes 2 languages concurrently for faster translation
- **Selective Translation:** Only processes missing keys when overwrite is disabled
- **VCS Integration:** Intelligent detection of uncommitted changes with user choice for modified keys
- **Change Analysis:** Compares before/after content to identify new and modified keys automatically
- **Key Validation:** Pre-translation validation to ensure proper property format
- **Duplicate Detection:** Advanced duplicate key detection and removal
- **Order Management:** Configurable key sorting with alphabetical or natural ordering
- **Nested JSON Flattening:** Converts complex nested structures to dot-notation for LLM processing
- **JSON Reconstruction:** Rebuilds proper nested structure from translated flat keys
- **Structure Preservation:** Maintains original JSON formatting and key ordering
- **Mixed Structure Support:** Handles combinations of flat and nested keys seamlessly

### 🚀 Performance & Optimization
- **Batch Processing:** Optimized batch sizes (100 keys) to avoid LLM token limits
- **Parallel Language Processing:** Translates multiple target languages concurrently
- **Selective Translation:** Only processes missing keys when overwrite is disabled
- **Memory Efficient:** Streams large JSON files without loading everything into memory
- **Background Processing:** Non-blocking UI with real-time progress updates
- **Automatic IDE Refresh:** Files appear immediately in project view after generation

### 🌍 Language & Locale Management
- **200+ Supported Locales:** Complete Java 17 locale support including language-country combinations
- **Intelligent Display Names:** "French (France) (fr_FR)" format for clear identification
- **Smart Search & Filtering:** Search by language name, locale code, or country
- **Automatic Detection:** Scans existing translation files to suggest target languages
- **Base Language Selection:** Choose source language for enhanced translation context
- **Custom Language Configurations:** Add specialized locales or custom language codes

### 🛡️ Reliability & Error Handling
- **Robust Error Recovery:** Continues processing other languages if one translation fails
- **Rate Limit Handling:** Automatic retry with exponential backoff (1s, 5s, 15s)
- **Comprehensive Error Collection:** Detailed error reporting with categorization
- **API Key Validation:** Real-time verification with secure storage via IntelliJ PasswordSafe
- **JSON Validation:** Pre-translation validation to catch syntax errors
- **Backup & Recovery:** Safe file operations with rollback capabilities

## 🔧 Configuration & Customization

### 📊 Advanced Translation Settings
- **Remove non-existent keys:** Automatically clean up orphaned translations that no longer exist in base files
- **Add generation comments:** Optional timestamp headers (disabled by default to prevent merge conflicts)
- **Key sorting strategies:** Alphabetical, natural ordering, or preserve original order
- **Duplicate handling:** Advanced duplicate detection and removal with configurable strategies
- **UTF-8 encoding:** Proper international character support with BOM handling
- **Pretty-printing:** Formatted JSON output with consistent indentation

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

## 🛠️ Troubleshooting & Best Practices

### 🚨 Common Issues & Solutions
- **Framework Not Detected:** Ensure package.json contains correct framework dependencies (react, vue, @angular/core, next, nuxt)
- **API Key Issues:** Verify API key validity, sufficient credits, and correct provider selection
- **File Path Problems:** Check that base JSON files are in standard framework directories
- **JSON Structure Errors:** Validate JSON syntax before translation using IDE's built-in JSON validator
- **Missing Translations:** Verify "Overwrite existing" setting and check if target keys already exist
- **XLF Translation Issues:** Ensure XLIFF files follow proper XML format and Angular XLIFF standards
- **Performance Issues:** For large files, consider breaking into smaller namespace files

### 💡 Professional Tips & Best Practices
- **Model Selection:** Use gpt-3.5-turbo for simple UI text, gpt-4 for complex content requiring nuance
- **Base Language Strategy:** Choose a well-supported language (English, Spanish, French) as source for better context
- **File Organization:** Use framework-specific patterns for better maintainability and team collaboration
- **Testing Workflow:** Start with small test files to verify LLM configuration before bulk translation
- **Project Management:** Enable "Remove duplicate keys" and "Remove non-existent keys" for cleaner codebases
- **Development Testing:** Use mock API keys for development without consuming API credits
- **Version Control:** Keep generation comments disabled to prevent unnecessary merge conflicts
- **VCS Workflow:** Use the intelligent change detection to focus translations on what actually changed
- **Change Management:** Review modified keys carefully before confirming translation to prevent data loss

### 📈 JSON Structure Examples

```json
// Flat Structure (Next.js next-intl)
{
  "homepage.title": "Welcome to our app",
  "homepage.buttons.login": "Login",
  "navigation.home": "Home"
}

// Nested Structure (Vue.js, React)
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

## 💰 Pricing & Value Proposition

### 🚀 Exceptional ROI for Heavy Users
- **Heavy User Economics:** Total annual cost ~$50-100 (plugin + API usage) vs $500+ freelancer or $1000+ developer time
- **10x+ Return on Investment:** Save thousands in manual translation costs for just hundreds in tool costs
- **Scale-friendly Pricing:** Pay only for API usage when you translate - no fixed monthly fees
- **Time Multiplication:** Translate 1000+ keys in minutes vs days of manual work
- **Quality Consistency:** Professional-grade translations with context awareness and terminology consistency

### 💡 Value Realization Examples
- **Next.js Application:** Complete i18n setup with 20+ components translated across 8 languages in 30 minutes
- **Vue.js E-commerce:** Product catalog, checkout flow, and user interface translated for global markets
- **React SaaS Platform:** Feature updates instantly available in all supported languages without development delays
- **Angular Enterprise App:** Complex nested JSON structures translated with perfect hierarchy preservation

### 🎯 Perfect for Heavy Users
- **Multi-Framework Projects:** React, Vue, Angular, Next.js applications with extensive i18n requirements
- **Frequent Feature Releases:** Continuous deployment workflows requiring rapid translation updates
- **Global Web Applications:** SaaS platforms, e-commerce sites, and enterprise portals
- **Complex JSON Structures:** Nested configurations with hundreds of translation keys

## 📞 Support & Resources

### 🆘 Getting Help
- **Technical Support:** eastgate3194@gmail.com
- **Documentation:** [GitHub Community Repository](https://github.com/eastgatedev/i18n-translate-community)
- **Feature Requests:** Submit via email with detailed use case descriptions
- **Bug Reports:** Include IDE version, plugin version, and reproduction steps

### 🔗 Related Plugins
- **Java Properties:** [i18n Translate Pro: JVM](https://plugins.jetbrains.com/plugin/27856-i18n-translate-pro-jvm) - For translating .properties files in Java projects
- **Plugin Compatibility:** Both plugins can be installed simultaneously for full-stack projects