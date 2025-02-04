# UIKit Arpyia :)

Para adicionar novos ícones, adicione seu **svg** no diretório `custom/icons`, como exemplo abaixo:

```svg
<svg width="20" height="20" viewBox="0 0 24 24">
    <path fill="currentColor" d="M13 14H11V9H13M13 18H11V16H13M1 21H23L12 2L1 21Z" />
</svg>
```

> Matenha o **width**, **height** e **viewBox** como no exemplo acima

Após adicionar, execute o comando `npm run compile` (tenha certeza de ter executado `npm i` antes).

O output será gerado no diretório `dist`. Os arquivos que precisam ser copiados são:

- css/uikit.min.css
- js/uikit.min.js
- js/uikit-icons.min.js

> Fontes de ícones: [Google Icons](https://fonts.google.com/icons); [Material Icons](https://materialdesignicons.com); [Tabler Icons](https://tabler-icons.io);

---

[![uikit banner](https://cloud.githubusercontent.com/assets/321047/21769911/474d7d9e-d681-11e6-9fe0-d95f8ccfd3a9.jpg)](https://getuikit.com/)

# UIkit

[![Discord](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/NEt4Pv7)

UIkit is a lightweight and modular front-end framework for developing fast and powerful web interfaces.

* [Homepage](https://getuikit.com) - Learn more about UIkit
* [@getuikit](https://twitter.com/getuikit) - Get the latest buzz on Twitter
* [Discord Chat](https://discord.gg/NEt4Pv7) - Join our developer chat on Discord.

---

<p align="center">
  <b>UIkit is an Open Source project developed by YOOtheme.</b>
  <br><br>
  <a href="https://yootheme.com" align="center">
      <img width="134" height="30" src="https://yootheme.com/site/images/yootheme-logo.svg" alt="YOOtheme">
  </a>
</p>

---

## Getting started

You have the following options to get UIkit:

- Download the [latest release](https://github.com/uikit/uikit/releases/latest) with pre-built CSS and JS.
- Install with [npm](https://npmjs.com) to get all source files as they are available on GitHub: ```npm install uikit```
- Install with [yarn](https://yarnpkg.com/) to get all source files as they are available on GitHub: ```yarn add uikit```
- Directly load UIkit from [jsDelivr](https://www.jsdelivr.com): https://www.jsdelivr.com/package/npm/uikit
- Clone the repo to get all source files including build scripts: `git clone git://github.com/uikit/uikit.git`

## Developers

To always have the latest development version of UIkit, even before a release, you may want to use npm or yarn with the `dev` tag.

- Using npm: ```npm install uikit@dev```
- Using yarn: ```yarn add uikit@dev```
- Using [cdn](cdn.jsdelivr.net): https://cdn.jsdelivr.net/npm/uikit@dev

## Contributing

Finding bugs, sending pull requests or improving our docs - any contribution is welcome and highly appreciated. To get started, head over to our [contribution guidelines](CONTRIBUTING.md). Thanks!

## Versioning

UIkit is maintained by using the [Semantic Versioning Specification (SemVer)](http://semver.org).

## Browser Support

![Chrome](https://raw.github.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png) | ![Firefox](https://raw.github.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png) | ![Edge](https://raw.github.com/alrra/browser-logos/master/src/edge/edge_48x48.png) | ![IE](https://raw.github.com/alrra/browser-logos/master/src/archive/internet-explorer_9-11/internet-explorer_9-11_48x48.png) | ![Safari](https://raw.github.com/alrra/browser-logos/master/src/safari/safari_48x48.png) | ![Opera](https://raw.github.com/alrra/browser-logos/master/src/opera/opera_48x48.png)
--- | --- | --- | --- | --- | --- |
Latest ✔ | Latest ✔ | Latest ✔ | 11+ ✔ | 9.1+ ✔ | Latest ✔ |

Tested With<br>[![BrowserStack](https://user-images.githubusercontent.com/355427/27389060-9f716c82-569d-11e7-923c-bd5fe7f1c55a.png)](https://www.browserstack.com)

## Copyright and License

Copyright [YOOtheme](https://yootheme.com) GmbH under the [MIT license](LICENSE.md).
