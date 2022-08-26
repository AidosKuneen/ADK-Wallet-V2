<h1 align="center">
  <br>
  <a href="https://aidoskuneen.com"><img src="https://aidoskuneen.com/wp-content/uploads/2020/08/cropped-adk-logo-footer-192x192.png" alt="Aidos Kuneen"></a>
  <br>
  Aidos Kuneen V2 Wallet
  <br>
</h1>

<h5 align="center">This repository contains the desktop wallet for Aidos Kuneen V2</h6>

<p align="center">
  <a href="https://raw.githubusercontent.com/AidosKuneen/ADK-V2-Wallet/master/LICENSE">
      <img src="https://img.shields.io/badge/license-GPLv3-blue.svg" alt="License">
  </a>
</p>

## Prebuilt binaries

If you want to just use the wallet app, please download [the latest release](https://github.com/AidosKuneen/ADK-V2-Wallet/releases) for your OS.

## Requirements

1. Operating System
   - Linux 64 bit (32bit not supported)
   - Windows 64bit and 32bit
   - MacOS 64bit (32bit not supported)
2. [NodeJS](https://nodejs.org/en/download/)

NodeJS is required to install and run the app.

## Build & Run

These instructions are only in case you want to build the wallet by yourself. Pre-built packages are available on [Release Page](https://github.com/AidosKuneen/ADK-V2-Wallet/releases).

1. Clone this repository:

```
git clone https://github.com/AidosKuneen/ADK-V2-Wallet
```

2. Install dependencies:

```
npm install
```

3. Run the app:

```
npm start
```


If you'd like to create a package only for a specific OS, you can do so by running:

```
npm run package
```

5.  After that you can find the compiled binaries in the `out` dir.

## [Changelog](https://github.com/AidosKuneen/ADK-V2-Wallet/blob/master/changelog.md)

## LICENSE

[GNU General Public License v3.0](https://github.com/AidosKuneen/ADK-V2-Wallet/blob/master/LICENSE)
