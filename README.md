# Simple Shooter

A minimal browser-based first-person shooter prototype built with Three.js.

## Controls

- Click the Start button to begin
- Move: W A S D
- Look: mouse movement
- Shoot: left mouse button

## Run locally

Because the game uses ES modules, start a local HTTP server from the project folder.

### Using Python 3

```powershell
cd "c:\Users\David\Documents\Agentic Coding\Simple Shooter"
python -m http.server 8080
```

Open `http://localhost:8080` in your browser.

### Using Node.js

If you have Node.js installed, you can use a simple server package such as `http-server`.

```powershell
npm install --global http-server
http-server . -p 8080
```

