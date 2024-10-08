---
layout: post
aliases: ["/news/coreweekly-19-2022"]
title:  "PrestaShop Core Weekly - Week 19 of 2022"
subtitle: "An inside look at the PrestaShop codebase"
date:   2022-05-18
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 9th to Sunday 15th of May 2022.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear developers,

[PrestaShop 1.7.8.6](https://build.prestashop.com/news/prestashop-1-7-8-6-maintenance-release/) has been released yesterday.

We suggest upgrading your store quickly to benefit from the bug fixes of this patch version. As usual, make sure to perform a full manual backup before, so you can roll back the upgrade if something goes wrong.

## Releases

* [PrestaShop](https://github.com/PrestaShop/PrestaShop): [1.7.8.6](https://github.com/PrestaShop/PrestaShop/releases/tag/1.7.8.6)
* [Autoupgrade](https://github.com/PrestaShop/autoupgrade) module: [v4.14.1](https://github.com/PrestaShop/autoupgrade/releases/tag/4.14.1)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [38 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2022-05-09..2022-05-15) have been created in the project repositories;
- [31 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2022-05-09..2022-05-15), including [6 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2022-05-09..2022-05-15) on the core;
- [39 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2022-05-09..2022-05-15) in the project repositories;
- [44 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2022-05-09..2022-05-15), including [32 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2022-05-09..2022-05-15).


## Code changes in the 'develop' branch


### Back office
* [#28459](https://github.com/PrestaShop/PrestaShop/pull/28459): Combination bulk action. Handle new bulk choices: select all | select all in page. Thank you [@zuk3975](https://github.com/zuk3975)
* [#28451](https://github.com/PrestaShop/PrestaShop/pull/28451): New product price display and product summary, by [@jolelievre](https://github.com/jolelievre)
* [#28447](https://github.com/PrestaShop/PrestaShop/pull/28447): Use toolbar buttons array index as class when missing, by [@sowbiba](https://github.com/sowbiba)
* [#28407](https://github.com/PrestaShop/PrestaShop/pull/28407): Combination list edit mode, by [@jolelievre](https://github.com/jolelievre)
* [#28277](https://github.com/PrestaShop/PrestaShop/pull/28277): Fix bugs for RTL languages by SCSS in BO. Thank you [@mparvazi](https://github.com/mparvazi)
* [#28140](https://github.com/PrestaShop/PrestaShop/pull/28140): Fix the sorting mechanism on the Stock page. Thank you [@marsaldev](https://github.com/marsaldev)
* [#27353](https://github.com/PrestaShop/PrestaShop/pull/27353): Refacto combination suppliers, by [@jolelievre](https://github.com/jolelievre)
* [#27308](https://github.com/PrestaShop/PrestaShop/pull/27308): Restore needed removed row in customer view, by [@NeOMakinG](https://github.com/NeOMakinG)


### Front office
* [#27738](https://github.com/PrestaShop/PrestaShop/pull/27738): FO : Fix offset for "NEW" products listing. Thank you [@idnovate](https://github.com/idnovate)


### Tests
* [#28493](https://github.com/PrestaShop/PrestaShop/pull/28493): Fix nightly 13/05/2022 - Fix failed Orders tests. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#28464](https://github.com/PrestaShop/PrestaShop/pull/28464): Fix nightly 11/05/2022 - Fix tests in 'Catalog > Stock' page. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#28456](https://github.com/PrestaShop/PrestaShop/pull/28456): Functional tests - Add 'data-role' attribute to 'header-desc' selectors. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)
* [#28309](https://github.com/PrestaShop/PrestaShop/pull/28309): Functional tests - Refacto 'Update order status'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation sources
* [#1377](https://github.com/PrestaShop/docs/pull/1377): Addresses webservice spelling fix. Thank you [@leemyongpakvn](https://github.com/leemyongpakvn)
* [#1376](https://github.com/PrestaShop/docs/pull/1376): Add missing `Column Types` docs. Thank you [@LouisAUTHIE](https://github.com/LouisAUTHIE)
* [#1370](https://github.com/PrestaShop/docs/pull/1370): Add missing word. Thank you [@leemyongpakvn](https://github.com/leemyongpakvn)
* [#1366](https://github.com/PrestaShop/docs/pull/1366): Remove redundant word. Thank you [@leemyongpakvn](https://github.com/leemyongpakvn)
* [#1364](https://github.com/PrestaShop/docs/pull/1364): Module error with namespace Foo\Repository. Thank you [@leemyongpakvn](https://github.com/leemyongpakvn)


### Customer reassurance block module
* [#399](https://github.com/PrestaShop/blockreassurance/pull/399): Bump webpack from 5.72.0 to 5.72.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#398](https://github.com/PrestaShop/blockreassurance/pull/398): Bump eslint from 8.14.0 to 8.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Faceted search module
* [#656](https://github.com/PrestaShop/ps_facetedsearch/pull/656): Bump webpack from 5.72.0 to 5.72.1. Built by [@dependabot[bot]](https://github.com/apps/dependabot)
* [#655](https://github.com/PrestaShop/ps_facetedsearch/pull/655): Bump eslint from 8.14.0 to 8.15.0. Built by [@dependabot[bot]](https://github.com/apps/dependabot)


### Hummingbird theme
* [#276](https://github.com/PrestaShop/hummingbird/pull/276): Improve Customization form. Thank you [@mparvazi](https://github.com/mparvazi)
* [#275](https://github.com/PrestaShop/hummingbird/pull/275): Improve Order Confirmation page display. Thank you [@mparvazi](https://github.com/mparvazi)
* [#272](https://github.com/PrestaShop/hummingbird/pull/272): Fix a11y for Desktop Menu. Thank you [@mparvazi](https://github.com/mparvazi)
* [#271](https://github.com/PrestaShop/hummingbird/pull/271): Improved scss files structure. Thank you [@Oksydan](https://github.com/Oksydan)
* [#261](https://github.com/PrestaShop/hummingbird/pull/261): Quickview improvements, by [@NeOMakinG](https://github.com/NeOMakinG)


### The PrestaShop open source project
* [#96](https://github.com/PrestaShop/open-source/pull/96): Add Hlavtox as scoped maintainer in the project organization, by [@matks](https://github.com/matks)
* [#79](https://github.com/PrestaShop/open-source/pull/79): Add Committer role to the project, by [@matks](https://github.com/matks)


### Auto Upgrade module
* [#485](https://github.com/PrestaShop/autoupgrade/pull/485): Fix typo in github workflows, by [@matks](https://github.com/matks)


### Email Alerts module
* [#114](https://github.com/PrestaShop/ps_emailalerts/pull/114): Rename incorrect translation domains. Thank you [@lmeyer1](https://github.com/lmeyer1)


### LocalizationFiles
* [#16](https://github.com/PrestaShop/LocalizationFiles/pull/16): Added states to ar.xml according to ISO 3166-2. Thank you [@rickygzz](https://github.com/rickygzz)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@leemyongpakvn](https://github.com/leemyongpakvn), [@LouisAUTHIE](https://github.com/LouisAUTHIE), [@zuk3975](https://github.com/zuk3975), [@dependabot[bot]](https://github.com/apps/dependabot), [@mparvazi](https://github.com/mparvazi), [@jolelievre](https://github.com/jolelievre), [@matks](https://github.com/matks), [@sowbiba](https://github.com/sowbiba), [@Oksydan](https://github.com/Oksydan), [@NeOMakinG](https://github.com/NeOMakinG), [@lmeyer1](https://github.com/lmeyer1), [@marsaldev](https://github.com/marsaldev), [@idnovate](https://github.com/idnovate), [@rickygzz](https://github.com/rickygzz)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/8/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/8/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/8/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!

