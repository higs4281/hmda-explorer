# CFPB's Public Data Platform

An interactive front-end for [Qu](https://github.com/cfpb/qu). View the [stable](https://fake.ghe.domain/pages/data-platform/public-data-platform/explore.html) or [nightly](https://fake.ghe.domain/pages/contolini/public-data-platform/explore.html) demo.

## Documentation

See some [front-end notes](https://fake.ghe.domain/data-platform/data-platform-docs/wiki/Front-End-Framework-Notes) or the [documented source](https://fake.ghe.domain/pages/data-platform/public-data-platform/docs/main.html) (use the top right menu).

## Contributing

1. [Install Node and Grunt](https://fake.ghe.domain/contolini/grunt-init-cfpb#prerequisites)
1. `git clone git@fake.ghe.domain:data-platform/public-data-platform.git`
1. `cd public-data-platform`
1. `npm install`
1. `bower install`
1. `grunt`
1. Open `localhost:8000` in a browser.

Only edit files in `src`. When anything is changed, Grunt will lint, test, compile and build everything. [grunt-cfpb-internal](https://fake.ghe.domain/contolini/grunt-cfpb-internal) generates this README. Bump versions in CHANGELOG when appropriate.

In lieu of a formal styleguide, take care to maintain the existing coding style.

## Release History

 * 2013-08-02   [v0.9.0](../../tree/v0.9.0)   New location section functionality. Moved templates into JST using grunt-contrib-jst task.
 * 2013-08-01   [v0.8.1](../../tree/v0.8.1)   Fix preview table bug that returned wrong number of columns.
 * 2013-07-31   [v0.8.0](../../tree/v0.8.0)   Initial NLW implementation.
 * 2013-07-31   [v0.7.6](../../tree/v0.7.6)   Add Co-Applicant toggle. Add CFPB logo.
 * 2013-07-30   [v0.7.5](../../tree/v0.7.5)   Improve test coverage of new API.
 * 2013-07-30   [v0.7.4](../../tree/v0.7.4)   Refactor API URL building method to better accommodate summary table $select/$group clauses.
 * 2013-07-30   [v0.7.3](../../tree/v0.7.3)   Use ZeroClipboard to save share URL to clipboard.
 * 2013-07-29   [v0.7.2](../../tree/v0.7.2)   Memoize AJAX requests. Add section toggle to explore page header.
 * 2013-07-24   [v0.7.1](../../tree/v0.7.1)   Section parameter is properly stored in sharing URL hash.
 * 2013-07-23   [v0.7.0](../../tree/v0.7.0)   Popular filters section w/ synchronizing toggle.
 * 2013-07-22   [v0.6.0](../../tree/v0.6.0)   Initial preview table implementation. Initial summary table implementation.
 * 2013-07-19   [v0.5.2](../../tree/v0.5.2)   Icons and sugar.
 * 2013-07-18   [v0.5.1](../../tree/v0.5.1)   Connect dependent dropdowns to concept data endpoints.
 * 2013-07-17   [v0.5.0](../../tree/v0.5.0)   Beef up testing suite. Fix text input caching bug. Change location of HTML files.
 * 2013-07-16   [v0.4.1](../../tree/v0.4.1)   Dependent fields are properly enabled/disabled.
 * 2013-07-15   [v0.4.0](../../tree/v0.4.0)   Help tooltips. Form styling. Chosen JS implementation.
 * 2013-07-12   [v0.3.0](../../tree/v0.3.0)   Modularize all JavaScript. Add hash deparam feature. Ability to set DOM fields from params hash.
 * 2013-07-10   [v0.2.0](../../tree/v0.2.0)   Asynchronously populate field options. Field dependency management.
 * 2013-07-09   [v0.1.6](../../tree/v0.1.6)   Initial URL building methods. General refactoring.
 * 2013-07-08   [v0.1.3](../../tree/v0.1.3)   Add global observer.
 * 2013-07-06   [v0.1.1](../../tree/v0.1.1)   Configure build process.
 * 2013-07-05   [v0.1.0](../../tree/v0.1.0)   Initial commit of static version (forked from `backbone` branch).

## License

Software source code written entirely by Consumer Financial Protection Bureau staff, and by contractors who are developing software on behalf of CFPB, is by default a public domain work.

Software source code previously released under an open source license and then modified by CFPB staff is considered a "joint work" (see 17 USC § 101); it is partially copyrighted, partially public domain, and as a whole is protected by the copyrights of the non-government authors and must be released according to the terms of the original open-source license.

For further details, please see: http://www.consumerfinance.gov/developers/sourcecodepolicy/

---

*This file was generated on Sat Aug 03 2013 20:36:11.*
