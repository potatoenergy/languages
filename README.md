# 🌍 Multilanguage Support for LavaMusic 🎶

## 🌟 How to Add a New Language

1. 📁 Create a new file in the `locales` directory with the name of the language in the format `language_code.json`. For example, `EnglishUS.json` for English, `SpanishES.json` for Spanish, etc.
2. 📋 Copy the contents of the `EnglishUS.json` file into the new file.
3. 🌐 Translate the strings in the new file to the desired language.

### Example Translation JSON

**English (US):**
```json
{
	"ping": {
		"description": "Shows the bot latency.",
		"author": "Bot latency",
		"content": "**Shard**: `{shardPing}ms`\n**API**: `{latency}ms`",
		"footer": "• Get more information on the status channel of the support server"
	}
}
```

**German (DE):**
```json
{
	"ping": {
		"description": "Zeigt die Latenz des Bots.",
		"author": "Bot-Latenz",
		"content": "**Shard**: `{shardPing}ms`\n**API**: `{latency}ms`",
		"footer": "• Erhalte mehr Informationen im Status-Kanal des Support-Servers."
	}
}
```

### Formatting Tags for i18n NPM
To ensure `{}` are not removed during translations, use the format tags: `["{", "}"]`.
