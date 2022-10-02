# User Manual

NOTE: This module has been renamed and move to https://backdropcms.org/project/user_guide_recipe

## Instructions

The content of this module is currently in development, but you are free to download, install, and offer feedback. 

Enabling this module on a site will also require downloading and installing a couple of other modules. It would be best to experiment with this module on a test or sandbox environment as it will add a bunch of content and some content types, fields and views that can only be removed manually.

## Details

The Getting Started module was created to help site owners and site architects that are relatively new to Backdrop get a jump start on understanding the power of Backdrop and what it can do. 

We've enabled and added some features to this site that will help you get started and learn more about how Backdrop CMS works. 

Specifically, here is a list of the changes that this module makes to your site:

- We create a new "About" page, place it in the main menu along with a few sub-menu items. If you already had an About page, we unpublished it. You can still find the old version, if there was one, in the list of content for the site - /admin/content.
- We generate over 20 pieces of content (nodes). The content generated is intended to help you better envision how Backdrop CMS can be used to build a website and to explain some of the features, while linking you to additional resources where you can learn more.
- In addition to generating additional new content, this module has modified the default content in default post and default page provided by Backdrop core. The content changes are intended to add useful information and context for someone using Backdrop CMS for the first time. 
- Enables the Book module (in core) and creates the User Manual book. The User Manual has general information about Backdrop, but can also be customized and used a site specific user manual for this specific site. 
- Installs and enables the Content View Access module. The Content View Access module is a contrib module that allows us to easily set access permissions for specific content types. We are using this module to make Book pages only accessible to authenticated users.
- Installs and enables the Mini Layouts module. The Mini Layouts module is a contrib module that allows us to create a layout within a layout. We are using this module to create a special "footer" layout that we can use throughout the site. Without the this special Footer mini layout, we would have to place footer blocks into each layout individually and edit them in multiple places. With this module enabled, we can create one mini layout and manage it in one place, but use it in many places. 
- We added a Contact Info block to the footer that can be modified and reused on this site or deleted. 
- We added a Recent Content view to the footer to help showcase how the Views module (in core) works and what you can do with it.
- Adds a hero image on the front page and makes it a little larger than it would be by default in the Basis theme. It also changes the message in the front page hero image. 
- We add a "profile" field to user accounts and populate that field for the #1 user = admin. 
- We add a Tags view and place it in the right sidebar of every post or tag taxonomy page. This provides a quick way to find related content on the site.

Uninstall or Upgrade Options
----------------------------

It is not currently possible to uninstall or upgrade this recipe.
If you no longer wish to keep this functionality, you will need 
to remove the items added by the recipe manually.


Current Maintainers
-------------------

- [Tim Erickson](https://github.com/stpaultim).

Credits
-------

- Sponsored by [Simplo](https://www.simplo.site)

License
-------

This project is GPL v2 software. 
See the LICENSE.txt file in this directory for complete text.
