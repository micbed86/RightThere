# RightThere - Your Instant AI Co-Pilot

**RightThere** transforms your workflow with instant AI access via a sleek, draggable, and resizable glass interface. Effortlessly interact with AI, leverage custom prompts, organize them with folders, and boost your productivity using intuitive keyboard shortcuts. This isn't just a tool; it's your daily AI co-pilot, seamlessly integrated to make your digital life incredibly convenient and efficient.

---

## ✨ Features

-   **Instant AI Access:** Summon the AI panel anytime, anywhere on the web with a customizable keyboard shortcut (default: `Alt + Q`).
-   **Elegant Glass UI:** A beautiful, semi-transparent glassmorphism interface that is draggable and resizable to fit your workflow without being intrusive.
-   **Powerful Prompt Management:** Create, edit, and organize your own library of custom prompts. Use folders to structure your prompts for different tasks (e.g., "Writing", "Coding", "Translation").
-   **Context-Aware Operations:**
    -   **Selected Text:** Automatically use any selected text on a page as the input for your prompt.
    -   **Page Content:** With a single click, use the entire content of the current webpage as context for the AI, perfect for summaries or analysis.
    -   **Ad-Hoc Queries:** No prompt needed! Just open the panel and type your question directly.
-   **Full Chat Interface:** Engage in multi-turn conversations with the AI, regenerate responses, and continue the dialogue.
-   **Highly Customizable:**
    -   **Theme Engine:** Switch between a polished Light and a sleek Dark mode.
    -   **Skin Tinting:** Personalize the panel's color and opacity to perfectly match your aesthetic.
    -   **Model Selection:** Choose from a wide range of models available through the OpenRouter.ai API.
    -   **Resizable Panel:** Adjust the panel's width and save it for future sessions.
-   **Seamless Workflow Integration:**
    -   **Copy:** Instantly copy the AI's response to your clipboard.
    -   **Replace Text:** Directly replace your selected text with the AI-generated content (works in editable fields).
-   **Data Portability:** Easily import and export your entire setup (settings, prompts, and folders) via JSON files.

---

## 🚀 Installation

1.  **Install a UserScript Manager:** You need a browser extension to run UserScripts. The most popular choice is **Tampermonkey**.
    -   [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)
    -   [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)
    -   [Tampermonkey for Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepofghjmenjbbm)

2.  **Install RightThere:**
    -   **[Click here to install the script](https://github.com/micbed86/RightThere/raw/main/RightThere.user.js)**
    -   Your UserScript manager will open a new tab. Click the "Install" button.

The script is now installed and ready for configuration!

---

## ⚙️ Configuration

Before you can use RightThere, you need to configure your API key.

1.  **Open the Settings Panel:** Press the activation shortcut (`Alt + Q` by default) for the first time on any webpage, then click the **settings icon** (⚙️).
2.  **Enter API Key:** In the `OpenRouter API Key` field, paste your key. You can get a free key from [OpenRouter.ai](https://openrouter.ai/).
3.  **Customize (Optional):**
    -   **Activation Shortcut:** Click the input field and press your desired key combination.
    -   **Default Model:** Choose your preferred AI model from the dropdown.
    -   **Items:** Add your first prompt or folder to start building your library.
    -   **Appearance:** Adjust the theme, panel color, and opacity to your liking.
4.  **Save & Close:** Click the "Save & Close" button.

---

## 📖 How to Use

-   **Activation:**
    -   Highlight any text on a webpage and press `Alt + Q`. The highlighted text will become the context.
    -   Press `Alt + Q` without any text selected to open the panel for an ad-hoc query or to use the full page content.

-   **Using Prompts:**
    -   After activating, a list of your prompts and folders will appear.
    -   Click on a prompt to run it against your selected text or page context.

-   **Using Page Content:**
    -   Before selecting a prompt or typing a query, check the "Use the content of this page as context" box. RightThere will parse the article's content and provide it to the AI.

-   **Chatting:**
    -   After receiving a response, you can continue the conversation by typing in the input field at the bottom.
    -   Use the `Regenerate`, `Replace`, and `Copy` buttons to manage the AI's output.

---

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
*Created by micbed86*
