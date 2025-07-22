# CodeFox 🦊

![CodeFox 🦊 Icon](/screenshots/banner.png)  
_From Clueless to Code-Master – One Hint at a Time._

---


## Table of Contents

- [Project Highlights](#project-highlights)
- [Key Features](#key-features)
- [Platform Compatibility](#platform-compatibility)
- [Requirements](#requirements)
- [Visual Tour](#screenshots)
- [How CodeFox Operates](#how-it-works)
- [Step-by-Step Installation](#installation)
- [Directory Layout](#file-structure)
- [Technology Stack](#technologies-used)
- [Ways to Contribute](#contributing)

---

## Project Highlights

**CodeFox** is a powerful, browser-based assistant crafted to supercharge your LeetCode problem-solving adventures. Seamlessly woven into LeetCode’s web interface, CodeFox offers tailored, AI-augmented support every time you land on a problem page. From strategic hints and adaptive pseudocode to annotated solutions and performance breakdowns, CodeFox helps you transition from learning to mastery, one challenge at a time. With a polished interface, end-to-end error handling, and secure API key integration, CodeFox stands apart as a robust, privacy-conscious tool for developers and learners alike.

---

## Key Features

- **Native LeetCode Augmentation:** Instantly attaches a “Get CodeFox Hints” button to your problem workspace for minimal disruption and maximum assistance.

- **Adaptive Guidance Flow:**
  - **Hint Cascade:** Multiple clue levels tailored to push your thinking, not spoil solutions.
  - **Strategic Blueprint:** Breakdowns of recommended data structures and stepwise approaches.
  - **Universal Pseudocode:** Intuitive, language-independent steps accessible to all proficiency levels.
  - **Solution Reveal:** Peer over the AI’s shoulder—see a thoroughly commented Java solution, demystified.
  - **Performance Insights:** Crisp, reasoned breakdowns of time/space complexity to fine-tune your learning.

- **Intuitive Modern UI:** Elegant slide-in panel, custom themes, and high-clarity code highlighting for distraction-free focus.

- **Private API Key Management:** Your Gemini API key remains encrypted—easy to set, never exposed.

- **Comprehensive Error Handling:** Friendly error reports and retry options help you stay on track, even when the network isn’t.

- **Rich Formatting:** Get everything in clean, Markdown-styled blocks—easier to study, share, and reference.

---

## Platform Compatibility

- **Guaranteed:** Google Chrome, Microsoft Edge
- **Also Works:** Chromium-based browsers such as Brave and Opera (not officially tested)
- **Optimized For:** Desktop experience

---

## Requirements

Before you install, ensure you have:

- The latest version of **Google Chrome** or **Microsoft Edge**
- An active **Gemini API key** (obtainable from Google AI Studio)
- No browser restrictions blocking local extensions

---
---
## Screenshots

| Image | Description |
|-------|-------------|
| ![Extension Popup](/screenshots/gemini.png) | Shows the extension icon and API key settings popup. |
| ![Analyze Button](/screenshots/analyzebtn.png) | Displays the "Analyze Problem" button on a LeetCode problem page. |
| ![Assistant Panel](/screenshots/hints.png) | Shows the main sliding panel of the LeetCode Learning Assistant. |
| ![Generated Content](/screenshots/code.png) | Displays AI-generated content (e.g., hints or code) in the panel. |

---
## How It Works

- ### API Key Setup
1. Click the **extension icon** in the browser toolbar to open the **API Key** popup.
2. Enter your **Gemini API key** in the input field.
3. Click **"Save Key"** to store the key securely.
4. Verify the confirmation message (green for success, red for errors).

- ### Using in LeetCode
1. Navigate to a LeetCode problem page (e.g., `https://leetcode.com/problems/score-after-flipping-matrix`).
2. Click the **"Analyze Problem"** button to open the sliding assistant panel.
3. Use the **"Reveal"** buttons to access:
   - **Hints :** 3-4 short hints to guide your thinking.
   - **Approach :** Data structure and algorithm details.
   - **Pseudocode :** Step-by-step pseudocode for the optimal solution.
   - **Solution :** Java code with comments and explanation.
   - **Complexity :** Time and space complexity analysis.
4. Click the close button (×) to hide the panel.

---
## Installation

Follow these steps to set up the extension:

1. Clone or Download the Repository:
   ```bash
   git clone https://github.com/Sparsh12321/CodeFox.git
   ```
   Or download and extract the ZIP file.

2. Open Extensions Page:
   - **Chrome**: Go to `chrome://extensions/`.
   - **Edge**: Go to `edge://extensions/`.

3. Enable Developer Mode:
   - Toggle "Developer mode" (top-right) to ON.

4. Load Unpacked Extension:
   - Click "Load unpacked" and select the `CodeFox` folder.

5. Set API Key:
   - Click the extension icon in the browser toolbar.
   - Enter your Gemini API key in the popup and click "Save Key".

6. Verify Setup:
   - Visit a LeetCode problem page (e.g., `https://leetcode.com/problems/score-after-flipping-matrix`).
   - Confirm the "Analyze Problem" button appears.

---
## File Structure

```
leetcode-assistant/
├── background.js          # Service worker for Gemini API calls
├── content_script.js      # Injects UI and handles LeetCode page interactions
├── icons/                 # Extension icons
├── screenshots/           # screenshots
├── manifest.json          # Extension configuration
├── panel.html             # HTML for the assistant panel
├── popup.html             # HTML for the API key settings popup
├── popup.js               # Logic for the popup
└── styles.css             # Styles for the button and panel
```

---
## Technologies Used

| Technology | Description |
|------------|-------------|
| HTML5  | Structures the popup and assistant panel UI. |
| CSS3   | Styles the UI with responsive design and animations. |
| JavaScript | Powers the extension’s logic and API communication. |
| Gemini 2.5 Flash Model API | Generates AI-powered hints, approaches, pseudocode, solutions, and complexity analysis. |
| Chrome Extension APIs | Enables storage (`chrome.storage`), messaging (`chrome.runtime`), and tab interactions (`chrome.tabs`). |

---
## Contributing

We welcome contributions to enhance the LeetCode Learning Assistant! To contribute:

1. Fork the Repository:
   ```bash
   git fork https://github.com/Sparsh12321/CodeFox.git
   ```
2. Create a Feature Branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make Changes: Implement your feature or bug fix.

4. Test Locally:
   - Load the updated extension in Chrome/Edge via "Load unpacked".
   - Test on multiple LeetCode problems to ensure compatibility.
5. Commit and Push:
   ```bash
   git commit -m "Add your feature description"
   git push origin feature/your-feature-name
   ```
6. Submit a Pull Request: Open a PR on GitHub with a detailed description of changes.
7. Report Issues: Open an issue for bugs or feature suggestions.



---
