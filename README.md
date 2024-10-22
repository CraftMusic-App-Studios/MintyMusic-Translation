# MintyMusic Translation Project

Welcome to the **MintyMusic** translation repository! MintyMusic is a Discord bot created by CraftMusic App Studios, designed to enhance your music experience. In this repository, we manage the translations of the bot into various languages. You can contribute by translating the bot's language files or improving existing translations.

## How to Contribute

1. **Fork the repository**: Click the "Fork" button at the top right of this repository to create your own copy of it.
2. **Clone your fork**: Clone your forked repository to your local machine.
3. **Edit or add translation files**: 
   - The language files are stored as `.json` files in the `langs` folder.
   - If you want to add a new language, copy the `EN.json` file and rename it to the respective language code (e.g., `FR.json` for French).
   - Translate the keys in the JSON file while maintaining the same structure.

4. **Submit a pull request**: 
   - Once you've completed your translation, commit your changes, push them to your fork, and create a pull request to the main repository.
   - Add a description to your pull request, specifying what language you translated or improved.

## JSON File Format

Each language file follows a specific structure to ensure that translations are applied correctly. Here's an example from the `EN.json` file:

```json
{
    "nodeReconnect": "Please try again! After the node reconnects.",
    "noChannel": "No voice channel to connect. Please either provide one or join one.",
    "alreadyConnected": "Already connected to a voice channel.",
    "noPermission": "Sorry! i don't have permissions to join or speak in your voice channel.",
    "noPlaySource": "Can't found any playable sources!",
}
```

Ensure that only the values (e.g., "Please try again! After the node reconnects.") are translated, and the keys (e.g., "nodeReconnect", "noChannel") remain unchanged.

## Guidelines

- Please ensure that your translations are accurate and culturally appropriate for the intended language.
- Check for spelling and grammar errors before submitting your pull request.
- Avoid using machine translations without reviewing the result thoroughly.

## Supported Languages

We aim to support as many languages as possible. Here's the current list of available languages:

- English (EN)
- German (DE)

If you want to help with translating a language not yet listed, feel free to add it!

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

Thank you for helping us make MintyMusic accessible to users all around the world!
