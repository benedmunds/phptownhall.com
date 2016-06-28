---
layout: post
title: "Episode 50: Low down on PSR-15"
date: 2016-03-16T18:00:00-05:00
filename: 50
bytes:
duration:
youtube_id: 1w56anBhWEg
---

An all star cast this episode, as Ben and Phil are joined by regular guest [Anthony Ferrara](https://twitter.com/ircmaxell) - thinker of good ideas and long-time part-time side-line contributor to the PHP-FIG, [Woody Gilk](https://twitter.com/shadowhand) - one-speed rider & BDFL of Kohana, and
[Beau Simensen](https://twitter.com/beausimensen) - author of a bunch of stuff including [StackPHP](http://stackphp.com/).

Here we're talking about some awesome stuff the PHP-FIG is working on: PSR-15 (HTTP Middleware). This PSR is in Draft mode, and is potentially not as well known about as some others. There was a bit of a cuffufle getting it started as before it had even passed an entrance vote there were alternatives and rewrites suggested, but now the major players are on the same page and things are moving forward.

We discuss all this, and the reason PSR-7 (HTTP Message) is not enough for the ecosystem to benefit from shareable middleware. Jumping away from PSR-15 for a second there is an interesting bit of insight into why the PHP-FIG didn't just slap a "PSR" sticker on Symfony's HTTP Kernel or HTTP Foundation.

Woody provides a bit of the decision-making process in a very tricky aspect of the FIGs job, which is: should standards be built entirely to match existing implementations, or should standards try to improve on the learnings of the existing implementations to better them all as implementations change to support the standard. It's all a bit chicken and egg, but a very worthy discussion to have.

- [All About Middleware](http://blog.ircmaxell.com/2016/05/all-about-middleware.html) - Anthony posts about PHP HTTP Middleware
- [Why Care About PHP Middleware?](https://philsturgeon.uk/php/2016/05/31/why-care-about-php-middleware/) - Summary of the initial Anthony vs Woody approaches and background on the HTTP middleware concept
- [StackPHP](http://stackphp.com/) - Composing HttpKernelInterface middlewares since 2013!
- [Equip](http://equip.github.io/) - Equip is a tiny and powerful PHP micro-framework created and maintained by the engineering team at [When I Work](http://wheniwork.com/)
