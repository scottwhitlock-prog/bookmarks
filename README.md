# Custom Chrome Android Homepage

A personal, mobile-friendly start page hosted on GitHub Pages featuring a frosted-glass design, automatic light/dark mode, a Google AI Mode search bar, a quick shortcut to Gemini, and categorized bookmarks.

## Files in This Repository
* **`index.html`** — The main webpage containing all styles, search bar, and bookmark links.
* **`bg.png`** — The full-screen background wallpaper. *(To change the wallpaper later, delete `bg.png` and upload a new image named `bg.png`.)*

## How to Add or Edit Bookmarks
1. Click **`index.html`** in the file list above.
2. Click the **pencil icon** (Edit this file) on the top right of the code box.
3. Find the section you want (`Shopping`, `Media & News`, `Books`, or `Finance & Home`) and copy-paste an existing `<a href="...">...</a>` block:
   ```html
   <a href="https://example.com">
     <div class="badge" style="background:#1a73e8;">E</div>
     <span class="label">Example</span>
   </a>
   ```
4. Update the web address (`href`), badge color (`background`), badge text/emoji, and link name (`label`).
5. Click **Commit changes...** twice. GitHub Pages automatically updates the live site within **1–2 minutes**.

## Setting on Chrome for Android
1. Open Chrome on Android and go to `https://<username>.github.io/<repository-name>/`.
2. Tap the **three-dot menu** > **Settings** > **Homepage**.
3. Toggle it **On**, choose **Enter custom web address**, and paste the URL.
