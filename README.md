# Pelican Pure

A [pure](http://purecss.io/) based theme for [Pelican](http://blog.getpelican.com/), based on [pelican-bootstrap3](https://github.com/DandyDev/pelican-bootstrap3) (unsurprisingly, a bootstrap based theme for Pelican)

Installation: Put the theme in a folder. Link that folder in your `pelicanconf.py` by setting the `THEME`-Variable like `THEME='link/to/pelican-pure'`

## Variables and Config
###Breadcrumbs
DISPLAY_BREADCRUMBS displays breadcrumbs if true.

###Favicon
Set the path to a favicon. You can use as well the variable FAVICON_IE to set the path to an `.ico` file and TOUCHICON to set the path to an touchicon for mobile aple devices.


### Index pages
DISPLAY_FULL_ARTICLES_ON_INDEX if true, the index page does not display summaries of the articles, but the full articles.

DISPLAY_ARTICLE_INFO_ON_INDEX if true, article info (date, tags) will be show under the title for each article instead of only title and summary.

### Sidebar
HIDE_SIDEBAR if true, the sidebar is hidden and the layout has a single colum.

### Menu
DISPLAY_INDEX_ON_PAGES_MENU: if true, the index.html page gets a link with the title "blog" in the menu.

DISPLAY_PAGEGROUPS_MENU: if true it generates a menu with nested groups. To recognize which pages belong to a group, you need to add the attribute "groupname" to your pages. As well each page should have a "page-order" attribute. Loads a script providing accessible navigation for the menu.

DISPLAY_MENU_EXCLUDE_SUBGROUPS: if true, generates a  menu with only the pages that have the same title as the entrys in the PAGE_ORDER array. Needs a PAGE_ORDER array.
If the page has a groupname, it is only included in the main menu, if the slug is the same as the the groupname.

This should be used with one these two options:

DISPLAY_RELATED_PAGES_ON_SIDEBAR: if true generates a generates a menu with all pages with the same groupname as the currently displayed page. It places the links in the sidebar.

DISPLAY_RELATED_PAGES_IN_HEADER: if true, generates a generates a menu with all pages with the same groupname as the currently displayed page. It places the links below the normal menu in the header.

MENUITEMS: if the MENUITEMS array exists, it generates a menu. Example for the array: ´(('pageTitle','http://linktopagetitle.com'),('otherTitle','http://anotherpagelinked.org')´ ...etc.. ´)´

DISPLAY_PAGES_ON_MENU: if true, simple list of  pages in the menu.

DISPLAY_CATEGORIES_ON_MENU: if true, simple list of with links to overviews of blog post categories in the menu.

## About Me
ABOUT_ME if set to a string, this text will be included in the sidebar.
If AVATAR is set to a link (`ìmages/myPortrait.jpg`) this will be included as well.  





## License

**The MIT License (MIT)**

Copyright (c) 2014 Jan Dittrich

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

-------------------------------

The Templates are based on  [pelican-bootstrap3](https://github.com/DandyDev/pelican-bootstrap3)’s Templates by [Daan Debie](https://github.com/DandyDev)

The used [Pure Framework](http://purecss.io) is licensed under a [BSD License](https://github.com/yahoo/pure/blob/master/LICENSE.md)
