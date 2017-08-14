<p align="center">
  <a href="https://ncarb.github.io/bootstrap">
    <img src="http://v4-alpha.getbootstrap.com/assets/brand/bootstrap-solid.svg" width=72 height=72>
  </a>

  <h3 align="center">NCARB Bootstrap</h3>

  <p align="center">
    Bootstrap with NCARB Styles
    <br>
    <a href="https://ncarb.github.io/bootstrap"><strong>Explore Bootstrap docs &raquo;</strong></a>
    <br>
    <br>
    <a href="https://themes.getbootstrap.com">Bootstrap Themes</a>
  </p>
</p>

<br>

## Table of contents

- [Quick start](#quick-start)
- [NCARB notes](#ncarb-notes)
- [Status](#status)
- [What's included](#whats-included)
- [Bugs and feature requests](#bugs-and-feature-requests)
- [Documentation](#documentation)
- [Contributing](#contributing)
- [Community](#community)
- [Versioning](#versioning)
- [Creators](#creators)
- [Copyright and license](#copyright-and-license)

## Quick start

Several quick start options are available:

- Clone the repo: `git clone https://github.com/ncarb/bootstrap.git`
- Install with [npm](https://www.npmjs.com): `npm install ncarb-bootstrap`
- Install with [yarn](https://github.com/yarnpkg/yarn): `yarn add ncarb-bootstrap`
- Install with [Bower](https://bower.io): `bower install ncarb-bootstrap'
- Install with NCARB&#8217;s [NuGet](https://www.nuget.org): CSS: `Install-Package ncarb-bootstrap` Sass: `Install-Package ncarb-bootstrap.sass`

Read the [Getting started page](https://ncarb.github.io/bootstrap/getting-started/) for information on the framework contents, templates and examples, and more.


## NCARB notes

Focus is on an `ncarb-bootstrap` stylesheet that cascades over `bootstrap`.

While we compile `bootstrap`, it&#8217;s for convenience; we depend on the seperate bootstrap package.

### Scripts

Use `npm run` to execute npm scripts found in `package.json`

Notable scripts:
- `npm run docs-serve`: runs http://localhost:9001
- `npm run watch-css`: rebuilds css on sass changes
- `npm run docs-push`: updates docs by pushing latest docs up to gh-pages branch
- `npm run release-version old new`: updates version everywhere

### Keeping up with Bootstrap

We plan to occasionally merge bootstrap updates into this repository.

## Status

[![Bower](https://img.shields.io/bower/v/bootstrap.svg)](https://bower.io/search/?q=ncarb-bootstrap)
[![npm version](https://img.shields.io/npm/v/bootstrap.svg)](https://www.npmjs.com/package/ncarb-bootstrap)
[![peerDependencies Status](https://david-dm.org/ncarb/bootstrap/peer-status.svg)](https://david-dm.org/ncarb/bootstrap?type=peer)
[![devDependency Status](https://img.shields.io/david/dev/ncarb/bootstrap.svg)](https://david-dm.org/ncarb/bootstrap?type=dev)

## What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
bootstrap/
├── css/
│   ├── bootstrap.css
│   ├── bootstrap.css.map
│   ├── bootstrap.min.css
│   ├── bootstrap.min.css.map
│   ├── ncarb-bootstrap.min.css
│   └── ncarb-bootstrap.min.css.map
└── js/
    ├── bootstrap.js
    └── bootstrap.min.js
```

We provide compiled CSS and JS (`bootstrap.*`, `ncarb-bootstrap.*`), as well as compiled and minified CSS and JS (`bootstrap.min.*`, `ncarb-bootstrap.*`). CSS [source maps](https://developers.google.com/web/tools/chrome-devtools/debug/readability/source-maps) (`bootstrap.*.map`, `ncarb-bootstrap.*.map`) are available for use with certain browsers' developer tools.


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/ncarb/bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/ncarb/bootstrap/issues/new).


## Documentation

Bootstrap's documentation, included in this repo in the root directory, is built with [Jekyll](https://jekyllrb.com) and publicly hosted on GitHub Pages at <https://getbootstrap.com>. The docs may also be run locally.

Documentation search is powered by [Algolia's DocSearch](https://community.algolia.com/docsearch/). Working on our search? Be sure to set `debug: true` in the `_scripts.html` include.

### Running documentation locally

1. Run through the [tooling setup](https://github.com/ncarb/bootstrap/blob/v4-dev/docs/4.0/getting-started/build-tools.md#tooling-setup) to install Jekyll (the site builder) and other Ruby dependencies with `bundle install`.
2. Run `npm run test` (or a specific NPM script) to rebuild distributed CSS and JavaScript files, as well as our docs assets.
3. From the root `/bootstrap` directory, run `bundle exec jekyll serve` in the command line.
4. Open <http://localhost:9001> in your browser, and voilà.

Learn more about using Jekyll by reading its [documentation](https://jekyllrb.com/docs/home/).

### Documentation for previous releases

Documentation for v2.3.2 has been made available for the time being at <https://getbootstrap.com/2.3.2/> while folks transition to Bootstrap 3.

[Previous releases](https://github.com/twbs/bootstrap/releases) and their documentation are also available for download.


## Contributing

Please read through our [contributing guidelines](https://github.com/twbs/bootstrap/blob/master/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/twbs/bootstrap/tree/master/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/twbs/bootstrap/blob/master/.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, Bootstrap is maintained under [the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw up, but we'll adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/twbs/bootstrap/releases) for changelogs for each release version of Bootstrap. Release announcement posts on [the official Bootstrap blog](https://blog.getbootstrap.com) contain summaries of the most noteworthy changes made in each release.


## Creators

**Mark Otto**

- <https://twitter.com/mdo>
- <https://github.com/mdo>

**Jacob Thornton**

- <https://twitter.com/fat>
- <https://github.com/fat>



## Copyright and license

Code and documentation copyright 2011-2017 the [Bootstrap Authors](https://github.com/twbs/bootstrap/graphs/contributors) and [Twitter, Inc.](https://twitter.com) Code released under the [MIT License](https://github.com/twbs/bootstrap/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/twbs/bootstrap/blob/master/docs/LICENSE).
