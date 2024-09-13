# ojus

[![npm version](https://img.shields.io/npm/v/ojus.svg)](https://www.npmjs.com/package/ojus)
[![npm downloads](https://img.shields.io/npm/dm/ojus.svg)](https://www.npmjs.com/package/ojus)
[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

**Lightweight, modular Node.js framework for quick API scaffolding**

## Table of contents

* [Installation](#installation)
* [Features](#features)
* [Quick Start](#quick-start)
* [Project Structure](#project-structure)
* [CLI Commands](#cli-commands)
* [Core Dependencies](#core-dependencies)
* [Contributing](#contributing)
* [Author](#author)
* [License](#license)

```js
const ojus = require('ojus')
const app = ojus()

app.get('/', function (req, res) {
  res.send('Hello World')
})

app.listen(3000)