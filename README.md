# Fork Awesome
### A fork of the iconic font and CSS toolkit

Fork Awesome is a full suite of 677 pictographic icons for easy scalable vector graphics on websites, originally created by [Dave Gandy](https://twitter.com/davegandy) and now maintained by a community.

Following concerns regarding [the development of Font Awesome](https://github.com/FortAwesome/Font-Awesome/issues/12199#issuecomment-362919956), the PR Freeze since Oct 2016 and the direction Fort Awesome is taking with the version 5.0 of their project, we are forking Font Awesome (4.7), in order to build on this incredible tool Dave Gandy has given us, while at the same time allowing this project to be run by a distributed community of contributors.

A tremendous gratitude is given to the whole team behind [Font Awesome](https://fontawesome.io), and you are encouraged to support them and buy Font Awesome Pro for your project.

This fork is still in its very early stage of development. Though If you wish to be part of the adventure, please start submitting patches.

## License
- The Font Awesome font is licensed under the SIL OFL 1.1:
  - http://scripts.sil.org/OFL
- Font Awesome CSS, LESS, and Sass files are licensed under the MIT License:
  - https://opensource.org/licenses/mit-license.html
- The Font Awesome documentation is licensed under the CC BY 3.0 License:
  - https://creativecommons.org/licenses/by/3.0/

## Changelog
- [v4.7.0 GitHub pull request](https://github.com/FortAwesome/Font-Awesome/pull/10012)
- [v4.6.3 GitHub pull request](https://github.com/FortAwesome/Font-Awesome/pull/9189)
- [v4.6.2 GitHub pull request](https://github.com/FortAwesome/Font-Awesome/pull/9117)
- [v4.6.1 GitHub pull request](https://github.com/FortAwesome/Font-Awesome/pull/8962)
- [v4.6.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?q=milestone%3A4.6.0+is%3Aclosed)
- [v4.5.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?q=milestone%3A4.5.0+is%3Aclosed)
- [v4.4.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?q=milestone%3A4.4.0+is%3Aclosed)
- [v4.3.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?q=milestone%3A4.3.0+is%3Aclosed)
- [v4.2.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=12&page=1&state=closed)
- [v4.1.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=6&page=1&state=closed)
- [v4.0.3 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=9&page=1&state=closed)
- [v4.0.2 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=8&page=1&state=closed)
- [v4.0.1 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=7&page=1&state=closed)
- [v4.0.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=2&page=1&state=closed)
- [v3.2.1 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=5&page=1&state=closed)
- [v3.2.0 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=3&page=1&state=closed)
- [v3.1.1 GitHub milestones](https://github.com/FortAwesome/Font-Awesome/issues?milestone=4&page=1&state=closed)
- v3.1.0 - Added 54 icons, icon stacking styles, flipping and rotating icons, removed Sass support
- v3.0.2 - much improved rendering and alignment in IE7
- v3.0.1 - much improved rendering in webkit, various bug fixes
- v3.0.0 - all icons redesigned from scratch, optimized for Bootstrap's 14px default

## Contributing

Please read through our [contributing guidelines](https://github.com/ForkAwesome/Fork-Awesome/blob/master/CONTRIBUTING.md).
Included are directions for opening issues, coding standards, and notes on development.

## Versioning

Fork Awesome will be maintained under the Semantic Versioning guidelines as much as possible. Releases will be numbered
with the following format:

`<major>.<minor>.<patch>`

And constructed with the following guidelines:

* Breaking backward compatibility bumps the major (and resets the minor and patch)
* New additions, including new icons, without breaking backward compatibility bumps the minor (and resets the patch)
* Bug fixes, changes to brand logos, and misc changes bumps the patch
* The fork is based on FontAwesome 4.7 and renamed. So it starts at version 0.4.7

For more information on SemVer, please visit http://semver.org.

## Original authors ot Font Awesome:
- Email: dave@fontawesome.io
- Twitter: http://twitter.com/davegandy
- GitHub: https://github.com/davegandy

## Component
To include as a [component](https://github.com/componentjs/component), just run

    $ component install ForkAwesome/Fork-Awesome

Or add

    "ForkAwesome/Fork-Awesome": "*"

to the `dependencies` in your `component.json`.

## Hacking on Font Awesome

**Before you can build the project**, you must first have the following installed:

- [Ruby](https://www.ruby-lang.org/en/)
- Ruby Development Headers
  - **Ubuntu:** `sudo apt-get install ruby-dev` *(Only if you're __NOT__ using `rbenv` or `rvm`)*
  - **Windows:** [DevKit](http://rubyinstaller.org/)
- [Bundler](http://bundler.io/) (Run `gem install bundler` to install).
- [Node Package Manager (AKA NPM)](https://docs.npmjs.com/getting-started/installing-node)
- [Less](http://lesscss.org/) (Run `npm install -g less` to install).
- [Less Plugin: Clean CSS](https://github.com/less/less-plugin-clean-css) (Run `npm install -g less-plugin-clean-css` to install).

From the root of the repository, install the tools used to develop.

    $ bundle install
    $ npm install

Build the project and documentation:

    $ bundle exec jekyll build

Or serve it on a local server on http://localhost:7998/Fork-Awesome/:

    $ bundle exec jekyll -w serve
