# 🌍 Onex Scripts — Community Translations

Community-contributed translations for all [Onex Scripts](https://onex-scripts.tebex.io) FiveM resources.
Since our scripts are encrypted for protection, this repo allows the community to contribute and maintain localization files that are automatically bundled into every release.

---

## 📁 Structure
```
{script-name}/
├── en.json   ← base language (do not edit)
├── tr.json
├── de.json
└── ...
```
---

## 🤝 How to Contribute

> ⚠️ Before contributing, you **MUST** read our guidelines: **[https://onexscripts.com/documentation/translations](https://onexscripts.com/documentation/translations)**

1. **Fork** this repository
2. Navigate to the script you want to translate
3. Copy `en.json` and rename it to your language code (e.g. `fr.json`, `ar.json`, `pl.json`)
4. Translate the values — **do not change the keys**
5. Open a **Pull Request** with the title format: `[script-name] Add {Language} translation`

> Use [ISO 639-1](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) language codes for file names.

---

## ✅ Translation Guidelines

- Only translate the **values**, never the keys
- Keep placeholders like `%s`, `{player}`, `{amount}` exactly as they are
- Match the tone — our scripts use short, clean UI text

---

## 📜 License

Translation files are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).
The scripts themselves remain proprietary and encrypted — only the locale files are open for contribution.

---

<p align="center">Made with ❤️ by <a href="https://github.com/OnexScripts">Onex Scripts</a></p>
