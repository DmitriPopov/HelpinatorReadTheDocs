===============
Wordpress CMS
===============


Wordpress is the most popular CMS in the world. If your website is based on Wordpress and you need to organize online help for your product - you don't need to create separate WebHelp section on your website aside from Wordpress. With Helpinator you can publish directly to Wordpress and turn topics into pages (not posts!). So you can use all Wordpress features in your online help!


There's an in-depth tutorial on using Helpinator "Publush to WordPress" feature combined with Helpinator theme and Quick Publish plugin on Helpinator Blog:


`https://www.helpinator.com/blog/2019/09/07/wordpress-for-online-documentation-how-to-use-helpinator-plugin-and-documentation-themes/ <https://www.helpinator.com/blog/2019/09/07/wordpress-for-online-documentation-how-to-use-helpinator-plugin-and-documentation-themes/>`_



To publish your help file to Wordpress you need to set up your account information and select publishing options.


.. image:: images/wordpress.png

Publish to WordPress



Helpinator operates "profiles" to manage Wordpress sites. You can have several profiles and publish documentation to several blogs (test site and the main product site, for example). Click "+" to add new profile and select profile name.


Then you need to enter account info:


* Blog host address
* Blog "endpoint" (when xmlrpc.php file is in subfolder)
* Whether to use HTTPS for connections
* Username and password
* "Check connection" button allows to test connection requisites


Note that Helpinator does not store your password anywhere for security reasons. If you close Helpinator your password is lost.


Publishing settings:

1. Page template - select one of PAGE templates available in your Wordpress theme. Click "Refresh" button next to it to get a list of templates.

2. Parent Page - a page to assign root page of documentation to. Leave it blank to publish to the main menu. Click "Refresh" button next to it to get a list of pages.

3. Root page order. By default your documentation root page will be attached to the end of parent page child pages list. You can change this value to insert it into another place.


Click "Save" to save your account info (without publishing) or "Publish" to publish it right away.


Don't forget to save your project after you publish your documentation, otherwise you will NOT be able to republish it (e.g. overwrite altered topics).


Major Mind Software provides some useful WordPress plugins and themes for registered users of Helpinator:


1. Helpinator QuickPublish plugin - this plugin extends WordPress API to allow to publish content faster and also fixes the problem of WordPress API that disrupts image republish feature blocking image rewrite.
2. Helpinator WebHelp WordPress theme - documentation theme that resembles  `WebHelp 2 <#tA31044183A93405FAD73451502C3A006>`_ in look and feel.
3. Helpinator Modern Help WordPress theme - responsive theme for software documentation.


You can download plugins and themes here:  `http://www.helpinator.com/download.html#wordpress <http://www.helpinator.com/download.html#wordpress>`_
