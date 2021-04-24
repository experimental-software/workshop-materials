# Workshop Materials

This repository contains a [Hugo](https://gohugo.io) theme for supporting materials for IT training workshops.

## Dependencies

The following tools need to be installed start using this theme:

- [Hugo](https://gohugo.io/getting-started/quick-start/)
- [git](https://git-scm.com/downloads)

## Getting started

To create new workshop materials, you can use the [Workshop Materials template](https://github.com/experimental-software/workshop-materials-template):

```
PROJECT_NAME=your-project-here
git clone --recurse \
  git@github.com:experimental-software/workshop-materials-template.git \
  $PROJECT_NAME
  
cd $PROJECT_NAME
git checkout --orphan master
git add .
git commit -m "Initial commit"
```

For further instructions on how to use the template, please refer to its [README](https://github.com/experimental-software/workshop-materials-template/blob/master/README.md) file.


## Credits

- The layout of the start page and the subject list pages is applied from a Bootstrap template by [Xiaoying Riley](https://themes.3rdwavemedia.com/) which is licensed under Creative Commons Attribution 3.0 License.
- The layout of the tutorial pages is inspired by [Google Codelabs](https://github.com/googlecodelabs/tools).
- The presentations are based on [RevealJS](https://revealjs.com/) which is licensed under the [MIT license](https://github.com/hakimel/reveal.js/blob/master/LICENSE).
- At various places of the website [Font Awesome](https://fontawesome.com/) icons are used.

## License

[MIT](./LICENSE)
