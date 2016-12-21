# Electron Draw Pro App

![Screenshot of my test Draw Pro electron app](https://drive.google.com/uc?export=view&id=0B6IVyE8wPQroS0tHd0FkMVgtck0)

**Clone and run for a quick way to see Electron in action.**

This is a minimal Electron application based on the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start) within the Electron documentation and some basic front-end styling to create a simple drawing app I call **Draw Pro**.

You are able to draw within the desktop app and save the drawing out as a `.png` file.

A basic Electron application needs just these files:

- `package.json` - Points to the app's main file and lists its details and dependencies.
- `main.js` - Starts the app and creates a browser window to render HTML. This is the app's **main process**.
- `index.html` - A web page to render. This is the app's **renderer process**.

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

### To Use

To clone and run this repository you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
git clone https://github.com/owain-stratton/Electron_DrawApp.git
# Go into the repository
cd Electron_DrawPro
# Install dependencies
npm install
# Run the app
npm start
```

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

#### License [CC0 1.0 (Public Domain)](LICENSE.md)
