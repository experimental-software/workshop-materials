# Workshop Materials

This repository contains a [Hugo](https://gohugo.io) theme for supporting materials for IT training workshops.

## Dependencies

The following tools need to be installed start using this theme:

- [Hugo](https://gohugo.io/getting-started/quick-start/)
- [git](https://git-scm.com/downloads)

## Content authoring

### Presentation

Run the following command at the root of your own repository to create a new presentation in Hugo's `content` directory:

```
hugo new --kind presentation ${TOPIC}/${NAME}
```

### Tutorial

Run the following command at the root of your own repository to create a new presentation in Hugo's `content` directory:

```
hugo new --kind tutorial2 ${TOPIC}/${NAME}
```

## Credits

- The layout of the start page and the subject list pages is applied from a Bootstrap template by [Xiaoying Riley](https://themes.3rdwavemedia.com/) which is licensed under Creative Commons Attribution 3.0 License.
- The layout of the tutorial pages is inspired by [Google Codelabs](https://github.com/googlecodelabs/tools).
- The presentations are based on [RevealJS](https://revealjs.com/) which is licensed under the [MIT license](https://github.com/hakimel/reveal.js/blob/master/LICENSE).

## License

[MIT](./LICENSE)
