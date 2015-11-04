The Verge News
=========

A block module for Drupal 7, that fetches news from The Verge Developer API.
Content belongs to The Verge, all rights reserved.

This is a simple module that defines a block with latest news from The Verge. All methods are explained and documented, so take a look in the .module-file.

## Files
***theverge_news.info***

This file describes the module to Drupal, and let you customize how your module is presented in the module overview (title, description, package, configuration settings).

***theverge_news.module***

This file contains (for this module; all) logic and methods for the module. It specifies a block to Drupal and requests data and prints it.

***theverge_news.install****

This file contains a couple of methods, that is run when the module is being installed/enabled/unabled/uninstalled.
Variables and tables are created/destroyed here.
