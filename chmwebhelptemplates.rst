======================
HTML-based Templates
======================


Each CHM/WebHelp template consists of two file groups:


1. Required files. Usually templates' main HTML page template and corresponding CSS file.
2. Additional files. Images used by template, scripts and etc.


In predefined templates there's jqueryui.zip file that contains JQuery UI theme for WebHelp (left pane with TOC, Index and Search). Inside it there's jqueryui.css and jqueryui.js files and "images" folder with images used by this theme.


HTML templates use several tags, enclosed in {%%}:


+--------------+----------------------------------------------------------------------------------------------------------------+
|**Tag**       |**Meaning**                                                                                                     |
+==============+================================================================================================================+
|TITLE         |Title of the current topic                                                                                      |
+--------------+----------------------------------------------------------------------------------------------------------------+
|BREADCRUMBS   |Place for breadcrumbs links                                                                                     |
+--------------+----------------------------------------------------------------------------------------------------------------+
|PREVNEXTTOPIC |Links to previous and next topics, combined                                                                     |
+--------------+----------------------------------------------------------------------------------------------------------------+
|PREVTOPIC     |Link to previous topic                                                                                          |
+--------------+----------------------------------------------------------------------------------------------------------------+
|NEXTTOPIC     |Link to next topic                                                                                              |
+--------------+----------------------------------------------------------------------------------------------------------------+
|PREVTOPIC_INCL|Link to previous topic, but instead of "Previous" text it uses HTML between this tag and END_PREVTOPIC_INCL tag.|
+--------------+----------------------------------------------------------------------------------------------------------------+
|NEXTTOPIC_INCL|Same as above but for next topic                                                                                |
+--------------+----------------------------------------------------------------------------------------------------------------+
|SEEALSO       |Lists related topics based on keywords match.                                                                   |
+--------------+----------------------------------------------------------------------------------------------------------------+


You can also use project variables inside templates.


.. image:: images/htmltemplates.png

HTML templates



.. image:: images/htmltemplates1.png

Inside an HTML template



**Adapting WebHelp to your website**


You can also adapt WebHelp appearance to the style of your website using WebHelp header and footer. This fields are not required, if empty WebHelp will fill entire browser page. When filled, header and footer will appear in separate frames.


.. image:: images/htmltemplates2.png

WebHelp Addons

