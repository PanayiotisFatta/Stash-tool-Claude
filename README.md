# Stash — Save highlights from Claude

Stash is a browser extension that lets you save, organise, and revisit useful text from your Claude conversations — without losing it when the tab closes or the conversation moves on.

It injects a sidebar directly into [claude.ai](https://claude.ai), so everything happens in-context without switching tools.

---

## What it does

### Save highlights instantly
Select any text in a Claude response and click the 📌 pin button that appears. A small popover lets you choose which list to save it to, add a note, or add tags before confirming.

### Organised by conversation and project
Stash automatically mirrors Claude's own structure. Each conversation gets its own folder. If you're working inside a Claude Project, Stash creates a matching project folder automatically. You can also create your own manual folders for freeform organisation.

### Lists inside each folder
Every conversation folder comes pre-seeded with three default lists: **To-do**, **Questions**, and **Important**. You can rename, delete, or create additional lists with a custom name and colour.

### Highlights stay visible
Saved highlights are marked with a coloured underline directly in the conversation, so you always know what you've already stashed.

### Drag and drop
Reorder highlights within a list, or drag them across lists and folders. The highlight colour updates automatically to match its new list.

### Checkboxes and completion
Action-oriented lists (To-do, Questions) have checkboxes enabled by default. Checking an item moves it to the archive with an undo prompt. Other lists (like Important) are reference lists — no checkboxes unless you turn them on.

### Navigate back to the source
Click the arrow icon on any saved highlight to jump straight back to the exact point in the original conversation where it was saved.

### Notes and tags
Attach a private note to any highlight at save time, and edit it later. Tag highlights with custom labels to group related items across different lists.

---

## Installation

Stash is not yet on the Chrome Web Store. Install it manually in a few steps:

1. Download the latest `stash-v2.zip` from the [Releases](../../releases) page
2. Unzip the file — you should see a folder called `dist` inside
3. Open Edge or Chrome and go to `edge://extensions` or `chrome://extensions`
4. Enable **Developer mode** using the toggle in the top-right corner
5. Click **Load unpacked** and select the `dist` folder
6. Navigate to [claude.ai](https://claude.ai) — the Stash sidebar will be available on every conversation

> **Note:** Stash only runs on claude.ai. It does not collect or transmit any data — everything is stored locally in your browser using IndexedDB.

---

## Usage

- **Select text** in any Claude response → click the 📌 pin button
- **Toggle the sidebar** by clicking the Stash icon in your browser toolbar
- **Right-click** the navigation arrow on a highlight to open its source in a new tab
- **Drag highlights** between lists to reorganise them
- **Right-click any list or folder** in the sidebar for rename, delete, and other options

---

## Requirements

- Microsoft Edge or Google Chrome (Manifest V3)
- A [claude.ai](https://claude.ai) account

---

## Known limitations

- Works on claude.ai only — not other AI tools
- Highlights saved before the source navigation feature was added do not support jump-back navigation
- If a conversation is deleted from Claude, any highlights saved from it will have their source links automatically removed

---

## Feedback and issues

Found a bug or have a feature request? Open an issue on this repository.
