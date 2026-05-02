# omanote-extension
Browser extension for omanote. Capture notes, bookmarks, and todos from anywhere into your omanote workspace.

Learn more on:[the official website](https://omanote.iambishistha.com)

# 1.Feature Set

### 1.1 Selection Bubble (Grammarly-style)

When the user selects any text on any page, a small omanote bubble appears near the selection. Clicking it opens an inline save modal.

- Selected **text** → defaults to **Note**
- Selected text that is a pure URL → defaults to **Bookmark**
- Selected text + page URL → **Note with source link** (checkbox to include URL)

The bubble disappears on click-away or Escape. It lives inside a **closed Shadow DOM** so page styles cannot interfere.

### 1.2 Context Menu (Right-click)

Four submenus injected into the browser's native context menu:

```
Right-click on selected text:
  └── Save to omanote
        ├── Save as Note
        └── Save as Todo

Right-click on a link:
  └── Save to omanote
        ├── Save as Bookmark
        └── Save as Note (with link)

Right-click on an image:
  └── Save to omanote
        └── Save as Bookmark (image URL)

Right-click anywhere (no selection):
  └── Save to omanote
        └── Save Page as Bookmark
```

### 1.3 Toolbar Popup

Clicking the extension icon opens a 360px React panel with:

- Type tabs: **Note / Bookmark / Todo**
- Form fields: content/URL, folder/category dropdown, hashtag input, source URL checkbox
- Last 4 saved items (Recent section)
- Link to open the full omanote app
- Settings screen: account info, keyboard shortcut info, disconnect button

### 1.4 Keyboard Shortcut

`Alt+Shift+O` (default, user-configurable in browser extension settings) opens the toolbar popup from any tab.

---

# 2. Loading in Chrome

1. Go to `chrome://extensions`
2. Enable **Developer mode**
3. Click **Load unpacked** → select `omanote-chromium.zip`

# 3. Loading in Firefox

Firefox requires signed extensions for `about:addons`. For development:

1. Go to `about:addons`
2. Click gear icon and select **Load from a file**
3. Select `omanote-firefox.xpi`


