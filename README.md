# Workshop Materials

The goal of the Workshop Materials project is to provide a simplistic tool for the creation of presentations and tutorials.

## Dependencies

The following tools need to be installed before you can start using the tool:

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
git submodule update --remote
git remote remove origin

DEFAULT_BRANCH=main
git checkout --orphan $DEFAULT_BRANCH
git add .
git commit -m "Initial commit"
```

For further instructions on how to use the template, please refer to the [project web site](https://experimental-software.github.io/workshop-materials).

## Development

### Internationalization

The keys for the localizations can be found here: [`i18n/`](./i18n)

In the templates the localizations can be included like this:

```
{{ i18n "tutorial.back" }}
```

## Maintenance

### Include changes

After changes has been made in this repository, do the following steps to apply those changes in a workshop repository:

```bash
{
git submodule update --remote
git add .
git commit -m "Update theme"
}

git push 
```

## Credits

- The layout of the start page and the subject list pages is applied from a Bootstrap template by [Xiaoying Riley](https://themes.3rdwavemedia.com/) which is licensed under Creative Commons Attribution 3.0 License.
- The layout of the tutorial pages is inspired by [Google Codelabs](https://github.com/googlecodelabs/tools).
- The presentations are based on [RevealJS](https://revealjs.com/) which is licensed under the [MIT license](https://github.com/hakimel/reveal.js/blob/master/LICENSE).
- At various places of the website [Font Awesome](https://fontawesome.com/) icons are used.
- For zooming in images in tutorials, the [medium-zoom](https://github.com/francoischalifour/medium-zoom) library from François Chalifour is being used. See [license](./3rd-party/LICENSE_MEDIUM_ZOOM).

## License

[MIT](./LICENSE)
