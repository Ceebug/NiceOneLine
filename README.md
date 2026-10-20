# NiceOneLine

A clean, minimalist patch for modern Firefox that forces the navigation bar and tabs into a single, seamless row.

## What it does
**NiceOneLine** merges the address bar and tabs horizontally, reclaiming valuable vertical screen space while preserving your native window controls and drag spaces.
It has some settings, which allow you to toggle history buttons or flip the menu position directly from a simple configuration block.

## How to Install

1. Open a new tab in Firefox and go to `about:config`.
2. Search for `toolkit.legacyUserProfileCustomizations.stylesheets` and set it to true.
3. Go to `about:support` and locate your Profile Directory row. Click Open Folder.
4. Create a folder named `chrome` if it does not already exist.
5. Copy the `userChrome.css` file into your local chrome folder.

> [!NOTE]
> If you already have a `userChrome.css` file, append the contents of the file to your already existing `userChrome.css`.

6. Open your `userChrome.css` file and adjust the variables at the top under `:root` (change values to `1` or `0`) to quickly toggle your preferred layout settings.
7. Restart ***all** open windows* of Firefox.

> [!TIP]
> **Don't be an idiot**<br>
> Make sure to save any work you care about.
