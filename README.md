# Tauri web app wrapper

A template for creating wrappers for existing web apps, so that you don't have to be distracted by the browser.

## Usage

### 1

`npm install`

### 2

Replace the following keywords:

- `REPLACE_NAME`: The app name, eg. "Brightspace"
- `REPLACE_URL`: The app url, eg. "https://brightspace.au.dk"
- `REPLACE_ID`: The app id, eg. "tauri-brightspace-app"

### 3

Replace the sample icon at `./app-icon.png`. Then run `npm run tauri icon` to generate icons.

### 4

If you need to, edit window size in _src-tauri/tauri.conf.json_.

### 5

Test the app: `npm run tauri dev`

### 6

Build the app: `npm run tauri build`

Bundle will be available in _src-tauri/target/release/bundle/_.
