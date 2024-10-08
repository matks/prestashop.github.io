---
layout: post
aliases: ["/news/prestashop-1-6-1-1-rc2"]
title:  "Test PrestaShop 1.6.1.1 RC2!"
subtitle: "Here we go again"
date:   2015-08-11 15:45:41
authors:  [ alexeven ]
icon: icon-leaf
tags:
 - version
 - rc
 - releases
 - development
 - "1.6.1.x"
 - "1.6"
---


Following the publication of [version 1.6.1.1 Release Candidate 1](http://build.prestashop.com/news/prestashop-1-6-1-1-rc1/), we have fixed a few more issues that had been identified. Thanks for helping with the tests and for the feedback!

[As announced earlier](http://build.prestashop.com/news/announcing-prestashop-1-6-1-1/), version 1.6.1.0 turned out great, but there were still a few bumps here and there. We have fixed the main issues that were reported: 163 pull requests were merged into this version!

We'd like to keep testing it with the help of our Community!
We need you to make sure that this release is as bug free as possible. Everyone can participate: merchants, developers, designers, translators, ... even customers! Test your modules, test your themes, make a test-upgrade on a copy of a real shop, etc.

Remember that 1.6.1.1 RC2 is a test version, and is therefore not yet deemed suitable for production use. Hence, do not upgrade your store just yet! Install the RC2 on your server (on as many server configurations as possible), or upgrade from a clone of your real store.

{{< cta "https://www.prestashop.com/versions" >}}Download and test PrestaShop 1.6.1.1 RC2 now!{{< /cta >}}

Remember: if you have any feedback to give, [create a ticket on the Forge](http://doc.prestashop.com/display/PS16/How+to+use+the+Forge+to+contribute+to+PrestaShop)!

Here is the full list of [the additional 23 pull requests that were merged into version 1.6.1.1](https://github.com/PrestaShop/PrestaShop/pulls?utf8=%E2%9C%93&q=is%3Apr+merged%3A%3E2015-08-05+base%3A1.6.1.x+), since RC1:

* [3229](https://github.com/PrestaShop/PrestaShop/pull/3229): [-] BO : Fix #PSCSX-5615 tinymce allow all html element
* [3604](https://github.com/PrestaShop/PrestaShop/pull/3604): FO : Fix bug #PSCSX-5153, bad free shipping display when carrier out of range
* [3614](https://github.com/PrestaShop/PrestaShop/pull/3614): BO : Set file as required in attachment form
* [3616](https://github.com/PrestaShop/PrestaShop/pull/3616): PDF: Fix shop_address missing in old order_invoice outside of upgrade process
* [3617](https://github.com/PrestaShop/PrestaShop/pull/3617): CORE: Fix namespace usage in new Core Stock management for PHP 5.2 until v1.7
* [3618](https://github.com/PrestaShop/PrestaShop/pull/3618): [-] BO : #PSCSX-6453 Import duplicates parent categories
* [3619](https://github.com/PrestaShop/PrestaShop/pull/3619): [-] BO : Fix filters errors
* [3621](https://github.com/PrestaShop/PrestaShop/pull/3621): [-] IN : [-] Import product: fix default category update with first one.
* [3623](https://github.com/PrestaShop/PrestaShop/pull/3623): [-] TEST : Clear hook_alias cache
* [3624](https://github.com/PrestaShop/PrestaShop/pull/3624): [-] BO : #PSCSX-6385 remove ability to order position while filtering
* [3625](https://github.com/PrestaShop/PrestaShop/pull/3625): [-] Partial refund: take "," into account for decimals #PSCSX-6313
* [3626](https://github.com/PrestaShop/PrestaShop/pull/3626): [-] FO : Fix missing cart rule lines in shopping cart
* [3627](https://github.com/PrestaShop/PrestaShop/pull/3627): [*] LO: add tabs translations in several languages
* [3628](https://github.com/PrestaShop/PrestaShop/pull/3628): [-] CORE : wrong currency on partial voucher using a different currency in an order
* [3631](https://github.com/PrestaShop/PrestaShop/pull/3631): // wrong padding for list in table
* [3633](https://github.com/PrestaShop/PrestaShop/pull/3633): [-] BO : #PSCSX-6441 small css fix
* [3634](https://github.com/PrestaShop/PrestaShop/pull/3634): [-] BO : #PSCSX-6441 small css fix
* [3635](https://github.com/PrestaShop/PrestaShop/pull/3635): [-] BO : #PSCSX-6441 small css fix
* [3645](https://github.com/PrestaShop/PrestaShop/pull/3645): [-] FO : Fix temp table on slave issue
* [3650](https://github.com/PrestaShop/PrestaShop/pull/3650): [-] BO : Fix #PSCSX-6474 currency input in orders
* [3652](https://github.com/PrestaShop/PrestaShop/pull/3652): // Convert & to HTML entities
* [3662](https://github.com/PrestaShop/PrestaShop/pull/3662): [-] PDF: EN to dejavusans
* [3663](https://github.com/PrestaShop/PrestaShop/pull/3663): [*] BO: Remove version under the employee drop down


The [PrestaShop 1.6.1.1 RC2 changelog](https://www.prestashop.com/en/developers-versions/changelog/1.6.1.1-rc2) is also available.
As a reminder, you'll find all you need to know about the [previous Release Candidate (RC1) here](http://build.prestashop.com/news/prestashop-1-6-1-1-rc1/).

This release was made possible by the hard work of the PrestaShop Core Team, with the essential help of the following contributors: Alphacom IT Solutions, Bruno Desprez, Conner Burnett, David-Julian BUCH, Eric  Rouvier, Gytis Škema, joseantgv, Julie Vernois, kermes, Kijam Lopez, manuelbcd Mikael Blotin, oleacorner, Pan Ploenes, PrestaEdit, prestamodule, and Quentin MONTANT. Thank gals and guys!

Now, go forth and test! Thank you again!
