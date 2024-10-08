---
layout: post
aliases: ["/news/coreweekly-47-2020"]
title:  "PrestaShop Core Weekly - Week 47 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-11-24
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 16th to Sunday 22th of November 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

Thanks to the contributors who tested the Release Candidate, a few bugs have been identified in the build that was published [three weeks ago](https://build.prestashop.com/news/prestashop-1-7-7-0-rc-release/).

These bugs have been fixed, so the road is now open to deliver PrestaShop 1.7.7.0 stable release. A new build has been created and delivered to QA team to run the tests campaign. Once it's verified, if no blocking bug is found, we will be able to release it!

## Releases

* [productcomments](https://github.com/PrestaShop/productcomments) module: [v4.2.0](https://github.com/PrestaShop/productcomments/releases/tag/v4.2.0)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [79 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-11-16..2020-11-22) have been created in the project repositories;
- [89 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-11-16..2020-11-22), including [31 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-11-16..2020-11-22) on the core;
- [84 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-11-16..2020-11-22) in the project repositories;
- [80 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-11-16..2020-11-22), including [68 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-11-16..2020-11-22).


## Code changes in the 'develop' branch


### Core
* [#21984](https://github.com/PrestaShop/PrestaShop/pull/21984): Improve Link::getProductLink : Avoid short variable names. Thank you [@PululuK](https://github.com/PululuK)
* [#21934](https://github.com/PrestaShop/PrestaShop/pull/21934): Fix PHPDoc Tools::displayPrice(). Thank you [@comxd](https://github.com/comxd)
* [#21855](https://github.com/PrestaShop/PrestaShop/pull/21855): Add missing SQL row for actionFrontControllerSetVariables hook. Thank you [@comxd](https://github.com/comxd)
* [#21094](https://github.com/PrestaShop/PrestaShop/pull/21094): Fixed array parameter processing in Link::getCategoryObject method. Thank you [@gfilippakis](https://github.com/gfilippakis)


### Back office
* [#22001](https://github.com/PrestaShop/PrestaShop/pull/22001): Fix some typos in admin filemanager, by [@matks](https://github.com/matks)
* [#21985](https://github.com/PrestaShop/PrestaShop/pull/21985): Remove wrong div endblock on order page view after the 177 merge, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21960](https://github.com/PrestaShop/PrestaShop/pull/21960): Fix legacy form selectors, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#21947](https://github.com/PrestaShop/PrestaShop/pull/21947): Adjust modal position when wrong used with a form, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21931](https://github.com/PrestaShop/PrestaShop/pull/21931): Remove special case of Product::toggleStatus, by [@jolelievre](https://github.com/jolelievre)
* [#21892](https://github.com/PrestaShop/PrestaShop/pull/21892): Fix badges on customer page, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21886](https://github.com/PrestaShop/PrestaShop/pull/21886): Fix radius on some custom components, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21849](https://github.com/PrestaShop/PrestaShop/pull/21849): Fix alert of compromised page and center window, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#21818](https://github.com/PrestaShop/PrestaShop/pull/21818): Improve feature wording in Product Settings page, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#21793](https://github.com/PrestaShop/PrestaShop/pull/21793): Fix Customer view Vouchers & Addresses tables, by [@atomiix](https://github.com/atomiix)
* [#21679](https://github.com/PrestaShop/PrestaShop/pull/21679): Simplify customer form. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#21628](https://github.com/PrestaShop/PrestaShop/pull/21628): Stream downloaded file for HTTP/2. Thank you [@sylwit](https://github.com/sylwit)
* [#21550](https://github.com/PrestaShop/PrestaShop/pull/21550): Introduce DuplicateProductCommand [product page migration]. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21510](https://github.com/PrestaShop/PrestaShop/pull/21510): Introduce ProductImageUploader and AddProductImageCommand [product page migration]. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21443](https://github.com/PrestaShop/PrestaShop/pull/21443): Made it so order preferences uses the same form theme as all others simplified forms. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)
* [#19776](https://github.com/PrestaShop/PrestaShop/pull/19776): Allow developers to use their own tinymce config, by [@NeOMakinG](https://github.com/NeOMakinG)


### Front office
* [#21908](https://github.com/PrestaShop/PrestaShop/pull/21908): Strip_tags() error when having an array in the URL, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#21725](https://github.com/PrestaShop/PrestaShop/pull/21725): Avoid global markup duplicate in checkout.tpl. Thank you [@micka-fdz](https://github.com/micka-fdz)
* [#21425](https://github.com/PrestaShop/PrestaShop/pull/21425): Add autocomplete attributes on FO login form, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20809](https://github.com/PrestaShop/PrestaShop/pull/20809): Update to check Language association to the current store. Thank you [@dgonzalez360](https://github.com/dgonzalez360)
* [#20080](https://github.com/PrestaShop/PrestaShop/pull/20080): Add eslint to themes and classic folders, by [@NeOMakinG](https://github.com/NeOMakinG)


### Tests
* [#21986](https://github.com/PrestaShop/PrestaShop/pull/21986): Add test "Disable multi store on CRUD shop group test". Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21973](https://github.com/PrestaShop/PrestaShop/pull/21973): Add test "CRUD multistore". Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21959](https://github.com/PrestaShop/PrestaShop/pull/21959): Fix step identifier checker command name, by [@boubkerbribri](https://github.com/boubkerbribri)
* [#21955](https://github.com/PrestaShop/PrestaShop/pull/21955): Remove transformation traits from behats and implement contexts instead. Thank you [@zuk3975](https://github.com/zuk3975)
* [#21954](https://github.com/PrestaShop/PrestaShop/pull/21954): Add test "Pagination DB backup". Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21946](https://github.com/PrestaShop/PrestaShop/pull/21946): Add test "Sort and pagination emails table". Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21869](https://github.com/PrestaShop/PrestaShop/pull/21869): Add test 'CRUD search'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21779](https://github.com/PrestaShop/PrestaShop/pull/21779): Add test 'Filter sort and pagination order return status'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#21646](https://github.com/PrestaShop/PrestaShop/pull/21646): Fix theme not being enabled when creating test database, by [@atomiix](https://github.com/atomiix)


## Code changes in the '1.7.7.x' branch


### Core
* [#21975](https://github.com/PrestaShop/PrestaShop/pull/21975): Correctly substring fields before update, remove duplicates and add missing sql queries, by [@PierreRambaud](https://github.com/PierreRambaud)


### Back office
* [#22018](https://github.com/PrestaShop/PrestaShop/pull/22018): Order zero ratio for order detail tax, by [@matks](https://github.com/matks)
* [#21994](https://github.com/PrestaShop/PrestaShop/pull/21994): Remove or cancel all products, by [@jolelievre](https://github.com/jolelievre)
* [#21781](https://github.com/PrestaShop/PrestaShop/pull/21781): Remove gifted quantity from product order quantity, by [@sowbiba](https://github.com/sowbiba)
* [#21721](https://github.com/PrestaShop/PrestaShop/pull/21721): Handle Shop context override in order editing, by [@jolelievre](https://github.com/jolelievre)


### Front office
* [#21981](https://github.com/PrestaShop/PrestaShop/pull/21981): Make sure favicon, stores_icon and logo are correctly settled for themes, by [@PierreRambaud](https://github.com/PierreRambaud)


### Installer
* [#21957](https://github.com/PrestaShop/PrestaShop/pull/21957): Update latest native modules, by [@jolelievre](https://github.com/jolelievre)
* [#21953](https://github.com/PrestaShop/PrestaShop/pull/21953): Fix "column count doesn't match value count" error during upgrade. Thank you [@okom3pom](https://github.com/okom3pom)


## Code changes in modules, themes & tools


### Visitors online statistics module
* [#18](https://github.com/PrestaShop/statslive/pull/18): Bump version to 2.1.1, by [@Progi1984](https://github.com/Progi1984)
* [#17](https://github.com/PrestaShop/statslive/pull/17): Improve project, by [@Progi1984](https://github.com/Progi1984)


### Faceted search module
* [#260](https://github.com/PrestaShop/ps_facetedsearch/pull/260): Bump webpack from 5.5.0 to 5.6.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#259](https://github.com/PrestaShop/ps_facetedsearch/pull/259): Bump webpack from 5.4.0 to 5.5.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#255](https://github.com/PrestaShop/ps_facetedsearch/pull/255): Migrated Travis to Github Actions, by [@Progi1984](https://github.com/Progi1984)


### Docker images
* [#239](https://github.com/PrestaShop/docker/pull/239): Fix outdated license headers, by [@matks](https://github.com/matks)
* [#233](https://github.com/PrestaShop/docker/pull/233): Refactor how images are built, by [@PierreRambaud](https://github.com/PierreRambaud)


### PrestaShop Specifications
* [#178](https://github.com/PrestaShop/prestashop-specs/pull/178): Update Order Page View.md. Thank you [@MatShir](https://github.com/MatShir)
* [#177](https://github.com/PrestaShop/prestashop-specs/pull/177): Add link for product images in product listing, by [@marionf](https://github.com/marionf)
* [#175](https://github.com/PrestaShop/prestashop-specs/pull/175): Add recycled packaging information, by [@LouiseBonnard](https://github.com/LouiseBonnard)
* [#174](https://github.com/PrestaShop/prestashop-specs/pull/174): Add specs for round on each item, by [@marionf](https://github.com/marionf)
* [#172](https://github.com/PrestaShop/prestashop-specs/pull/172): Edit Shop Parameters > Search, by [@LouiseBonnard](https://github.com/LouiseBonnard)


### Auto Upgrade module
* [#352](https://github.com/PrestaShop/autoupgrade/pull/352): Remove VSCode config files, by [@matks](https://github.com/matks)
* [#351](https://github.com/PrestaShop/autoupgrade/pull/351): Add travis badge status, by [@matks](https://github.com/matks)


### Webservices PHP Client
* [#73](https://github.com/PrestaShop/PrestaShop-webservice-lib/pull/73): Remove duplicate `@throws` in PHPDoc. Thank you [@davidglezz](https://github.com/davidglezz)


### Docker internal images
* [#34](https://github.com/PrestaShop/docker-internal-images/pull/34): Use 1.7 instead of 1.7-7.2-apache, by [@PierreRambaud](https://github.com/PierreRambaud)


### Prestashop UI Kit
* [#119](https://github.com/PrestaShop/prestashop-ui-kit/pull/119): Update UIKit version inside the readme, by [@NeOMakinG](https://github.com/NeOMakinG)


### Product Comments module
* [#81](https://github.com/PrestaShop/productcomments/pull/81): Release 4.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#80](https://github.com/PrestaShop/productcomments/pull/80): Bump to 4.2.0, by [@PierreRambaud](https://github.com/PierreRambaud)


### PHP Developer Tools
* [#39](https://github.com/PrestaShop/php-dev-tools/pull/39): phpstan config : add  `_PS_MODE_DEV_` to dynamicConstantNames. Thank you [@SebSept](https://github.com/SebSept)


### Changes in developer documentation
* [#801](https://github.com/PrestaShop/docs/pull/801): More informations for maintainers : red flags for code reviews, BC breaks, what it means to approve a PR, by [@matks](https://github.com/matks)
* [#782](https://github.com/PrestaShop/docs/pull/782): Add tinymce config extend documentation, by [@NeOMakinG](https://github.com/NeOMakinG)


## Where to start contributing?

What about improving the Reset Url button of product page? There is a [bug with accented URLs](https://github.com/PrestaShop/PrestaShop/issues/21495) about it reported in October, and it is one of our [good first issues](https://github.com/PrestaShop/PrestaShop/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22).

Good first issues are a list of all beginner-friendly improvements and bugs to fix in the project. You can read more about this label on [our article about it](https://build.prestashop.com/news/a-definition-of-the-good-first-issue-label).


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@Progi1984](https://github.com/Progi1984), [@dependabot[bot]](https://github.com/apps/dependabot), [@matks](https://github.com/matks), [@MatShir](https://github.com/MatShir), [@jolelievre](https://github.com/jolelievre), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@NeOMakinG](https://github.com/NeOMakinG), [@PululuK](https://github.com/PululuK), [@PierreRambaud](https://github.com/PierreRambaud), [@marionf](https://github.com/marionf), [@davidglezz](https://github.com/davidglezz), [@matthieu-rolland](https://github.com/matthieu-rolland), [@boubkerbribri](https://github.com/boubkerbribri), [@zuk3975](https://github.com/zuk3975), [@okom3pom](https://github.com/okom3pom), [@LouiseBonnard](https://github.com/LouiseBonnard), [@comxd](https://github.com/comxd), [@atomiix](https://github.com/atomiix), [@SebSept](https://github.com/SebSept), [@sowbiba](https://github.com/sowbiba), [@micka-fdz](https://github.com/micka-fdz), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@sylwit](https://github.com/sylwit), [@gfilippakis](https://github.com/gfilippakis), [@dgonzalez360](https://github.com/dgonzalez360)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
