# Insomnia REST Client 

[![Insomnia REST Client](https://img.shields.io/badge/maintainer-Insomnia-purple.svg?colorB=6e60cc)](https://insomnia.rest)
[![Build status](https://ci.appveyor.com/api/projects/status/pj03skhct2p1sved/branch/master?svg=true)](https://ci.appveyor.com/project/gschier/insomnia/branch/master)
[![license](https://img.shields.io/github/license/getinsomnia/insomnia.svg)]()

Insomnia is a cross-platform _REST client_, built on top of [Electron](http://electron.atom.io/).

![Insomnia REST Client Screenshot](https://insomnia.rest/images/docs/promo.png)

## Bugs and Feature Requests

Have a bug or a feature request? Please first read the 
[issue guidelines](CONTRIBUTING.md#using-the-issue-tracker) and search for existing and 
closed issues. If your problem or idea is not addressed yet, [please open a new issue](/issues).

## Contributing

Please read through our [contributing guidelines](CONTRIBUTING.md). Included are directions 
for opening issues, coding standards, and notes on development.

More over, if your pull request contains JavaScript patches or features, you must 
include relevant unit tests.

Editor preferences are available in the [editor config](.editorconfig) for easy use in 
common text editors. Read more and download plugins at <http://editorconfig.org>.

## Developing

Development on Insomnia can be done on Windows, Mac, and Linux with few requirements and only
requires [NodeJS 7.4](https://nodejs.org) and [Git](https://git-scm.com/) to get started.

```bash
# Install dependencies and build addons for Electron
npm install
npm run rebuild

# Start app
npm run dev

# Run tests
npm test
```

## License

[GNU AGPLv3](LICENSE) &copy; [Insomnia](https://insomnia.rest)
