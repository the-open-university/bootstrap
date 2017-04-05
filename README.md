# [OU ICE](http://the-open-university.github.io/ouice)

OU ICE is a set of design patterns, components and templates so we can provide our students with a consistent user experience.

It is a part of the same family of work as the design used for the OU public website but is more tailored to the requirements of our students and their study journey. This is the fourth version of the framework (v4). It is an evolution from the previous versions of the OU ICE framework but is mostly backwards-compatible.

To get started, check out <http://the-open-university.github.io/ouice/>!


## Table of contents

* [Quick start](#quick-start)
* [Bugs and feature requests](#bugs-and-feature-requests)
* [Documentation](#documentation)
* [Contributing](#contributing)
* [Community](#community)
* [Versioning](#versioning)
* [Creators](#creators)
* [Copyright and license](#copyright-and-license)


## Quick start

Several quick start options are available:

* [Download the latest release](https://github.com/the-open-university/ouice-bootstrap/archive/v3-dev.zip).
* Clone the repo: `git clone https://github.com/the-open-university/ouice-bootstrap.git`.
* Install with [Bower](http://bower.io): (coming soon).
* Install with [npm](https://www.npmjs.com): (coming soon).
* Install with [Meteor](https://www.meteor.com): (coming soon).
* Install with [Composer](https://getcomposer.org): (coming soon).

Read the [Getting started page](http://the-open-university.github.io/ouice/getting-started.html) for information on the framework contents, templates and examples, and more.

### What's included

Within the download you'll find the following directories and files, logically grouping common assets and providing both compiled and minified variations. You'll see something like this:

```
ouice/
├── css/
│   ├── ouice.css
│   ├── ouice.css.map
│   ├── ouice.min.css
│   ├── ouice.min.css.map
├── js/
│   ├── ouice.js
│   └── ouice.min.js
└── fonts/
    ├── glyphicons-halflings-regular.eot
    ├── glyphicons-halflings-regular.svg
    ├── glyphicons-halflings-regular.ttf
    ├── glyphicons-halflings-regular.woff
    └── glyphicons-halflings-regular.woff2
```

We provide compiled CSS and JS (`ouice.*`), as well as compiled and minified CSS and JS (`ouice.min.*`). CSS [source maps](https://developer.chrome.com/devtools/docs/css-preprocessors) (`ouice.*.map`) are available for use with certain browsers' developer tools. Fonts from Glyphicons are included.


## Bugs and feature requests

Have a bug or a feature request? Please first read the [issue guidelines](https://github.com/the-open-university/ouice-bootstrap/blob/master/CONTRIBUTING.md#using-the-issue-tracker) and search for existing and closed issues. If your problem or idea is not addressed yet, [please open a new issue](https://github.com/the-open-university/ouice-bootstrap/issues/new).


## Documentation

OU ICE's documentation, included in this repo in the root directory, is built with [Jekyll](http://jekyllrb.com) and publicly hosted on GitHub Pages at <http://the-open-university.github.io/ouice>. The docs may also be run locally.

### Running documentation locally

1. If necessary, [install Jekyll](http://jekyllrb.com/docs/installation) and other Ruby dependencies with `bundle install`.
   **Note for Windows users:** Read [this unofficial guide](http://jekyll-windows.juthilo.com/) to get Jekyll up and running without problems.
2. From the root `/ouice` directory, run `bundle exec jekyll serve` in the command line.
4. Open `http://localhost:9001` in your browser, and voilà.

Learn more about using Jekyll by reading its [documentation](http://jekyllrb.com/docs/home/).


## Contributing

Please read through our [contributing guidelines](https://github.com/the-open-university/ouice-bootstrap/blob/master/CONTRIBUTING.md). Included are directions for opening issues, coding standards, and notes on development.

Moreover, if your pull request contains JavaScript patches or features, you must include [relevant unit tests](https://github.com/the-open-university/ouice-bootstrap/tree/master/js/tests). All HTML and CSS should conform to the [Code Guide](https://github.com/mdo/code-guide), maintained by [Mark Otto](https://github.com/mdo).

Editor preferences are available in the [editor config](https://github.com/the-open-university/ouice-bootstrap/blob/master/.editorconfig) for easy use in common text editors. Read more and download plugins at <http://editorconfig.org>.


## Versioning

For transparency into our release cycle and in striving to maintain backward compatibility, OU ICE is maintained under [the Semantic Versioning guidelines](http://semver.org/). Sometimes we screw up, but we'll adhere to those rules whenever possible.

See [the Releases section of our GitHub project](https://github.com/the-open-university/ouice-bootstrap/releases) for changelogs for each release version of OU ICE.


## Copyright and license

Code and documentation copyright 2011-2016 Twitter, Inc. Code released under [the MIT license](https://github.com/twbs/bootstrap/blob/master/LICENSE). Docs released under [Creative Commons](https://github.com/twbs/bootstrap/blob/master/docs/LICENSE).
