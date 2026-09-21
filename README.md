# omanote-extension
Browser extension for omanote. Capture notes, bookmarks, and todos or subscribe to RSS (if available) from anywhere into your omanote.

Learn more on: [the official website](https://omanote.com)

> Download the latest version from the official browser's plugin page mentioned below

# 1.Feature Set

### 1.1 Selection Bubble

When the user selects any text on any page, a small omanote bubble appears near the selection. Clicking it opens an inline save modal.

- Selected **text** → defaults to **Note**
- Selected text that is a pure URL → defaults to **Bookmark**
- Selected text + page URL → **Note with source link** (checkbox to include URL)

You can flag website to you choose where you don't want the bubble to appear from the extension popup.

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

Right-click anywhere (no selection):
  └── Subscribe to feed
        └── Detects RSS feed in the website to subscribe
```

### 1.3 Toolbar Popup

Clicking the extension icon opens a panel with:

- Type tabs: **Note / Bookmark / Todo**
- Form fields: content/URL, folder/category dropdown, hashtag input, source URL checkbox
- Last 4 saved items (Recent section)
- Link to open the full omanote app
- Settings screen: account info, keyboard shortcut info, disconnect button

### 1.4 Keyboard Shortcut

`Alt+Shift+O` (default, user-configurable in browser extension settings) opens the toolbar popup from any tab.

---

# 2. Loading in Chrome

> Download the official version from [Chrome Webstore](https://chromewebstore.google.com/detail/omanote/foafmfgfdbdiiggmmfdoalgpfhkejbjn)

# 3. Loading in Firefox

> Download the official version from [Firefox Addons](https://addons.mozilla.org/en-US/firefox/addon/omanote/).


