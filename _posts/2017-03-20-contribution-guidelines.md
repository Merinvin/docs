---
layout: single
title: Contribution Guidelines
permalink: /community/contribution-guidelines/
category:
- community
- home
tag:
- info
- contribution
---

Have you just learnt about some new technical topic? Do you think others could benefit from that knowledge? Do you want some publicity for sharing that knowledge? You're in the right place.

If it is your first time contributing, you'll need to add yourself as an author.

## Add Yourself as an Author (first time only)
Add yourself in the `_data/authors.yml` file and add links\* that you wish to promote next to your post.

Here is my author template (yes, that one on the left) that you can fill in however you like (all external links are optional).

``` yml
author:
  name             : "Max Goodridge"
  avatar           : "/assets/images/max.jpg"
  bio              : "Feel free to contribute to this site by writing a post and opening a pull request on GitHub."
  location         : "Gloucestershire, UK"
  youtube          : "https://www.youtube.com/channel/UCAx4nmhI7S1RcPiaG-Uw0tg"
  email            : "youtube@maxgoodridge.com"
  github           : "maxg203"
  instagram        : "maxg303"
  linkedin         : "max-goodridge-6199bb122"
  stackoverflow    : "4548304/max-goodridge"
  twitter          : "@maxg203"
```

\* A full list of link types that you may promote is listed in the main site configuration file `_config.yml`.

## Edit Directly on GitHub
1. Go to [this page](https://github.com/maxg203/docs/edit/master/_posts/2017-03-20-contribution-guidelines.md) on GitHub.
2. Copy the [Jekyll front matter](https://jekyllrb.com/docs/frontmatter/) from that file.
3. Create a [new markdown file](https://github.com/maxg203/docs/new/master/_posts) right on GitHub. It will expect you to fork the repository, that is fine. Make sure you put the file in the `_posts` folder so that your post will show up in the right place on the website.
4. Paste the previously copied front matter.
5. Change the `title` and `tags` to better reflect the technical topic that you want to write about.
6. Be sure to add `author: Your Name` so that your author biography will show up next to your post.
6. Add your content

## Clone the Repository
You can also clone [the GitHub repository](http://github.com/maxg203/docs), make your changes and create a pull request. Follow some of the instructions above to ensure your markdown file is in the expected format.

The method is the same as what you would have done on GitHub directly, except that you'll probably find it easier to make changes in your own development environment.

## Issues
If you find any issues, please feel free to open them in the [GitHub issue tracker](https://github.com/maxg203/docs/issues) for this repository.
