# Ganita Bingya App Translations

Welcome to the official translation repository for the **Ganita Bingya** mobile application. This repository manages all the string resources (`strings.xml`) used within the app.

## Languages

This project maintains multiple language files to provide a localized experience for our users.

*   **Default Language:** **Odia (or)** is the primary and source language for all translations.
*   **Secondary Language:** **English (en)** is the first supported translation.

### Available Languages

| Language | ISO Code | Status      | Folder          |
| :------- | :------- | :---------- | :-------------- |
| Odia     | `or`     | ✅ Default  | `values-or/`    |
| English  | `en`     | ✅ Complete | `values-en/`    |

---

## How to Contribute

We welcome contributions from everyone! If you want to add a new language or improve an existing one, please follow these steps.

### Add or Update a Translation

1.  **Fork** this repository.
2.  To add a new language, create a new folder named `values-xx` where `xx` is the [ISO 639-1 language code](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) (e.g., `values-hi` for Hindi).
3.  **Copy** the base file from `values-or/strings.xml` into your new folder.
4.  Translate the text values from Odia into the new language.
5.  To update an existing language, simply edit the `strings.xml` file in its corresponding folder.
6.  Create a **Pull Request** with your changes.

For a more detailed guide, please read our [**CONTRIBUTING.md**](CONTRIBUTING.md) file.

### Request a New Language

If you want to see the app in a new language but cannot contribute a translation yourself, you can request it!

➡️ **[Click here to request a new language translation](https://github.com/YOUR_USERNAME/ganita-bingya-app-translations/issues/new?assignees=&labels=translation%2Cenhancement&template=request-new-translation.md&title=%5BLang+Request%5D%3A+)**

Please use the issue template to provide the language name and its ISO code.

---

## Future Plans

We are exploring automation tools like [Weblate](https://weblate.org/) or [Tolgee](https://tolgee.io/) to streamline the translation process in the future. This will make it even easier for contributors to manage translations through a web interface. Stay tuned!
