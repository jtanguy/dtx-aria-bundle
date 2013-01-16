Master ARIA LaTeX packages
==========================

Installation
============
To extract the files from the `dtx` bundle, run

```
latex aria-bundle.dtx
```

To typeset the documentation alongside, run

```
pdflatex aria-bundle.dtx
```

There are two ways to install this bundle: either locally or globally.
The former is the most simple way, but you have to repeat it for each 
separate document you want to typeset.
The latter lets you install the package once and then use it anywhere.
But if you don't know what a TDS tree is, you should use the former method.

Local install
-------------
To use the files extracted from the documentation, simply copy the `.cls` or `.sty` files
in the directory of your master `.tex` file. *LaTeX* will find it automatically.

You must repeat this operation for each project/document using files from this bundle.

Global install
--------------
To install this bundle once and for all, place all the extracted files in your TDS tree.
The install locations ---relative to your TDS root--- of the files are given by the
output of the installation commands.

