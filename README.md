# PakhshKit JS Cast Sender

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

PakhshKit JS Cast Sender integrates the [Cast Chrome Sender Framework API] with the [Vidiun Player JS].

PakhshKit JS Cast Sender uses the _Remote Framework_ of the [Vidiun Player JS] to implement the neccesary APIs to control the player while casting.

PakhshKit JS Cast Sender is written in [ECMAScript6], statically analysed using [Flow] and transpiled in ECMAScript5 using [Babel].

[cast chrome sender framework api]: https://developers.google.com/cast/docs/chrome_sender_setup
[vidiun player js]: https://github.com/vidiun/vidiun-player-js
[flow]: https://flow.org/
[ecmascript6]: https://github.com/ericdouglas/ES6-Learning#articles--tutorials
[babel]: https://babeljs.io

## Getting Started

### Installing

First, clone and run [yarn] to install dependencies:

[yarn]: https://yarnpkg.com/lang/en/

```
git clone https://github.com/vidiun/pakhshkit-js-cast-sender.git
cd pakhshkit-js-cast-sender
yarn install
```

### Building

Then, build the sender

```javascript
yarn run build
```

## Documentation

- [**Configuration & API**](docs/api.md)

## Compatibility

TBD

## Contributing

Please read [CONTRIBUTING.md](https://github.com/vidiun/platform-install-packages/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/vidiun/pakhshkit-js-providers/tags).

## License

This project is licensed under the AGPL-3.0 License - see the [LICENSE](LICENSE) file for details
