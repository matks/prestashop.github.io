---
layout: post
aliases: ["/news/coreweekly-36-2020"]
title:  "PrestaShop Core Weekly - Week 36 of 2020"
subtitle: "An inside look at the PrestaShop codebase"
date:   2020-09-08
authors: [ PrestaShop ]
image: /assets/images/2017/04/core_weekly_banner.jpg
twitter_image: /assets/images/theme/banner-core-weekly.jpg
icon: icon-calendar
tags:
 - core-monthly
---

This edition of the Core Weekly report highlights changes in PrestaShop's core codebase from Monday 31th August to Sunday 6th of September 2020.

![Core Weekly banner](/assets/images/2018/12/banner-core-weekly.jpg)

## General messages

Dear Developers,

In case you missed it, [1.7.7 beta 2 has been released last week](https://build.prestashop.com/news/prestashop-1-7-7-0-beta2-release/)!

Testing this second beta version before the release of the stable version is very important. As usual, we strongly recommend checking that all your modules and themes are working properly, especially if you develop them yourself. Please download, install and test this new beta and [report the issues you might find](https://github.com/PrestaShop/PrestaShop/issues/new?template=bug_report.md). Also, of course, your help is welcome to fix issues.


## Releases

* [Ps_facetedsearch](https://github.com/PrestaShop/ps_facetedsearch): [v3.6.0](https://github.com/PrestaShop/ps_facetedsearch/releases/tag/v3.6.0)
* [Php-dev-tools](https://github.com/PrestaShop/php-dev-tools): [v3.9](https://github.com/PrestaShop/php-dev-tools/releases/tag/v3.9)


## A quick update about PrestaShop's GitHub issues and pull requests:

- [51 new issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+created%3A2020-08-31..2020-09-06) have been created in the project repositories;
- [60 issues have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+closed%3A2020-08-31..2020-09-06), including [33 fixed issues](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Aissue+label%3Afixed+closed%3A2020-08-31..2020-09-06) on the core;
- [108 pull requests have been opened](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+created%3A2020-08-31..2020-09-06) in the project repositories;
- [152 pull requests have been closed](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+closed%3A2020-08-31..2020-09-06), including [88 merged pull requests](https://github.com/search?q=org%3APrestaShop+is%3Apublic++-repo%3Aprestashop%2Fprestashop.github.io++is%3Apr+merged%3A2020-08-31..2020-09-06).


## Code changes in the 'develop' branch


### Core
* [#20822](https://github.com/PrestaShop/PrestaShop/pull/20822): Fix a typo in README.md file, by [@SimonGrn](https://github.com/SimonGrn)
* [#20806](https://github.com/PrestaShop/PrestaShop/pull/20806): The value of tabCore->name can be array when multilang. Thank you [@zalexki](https://github.com/zalexki)
* [#20716](https://github.com/PrestaShop/PrestaShop/pull/20716): Update composer.lock to prevent fixed bugs. Thank you [@mvorisek](https://github.com/mvorisek)
* [#20689](https://github.com/PrestaShop/PrestaShop/pull/20689): Try to use the real command to clear the cache when the kernel is available, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20656](https://github.com/PrestaShop/PrestaShop/pull/20656): Class HelperTreeCategoriesCore is not translated. Thank you [@PululuK](https://github.com/PululuK)
* [#20638](https://github.com/PrestaShop/PrestaShop/pull/20638): Wrong install redirection when we are in admin directory, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20634](https://github.com/PrestaShop/PrestaShop/pull/20634): Allow to disable make usage and use .env file, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20622](https://github.com/PrestaShop/PrestaShop/pull/20622): Do not proceed setCurrentState if order already has the right state. Thank you [@prestaquality](https://github.com/prestaquality)


### Back office
* [#20829](https://github.com/PrestaShop/PrestaShop/pull/20829): Fix code style in Tree.php. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20815](https://github.com/PrestaShop/PrestaShop/pull/20815): Fix product.yml ident to 4 spaces. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20774](https://github.com/PrestaShop/PrestaShop/pull/20774): Do not put the user as connected if he's not connected, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20713](https://github.com/PrestaShop/PrestaShop/pull/20713): Fix merge error, by [@atomiix](https://github.com/atomiix)
* [#20699](https://github.com/PrestaShop/PrestaShop/pull/20699): Fix width of invoice quantity column on certain langs, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20681](https://github.com/PrestaShop/PrestaShop/pull/20681): Fixed language deletion with open_basedir restriction. Thank you [@rozwell](https://github.com/rozwell)
* [#20680](https://github.com/PrestaShop/PrestaShop/pull/20680): Fixed the reset of the unit_price_ratio when the product is activated / deactivated from the product listing page. Thank you [@artaban](https://github.com/artaban)
* [#20614](https://github.com/PrestaShop/PrestaShop/pull/20614): Wrong validation while uploading product image more than defined size limit.. Thank you [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul)
* [#20553](https://github.com/PrestaShop/PrestaShop/pull/20553): Add GetProductSupplierOptions query. Remove it from ProductForEditing. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20546](https://github.com/PrestaShop/PrestaShop/pull/20546): Add RemoveAllProductsFromPackCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20473](https://github.com/PrestaShop/PrestaShop/pull/20473): Add UpdateProductSeoCommand. Thank you [@zuk3975](https://github.com/zuk3975)
* [#20188](https://github.com/PrestaShop/PrestaShop/pull/20188): Notifications bell icon read fix. Thank you [@rajat315315](https://github.com/rajat315315)
* [#19404](https://github.com/PrestaShop/PrestaShop/pull/19404): Put back prefix for filter name inside CustomerQueryBuilder. Thank you [@juliendombret](https://github.com/juliendombret)


### Front office
* [#20813](https://github.com/PrestaShop/PrestaShop/pull/20813): Bump elliptic from 6.5.2 to 6.5.3 in /admin-dev/themes/default. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#20812](https://github.com/PrestaShop/PrestaShop/pull/20812): Bump elliptic from 6.4.0 to 6.5.3 in /themes/classic/_dev. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#20773](https://github.com/PrestaShop/PrestaShop/pull/20773): Make sure sanitizeUrl method allows array in $_GET, and make methods protected to be reused, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#20660](https://github.com/PrestaShop/PrestaShop/pull/20660): Remove available_date from presented product if in the past. Thank you [@awitkutarahil](https://github.com/awitkutarahil)
* [#20530](https://github.com/PrestaShop/PrestaShop/pull/20530): Fix facets.js pendingQuery was always false. Thank you [@davidglezz](https://github.com/davidglezz)
* [#20499](https://github.com/PrestaShop/PrestaShop/pull/20499): Ecotax is displayed tax excl instead of tax incl in FO. Thank you [@PululuK](https://github.com/PululuK)
* [#20309](https://github.com/PrestaShop/PrestaShop/pull/20309): Improve sitemap-nested-list.tpl. Thank you [@davidglezz](https://github.com/davidglezz)
* [#20203](https://github.com/PrestaShop/PrestaShop/pull/20203): Adding a link to the general terms and conditions in the checkout footer (Opquast n°45). Thank you [@Sinepel](https://github.com/Sinepel)


### Tests
* [#20860](https://github.com/PrestaShop/PrestaShop/pull/20860): Fix memory_limit while installing with CLI on docker, by [@boubkerbribri](https://github.com/boubkerbribri)


## Code changes in the '1.7.7.x' branch


### Core
* [#20794](https://github.com/PrestaShop/PrestaShop/pull/20794): Send an 'action' parameter to actionProductCancel hook, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#20741](https://github.com/PrestaShop/PrestaShop/pull/20741): Fix cumulative free gift + percentage discounts, by [@atomiix](https://github.com/atomiix)
* [#20738](https://github.com/PrestaShop/PrestaShop/pull/20738): Disable jquery migrate deprecation messages when prestashop debug mode is off, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#20693](https://github.com/PrestaShop/PrestaShop/pull/20693): Cancel/Refunds... adding missing hooks and cancel product refactor, by [@matthieu-rolland](https://github.com/matthieu-rolland)


### Back office
* [#20798](https://github.com/PrestaShop/PrestaShop/pull/20798): Do not recalculate shipping if PS_ORDER_RECALCULATE_SHIPPING is false, by [@atomiix](https://github.com/atomiix)
* [#20796](https://github.com/PrestaShop/PrestaShop/pull/20796): Fix OrderReturnState should not use soft delete, by [@atomiix](https://github.com/atomiix)
* [#20792](https://github.com/PrestaShop/PrestaShop/pull/20792): Fix cannot add twice a product out of stock but allowed to be ordered, by [@atomiix](https://github.com/atomiix)
* [#20757](https://github.com/PrestaShop/PrestaShop/pull/20757): Save customer message on order creation from BO, by [@sowbiba](https://github.com/sowbiba)
* [#20734](https://github.com/PrestaShop/PrestaShop/pull/20734): Allow to create Order from BO using soft deleted address, by [@matks](https://github.com/matks)
* [#20714](https://github.com/PrestaShop/PrestaShop/pull/20714): Fix max attribute on qty input of an out of stock attribute available on create order, by [@NeOMakinG](https://github.com/NeOMakinG)
* [#20704](https://github.com/PrestaShop/PrestaShop/pull/20704): Expose missing route, by [@atomiix](https://github.com/atomiix)
* [#20603](https://github.com/PrestaShop/PrestaShop/pull/20603): Redirect to customer when canceling new customer address creation. Thank you [@ks129](https://github.com/ks129)


### Tests
* [#20850](https://github.com/PrestaShop/PrestaShop/pull/20850): Add behat tests for order shipping computing, and add new carriers fixtures, by [@jolelievre](https://github.com/jolelievre)
* [#20802](https://github.com/PrestaShop/PrestaShop/pull/20802): Add test 'CRUD cart rule'. Thank you [@nesrineabdmouleh](https://github.com/nesrineabdmouleh)


## Code changes in modules, themes & tools


### Changes in developer documentation
* [#706](https://github.com/PrestaShop/docs/pull/706): Use meta properties instead of meta names, by [@matks](https://github.com/matks)
* [#705](https://github.com/PrestaShop/docs/pull/705): Add meta og because it seems Twitter wants them, by [@matks](https://github.com/matks)
* [#704](https://github.com/PrestaShop/docs/pull/704): Fix twitter meta tag, by [@matks](https://github.com/matks)
* [#703](https://github.com/PrestaShop/docs/pull/703): Add twitter card meta tags, by [@matks](https://github.com/matks)
* [#702](https://github.com/PrestaShop/docs/pull/702): Update PHP compatibility chart for 1.7.8, by [@eternoendless](https://github.com/eternoendless)
* [#701](https://github.com/PrestaShop/docs/pull/701): Add "How become a maintainer", by [@eternoendless](https://github.com/eternoendless)
* [#700](https://github.com/PrestaShop/docs/pull/700): Fixed property in sample for Creating a new resource, by [@Progi1984](https://github.com/Progi1984)
* [#699](https://github.com/PrestaShop/docs/pull/699): Add cancellations and refunds documentation, by [@matthieu-rolland](https://github.com/matthieu-rolland)
* [#698](https://github.com/PrestaShop/docs/pull/698): Declare strict types don't apply on interfaces, by [@Progi1984](https://github.com/Progi1984)
* [#697](https://github.com/PrestaShop/docs/pull/697): Maintainer guide: Explain what maintainer must do when merging a PR, by [@matks](https://github.com/matks)
* [#696](https://github.com/PrestaShop/docs/pull/696): For png-images with transparent background made background white.. Thank you [@likemusic](https://github.com/likemusic)
* [#695](https://github.com/PrestaShop/docs/pull/695): Svg images instead of png.. Thank you [@likemusic](https://github.com/likemusic)
* [#694](https://github.com/PrestaShop/docs/pull/694): Fix broken links. Thank you [@likemusic](https://github.com/likemusic)
* [#693](https://github.com/PrestaShop/docs/pull/693): Fix paths for `ref` and `relref` shortcodes to have anchors in generated html-files.. Thank you [@likemusic](https://github.com/likemusic)
* [#688](https://github.com/PrestaShop/docs/pull/688): Fix `callout` description.. Thank you [@likemusic](https://github.com/likemusic)


### Faceted search module
* [#204](https://github.com/PrestaShop/ps_facetedsearch/pull/204): Update dependencies from dependabot notifications, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#203](https://github.com/PrestaShop/ps_facetedsearch/pull/203): Use the new version of CleanWebpackPlugin, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#200](https://github.com/PrestaShop/ps_facetedsearch/pull/200): Bump @babel/register from 7.9.0 to 7.11.5. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#195](https://github.com/PrestaShop/ps_facetedsearch/pull/195): Bump sass-loader from 7.1.0 to 7.3.1. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#194](https://github.com/PrestaShop/ps_facetedsearch/pull/194): Bump clean-webpack-plugin from 2.0.0 to 3.0.0. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#193](https://github.com/PrestaShop/ps_facetedsearch/pull/193): Bump mockery/mockery from 1.3.2 to 1.3.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#192](https://github.com/PrestaShop/ps_facetedsearch/pull/192): Bump webpack-cli from 3.2.3 to 3.3.12. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#191](https://github.com/PrestaShop/ps_facetedsearch/pull/191): Bump to 3.6.0, by [@PierreRambaud](https://github.com/PierreRambaud)
* [#190](https://github.com/PrestaShop/ps_facetedsearch/pull/190): Make rebuild index counter work, by [@PierreRambaud](https://github.com/PierreRambaud)


### OnBoarding module
* [#68](https://github.com/PrestaShop/welcome/pull/68): Bump css-loader from 0.23.1 to 0.28.11. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestonBot
* [#101](https://github.com/PrestaShop/prestonbot/pull/101): Set max execution time to 3min for new wording detection, by [@atomiix](https://github.com/atomiix)
* [#100](https://github.com/PrestaShop/prestonbot/pull/100): Fix bad QA label, by [@atomiix](https://github.com/atomiix)


### Issues Bot
* [#7](https://github.com/PrestaShop/issuebot/pull/7): Bump lodash from 4.17.15 to 4.17.20. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Example modules
* [#25](https://github.com/PrestaShop/example-modules/pull/25): Bump lodash from 4.17.15 to 4.17.20 in /demodoctrine/js. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#24](https://github.com/PrestaShop/example-modules/pull/24): Bump elliptic from 6.5.2 to 6.5.3 in /demodoctrine/js. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#22](https://github.com/PrestaShop/example-modules/pull/22): Demosymfonyform module. Thank you [@JevgenijVisockij](https://github.com/JevgenijVisockij)


### Stylelint browser ccompatibility
* [#2](https://github.com/PrestaShop/stylelint-browser-compatibility/pull/2): Bump lodash from 4.17.15 to 4.17.20. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#1](https://github.com/PrestaShop/stylelint-browser-compatibility/pull/1): Bump kind-of from 6.0.2 to 6.0.3. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### PrestaShop contributors website
* [#18](https://github.com/PrestaShop/TopContributors/pull/18): Bump lodash from 4.17.10 to 4.17.20. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#17](https://github.com/PrestaShop/TopContributors/pull/17): Bump lodash.mergewith from 4.6.1 to 4.6.2. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)
* [#16](https://github.com/PrestaShop/TopContributors/pull/16): Bump fstream from 1.0.11 to 1.0.12. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Product Comments module
* [#70](https://github.com/PrestaShop/productcomments/pull/70): Bump symfony/css-selector from 3.4.43 to 3.4.44. Thank you [@dependabot[bot]](https://github.com/apps/dependabot)


### Traces
* [#12](https://github.com/PrestaShop/traces/pull/12): Added generation date, by [@Progi1984](https://github.com/Progi1984)


### Contact Form module
* [#48](https://github.com/PrestaShop/contactform/pull/48): Add customer name to form. Thank you [@bodi000](https://github.com/bodi000)


### Contact informations module
* [#37](https://github.com/PrestaShop/ps_contactinfo/pull/37): Update templates to reflect changes in classic theme. Thank you [@ziegenberg](https://github.com/ziegenberg)


### Carrier comparison module
* [#6](https://github.com/PrestaShop/ps_carriercomparison/pull/6): Dir constant. Thank you [@MathiasReker](https://github.com/MathiasReker)
* [#5](https://github.com/PrestaShop/ps_carriercomparison/pull/5): No alias functions. Thank you [@MathiasReker](https://github.com/MathiasReker)


### Custom text module
* [#16](https://github.com/PrestaShop/ps_customtext/pull/16): No alias functions. Thank you [@MathiasReker](https://github.com/MathiasReker)


<hr />

Thank you to the contributors whose pull requests were merged since the last Core Weekly Report: [@boubkerbribri](https://github.com/boubkerbribri), [@matks](https://github.com/matks), [@eternoendless](https://github.com/eternoendless), [@PierreRambaud](https://github.com/PierreRambaud), [@dependabot[bot]](https://github.com/apps/dependabot), [@jolelievre](https://github.com/jolelievre), [@atomiix](https://github.com/atomiix), [@zuk3975](https://github.com/zuk3975), [@SimonGrn](https://github.com/SimonGrn), [@Progi1984](https://github.com/Progi1984), [@matthieu-rolland](https://github.com/matthieu-rolland), [@zalexki](https://github.com/zalexki), [@nesrineabdmouleh](https://github.com/nesrineabdmouleh), [@likemusic](https://github.com/likemusic), [@sowbiba](https://github.com/sowbiba), [@mvorisek](https://github.com/mvorisek), [@NeOMakinG](https://github.com/NeOMakinG), [@rozwell](https://github.com/rozwell), [@artaban](https://github.com/artaban), [@awitkutarahil](https://github.com/awitkutarahil), [@PululuK](https://github.com/PululuK), [@prestaquality](https://github.com/prestaquality), [@Amit-Kumar-Tiwari-Webkul](https://github.com/Amit-Kumar-Tiwari-Webkul), [@ks129](https://github.com/ks129), [@JevgenijVisockij](https://github.com/JevgenijVisockij), [@davidglezz](https://github.com/davidglezz), [@bodi000](https://github.com/bodi000), [@Sinepel](https://github.com/Sinepel), [@rajat315315](https://github.com/rajat315315), [@ziegenberg](https://github.com/ziegenberg), [@juliendombret](https://github.com/juliendombret), [@MathiasReker](https://github.com/MathiasReker)!

Thank you to the contributors whose PRs haven't been merged yet! And of course, a big thank you to all those who contribute with issues and comments [on GitHub](https://github.com/PrestaShop/PrestaShop)!

If you want to contribute to PrestaShop with code, please read these pages first:

 * [Contributing code to PrestaShop](https://devdocs.prestashop.com/1.7/contribute/contribution-guidelines/)
 * [Coding standards](https://devdocs.prestashop.com/1.7/development/coding-standards/)

...and if you do not know how to fix an issue but wish to report it, please read this: [How to use GitHub to report an issue](https://devdocs.prestashop.com/1.7/contribute/contribute-reporting-issues/). Thank you!

Happy contributin' everyone!
