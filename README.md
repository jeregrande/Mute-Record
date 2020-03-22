# ScreenCord: Lite Screen Recorder
A simple screen recorder built with Electron's desktopCapturer  
Download it for Windows: [ZIP](https://drive.google.com/open?id=1A-bgr2s87NZGqD4b0U_29m_XpT96Oi_R),   [Installer](https://drive.google.com/open?id=1CoU3-o58EFVhnI-_y9WnxG8YxrliXZSs)

## Build pre-requisites
1. `npm` must be installed
2. Electron must be installed: `npm install electron -g`

## To build
1. Create a blank Electron app with `npx create-electron-app app-name`   
2. `git clone` this branch into a sibling directory  
3. Copy the content from within the cloned directory into the `app-name` directory  
4. `cd` into `app-name`  
5. Run `npm i custom-electron-titlebar` to get the custom toolbar package
6. Run `npm start` to start the app, or `npm run make` to build an executable

Note: The outputted executable might not be treated nicely by anti-virus programs

Custom toolbar package: https://www.npmjs.com/package/custom-electron-titlebar
