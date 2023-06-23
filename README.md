# OpenJournal

A minimal, typography-heavy newsletter [Ghost](https://github.com/TryGhost/Ghost) theme fork of [Journal](https://github.com/TryGhost/Journal).

**Demo: [https://journal.ghost.io](https://journal.ghost.io)**

---

## Translation

> This repo will be updated with non-native translations for searchbar and some other spots not accessible by theme by default

This fork provides translation support for Journal theme via Ghost's locale files.

To create a custom translation:
1) Make a copy of `en.json` in `locales/`
2) Name it like your country code (Ex: `de.json`, `es.json`)
3) Translate it
4) Zip it and upload to your website
5) Set corresponding country code in Ghost settings
6) (Optional) Make pull request to this repository to add your language (appreciated)

# Instructions

1. [Download this theme](https://github.com/m41denx/Journal/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Edition styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/journal.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Contribution

This repo is synced automatically with [TryGhost/Themes](https://github.com/TryGhost/Themes) monorepo. If you're looking to contribute or raise an issue, head over to the main repository [TryGhost/Themes](https://github.com/TryGhost/Themes) where our official themes are developed.

# Copyright & License

### Ghost Blog Software and Journal Theme:
Copyright (c) 2013-2023 [Ghost Foundation](https://ghost.org) - Released under the [MIT license](LICENSE).

### Translation engine and languages [English, Russian]:
Copyleft (🐱) 2023 [M41den](https://github.com/m41denx)

### Other languages
- No one contributed yet
