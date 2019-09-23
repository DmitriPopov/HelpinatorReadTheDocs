===================
Command line tool
===================


Helpinator comes with command-line compiler **chelpinator.exe** that you can use in batch files (.bat, .cmd).

It has the following parameters:

**chelpinator.exe <projectfile> <batchname>**

<projectfile> (required) - full path to the Helpinator project you are about to compile.

<batchname> (required) - name of the batch saved to the project file.

Example.

Suppose path to your project is C:\Project\Help\myproject.hpz.

You need to compile PDF help from it and place it into C:\PDF folder. You have variable preset "pro" and want to use it. You have several languages in the project and you want to use "English (United States)"

You need to do the following:


1. Click on the lightning bolt icon on the main toolbar
2. Click "New batch"
3. Double-click PDF output on the left to add it to the batch
4. Set output path to "C:\PDF"
5. Save the batch with a meaningful name like "mypdf".
6. Save proejct file.


Now you can call command line compiler to produce PDF:

chelpinator.exe "C:\Project\Help\myproject.hpz" "mypdf"
