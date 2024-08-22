# PWA Text Editor

## Description

The PWA Text Editor is a Progressive Web Application (PWA) that allows users to create, edit, and save text documents directly in their browser. The application works offline and provides a rich text editing experience that persists data between sessions. It can also be installed as a standalone application on desktops or mobile devices for ease of use. This project demonstrates the implementation of a text editor as a PWA with local data storage and a service worker for offline capabilities.

## Table of Contents

- [Description](#description)
- [Instructions](#instructions)
- [Required Packages](#required-packages)
- [Installation](#installation)

## Instructions

1. Open the PWA Text Editor application in your preferred web browser.
2. Create or edit your text directly in the editor.
3. The application automatically saves your work in local storage, so you won't lose your progress if you close the browser.
4. For offline use, install the application by clicking the "Install" button or using the browser's PWA installation option.
5. To retrieve your saved work, simply revisit the application or launch it from your installed apps.

## Required Packages

- Express.js (to serve the app)
- Webpack (for bundling)
- idb (IndexedDB wrapper to manage data storage)
- Service Worker (for caching files for offline use)
- Babel (for compatibility across browsers)
- CodeMirror (text editor library)
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/crob127/pwa-text-editor-19.git
    ```

2. Navigate to the project directory:
    ```bash
    cd pwa-text-editor-19
    ```

3. Install the required dependencies:
    ```bash
    npm install
    ```

4. Run the application locally:
    ```bash
    npm run start
    ```

5. Open the application in your browser at `http://localhost:3000` and start editing your text.

6. Optionally, you can build the app for production by running:
    ```bash
    npm run build
    ```

The application will now be ready for offline use and installation as a Progressive Web App!

