<p align="center">
<img alt="Logo Banner" src="https://raw.githubusercontent.com/masejs/masejs/main/banner/banner.svg?sanitize=true"/>
<br/>

![Forks](https://img.shields.io/github/forks/masejs/masejs.svg?style=flat)
![Stars](https://img.shields.io/github/stars/masejs/masejs.svg?style=flat)
![License](https://img.shields.io/badge/license-MIT-green)
[![Donate on Kofi](https://img.shields.io/badge/Donate-Kofi-F16061?logo=ko-fi&logoColor=white)](https://ko-fi.com/brick_wall)
<a href="https://discord.gg/Mbtnv9BN">
  <img src="https://img.shields.io/badge/discord-join-7289DA.svg?logo=discord&longCache=true&style=flat" />
</a>

<div align="left">A list of websites / projects built using masejs.</div>
<div align="left">

<!--[Documentation](https://paperui.com/)-->
<!--[Discord](https://discord.gg/Mbtnv9BN)-->

</div>

## Installation

### CDN

Import Mase JS using CDN.

```js
import { MaseJSInterpreter } from 'https://cdn.jsdelivr.net/npm/masejs';
```

#### 🚧 Specific Version
```js
import { MaseJSInterpreter } from 'https://cdn.jsdelivr.net/npm/masejs@latest';
```

<!--#### 🚧 Development
```html
<script type="module" src="https://cdn.jsdelivr.net/npm/paperjs@latest"></script>
```-->

### NPM

Install Mase JS using [npm and node](https://nodejs.org/en).

```bash
npm install masejs
```

## Import

Import Mase JS definitions from ```MaseJSInterpreter```.

```index.js```

```js
import { MaseJSInterpreter } from 'masejs';

MaseJSInterpreter.interpret(masejs);
```

## Usage

Use the tree structure in your Javascript. <!--Refer to the [Documentation](https://paperui.com) for more guidance on using the library.-->That's it 🎉.

```script.js```

```js
import { MaseJSInterpreter } from 'https://cdn.jsdelivr.net/npm/masejs@latest';

const masejs = {
  div: {
    class: 'button-container',
    styles: {
      height: '100%',
      width: '100%',
      'align-items': 'center',
      display: 'flex',
      'justify-content': 'center',
      inset: '0px',
      position: 'fixed',
    },
    button: [
      {
        value: 'Click me',
        styles: {
          color: 'white',
          'background-color': '#000000',
          outline: 'none',
          border: 'none',
          height: '38px',
          width: '88px',
          'border-radius': '5px'
        },
        class: 'button',
        id: 'button',
        events: {
          click: () => alert('Button clicked!')
        },
      }
    ]
  }
};

MaseJSInterpreter.interpret(masejs);
```

## Examples

* A basic form with [MaseJS](https://codepen.io/GreenestGoat/pen/zYQEjML).

* A simple sidebar with [MaseJS](https://codepen.io/GreenestGoat/pen/qBGVxbv).

* Using the library with [Material UI](https://codepen.io/GreenestGoat/pen/GRaMLXR?editors=1010).

<!--## Backers

Thank you to all our backers! 🙏.

[![Backers](https://opencollective.com/bootstrap/backers.svg?width=890)](https://opencollective.com/bootstrap#backers)-->


## Copyright and license

Licensed under the MIT License, Copyright © 2024-present masejs.

See [LICENSE](https://github.com/masejs/masejs/blob/main/LICENSE) for more information.
