---
layout: post
aliases: ["/news/coreweekly-27-2021"]
title:  "PrestaShop Core Weekly - Week 27 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-07-19 13:55:00
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 5th to Sunday 11th of July 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## Releases

* [Emailsubscription](https://github.com/PrestaShop/ps_emailsubscription) module: [v2.7.0](https://github.com/PrestaShop/ps_emailsubscription/releases/tag/v2.7.0)
* [Mainmenu](https://github.com/PrestaShop/ps_mainmenu) module: [v2.3.0](https://github.com/PrestaShop/ps_mainmenu/releases/tag/v2.3.0)
* [Searchbar](https://github.com/PrestaShop/ps_searchbar) module: [v2.1.1](https://github.com/PrestaShop/ps_searchbar/releases/tag/v2.1.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [40 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-07-05..2021-07-11) have been created in the project repositories;
- [40 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-07-05..2021-07-11), including [11 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-07-05..2021-07-11) on the core;
- [77 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-07-05..2021-07-11) in the project repositories;
- [64 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-07-05..2021-07-11), including [45 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-07-05..2021-07-11).



## Code changes in the 'develop' branch


### Core
* [#25287](https://github.com/PrestaShop/PrestaShop/pull/25287): Removed code related to Gamification module, by [@Progi1984](https://github.com/Progi1984)
* [#25052](https://github.com/PrestaShop/PrestaShop/pull/25052): Remove Symfony 4.4 deprecations, by [@atomiix](https://github.com/atomiix)


### Back office
* [#24932](https://github.com/PrestaShop/PrestaShop/pull/24932): Fix unexpected condition in country-state-selection-toggler. Thank you [@davidglezz](https://github.com/davidglezz)


### Tests
* [#25266](https://github.com/PrestaShop/PrestaShop/pull/25266): Fix develop tests crashing because of outdated translation wordings, by [@atomiix](https://github.com/atomiix)
* [#25238](https://github.com/PrestaShop/PrestaShop/pull/25238): Migrated some Legacy Tests to Integration/Unit Tests, by [@Progi1984](https://github.com/Progi1984)
* [#25146](https://github.com/PrestaShop/PrestaShop/pull/25146): Separate functional tests to BO and FO and Add regression campaign to the actual run, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.8.x' branch


### Tests
* [#25292](https://github.com/PrestaShop/PrestaShop/pull/25292): Fix 1.7.8.x test for product duplicate. Thank you [@okom3pom](https://github.com/okom3pom)


## Code changes in the '1.7.7.x' branch


### Back office
* [#25200](https://github.com/PrestaShop/PrestaShop/pull/25200): In Invoice PDF, escape customization name, by [@Progi1984](https://github.com/Progi1984)
* [#25107](https://github.com/PrestaShop/PrestaShop/pull/25107): Fixed meta title in BO - Order View, by [@Progi1984](https://github.com/Progi1984)
* [#25106](https://github.com/PrestaShop/PrestaShop/pull/25106): Fixed management of INNER JOIN & GROUP BY in SqlQueryValidator, by [@Progi1984](https://github.com/Progi1984)
* [#25059](https://github.com/PrestaShop/PrestaShop/pull/25059): Fixed translated order messages in Order View, by [@Progi1984](https://github.com/Progi1984)
* [#24324](https://github.com/PrestaShop/PrestaShop/pull/24324): Orders View : Display right price depending configuration, by [@Progi1984](https://github.com/Progi1984)


### Front office
* [#25216](https://github.com/PrestaShop/PrestaShop/pull/25216): Fix brands links not clickable inside description, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#24868](https://github.com/PrestaShop/PrestaShop/pull/24868): Fixed cart rule on selected product with product with ecotax, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#25281](https://github.com/PrestaShop/PrestaShop/pull/25281): Rise Apache Travis timeout to workaround addons module install issues, by [@matks](https://github.com/matks)


## Code changes in modules, themes & tools


### User documentation landing page
* [#92](https://github.com/PrestaShop/user-documentation-landing/pull/92): chore(deps-dev): bump sass from 1.35.1 to 1.35.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#91](https://github.com/PrestaShop/user-documentation-landing/pull/91): chore(deps-dev): bump eslint from 7.29.0 to 7.30.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Main menu module
* [#55](https://github.com/PrestaShop/ps_mainmenu/pull/55): Fix composer dependencies, by [@atomiix](https://github.com/atomiix)
* [#54](https://github.com/PrestaShop/ps_mainmenu/pull/54): Release v2.3.0, by [@atomiix](https://github.com/atomiix)
* [#49](https://github.com/PrestaShop/ps_mainmenu/pull/49): Fix "edit" button that was mistakenly "add". Thank you [@okom3pom](https://github.com/okom3pom)


### Customer reassurance block module
* [#233](https://github.com/PrestaShop/blockreassurance/pull/233): Bump webpack from 5.42.1 to 5.43.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#232](https://github.com/PrestaShop/blockreassurance/pull/232): Bump webpack from 5.42.0 to 5.42.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#231](https://github.com/PrestaShop/blockreassurance/pull/231): Bump mini-css-extract-plugin from 2.0.0 to 2.1.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#230](https://github.com/PrestaShop/blockreassurance/pull/230): Bump webpack from 5.41.1 to 5.42.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#219](https://github.com/PrestaShop/blockreassurance/pull/219): Removed Addons Suggestions, by [@Progi1984](https://github.com/Progi1984)


### Faceted search module
* [#466](https://github.com/PrestaShop/ps_facetedsearch/pull/466): Bump webpack from 5.42.1 to 5.43.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#465](https://github.com/PrestaShop/ps_facetedsearch/pull/465): Bump webpack from 5.42.0 to 5.42.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#464](https://github.com/PrestaShop/ps_facetedsearch/pull/464): Bump mocha from 9.0.1 to 9.0.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#463](https://github.com/PrestaShop/ps_facetedsearch/pull/463): Bump webpack from 5.41.1 to 5.42.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Changes in developer documentation
* [#1074](https://github.com/PrestaShop/docs/pull/1074): Copy over helper documentation from 1.6, by [@eternoendless](https://github.com/eternoendless)
* [#1073](https://github.com/PrestaShop/docs/pull/1073): Fix diverse style issues, by [@eternoendless](https://github.com/eternoendless)
* [#1071](https://github.com/PrestaShop/docs/pull/1071): Update module file structure, by [@eternoendless](https://github.com/eternoendless)
* [#1070](https://github.com/PrestaShop/docs/pull/1070): Make inline code look better in headings and links, by [@eternoendless](https://github.com/eternoendless)
* [#1069](https://github.com/PrestaShop/docs/pull/1069): Update naming conventions, by [@eternoendless](https://github.com/eternoendless)
* [#1066](https://github.com/PrestaShop/docs/pull/1066): Reorganize database documentation, by [@eternoendless](https://github.com/eternoendless)
* [#1065](https://github.com/PrestaShop/docs/pull/1065): Add minimalist context documentation, by [@eternoendless](https://github.com/eternoendless)
* [#1064](https://github.com/PrestaShop/docs/pull/1064): Fix spacing in definition lists, by [@eternoendless](https://github.com/eternoendless)
* [#1063](https://github.com/PrestaShop/docs/pull/1063): Update Module > Getting Started section, by [@eternoendless](https://github.com/eternoendless)


### Prestashop UI Kit
* [#166](https://github.com/PrestaShop/prestashop-ui-kit/pull/166): Add black color to warning and light buttons, by [@NeOMakinG](https://github.com/NeOMakinG)


### Example modules
* [#71](https://github.com/PrestaShop/example-modules/pull/71): Detail multistore features in README, by [@marionf](https://github.com/marionf)


### Search Bar module
* [#37](https://github.com/PrestaShop/ps_searchbar/pull/37): Release v2.1.1, by [@atomiix](https://github.com/atomiix)


### Wishlist block module
* [#125](https://github.com/PrestaShop/blockwishlist/pull/125): Add TS-loader and fix webpack configuration to support next version, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#124](https://github.com/PrestaShop/blockwishlist/pull/124): Fix RTL issues on add to wishlist button on FO, by [@NeOMakinG](https://github.com/NeOMakinG)


### Email subscription module
* [#83](https://github.com/PrestaShop/ps_emailsubscription/pull/83): Release v2.7.0, by [@atomiix](https://github.com/atomiix)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@okom3pom](https://github.com/okom3pom), [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@atomiix](https://github.com/atomiix), [@eternoendless](https://github.com/eternoendless), [@NeOMakinG](https://github.com/NeOMakinG), [@marionf](https://github.com/marionf), [@boubkerbribri](https://github.com/boubkerbribri), [@davidglezz](https://github.com/davidglezz)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
