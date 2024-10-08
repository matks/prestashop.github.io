---
layout: post
aliases: ["/news/coreweekly-34-2021"]
title:  "PrestaShop Core Weekly - Week 34 of 2021"
subtitle: "An inside look at the PrestaShop codebase"
date:   2021-08-30
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 23th to Sunday 29th of August 2021.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [37 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2021-08-23..2021-08-29) have been created in the project repositories;
- [24 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2021-08-23..2021-08-29), including [9 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2021-08-23..2021-08-29) on the core;
- [47 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2021-08-23..2021-08-29) in the project repositories;
- [76 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2021-08-23..2021-08-29), including [57 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2021-08-23..2021-08-29).
        


## Code changes in the 'develop' branch


### Core
* [#25702](https://github.com/PrestaShop/PrestaShop/pull/25702): Create "modules" directory inside "var" for data, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25673](https://github.com/PrestaShop/PrestaShop/pull/25673): Remove the old `deprecated` comment to avoid confusion with new hook. Thank you [@PululuK](https://github.com/PululuK)
* [#23969](https://github.com/PrestaShop/PrestaShop/pull/23969): Fix glob result when path is outside open_basedir. Thank you [@mvorisek](https://github.com/mvorisek)
* [#17101](https://github.com/PrestaShop/PrestaShop/pull/17101): Fixed in mutishop weight for attributes in cart, by [@Progi1984](https://github.com/Progi1984)


### Back office
* [#25559](https://github.com/PrestaShop/PrestaShop/pull/25559): Removed Addons Connect button in Edit Employee Form in BO, by [@Progi1984](https://github.com/Progi1984)
* [#25558](https://github.com/PrestaShop/PrestaShop/pull/25558): Fixed save in Symfony Form Merchandise Return Options, by [@Progi1984](https://github.com/Progi1984)
* [#25440](https://github.com/PrestaShop/PrestaShop/pull/25440): Localized dates on BackOffice pages, by [@Progi1984](https://github.com/Progi1984)
* [#25314](https://github.com/PrestaShop/PrestaShop/pull/25314): Don't set UPGRADE as a main button in module list. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25054](https://github.com/PrestaShop/PrestaShop/pull/25054): Order feature by position then id_feature_value in productForm V2. Thank you [@e-gaulue](https://github.com/e-gaulue)
* [#24790](https://github.com/PrestaShop/PrestaShop/pull/24790): Migrate modern admin theme JS components to TypeScript, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#24491](https://github.com/PrestaShop/PrestaShop/pull/24491): BO SpecificPriceRule - Fix Multi Shop filter on conditions. Thank you [@Seb33300](https://github.com/Seb33300)
* [#24401](https://github.com/PrestaShop/PrestaShop/pull/24401): Remove support for legacy Core translation dictionaries in Back Office, by [@eternoendless](https://github.com/eternoendless)


### Front office
* [#25564](https://github.com/PrestaShop/PrestaShop/pull/25564): In checkout, shipping method is not displayed if cart is only virtual, by [@Progi1984](https://github.com/Progi1984)


### Tests
* [#25708](https://github.com/PrestaShop/PrestaShop/pull/25708): Wrong hook path for nightly reports, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25676](https://github.com/PrestaShop/PrestaShop/pull/25676): Use node_14.x instead of node_10.x, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25017](https://github.com/PrestaShop/PrestaShop/pull/25017): Upgrade mochawesome version and fix merge reports, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.8.x' branch


### Back office
* [#25612](https://github.com/PrestaShop/PrestaShop/pull/25612): Fix helpbox outside form label on product page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#25427](https://github.com/PrestaShop/PrestaShop/pull/25427): Fix overflowing buttons. Thank you [@Hlavtox](https://github.com/Hlavtox)
* [#25084](https://github.com/PrestaShop/PrestaShop/pull/25084): Fix menu active items spacing, by [@NeOMakinG](https://github.com/NeOMakinG)


### Front office
* [#25569](https://github.com/PrestaShop/PrestaShop/pull/25569): Fix next icon going outside imageslider on classic theme, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#25707](https://github.com/PrestaShop/PrestaShop/pull/25707): Add Timeout on stock page function. Thank you [@SD1982](https://github.com/SD1982)
* [#25699](https://github.com/PrestaShop/PrestaShop/pull/25699): Add a default value to cart rule code on faker file, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25685](https://github.com/PrestaShop/PrestaShop/pull/25685): Change db prefix for sql tests, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25681](https://github.com/PrestaShop/PrestaShop/pull/25681): Update stock location default value on faker file, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25679](https://github.com/PrestaShop/PrestaShop/pull/25679): Use node_14.x instead of node_10.x, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#25664](https://github.com/PrestaShop/PrestaShop/pull/25664): Run tests with different DB prefix, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25357](https://github.com/PrestaShop/PrestaShop/pull/25357): Fix create product with combination. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25354](https://github.com/PrestaShop/PrestaShop/pull/25354): Functional tests - Refacto shipping and payment tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25307](https://github.com/PrestaShop/PrestaShop/pull/25307): Functional tests - Refacto customer service tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25289](https://github.com/PrestaShop/PrestaShop/pull/25289): Functional tests - Refacto customers/addresses tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25275](https://github.com/PrestaShop/PrestaShop/pull/25275): Functional tests - Refacto Files, Discounts and Stocks tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25263](https://github.com/PrestaShop/PrestaShop/pull/25263): Functional tests -  Refacto brands & suppliers tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25189](https://github.com/PrestaShop/PrestaShop/pull/25189): Functional tests - Refacto customers tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#25178](https://github.com/PrestaShop/PrestaShop/pull/25178): Add js-doc on some data classes, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#25158](https://github.com/PrestaShop/PrestaShop/pull/25158): Functional tests - Update JS doc for FO pages. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#24969](https://github.com/PrestaShop/PrestaShop/pull/24969): Add new FO test "Write a review". Thank you [@SD1982](https://github.com/SD1982)


## Code changes in modules, themes & tools


### Changes in developer documentation sources
* [#1132](https://github.com/PrestaShop/docs/pull/1132): Updated .php-cs-fixer and pre-commit links. Thank you [@mreduar](https://github.com/mreduar)
* [#1129](https://github.com/PrestaShop/docs/pull/1129): Show a better way to push tag with alternative, by [@PierreRambaud](https://github.com/PierreRambaud)


### Changes in developer documentation theme
* [#8](https://github.com/PrestaShop/ps-docs-theme/pull/8): Remove unused fonts & optimize font loading, by [@eternoendless](https://github.com/eternoendless)
* [#7](https://github.com/PrestaShop/ps-docs-theme/pull/7): Only load mermaid when the page specifically enables it, by [@eternoendless](https://github.com/eternoendless)
* [#6](https://github.com/PrestaShop/ps-docs-theme/pull/6): Add version meta to every page, by [@eternoendless](https://github.com/eternoendless)
* [#5](https://github.com/PrestaShop/ps-docs-theme/pull/5): Extract docsearch template, use parameters and support versioning, by [@eternoendless](https://github.com/eternoendless)


### Changes in developer documentation site
* [#7](https://github.com/PrestaShop/devdocs-site/pull/7): Use docsearch settings, by [@eternoendless](https://github.com/eternoendless)


### presthubot
* [#35](https://github.com/PrestaShop/presthubot/pull/35): Skip orphan reviews, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#401](https://github.com/PrestaShop/autoupgrade/pull/401): Bump path-parse from 1.0.6 to 1.0.7 in /tests/e2e. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#394](https://github.com/PrestaShop/autoupgrade/pull/394): Update mochawesome and fix nightly import, by [@boubkerbribri](https://github.com/boubkerbribri)


### OnBoarding module
* [#126](https://github.com/PrestaShop/welcome/pull/126): Bump eslint-plugin-import from 2.24.1 to 2.24.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Customer reassurance block module
* [#258](https://github.com/PrestaShop/blockreassurance/pull/258): Bump eslint-plugin-import from 2.24.1 to 2.24.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#495](https://github.com/PrestaShop/ps_facetedsearch/pull/495): Bump eslint-plugin-import from 2.24.1 to 2.24.2. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### User documentation landing page
* [#111](https://github.com/PrestaShop/user-documentation-landing/pull/111): fix(deps): bump core-js from 3.16.2 to 3.16.3. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#110](https://github.com/PrestaShop/user-documentation-landing/pull/110): chore(deps-dev): bump sass from 1.38.0 to 1.38.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#109](https://github.com/PrestaShop/user-documentation-landing/pull/109): chore(deps-dev): bump eslint-plugin-prettier from 3.4.0 to 3.4.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Example modules
* [#78](https://github.com/PrestaShop/example-modules/pull/78): Add missing logos and fix some Composer informations, by [@matks](https://github.com/matks)


### Customer data privacy block module
* [#31](https://github.com/PrestaShop/ps_dataprivacy/pull/31): Fix module uninstall, by [@Matt75](https://github.com/Matt75)


### PrestaShop test scenarios
* [#4](https://github.com/PrestaShop/test-scenarios/pull/4): Migrated theme from hugo-geekdoc to ps-docs-theme, by [@Progi1984](https://github.com/Progi1984)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@matks](https://github.com/matks), [@PierreRambaud](https://github.com/PierreRambaud), [@SD1982](https://github.com/SD1982), [@mreduar](https://github.com/mreduar), [@boubkerbribri](https://github.com/boubkerbribri), [@dependabot[bot]](https://github.com/apps/dependabot), [@eternoendless](https://github.com/eternoendless), [@Progi1984](https://github.com/Progi1984), [@PululuK](https://github.com/PululuK), [@NeOMakinG](https://github.com/NeOMakinG), [@Matt75](https://github.com/Matt75), [@Hlavtox](https://github.com/Hlavtox), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@e-gaulue](https://github.com/e-gaulue), [@Seb33300](https://github.com/Seb33300), [@mvorisek](https://github.com/mvorisek)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

