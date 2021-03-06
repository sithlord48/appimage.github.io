---
layout: app

permalink: /storyboarder/
description: The fastest way to storyboard.

icons:
  - storyboarder/icons/512x512/storyboarder.png

screenshots:
  - storyboarder/screenshot.png

authors:
  - name: wonderunit
    url: https://github.com/wonderunit

links:
  - type: GitHub
    url: wonderunit/storyboarder
  - type: Download
    url: https://github.com/wonderunit/storyboarder/releases

desktop:
  Desktop Entry:
    Name: Storyboarder
    Comment: The fastest way to storyboard.
    Exec: AppRun
    Terminal: false
    Type: Application
    Icon: storyboarder
    StartupWMClass: Storyboarder
    X-AppImage-Version: 1.9.2
    MimeType: x-scheme-handler/storyboarder
    Categories: Graphics
    X-AppImage-BuildId: 1CQYpNKNAcDlL8rf49ngmoKvmcn
  AppImageHub:
    X-AppImage-Signature: no valid OpenPGP data found. the signature could not be verified.
      Please remember that the signature file (.sig or .asc) should be the first file
      given on the command line.
    X-AppImage-Type: 2
    X-AppImage-Architecture: x86_64

electron:
  description: The fastest way to storyboard.
  main: src/js/main.js
  repository:
    type: git
    url: git+https://github.com/wonderunit/storyboarder.git
  author: Wonder Unit Inc.
  dependencies:
    "@ffmpeg-installer/ffmpeg": 1.0.13
    ag-psd: "^1.2.0"
    alchemancy: github:wonderunit/alchemancy#v1.5.1
    archiver: 2.0.3
    caf: 7.0.4
    chokidar: 2.0.3
    color-js: "^1.0.4"
    eases: 1.0.8
    electron-google-analytics: 0.0.16
    electron-is-dev: 0.3.0
    electron-redux: 1.3.1
    electron-updater: 3.1.2
    electron-util: 0.4.1
    etch: 0.12.8
    execa: 0.8.0
    express: "^4.15.4"
    fraction.js: 4.0.3
    fs-extra: 4.0.2
    gifencoder: "^1.1.0"
    gl-vec2: "^1.0.0"
    jsfeat: 0.0.8
    jsonwebtoken: 8.1.1
    lodash.throttle: 4.1.1
    moment: 2.19.3
    node-fetch: 2.1.2
    node-machine-id: 1.1.10
    paper: 0.11.5
    pdfjs-dist: 2.0.550
    pdfkit: "^0.8.3"
    plist: 2.1.0
    promise-cancelable: 2.1.1
    qr-image: "^3.2.0"
    qrcode-reader: "^1.0.0"
    ramda: 0.25.0
    redux: 3.7.2
    redux-promise: 0.5.3
    redux-thunk: 2.2.0
    request: 2.83.0
    request-promise-native: 1.0.5
    socket.io: "^2.0.3"
    stats.js: 0.17.0
    tether: 1.4.0
    tether-tooltip: 1.2.0
    tmp: 0.0.33
    tonal: 0.69.9
    tone: 0.12.0
    trash: 4.0.1
    wav-encoder: 1.3.0
    xml2js: 0.4.19
---
