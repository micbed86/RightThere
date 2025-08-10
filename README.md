# RightThere - Your Instant AI Co-pilot for the Web

<p align="center">
  <img src="https://img.shields.io/badge/version-0.13.11-blue?style=for-the-badge" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green?style=for-the-badge" alt="License">
  <img src="https://img.shields.io/badge/platform-Chrome%20%7C%20Edge-orange?style=for-the-badge" alt="Platform">
</p>

**RightThere** evolves your workflow with instant AI access on any webpage. Summon a sleek, draggable, and resizable glass interface to interact with cutting-edge AI models. Leverage a powerful prompt library with folders, use images and your voice for input, control AI reasoning, and boost productivity with intuitive shortcuts. This isn't just a tool; it's a comprehensive AI co-pilot, seamlessly integrated into your browser.

---

<p align="center">
  <em><img src="https://host398815.xce.pl/drive/img/msedge_0a5kaa43Gz.png" alt="MainWindowExample"></em>
  <br>
  </p>

---

## ✨ Key Features

### Advanced Inputs & Context

* **Image & Vision Support:** Attach images directly to your chat! Interact with multi-modal vision models to analyze, describe, or ask questions about visual content.
* **Voice Dictation:** Go hands-free. Use the built-in speech-to-text to dictate your queries and messages directly into the chat.
* **Rich Context-Awareness:**
  * **Selected Text:** Instantly use any highlighted text as the primary input for your query.
  * **Page Content:** With one click, feed the entire article content of the current page to the AI for summaries, analysis, or Q&A. A robust parsing engine (Mercury, Readability, and heuristics) ensures the best possible extraction.
  * **Ad-Hoc Chat:** No prompt needed! Just open the panel and start asking questions.

### Powerful AI & Prompt Control

* **Complete Prompt Library:** Create, edit, and organize a personal library of prompts. Structure them in nested folders for different tasks (e.g., "Writing," "Coding," "Translation").
* **AI Reasoning Control:** A unique feature for advanced users! Toggle the AI's reasoning process on or off and set the effort level (low, medium, high) to see the "thought process" behind the answer (for supported models).
* **Full Chat Interface:** Engage in multi-turn conversations, regenerate responses, and maintain a seamless dialogue with the AI.
* **Model Freedom:** Natively integrated with **OpenRouter.ai**, giving you access to a massive and ever-growing list of models from different providers.
* **Drag & Drop Organization:** Effortlessly reorder your prompts and folders with a simple drag-and-drop interface in the settings.

### Elegant & Customizable UI

* **Instant Access:** Summon the AI panel anytime with a customizable keyboard shortcut (default: `Alt + Q`).
* **Draggable & Resizable Glass UI:** A beautiful, semi-transparent glassmorphism interface that you can move and resize to fit your workflow without being intrusive.
* **Deeply Customizable:**
  * **Themes:** Switch between a polished Light and a sleek Dark mode.
  * **Skin Tinting:** Personalize the panel's color and opacity to perfectly match your aesthetic.
  * **Persistent Width:** The panel remembers its width across sessions if you want it to.

### Seamless Workflow Integration

* **Copy & Replace:** Instantly copy the AI's response to your clipboard or directly replace your selected text with the AI-generated content in any editable field.
* **Data Portability:** Easily import and export your entire setup—including prompts, folders, and all settings—via JSON files.

---

## 🚀 Installation

### Method 1: From Official Stores (Recommended)

Once published, you can install RightThere directly from your browser's extension store for automatic updates and security.

* **[Chrome Web Store](https://link-to-chrome-store)** (Link not yet available)
* **[Firefox Browser Add-ons](https://link-to-firefox-store)** (Link not yet available)
* **[Microsoft Edge Add-ons](https://link-to-edge-store)** (Link not yet available)

### Method 2: Manual Installation (For Developers)

If you want to install from the source code:

1. Download this repository as a ZIP file and extract it, or clone it using Git.
2. Open your browser and navigate to the extensions page:
   * Chrome: `chrome://extensions`
   * Edge: `edge://extensions`
3. Enable **"Developer mode"** (usually a toggle in the top-right corner).
4. Click **"Load unpacked"** and select the directory where you extracted the repository files.
5. The RightThere extension icon should now appear in your browser's toolbar.

---

## ⚙️ Getting Started

Before you can use RightThere, you need to configure your API key.

1. **Open the Settings Panel:** Press the activation shortcut (`Alt + Q` by default) on any webpage, then click the **settings icon** (⚙️).
2. **Enter API Key:** In the `OpenRouter API Key` field, paste your key. You can get a key from [OpenRouter.ai](https://openrouter.ai/).
3. **Customize (Optional):**
   * **Activation Shortcut:** Click the input field and press your desired key combination.
   * **Default Model:** Choose your preferred AI model from the extensive dropdown list. Models with Vision or Reasoning capabilities are highlighted.
   * **Items:** Click "Add New Prompt" or "Add New Folder" to start building your library.
   * **Appearance:** Adjust the theme, panel color, and opacity to your liking.
4. **Save & Close:** Click the "Save & Close" button. You're all set!

---

## 📖 How to Use

* **Core Workflow:**
  
  1. Highlight text on a webpage.
  2. Press `Alt + Q`.
  3. Select a prompt from your library to run it on the highlighted text.

* **Using Page Content:**
  
  * Before selecting a prompt or typing, check the "Use the content of this page as context" box. RightThere will parse the article and provide it to the AI.

* **Using Vision:**
  
  * Click the **Image icon** to attach an image from your computer.
  * Type your query related to the image and send. (Requires a vision-capable model).

* **Using Voice:**
  
  * Click the **Microphone icon** to start dictating. Click it again or press any key to stop.

* **Chatting & Managing Output:**
  
  * After a response, continue the conversation by typing in the input field.
  * Use the `Regenerate`, `Replace`, and `Copy` buttons to manage the AI's output.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Created by micbed86*

