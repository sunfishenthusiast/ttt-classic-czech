# TTT Classic Localizations

This repository contains the localization files for **[TTT Classic](https://store.steampowered.com/app/4570530/TTT_Classic/)**. 

We welcome contributions from anyone! If you would like to correct existing translations or add support for a new language, please feel free to submit a pull request.

---

## File Structure & Descriptions

Currently, the primary language files are housed inside language-specific directories (such as the `/en` folder for English). Here is what each file/folder corresponds to:

*   **`quickchat/`** – Contains audio files that play when quickchat is used. These correspond directly with the translation keys starting with `TTT_QUICK_`.
*   **`4570530_loc_<language>.vdf`** – Steam Achievement localizations.
*   **`gameui_<language>.txt`** – Stock Half-Life Game UI strings.
*   **`serverbrowser_<language>.txt`** – Stock Half-Life Server Browser strings.
*   **`valve_<language>.txt`** – Stock Half-Life engine/game strings.
*   **`ttt_<language>.txt`** – TTT Classic-specific gameplay and UI strings.
*   **`storepage.json`** – The text used for the Steam Store page listing (located in the root directory).

---

## How to Contribute

We support editing existing language translations or proposing new ones.

### Modifying Existing Translations
1. Locate the language folder you want to edit (e.g., `/en`).
2. Make your corrections/updates to the relevant translation file.
3. Submit a pull request with a brief explanation of the changes.

### Proposing a New Language
If you want to add a language not yet present:
1. Refer to the list of supported Steam languages: [Steam Localization Languages](https://partner.steamgames.com/doc/store/localization/languages).
2. Note the type of language support needed:
    *   **Full Platform** languages should provide localizations for achievements (`4570530_loc_<language>.vdf`) and `storepage.json`.
    *   **Game Support** languages are used for all other files (`quickchat/`, `gameui_`, `serverbrowser_`, `valve_`, and `ttt_`).
3. Copy the English files as a baseline, rename them matching your language's suffix (e.g., `_german` or `_spanish`), translate the text, and submit your pull request!
