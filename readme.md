## Chrome Extension Boilerplate (with TypeScript, Tailwind CSS & Manifest V3)

### Quick Start

```sh
npm install
npm run start
```

Below is a list of commands you will probably find useful:

`npm run start`

- Runs the project in development/watch mode.
- Load your extension on Chrome
  - Access `chrome://extensions/`
  - Check `Developer mode`
  - Click on `Load unpacked extension`
  - Select the `dist` folder.

`npm run build`

- builds the project and places the code in the `dist` folder

---

Manifest verison V3 doesn't support hot reloading. The following extension https://chrome.google.com/webstore/detail/dev-extensions-reload/bbanndmhbmgajamonlgnjnfdbifbnbdj might be helpful to reload your code in the browser.
