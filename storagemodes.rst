===============
Storage Modes
===============


Helpinator has two storage modes:

1. Single-file mode. Everything is in one zip-compatible project file with .hpz extension. Good if you don't use VCS system or want to deal with one file.

2. VCS-friendly mode. In this mode Helpinator stores every item in a separate file (or several files) and updates only changed files. So you don't need to check-in entire project every time you change something.


Modes are interchangeable. You can zip project folder (with project.xml in the root) and change extension from zip to hpz and work with your project in single-file mode. Or you can extract everything from hpz file and work in VCS-friendly mode.
