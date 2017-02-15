# TX-041 Squadron Website - Jekyll Theme

- A [Jekyll](https://jekyllrb.com) version of the "Future Imperfect" theme by [HTML5 UP](https://html5up.net).
- Hosted on [GitHub Pages](https://pages.github.com).
- HTTPS, content delivery and caching provided by [CloudFlare](https://www.cloudflare.com).
- Fonts by [Google Fonts](https://fonts.google.com).
- Facebook news feed by [social-feed](https://github.com/pavelk2/social-feed).
- Senior staff listing provided by Texas Wing API feed.
- Icons provided by [Font Awesome](https://fortawesome.github.com/Font-Awesome).

## How-To

Unless you are an HTML designer who understands Liquid Markup and the Jekyll Ruby Gem library, 
you should only edit files inside the `_data` folder. You may also want to read the 
[GitHub Guide](https://guides.github.com/activities/hello-world/) for getting started with using 
GitHub.

## What Is What

- `_data/faqs.yml` is the file that contains the questions and answers on the FAQs page.
- `_data/main.yml` has all main (Front Page) website data.
- `_data/meeting.yml` has the meeting data for the Contact page.
- `_data/resources.yml` has the links/bookmarks for the Resources page.
- `_data/socialfeed.yml` has the Facebook account and API information for the Front Page.
- `_data/staff.yml` has the position titles, ordering, and formatting for the staff page, but not
the names of the people holding the positions; that data is pulled from the Texas Wing website.

- The `_includes`, `_layouts`, and `_sass` folders are for Jekyll designers and contains the templates 
used for creating individual page layouts and their associated CSS stylesheets.

- The `about`, `missions`, `calendar`, `resources`, `faqs`, `join`, and `contact` folders contain the 
actual pages (as either `index.html` or `index.md`) for each of the major sections on the website. These 
files can be edited by anyone with a basic understanding of HTML, but care must be taken to not break 
the Jekyll dependencies... only simple content changes should be attempted without a full understanding 
of Jekyll.

- The `assets` folder contains static CSS pages for Font Awesome and IE8/9 shims, the main SCSS stylesheet, 
and JavaScript for the fundamental site theme.  Nothing should be altered in here unless `main.scss` needs 
to be updated.

- The `bower_components` folder contains all the required files for SocialFeed.

- The `images` folder is the home for all image files on the website.

- The `search` folder is the results page for the in-site Google Custom Search.

- `_config.yml` is the main config file for the Jekyll site and does not need any altering unless 
the site's navigation menu is to be changed.

- `index.html` is the Front Page for the website.

- `template.html` is the template for a SocialFeed item.

## Other Credits
	jQuery (jquery.com)
	html5shiv.js (@afarkas @jdalton @jon_neal @rem)
	Misc. Sass functions (@HugoGiraudel)
	Respond.js (j.mp/respondjs)
	Skel (skel.io)
