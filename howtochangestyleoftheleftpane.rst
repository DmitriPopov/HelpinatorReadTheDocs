======================================
How to Change Style of the Left Pane
======================================


WebHelp is based on JQueryUI so you can use it's styles to change style of WebHelp template. Take a look at "Additional Files" section of default template. There you can see jqueryui.zip file. This file contains all required style data. The following steps show how to create your own:


1. Go to  `http://jqueryui.com/themeroller/ <http://jqueryui.com/themeroller/>`_

2. Select colors that you like, then download corresponging zip archive

3. Unzip it

4. Create another folder were you will place working files

5. Go to "CSS" folder unzipped from the archive.

6. Copy images folder to your new folder

7. Copy jquery-ui-\*.css to the root of our new folder, rename it to jqueryui.css

8. Go to "js" folder unzipped from the archive.

9. Copy jquery-ui-\*.js file to the root of our new folder, rename it jqueryui.js

10. Zip our new folder (so jqueryui.css and jqueryui.js are in the root of the archive) and name it jqueryui.zip

11. Place it into "default_files" folder or your own template folder, say "mytemplate_files" or remove default file from project template and add your own instead of it.

12. Voila, you can compile WebHelp with your own color settings.
