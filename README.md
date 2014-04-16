# **Bootstrings** - querystrings for Bootstrap

#### Chrome Extension: [Install Bootstrings](https://chrome.google.com/webstore/detail/bootstrings/bafdolhkidkdhgfbcfkmggojbipofdpb)

## Table of contents

 - [What are Bootstrings](#what-are-bootstrings)
 - [How to Install Bootstring](#how-to-install-bootstrings)
 - [How to Use Bootstrings](#how-to-use-bootstrings)
 - [Licenses](#licenses)

## What are Bootstrings?

#### Bootstrings allow you to reach deeper into Bootstrap-powered websites

Have you ever wished you could link to a page on a Bootstrap-powered website and have a modal displaying directly after load, or link somebody to a page that uses Bootstrap's tab component with a specific tab pre-selected when they get there? Bootstrings allows you to link directly to different states of Bootstrap components by using querystrings, and there are two ways to add this functionality to your web browsing experience:

#### Regular Users: Add Bootstrings to your browser for every Bootstrap-powered website you visit

You can install Bootstings as a Chrome extension, which will allow you to use querystrings with any Bootstrap-powered website you visit, and you're able to share Bootstring-enhanced links with any other user who has Bootstrings installed.

> If you notice a website where Bootstrings could really help a lot of users, feel free to contact the website admin and direct them here. Read below to find out how a site owner can add Bootstrings directly to their website to enable that functionality for all site visitors!

#### Developers and Site Owners: Add Bootstrings to your Bootstrap-powered website for every visitor

At the heart of Bootstrings is a simple set of JavaScript rules that interpret any query strings you add to the URL when the page loads. If you add this to your site, you will be able to make use of these query strings in links that all visitors can access, even if they don't have the Bootstring extension installed (and in all browsers, not just Chrome).


## How to Install Bootstrings

### How To Install Bootstrings as a Chrome Extension

#### 1) Search for Bootstrings in the Chrome Web Store

Visit the [Chrome Web Store](https://chrome.google.com/webstore/category/extensions) and search for '[Bootstrings](https://chrome.google.com/webstore/detail/bootstrings/bafdolhkidkdhgfbcfkmggojbipofdpb)'

#### 2) Install the Bootstrings Extension

Select the Bootstrings extension and install the extension from the info window by clicking the blue button that says '+ Free'. This will add Bootstrings to your Chrome browser.

#### 3) Try it out

Visit a web page with Bootstrap components on it and use some custom querystrings to verify that it works. For example, visit [https://secure.ballr.com/?modal=terms](https://secure.ballr.com/?modal=terms) to view [Ballr.com](https://secure.ballr.com) with the Terms of Service Modal automatically launched.

### How to Install Bootstrings onto your website

#### 1) Download `bootstrings.js`

Visit the [Github Project](https://github.com/tomhodgins/bootstrings) for this extension and download the file named `bootstrings.js`.

#### 2) Add Bootstrings to your website (it depends on jQuery being present)

Add `bootstrings.js` to your website with something simliar to the code below, and make sure to load this after [jQuery](http://jquery.com) and [Bootstrap](http://getbootstrap.com)'s JavaScript is already loaded.

    <script src="path/to/bootstrings.js" type="text/javascript"></script>

#### 3) Try it out

Add one of the querystrings below to the end of the URLs of one of your web pages that makes use of the corresponding Bootstrap component. If you have a page at `http://website.com/example` and it had a modal with an `id` of `login`, you could verify that Bootstrings was installed and working for all users by testing a URL like `http://website.com/example?modal=login` in Firefox, Safari, or any other non-Chrome browser.


## How to Use Bootstrings

### Modals `?modal=`
To display a modal after page load, we'll want to append a query string like this to the end of the URL:

`?modal=demo`

This would open the modal with an ID of `demo`. If the modal is launched through a link on the page you may be able to discover the ID of the modal you wish to display by hovering over the link, otherwise you may have to View Source, or Inspect Element to find the ID you want.

Try it out: https://www.engineyard.com/?modal=myModal


### Tooltips `?tooltip=`
To display a tooltip after page load, we'll want to append a query string like this to the end of the URL:

`?tooltip=demo`

This would open a tooltip with an ID of `demo`. If the tooltip is launched through a link on the page you may be able to discover the ID of the tooltip you wish to display by hovering over the link, otherwise you may have to View Source, or Inspect Element to find the ID you want.

Try it out: http://www.themeclue.com/?tooltip=fav0


### Popovers `?popover=`
To display a popover after page load, we'll want to append a query string like this to the end of the URL:

`?popover=demo`

This would open a popover with an ID of `demo`. If the popover is launched through a link on the page you may be able to discover the ID of the tooltip you wish to display by hovering over the link, otherwise you may have to View Source, or Inspect Element to find the ID you want.

### Tabs `?tab=`
To display a tab after page load, we'll want to append a query string like this to the end of the URL:

`?tab=demo`

This would open a tab with an ID of `demo`. If the tab is launched through a link on the page you may be able to discover the ID of the tooltip you wish to display by hovering over the link, otherwise you may have to View Source, or Inspect Element to find the ID you want.


## Licenses

`bootstrap.min.js` provided from the [Bootstrap](https://github.com/twbs/bootstrap) project and is copyright 2011-2014 Twitter, Inc. Code released under the MIT license.

`jquery-latest.js` provided from the [jQuery](https://jquery.org/license) project and is released under the MIT license.
