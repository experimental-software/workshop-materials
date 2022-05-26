# Workshop Materials

The Workshop Materials project provides a simplistic tool for the creation of a website hosting presentations and tutorials for IT workshops.

## Unique value proposition

- The workshop materials are presented in a way which effectively supports the learners (hopefully).
- The workshop materials can be edited with minimal overhead; the tutorials with Markdown and the presentations with HTML.
- The website renderer is maximum easy and robust to install.

## Dependencies

The following tools need to be installed before you can start using the tool:

- [Hugo](https://gohugo.io/getting-started/quick-start/)
- [git](https://git-scm.com/downloads)

## Getting started

To create new workshop materials, you can use the [Workshop Materials template](https://github.com/experimental-software/workshop-materials-template):

```
PROJECT_NAME=your-project-here
{
git clone --recurse \
  https://github.com/experimental-software/workshop-materials-template.git \
  $PROJECT_NAME

cd $PROJECT_NAME
git submodule update --remote
git remote remove origin
}

DEFAULT_BRANCH=main
{
git checkout --orphan $DEFAULT_BRANCH
git add .
git commit -m "Initial commit"
}
```

Afterwards, refer to the README file of the new project, for hints what should be done next.

## Development

This section contains hints for working on the Workshop Materials theme.

### Internationalization

The keys for the localizations can be found here: [`i18n/`](./i18n)

In the templates the localizations can be included like this:

```
{{ i18n "tutorial.back" }}
```

## Credits

- The layout of the start page and the subject list pages is applied from a Bootstrap template by [Xiaoying Riley](https://themes.3rdwavemedia.com/) which is licensed under Creative Commons Attribution 3.0 License.
- The layout of the tutorial pages is inspired by [Google Codelabs](https://github.com/googlecodelabs/tools).
- The presentations are based on [RevealJS](https://revealjs.com/) which is licensed under the [MIT license](https://github.com/hakimel/reveal.js/blob/master/LICENSE).
- At various places of the website [Font Awesome](https://fontawesome.com/) icons are used.
- For zooming in images in tutorials, the [medium-zoom](https://github.com/francoischalifour/medium-zoom) library from François Chalifour is being used. See [license](./3rd-party/LICENSE_MEDIUM_ZOOM).
- The theme uses [Google Fonts](https://fonts.google.com/attribution), self-hosted with the help of [google-webfonts-helper](https://github.com/majodev/google-webfonts-helper/).

## License

[MIT](./LICENSE)
