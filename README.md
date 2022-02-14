# Colima + Docker + Docker compose

## Setup Colima and Docker

Colima: https://github.com/abiosoft/colima

1. brew install colima
2. brew install docker
3. colima start
4. brew install docker-compose

## Setup VSCode

1. Install VSCode [Remote Extension](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
2. Restart VSCode

## Start development

1. Run `docker-compose -f docker-compose.debug.yml up --build` in terminal
2. Click remote dev icon at left bottom corner or press `command + shift + P`
3. Choose option "Open Folder in Container..."
4. Browse to your project folder in host and choose container
5. Press `command + O` and type WORKDIR(`/usr/src/app`) of container

Visit [http://localhost:3000](http://localhost:3000) in your browser.

Try to change [./src/App.js](./src/App.js) file, and see if the change is reflected in the site.
