# Rinvex Cacheable

**Rinvex Cacheable** is a granular, intuitive, and fluent caching system for eloquent models. Simple, but yet powerful, plug-n-play with no hassle.

What this package do -technically- caching eloquent query passing through the `get` method, whatever it is and it's smart enough to indicated any conditions, limit, offset, wheres, orders, groups, ..etc and take that criteria into account when caching and checking for cached version. Also by default any create, update, or delete event will flush all cache for that specific model. Awesome, right?

[![Packagist](https://img.shields.io/packagist/v/rinvex/cacheable.svg?label=Packagist&style=flat-square)](https://packagist.org/packages/rinvex/cacheable)
[![VersionEye Dependencies](https://img.shields.io/versioneye/d/php/rinvex:cacheable.svg?label=Dependencies&style=flat-square)](https://www.versioneye.com/php/rinvex:cacheable/)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/rinvex/cacheable.svg?label=Scrutinizer&style=flat-square)](https://scrutinizer-ci.com/g/rinvex/cacheable/)
[![Code Climate](https://img.shields.io/codeclimate/github/rinvex/cacheable.svg?label=CodeClimate&style=flat-square)](https://codeclimate.com/github/rinvex/cacheable)
[![Travis](https://img.shields.io/travis/rinvex/cacheable.svg?label=TravisCI&style=flat-square)](https://travis-ci.org/rinvex/cacheable)
[![SensioLabs Insight](https://img.shields.io/sensiolabs/i/f2dca242-eb65-4bcc-8481-cd27ea16c804.svg?label=SensioLabs&style=flat-square)](https://insight.sensiolabs.com/projects/f2dca242-eb65-4bcc-8481-cd27ea16c804)
[![StyleCI](https://styleci.io/repos/66037019/shield)](https://styleci.io/repos/66037019)
[![License](https://img.shields.io/packagist/l/rinvex/cacheable.svg?label=License&style=flat-square)](https://github.com/rinvex/cacheable/blob/develop/LICENSE)


## Installation & Usage

1. Install the package via composer:
    ```shell
    composer require rinvex/cacheable
    ```

2. Use the `\Rinvex\Cacheable\CacheableEloquent` in your desired model, and you're done!

3. Seriously, that's it!

Check the [`CacheableEloquent`](blob/master/src/CacheableEloquent.php) source code for more awesome stuff if you need advanced control.


## Changelog

Refer to the [Changelog](CHANGELOG.md) for a full history of the project.


## Support

The following support channels are available at your fingertips:

- [Chat on Slack](http://chat.rinvex.com)
- [Help on Email](mailto:help@rinvex.com)
- [Follow on Twitter](https://twitter.com/rinvex)


## Contributing & Protocols

Thank you for considering contributing to this project! The contribution guide can be found in [CONTRIBUTING.md](CONTRIBUTING.md).

Bug reports, feature requests, and pull requests are very welcome.

- [Versioning](CONTRIBUTING.md#versioning)
- [Pull Requests](CONTRIBUTING.md#pull-requests)
- [Coding Standards](CONTRIBUTING.md#coding-standards)
- [Feature Requests](CONTRIBUTING.md#feature-requests)
- [Git Flow](CONTRIBUTING.md#git-flow)


## Security Vulnerabilities

We want to ensure that this package is secure for everyone. If you've discovered a security vulnerability in this package, we appreciate your help in disclosing it to us in a [responsible manner](https://en.wikipedia.org/wiki/Responsible_disclosure).

Publicly disclosing a vulnerability can put the entire community at risk. If you've discovered a security concern, please email us at [security@rinvex.com](mailto:security@rinvex.com). We'll work with you to make sure that we understand the scope of the issue, and that we fully address your concern. We consider correspondence sent to [security@rinvex.com](mailto:security@rinvex.com) our highest priority, and work to address any issues that arise as quickly as possible.

After a security vulnerability has been corrected, a security hotfix release will be deployed as soon as possible.


## About Rinvex

Rinvex is a software solutions startup, specialized in integrated enterprise solutions for SMEs established in Alexandria, Egypt since June 2016. We believe that our drive The Value, The Reach, and The Impact is what differentiates us and unleash the endless possibilities of our philosophy through the power of software. We like to call it Innovation At The Speed Of Life. That’s how we do our share of advancing humanity.


## License

This software is released under [The MIT License (MIT)](LICENSE).

(c) 2016-2017 Rinvex LLC, Some rights reserved.