TwoFactorAuth.org
=================

[![Build Status](https://travis-ci.org/2factorauth/twofactorauth.svg)](https://travis-ci.org/2factorauth/twofactorauth)
[![License](https://img.shields.io/badge/license-mit-blue.svg?style=flat)](/LICENSE)
[![Gitter](https://img.shields.io/gitter/room/2factorauth/twofactorauth.svg)](https://gitter.im/2factorauth/twofactorauth)
[![Twitter](https://img.shields.io/badge/Twitter-@2faorg-blue.svg)](https://twitter.com/useNano)

A directory of merchants that accept Nano cryptocurrency payments.

## The Goal

The goal is to build a website ([usenano.co](https://usenano.co)) with a comprehensive list of merchants that accept Nano, as well as their website and contact information.

Our aim is to promote global adoption of Nano, a peer to peer feeless and instant digital currency.

## Contributing

If you'd like to contribute, read the entire guidelines here in
[CONTRIBUTING.md][contrib].

## Running Locally

useNano.org is built upon [Jekyll](https://jekyllrb.com/), using the [github-pages](https://github.com/github/pages-gem) gem.
In order to run the site locally, it is necessary to install bundler, install all dependencies, and then use Jekyll to serve
the site. If the `gem` command is not available to you, it is necessary to install Ruby with RubyGems.
Once Ruby and RubyGems are installed and available from the command line, TwoFactorAuth can be setup using the following commands.

```
gem install bundler
cd ~/usenano
bundle install
bundle exec jekyll serve
```

The useNano website should then be accessible from `http://localhost:4000`.

## License

This code is distributed under the MIT license. For more info, read the
[LICENSE][license] file distributed with the source code.

[contrib]: /CONTRIBUTING.md
[license]: /LICENSE
