# forge-gltf-server

Experimental Node.js server app generating glTF files for Autodesk Forge models.

## Running locally

### Prerequisites

- [Register a Forge application](https://forge.autodesk.com/en/docs/oauth/v2/tutorials/create-app)
- [Node.js](https://nodejs.org) (we recommend the Long Term Support version)
- Terminal (for example, [Windows Command Prompt](https://en.wikipedia.org/wiki/Cmd.exe)
or [macOS Terminal](https://support.apple.com/guide/terminal/welcome/mac))

### Setup & Run

- Clone the repository
- Install dependencies: `npm install` or `yarn install`
- Setup environment variables:
  - `FORGE_CLIENT_ID` - your Forge application client ID
  - `FORGE_CLIENT_SECRET` - your Forge application client secret
  - `HOST_URL` - URL where this app is running (used to build the OAuth callback URL)
  - `SERVER_SESSION_SECRET` - a secret phrase used to encrypt session cookies
- Run the server: `npm start`

> When using [Visual Studio Code](https://code.visualstudio.com),
you can specify the env. variables listed above in a _.env_ file in this
folder, and run & debug the application directly from the editor.
