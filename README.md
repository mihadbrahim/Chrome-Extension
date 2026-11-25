Lead Tracker — Chrome Extension

A lightweight, fast Chrome Extension built with vanilla JavaScript, HTML5, and CSS3 that allows users to capture, organize, and persist sales leads or important URLs directly from their browser toolbar with one click.

Features:
- One-Click Active Tab Capture: Integrates with the Chrome Tabs API (`chrome.tabs`) 
- Manual URL Entry: Allows users to type or paste custom URLs 
- Persistent Browser Storage:Uses `localStorage` with JSON serialization (`JSON.stringify` / `JSON.parse`) 
- Instant Clickable Links: Renders saved URLs as clickable links that open in a new tab (`target="_blank"`).

Tech Stack

- Manifest V3: Modern Chrome Extension configuration defining popup UI, extension icons, and `tabs` permissions.
- JavaScript (ES6+): Chrome Extension APIs (`chrome.tabs.query`), `localStorage` state persistence, and dynamic DOM rendering.
- HTML5 & CSS3