===============
Cloned Images
===============


Helpinator’s “Image Library” allows you to create “cloned” images. What are they?

Let’s say you have a big complicated tool bar in your application. You need to explain your users how to work with it, what buttons trigger specific actions, all grouped by specific tasks… This probably will require a lot of copies of the toolbar image, each one with it’s own callouts, arrows and text boxes, but all with the same background – application toolbar.

Now suppose that during project evolution toolbar changes significantly – updated icons, some new buttons. Now you need to update a bunch of images to reflect changes in the UI. That could be a nightmare! But not if you use Helpinator’s image library and “cloned” images.

In the following example will’ take a look at one simple but very common situation. Suppose you have a set of images in your project, describing different parts of the toolbar, but all of them contain application name and version in the window title like this:

.. image:: images/{264733B0-0907-4710-BF67-CFFF8D2A5163}.png

One image has callouts for language bar:

.. image:: images/{C07702C6-836E-464D-BDB7-3F2906134B7C}.png

Another for compile buttons, and so on…

.. image:: images/{3737ADA8-A871-4A9C-A9D5-BA21C0DDFB78}.png

We’ll make the first one “donor” image and two other images will be cloned.

.. image:: images/newclonedimage.png

New cloned image


Now suppose application version changes to 3.5. You need to update all those images. Luckily you have only one donor image and two clones, so you only need to update one image.

Select Tools->Replace Image when donor image is open in the editor.

.. image:: images/replacebitmap.png

Replace bitmap


Now all cloned images are updated:

.. image:: images/{B9F6839E-6B6B-4073-B60A-3981907DF019}.png

.. image:: images/{24E4B81A-84E6-45BE-9470-B9064C2951C1}.png


There's also a handy feature that is called "Active region". It allows to use only a square portion of the donor image. Define active region and set "Effect for..." to "Crop".

.. image:: images/imageactiveregion.png

Change active region


**Example.**

This image is the large donor image. But we do not need it as a whole, more than that, it will be discussed in different topics.

.. image:: images/cloneexampledonor.png

Donor


So we can create two clones and define different active regions for them.

.. image:: images/cloneexampleclone1.png

Clone 1



.. image:: images/cloneexampleclone2.png

Clone 2


