# BTCMZ Pluton Wallet

![Download Count](https://img.shields.io/github/downloads/bitcoinmono/bitcoinmono-wallet-pluton/total.svg?include_prereleases)
![Open Issue Count](https://img.shields.io/github/issues/bitcoinmono/bitcoinmono-wallet-pluton)
![License](https://img.shields.io/github/license/bitcoinmono/bitcoinmono-wallet-pluton)
![Version](https://img.shields.io/github/v/release/bitcoinmono/bitcoinmono-wallet-pluton?include_prereleases)

<img src="https://raw.githubusercontent.com/bitcoinmono/bitcoinmono-wallet-pluton/master/screenshots/screenshot-01.png">

<img src="https://raw.githubusercontent.com/bitcoinmono/bitcoinmono-wallet-pluton/master/screenshots/screenshot-02.png">

<img src="https://raw.githubusercontent.com/bitcoinmono/bitcoinmono-wallet-pluton/master/screenshots/screenshot-03.png">

Pluton Wallet is a WrkzCoin wallet forked from <a hreft="https://github.com/turtlecoin/turtle-wallet-proton">Proton</a> using:

- <a href="http://electron.atom.io/">Electron</a>
- <a href="https://facebook.github.io/react/">React</a>
- <a href="https://github.com/turtlecoin/turtlecoin-wallet-backend-js">Turtlecoin-Wallet-Backend-JS</a>
- <a href="https://github.com/reactjs/redux">Redux</a>
- <a href="https://github.com/reactjs/react-router">React Router</a>
- <a href="http://webpack.github.io/docs/">Webpack</a>
- and <a href="https://github.com/gaearon/react-hot-loader">React Hot Loader</a>.

<p>
  All of the code is released under the GPLv3 license. The icons in the ./resources and ./app/images folders from <a href="https://icons8.com/license">icons8.</a>
</p>

## Development Setup (All Platforms)

### Dependencies

#### You will need the following dependencies installed before you can proceed to the "Setup" step:

- Node.JS (Latest LTS version - 10.x) https://nodejs.org/

- Yarn https://yarnpkg.com/en/

- Git https://git-scm.com/downloads

Tip: If you already have a different version of node.js installed besides 10.x, try using [Node Version Manager](https://github.com/nvm-sh/nvm#install--update-script).

#### Setup

First, clone the repo via git:

```bash
git clone https://github.com/bitcoinmono/bitcoinmono-wallet-pluton.git
```

And then install the dependencies with yarn.

```bash
$ cd bitcoinmono-wallet-pluton
$ yarn
```

Run the wallet.

```bash
$ yarn start
```
*I found the default public node would refuse to sync, the developers have usefully detailed alternatives here - https://github.com/bitcoinmono/bitcoinmono-nodes-json


### Starting Development

Start the app in the `dev` environment. This starts the renderer process in [**hot-module-replacement**](https://webpack.js.org/guides/hmr-react/) mode and starts a webpack dev server that sends hot updates to the renderer process:

```bash
$ yarn dev
```

### Packaging

To package apps for the local platform:

```bash
$ yarn package
```

## License

© 2019-2020, [ExtraHash](https://github.com/ExtraHash)
© 2019-2020, [WrkzCoin](https://github.com/wrkzcoin/wrkz-wallet-pluton)
© 2020, [Bitcoinmono](https://github.com/bitcoinmono/bitcoinmono-wallet-pluton)
See included License file for more details.
