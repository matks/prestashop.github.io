---
layout: post
aliases: ["/news/coreweekly-week-17-2019"]
title:  "PrestaShop Core Weekly - Week 17 of 2019"
subtitle: "An inside look at the PrestaShop codebase"
date:   2019-05-03 15:30:00
authors: [ AntoineThomas ]
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 22th to Sunday 28th of April 2019.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)


## General messages

Dear Developers,

That was amazing to see the huge mobilization to find workarounds in a hurry, during the weekend, to fix the [spam issue](http://build.prestashop.com/news/fighting-against-spamming-again/) with the account creation form.

You will see in this core-weekly the pull requests that fix this issue. And, in case your missed it, two versions of PrestaShop have been released this morning: [1.6.1.24 and 1.7.5.2](http://build.prestashop.com/news/prestashop-1-7-5-2-1-6-1-24-maintenance-release/). 


## A quick update about PrestaShop's GitHub issues and pull requests:

- [43 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2019-04-22..2019-04-28) have been created in the project repositories;
- [49 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2019-04-22..2019-04-28), including [14 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2019-04-22..2019-04-28) on the core;
- [55 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2019-04-22..2019-04-28) in the project repositories;
- [50 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2019-04-22..2019-04-28), including [36 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2019-04-22..2019-04-28).


## Code changes in the 'develop' branch (for 1.7.7.0)

### Core

* [#13482](https://github.com/PrestaShop/PrestaShop/pull/13482): Merge 1.7.6.x to develop - 18/04/2019, by [@matks](https://github.com/matks)
* [#13542](https://github.com/PrestaShop/PrestaShop/pull/13542): Merge 1.7.6.x to develop - 23/04/2019, by [@matks](https://github.com/matks)
* [#13557](https://github.com/PrestaShop/PrestaShop/pull/13557): Merge 1.7.6.x to develop - 25/04/2019, by [@matks](https://github.com/matks)


### Back office

* [#13152](https://github.com/PrestaShop/PrestaShop/pull/13152): Updates characters length for Category meta fields. Thank you [@sarjon](https://github.com/sarjon)
* [#13233](https://github.com/PrestaShop/PrestaShop/pull/13233): Enable 'back' GET parameter management. Thank you [@tomas862](https://github.com/tomas862)
* [#13454](https://github.com/PrestaShop/PrestaShop/pull/13454): Fix on product redirect in SEO tabs . Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#13472](https://github.com/PrestaShop/PrestaShop/pull/13472): Create SF command to list tactician commands and queries. Thank you [@zuk3975](https://github.com/zuk3975)
* [#13572](https://github.com/PrestaShop/PrestaShop/pull/13572): Add FiltersSubmitButtonEnablerExtension to profiles page. Thank you [@zuk3975](https://github.com/zuk3975)


## Code changes in the "1.7.6.x" branch (for v1.7.6.0)

### Core

* [#13540](https://github.com/PrestaShop/PrestaShop/pull/13540): Update upgrade scripts to PS 1.7.6.0, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)
* [#13560](https://github.com/PrestaShop/PrestaShop/pull/13560): Remove duplicate method call, by [@eternoendless](https://github.com/eternoendless)


### Back office

* [#13484](https://github.com/PrestaShop/PrestaShop/pull/13484): Fixes Categories grid filtering by position. Thank you [@sarjon](https://github.com/sarjon)
* [#13508](https://github.com/PrestaShop/PrestaShop/pull/13508): Enable ChoiceTree javascript in manufacturers form . Thank you [@zuk3975](https://github.com/zuk3975)
* [#13528](https://github.com/PrestaShop/PrestaShop/pull/13528): Fix calendar overflow. Thank you [@zuk3975](https://github.com/zuk3975)
* [#13535](https://github.com/PrestaShop/PrestaShop/pull/13535): Fix responsive showcase cards . Thank you [@YeLnatSs](https://github.com/YeLnatSs)
* [#13547](https://github.com/PrestaShop/PrestaShop/pull/13547): Deprecate Language::installEmailsLanguagePack, by [@jolelievre](https://github.com/jolelievre)
* [#13550](https://github.com/PrestaShop/PrestaShop/pull/13550): Add missing check in Manufacturer image uploader. Thank you [@zuk3975](https://github.com/zuk3975)


#Front office

* [#13411](https://github.com/PrestaShop/PrestaShop/pull/13411): Hide tax label in front when tax display is disabled in the shop, by [@jolelievre](https://github.com/jolelievre)
* [#13525](https://github.com/PrestaShop/PrestaShop/pull/13525): fix currency display on not existing language, by [@tomlev](https://github.com/tomlev)


### Tests

* [#13503](https://github.com/PrestaShop/PrestaShop/pull/13503): FIx test Create Attribute Suite Full. Thank you [@boubkerbribri](https://github.com/boubkerbribri)
* [#13534](https://github.com/PrestaShop/PrestaShop/pull/13534): Fix tests manufacturer. Thank you [@boubkerbribri](https://github.com/boubkerbribri)
* [#13536](https://github.com/PrestaShop/PrestaShop/pull/13536): Fixes e2e broken selectors, by [@mbadrani](https://github.com/mbadrani)
* [#13552](https://github.com/PrestaShop/PrestaShop/pull/13552): Fix tests International/localization and international/taxes. Thank you [@boubkerbribri](https://github.com/boubkerbribri)
* [#13561](https://github.com/PrestaShop/PrestaShop/pull/13561): fix for tests 1 and 2 of the shop_parameters test suite, by [@SimonGrn](https://github.com/SimonGrn)
* [#13568](https://github.com/PrestaShop/PrestaShop/pull/13568): Fix tests 10_module Suite Full. Thank you [@boubkerbribri](https://github.com/boubkerbribri)
* [#13581](https://github.com/PrestaShop/PrestaShop/pull/13581): fix test feature update. Thank you [@ntiepresta](https://github.com/ntiepresta)


## Code changes in the '1.7.5.x' branch (for 1.7.5.2)

### Core

* [#13549](https://github.com/PrestaShop/PrestaShop/pull/13549): Forbid URLs to be inserted into Name fields, by [@matks](https://github.com/matks)
* [#13567](https://github.com/PrestaShop/PrestaShop/pull/13567): Improve name validation, by [@eternoendless](https://github.com/eternoendless)


## Code changes in the '1.6.1.x' branch (for 1.6.1.24)

### Core

* [#13559](https://github.com/PrestaShop/PrestaShop/pull/13559): Forbid URLs to be inserted into Name fields, by [@matks](https://github.com/matks)
* [#13574](https://github.com/PrestaShop/PrestaShop/pull/13574): Improve name validation, by [@eternoendless](https://github.com/eternoendless)
* [#13581](https://github.com/PrestaShop/PrestaShop/pull/13581): fix test feature update. Thank you [@ntiepresta](https://github.com/ntiepresta)


## Code changes in modules, themes & tools

### Auto upgrade

* [#299](https://github.com/PrestaShop/autoupgrade/pull/299): Init Kernel on UpgradeDB when upgrading to 1.7, by [@Quetzacoalt91](https://github.com/Quetzacoalt91)


### UI kit

* [#64](https://github.com/PrestaShop/prestashop-ui-kit/pull/64): asset path in README.md, by [@david-piatek](https://github.com/david-piatek)


### Classic Rocket

* [#47](https://github.com/PrestaShop/classic-rocket/pull/47): Update microdata-jsonld.tpl. Thank you [@bhavikvaghani](https://github.com/bhavikvaghani)
* [#48](https://github.com/PrestaShop/classic-rocket/pull/48): Smarty Replace Warning. Thank you [@bhavikvaghani](https://github.com/bhavikvaghani)


### Preston Bot

* [#80](https://github.com/PrestaShop/prestonbot/pull/80): Disable Classic Theme listener to stop assigning StarterTheme label, by [@matks](https://github.com/matks)


## Changes in Documentation

* [#257](https://github.com/PrestaShop/docs/pull/257): Document DTOs. Thank you [@sarjon](https://github.com/sarjon)
* [#259](https://github.com/PrestaShop/docs/pull/259): Improve PHP compatibility chart, by [@eternoendless](https://github.com/eternoendless)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: @bhavikvaghani, @boubkerbribri, @ntiepresta, @sarjon, @tomas862, @YeLnatSs, @zuk3975!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
