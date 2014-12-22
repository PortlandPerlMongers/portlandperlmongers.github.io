# PDX.pm Website

This is the code that builds http://pdx.pm.org. Patches welcome.

http://pdx.pm.org is hosted using [Github Pages][4] and powered by [Jekyll][1], [Twitter Bootstrap][2], and [Font Awesome][3].

# Adding a Meetings

To add a meeting announcement, submit a pull request that adds a Markdown file
to the `_posts` path. The file must be named in the format
`YYYY-MM-DD-<title>.md` and should have the proper metadata at the top of the
file:

```
---
title: Jan 2015 - Title
layout: article
category: meetings
excerpt: This is the excerpt.
---

This is the body.
```

# Contributing

If you would like to contribute to this repo, fork and please send a pull request!

# Attribution

This site is build on the template that
<a href='https://github.com/bak'>@bak</a> built for
<a href='https://github.com/pdxgit/pdxgit.github.com'>@pdxgit</a>.

# License

<a href="http://creativecommons.org/licenses/by-nc-sa/3.0/legalcode">
<img src="http://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png">
</a>

If you would like to use this content under a different license, feel free to contact the [Mailing list][5]

[1]: http://jekyllrb.com
[2]: http://twitter.github.com/bootstrap/
[3]: http://fortawesome.github.com/Font-Awesome/
[4]: http://pages.github.com
[5]: https://github.com/PortlandPerlMongers/portlandperlmongers.github.io/wiki/MailingList
