pelican-neat
============

A neat and flexible [pelican](http://docs.getpelican.com) theme based
on the [personal blog](https://github.com/berkerpeksag/berkerpeksag) 
theme of [Berker Peksag](http://twitter.com/berkerpeksag).

Preview
-------

  - Index:
    ![index screenshot](https://github.com/BYK/pelican-neat/raw/master/screenshots/index.png)
  - Article:
    ![article screenshot](https://github.com/BYK/pelican-neat/raw/master/screenshots/article.png)
  - Article Scrolled:
    ![index screenshot](https://github.com/BYK/pelican-neat/raw/master/screenshots/article-scroll.png)

Configuration Options
---------------------

  - `SITE_SOURCE` _(URL)_ - URL to site's source if exists
  - `SITE_TAGLINE` _(multi-line string)_ - Tagline for the site
  - `SITE_ICON` _(URL)_ - URL for the site's favicon. _(can be a data URL)_
  - `PRINT` _(boolean)_ - Set to `True` to enable a print link in pages.
  - `AUTHOR_SHORTBIO` _(multi-line string)_ - Info about the author to be
    displayed on footer.
  - `AUTHOR_EMAIL` _(email)_ - E-mail address of the author to be displayed on
    the pages.
  - `AUTHOR_EMAIL_HASH` _(string)_ - The md5 hash of the author e-mail to fetch
    his/her avatar from [Gravatar](http://gravatar.com). Recommended value is
    `md5(AUTHOR_EMAIL).hexdigest()` with `from hashlib import md5`
  - `TWITTER_USERNAME` _(string)_ - Twitter username of the auther to be used
    in various places such as share referrals and bio section.
  - `GITHUB_USERNAME` _(string)_ - GitHub username of the author to be used in
    various places such as the bio section and the
    [GitHub Badge](http://githubbadge.appspot.com) if enabled.
  - `GITHUB_BADGE` _(boolean)_ - Set to `True` if you want to display the badge
    for your `GITHUB_USERNAME` in the bottom right corner of the pages.

Who's Using Neat
----------------

  - [Read at BYK's](http://read.byk.im)
  - [web development notes by Murat Çorlu](http://muratcorlu.com/)
  - [dominicrodger.com](http://dominicrodger.com)

License
-------

All files that are part of this project are covered by the following license,
except where explicitly noted.

> This Source Code Form is subject to the terms of the Mozilla Public
> License, v. 2.0. If a copy of the MPL was not distributed with this
> file, You can obtain one at http://mozilla.org/MPL/2.0/.
