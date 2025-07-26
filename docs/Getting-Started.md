# Getting Started

This guide will walk you through the initial setup and your first translation.

## 1. Installation

All i18n Translate plugins are installed directly from the JetBrains Marketplace.

1.  Open your IDE's settings (`File` > `Settings` or `IntelliJ IDEA` > `Preferences`).
2.  Navigate to the **Plugins** section.
3.  Select the **Marketplace** tab.
4.  Search for "i18n Translate Pro" and find the specific plugin for your platform (e.g., "i18n Translate Pro: JVM").
5.  Click the **Install** button and restart the IDE when prompted.

## 2. Configuring Your LLM API Key

The plugin requires an API key from a supported Large Language Model (LLM) provider to perform translations.

1.  After installation, open the IDE settings again.
2.  Navigate to **Tools** > **i18n Translate Pro**.
3.  Select your preferred LLM provider (e.g., OpenAI, Anthropic).
4.  Enter your API key in the designated field.
5.  Click **Apply** to save the configuration.

*You can acquire an API key from the respective provider's website (e.g., [OpenAI](https://platform.openai.com/api-keys), [Anthropic](https://console.anthropic.com/settings/keys)).*

## 3. Performing Your First Translation

1.  Open a project containing a resource file you want to translate (e.g., a `messages.properties` file for the JVM plugin).
2.  Right-click on the file in the Project view.
3.  From the context menu, select **Translate Properties File** (the name may vary depending on the file type).
4.  A dialog will appear. Select the target languages you want to translate to.
5.  Click the **Translate** button.

The plugin will then generate the translated files in the same directory as the source file.
