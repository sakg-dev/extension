## Chrome Extension Template (Manifest V3)

A clean and simple starter template to help you build Chrome Extensions using Manifest V3 with a modern workflow.

---

## Getting Started

Follow these steps to set up and start building your extension:

1. **Clone the repository**

   ```bash
   git clone https://github.com/sakg-dev/extension
   cd extension
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Set up extension icons**

   * Convert your PNG into Chrome extension icons using this tool:
     https://alexleybourne.github.io/chrome-extension-icon-generator/
   * Click **“Download All”**
   * Extract the downloaded `icons.zip` into the `public` directory

4. **Customize your extension**

   * Open `manifest.json`
   * Update the following fields:

     * `name`
     * `description`

---

## Development

Start building your extension by modifying the source files as needed.

---

## Build Your Extension

Once you're ready:

```bash
npm run build
```

Your production-ready extension will be generated in the `dist` directory.

---

## Load Extension in Chrome

1. Open Chrome and go to `chrome://extensions/`
2. Enable **Developer Mode** (top right)
3. Click **Load unpacked**
4. Select the `dist` folder

---

## Project Structure (Overview)

```
├── public/          # Static assets (icons, HTML files, manifest.json, etc.)
├── src/             # Source code (.ts files)
├── dist/            # Build output
├── package.json     # Project dependencies and scripts
├── tsconfig.json    # TypeScript configuration
```