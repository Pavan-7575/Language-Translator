# Language Translator

A simple client‑side web application that translates text between languages using the MyMemory API.

## Files

- `Translate.html` – main page, includes the structure and links to CSS/JS.
- `Translate.css` – styling for layout, responsive behaviour, and colors.
- `Translate.js` – handles populating language selectors, translation requests, swapping languages, and copy/speak controls.

> Note: the current working copy has these files under a `CODE/` subfolder; update paths if you move them.

## Features

- Select a source and target language from dropdowns.
- Enter text and click *Translate it* to get results from the API.
- Swap languages with the exchange icon.
- Copy the input or output text to the clipboard.
- Speak the input or translation using the Web Speech API.
- Defaults to English → Hindi on load; heading styled with a purple theme.

## Usage

1. Open `Translate.html` in your browser. (No build step required.)
2. Enter or paste text into the top textarea.
3. Choose the desired languages and press the button.
4. The translation appears below; use icons for additional actions.

## Development

- You can edit any of the three files directly. They are plain HTML/CSS/JS and don't require a server.
- The project is portable; just keep all files together in a directory.

## Collaboration

Anyone interested in contributing or collaborating is welcome to join. Feel free to fork the repository, suggest changes, or reach out if you'd like to work together on new features or improvements.
