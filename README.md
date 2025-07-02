<span style="font-family:monospace; font-size:13px; background: linear-gradient(90deg, #8B0000, #b20000, #ff4e50, #ff7e5f); -webkit-background-clip: text; color: transparent; display: block;">

```
 __       __  ______  __    __  ______   ______   ________  _______   __      __        ________  ______    ______   __         ______         __     __    __         ______       ______  
/  \     /  |/      |/  \  /  |/      | /      \ /        |/       \ /  \    /  |      /        |/      \  /      \ /  |       /      \       /  |   /  | _/  |       /      \     /      \ 
$$  \   /$$ |$$$$$$/ $$  \ $$ |$$$$$$/ /$$$$$$  |$$$$$$$$/ $$$$$$$  |$$  \  /$$/       $$$$$$$$//$$$$$$  |/$$$$$$  |$$ |      /$$$$$$  |      $$ |   $$ |/ $$ |      /$$$$$$  |   /$$$$$$  |
$$$  \ /$$$ |  $$ |  $$$  \$$ |  $$ |  $$ \__$$/    $$ |   $$ |__$$ | $$  \/$$/           $$ |  $$ |  $$ |$$ |  $$ |$$ |      $$ \__$$/       $$ |   $$ |$$$$ |      $$$  \$$ |   $$$  \$$ |
$$$$  /$$$$ |  $$ |  $$$$  $$ |  $$ |  $$      \    $$ |   $$    $$<   $$  $$/            $$ |  $$ |  $$ |$$ |  $$ |$$ |      $$      \       $$  \ /$$/   $$ |      $$$$  $$ |   $$$$  $$ |
$$ $$ $$/$$ |  $$ |  $$ $$ $$ |  $$ |   $$$$$$  |   $$ |   $$$$$$$  |   $$$$/             $$ |  $$ |  $$ |$$ |  $$ |$$ |       $$$$$$  |       $$  /$$/    $$ |      $$ $$ $$ |   $$ $$ $$ |
$$ |$$$/ $$ | _$$ |_ $$ |$$$$ | _$$ |_ /  \__$$ |   $$ |   $$ |  $$ |    $$ |             $$ |  $$ \__$$ |$$ \__$$ |$$ |_____ /  \__$$ |        $$ $$/    _$$ |_  __ $$ \$$$$ |__ $$ \$$$$ |
$$ | $/  $$ |/ $$   |$$ | $$$ |/ $$   |$$    $$/    $$ |   $$ |  $$ |    $$ |             $$ |  $$    $$/ $$    $$/ $$       |$$    $$/          $$$/    / $$   |/  |$$   $$$//  |$$   $$$/ 
$$/      $$/ $$$$$$/ $$/   $$/ $$$$$$/  $$$$$$/     $$/    $$/   $$/     $$/              $$/    $$$$$$/   $$$$$$/  $$$$$$$$/  $$$$$$/            $/     $$$$$$/ $$/  $$$$$$/ $$/  $$$$$$/  
                                                                                                                                                                                            
                                                                                                                                                                                            
                                                                                                                                                                                            
```
</span>

# 🛠️ Ministry Tools Suite

**A premium, all-in-one desktop application for subtitle translation, AI-powered media generation, and creative workflows.**  
Designed for creators, ministries, and content producers seeking a unified, efficient, and beautiful toolkit.

---

## 📖 Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [First Launch & Profiles](#first-launch--profiles)
- [Navigating the Suite](#navigating-the-suite)
- [Tool Details](#tool-details)
  - [Prompt Generator](#prompt-generator)
  - [Image Generator](#image-generator)
  - [SRT Checker](#srt-checker)
  - [SRT Translator](#srt-translator)
  - [AI Chat Bot](#ai-chat-bot)
- [API Key Management](#api-key-management)
- [Profiles](#profiles)
- [Troubleshooting & Tips](#troubleshooting--tips)
- [FAQ](#faq)
- [Credits](#credits)

---

## 🏆 Overview

**Ministry Tools Suite** brings together the most essential creative and translation tools in a single, cross-platform app:

| Tool                 | Description                                                |
|----------------------|------------------------------------------------------------|
| 🎨 **Image Generator**  | Create images from prompts using OpenAI DALL·E            |
| 🧠 **Prompt Generator** | Turn lyrics or descriptions into vivid AI prompts         |
| 🌐 **SRT Translator**   | Translate `.srt` subtitle files via DeepL                |
| 🔍 **SRT Checker**      | Compare original and translated subtitles for quality     |
| 🤖 **AI Chat Bot**      | Conversational AI assistant powered by DeepSeek          |
| 👤 **Profile Manager**  | Personalize your experience with named profiles          |

No Python installation required. Runs as a standalone app for **Windows** and **macOS**.

---

## 💾 Installation

### Windows

1. **Download** the `.exe` or `.zip` file.
2. If `.zip`, **extract** and run the `.exe` inside.
3. If Windows shows a security warning, click **"More Info" → "Run Anyway"**.
4. No Python or extra setup required.

### macOS

1. **Download** the `.dmg` or `.zip` file.
2. **Drag** the `.app` to your **Applications** folder.
3. If macOS prevents launch, right-click → **Open** and approve via **System Settings > Privacy & Security**.
4. No Python or extra setup required.

---

## 👤 First Launch & Profiles

1. **Start the app**. You'll see a login/profile screen.
2. **Create a profile**:  
   - Enter your name and click **Add Profile**.
   - Your profile appears in the dropdown.
3. **Select your profile** and click **Login**.
4. Profiles are stored in `profiles.json` in the app directory.

---

## 🗺️ Navigating the Suite

- After login and a brief loading screen, you'll see the **Tool Menu**.
- Each tool is shown as a card with an icon and description.
- **Open a tool**: Click the **Open** button on any card.
- **Return to Tool Menu**: Click the **←** (Back) button in the top-right of any tool window.

---

## 🧰 Tool Details

### 🧠 Prompt Generator

- **Purpose**: Turn lyrics or scene descriptions into detailed prompts for AI image generation.
- **How to Use**:
  1. Enter your **DeepSeek API key** and click **💾 Save API Key**.
  2. Paste lyrics/descriptions or load from a `.txt` file.
  3. Configure: number of prompts, lines per prompt, length, style, and merging options.
  4. Choose output file.
  5. Click **⚡ Generate Prompts**. Prompts are saved to your file.

### 🎨 Image Generator

- **Purpose**: Generate images from prompts using OpenAI DALL·E.
- **How to Use**:
  1. Enter your **OpenAI API key** and click **💾 Save API Key**.
  2. Paste prompts or load from file.
  3. Select resolution and style.
  4. Choose output folder.
  5. Click **⚡ Generate Images**. Images are saved as PNG files.

### 🔍 SRT Checker

- **Purpose**: Compare original and translated SRT files for translation quality.
- **How to Use**:
  1. Load original and translated SRT files.
  2. Click **🔎 Check Translation**.
  3. Review results and export the log if needed.

### 🌐 SRT Translator

- **Purpose**: Translate SRT subtitle files using DeepL.
- **How to Use**:
  1. Enter your **DeepL API key** and click **💾 Save API Key**.
  2. Select input SRT file and output file.
  3. Choose target language.
  4. Click **⚡ Translate SRT**. Progress and logs are shown.

### 🤖 AI Chat Bot

- **Purpose**: Chat with an AI assistant powered by DeepSeek.
- **How to Use**:
  1. Enter your **DeepSeek API key** and click **💾 Save API Key**.
  2. Type your message and click **Send**.
  3. The bot responds in the chat area.

---

## 🔐 API Key Management

Each tool uses its own `.txt` key file:

| Tool                        | Key File               |
|-----------------------------|------------------------|
| Prompt Generator / Chat Bot | `deepseek_api_key.txt` |
| SRT Translator              | `deepl_api_key.txt`    |
| Image Generator             | `open_ai.txt`          |

- Keys are stored locally and loaded automatically.
- To update or delete a key:
  - Use the **Save API Key** button in-app, or
  - Delete the `.txt` file directly.

---

## 🧠 Profiles

- Create a profile on first launch.
- Profiles are stored in `profiles.json` in the app directory.
- Profiles personalize your experience and may be expanded in future versions.

---

## 🧩 Troubleshooting & Tips

### General

- Ensure API keys are valid and saved.
- Stable internet connection is required for all AI features.
- Use the **Back** button (top right) to return to the main menu.

### Windows

- “Unknown publisher” warning? Click **Run Anyway**.
- App won’t launch? Check antivirus or firewall permissions.

### macOS

- App blocked? Right-click → **Open**, then approve in **System Settings**.

---

## ❓ FAQ

**Q: Can I use the same API key for all tools?**  
A: No. Each tool uses a different service (OpenAI, DeepL, DeepSeek).

**Q: Does the app work offline?**  
A: No. AI and translation features require internet access.

**Q: Where are my profiles stored?**  
A: In `profiles.json` within the app directory.

**Q: How do I update the app?**  
A: Overwrite your app folder with the latest version from the developer.

---

## 🙌 Credits

Developed by **Max** for **Ernie**  
Powered by:

* OpenAI (Image generation)
* DeepSeek (Prompt generation, chatbot)
* DeepL (Subtitle translation)

UI design inspired by modern desktop aesthetics and workflow simplicity.

---

> For questions or support, please contact the developer or system administrator.

---
