# PolyglotPal

PolyglotPal is a client-side, single-page web application that instantly translates text between over 100 languages. It features speech synthesis with selectable voices, phrase history with import/export/clear, favorites, copy & download, and light/dark mode—all without sending your text to any server.

---

## Live Demo

View it on GitHub Pages:  
https://bocaletto-luca.github.io/PolyglotPal

---

## Features

- **100+ Languages**  
  Translate between dozens of languages, from English, Spanish, French, German to Hindi, Vietnamese, Ukrainian and more.

- **Client-Side Only**  
  All translation requests use the MyMemory public API; speech synthesis and UI run entirely in your browser.

- **Speech Synthesis**  
  Pick from your system’s installed voices and listen to translations aloud.

- **Phrase History**  
  Automatically saves your last 50 translations.  
  - **Import/Export** your history to JSON  
  - **Clear** your history with one click

- **Favorites**  
  Bookmark any translation for quick recall.

- **Copy & Download**  
  One-click copy of the translated text to clipboard or download as a `.txt` file.

- **Light & Dark Mode**  
  Toggle between light and dark themes for comfortable reading.

- **No Dependencies**  
  Pure HTML, CSS, and JavaScript. No build tools, no frameworks—just a single `index.html`.

---

## Installation

1. **Clone the repository**  
   ```bash
   git clone https://github.com/bocaletto-luca/PolyglotPal.git
   cd PolyglotPal
   ```

2. **Serve the app locally**  
   Modern browsers block `fetch()` on `file://`, so you must use a simple HTTP server:

   - **Python 3**  
     ```bash
     python3 -m http.server 8000
     ```
   - **Node.js (http-server)**  
     ```bash
     npx http-server . -p 8000
     ```
   - **Ruby**  
     ```bash
     ruby -run -e httpd . -p 8000
     ```

3. **Open in browser**  
   Navigate to `http://localhost:8000/index.html`.

---

## Usage

1. **Select Languages**  
   - Use the two dropdowns to pick your source and target languages.

2. **Enter Text**  
   - Type or paste text into the top textarea. Press **Enter** or click **Translate**.

3. **View Translation**  
   - The translated text appears in the bottom textarea.

4. **Speak Translation**  
   - Choose a voice from the **Voice** dropdown, then click **🔊 Speak** to hear it.

5. **Copy or Download**  
   - Click **📋 Copy** to copy to clipboard, or **⬇️ Download .txt** to save as a text file.

6. **Manage History**  
   - Your most recent translations show under **History**.  
   - **Export** to JSON, **Import** a JSON file, or **Clear** all history.

7. **Favorites**  
   - Click the star icon next to any history entry to add/remove from **Favorites**.

8. **Toggle Theme**  
   - Click the **🌙/☀️** button to switch between dark and light modes.

---

## File Structure

```
PolyglotPal/
├── index.html       # Single-page application
├── LICENSE          # GNU GPL v3
└── README.md        # This documentation
```

---

## Contributing

Bug reports, feature requests, and pull requests are welcome!

1. Fork the repo  
2. Create a branch: `git checkout -b feature/YourFeature`  
3. Commit your changes: `git commit -m "Add YourFeature"`  
4. Push: `git push origin feature/YourFeature`  
5. Open a pull request on GitHub

Please test your changes and keep the code style consistent.

---

## License

This project is open source under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) for details.

---

## Author

**Bocaletto Luca**  
- GitHub: [@bocaletto-luca](https://github.com/bocaletto-luca)  
- Repository: [PolyglotPal](https://github.com/bocaletto-luca/PolyglotPal)
