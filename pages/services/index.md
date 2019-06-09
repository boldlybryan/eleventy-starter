---
title: Services index
permalink: /services/
---
This is an example index page for a subdirectory of ```/pages```. Separating out pages like this keeps the clutter down in the main Eleventy directory. The only gotcha here is you have to specify the permalink on every page, or else the URL will be prepended with ```/pages/```.

There is a config file, ```pages.json```, that allows you to control data for the entire directory. Currently, it just specifies that layout type for all pages to use. It could be utilized for many purposes, including permalinks or other template data. Additionally, each subdirectory could have it's own version of this file that would give more granular control over template data.
