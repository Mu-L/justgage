# JustGage

<p align="center"><img src="docs/public/logo.png"/></p>

[![NPM Version](https://img.shields.io/npm/v/justgage.svg)](https://www.npmjs.com/package/justgage)
[![Downloads](https://img.shields.io/npm/dm/justgage.svg)](https://www.npmjs.com/package/justgage)
[![Bundle Size](https://img.shields.io/bundlephobia/minzip/justgage.svg)](https://bundlephobia.com/package/justgage)

[![Deploy Docs](https://github.com/toorshia/justgage/actions/workflows/deploy-docs.yml/badge.svg)](https://github.com/toorshia/justgage/actions/workflows/deploy-docs.yml)
[![Tests](https://img.shields.io/github/actions/workflow/status/toorshia/justgage/build.yml?label=tests)](https://github.com/toorshia/justgage/actions/workflows/ci.yml)

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![MIT Licence](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/mit-license.php)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

Modern ES6+ JavaScript library for creating animated dashboard gauges using native SVG APIs

<p align="center">
  ⚡ **Zero Dependencies** •
  💖 **Modern ES6+** •
  🎛️ **Highly Customizable** •
  📱 **Responsive Design** •
  🚀 **High Performance** •
  🛡️ **Battle Tested**
</p>

<p align="center">
  🎮 **[Try Live Demo & Playground](https://toorshia.github.io/justgage)** •
  📚 **[Full Documentation](https://toorshia.github.io/justgage/docs)**
</p>

## Quick Start

### Installation

```bash
npm install justgage
```

### Basic Usage

```javascript
import { JustGage } from 'justgage';

const gauge = new JustGage({
  id: 'my-gauge',
  value: 75,
  min: 0,
  max: 100,
});
```

## More Information

- 📖 **[Complete Documentation](https://toorshia.github.io/justgage/docs)** - API reference, configuration options, and examples
- 🎮 **[Interactive Playground](https://toorshia.github.io/justgage/playground)** - Try different configurations live
- 🚀 **[Migration Guide](https://toorshia.github.io/justgage/docs#migration)** - Upgrading from v1.x to v2.0+
- 🤝 **[Contributing](CONTRIBUTING.md)** - Development setup and contribution guidelines

## License

This project is licensed under [MIT](LICENSE) License

## Author & Maintainers

- **Original Author**: [Bojan Djuricic](https://github.com/toorshia)
- **v2.0 Modernization & Maintenance**: [Daniel Sorridi (robertsLando)](https://github.com/robertsLando)
