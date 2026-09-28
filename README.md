# p5.js Starter

A minimal p5.js sketch for experimenting in GitHub Codespaces. The p5.js library is loaded from jsDelivr, so the Codespace needs internet access when the page is first opened.

## Open in Codespaces

1. On GitHub, open the repository and choose **Code** > **Codespaces** > **Create codespace on main** (or choose the class branch your instructor specifies).
2. Wait for the Codespace to finish configuring. Live Preview is installed automatically.
3. Open `index.html` and choose **Show Preview** in the editor, or right-click the file and choose **Show Preview**.
4. Edit `sketch.js`. Live Preview refreshes the page when files change.

You can also open the Command Palette and run **Live Preview: Show Preview (Internal Browser)**.

## If the embedded preview is blank

Live Preview currently documents a one-time Codespaces redirect workaround:

1. Open the **Ports** panel in the bottom panel.
2. Open the local address for port 3000, and port 3001 if it is listed, in a browser tab.
3. Wait for each page to finish redirecting, then close those tabs.
4. Reopen the Live Preview window.

If needed, use **Live Preview: Show Preview (External Browser)** from the Command Palette instead.

## Project files

- `index.html` loads p5.js and the sketch.
- `sketch.js` contains the starter `setup()` and `draw()` functions.
- `style.css` styles the page around the canvas.
- `.devcontainer/devcontainer.json` installs Live Preview and forwards its usual ports in Codespaces.

The p5.js version is pinned in `index.html`. To change versions, update the URL in its p5.js script tag.