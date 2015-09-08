# thumbnail_index 
## make an HTML index file for a bunch of images
### version of 03feb98

Fork of Jef Poskanzer's thumbnail_index (http://acme.com/software/thumbnail_index/)

Run this script in a web directory consisting of all or mostly image
files.  It'll create an index.html of thumbnail images, putting
the thumbnail files in a hidden subdirectory.

It avoids unnecessary work by comparing the dates on already existing
thumbnail files and not re-creating them if the corresponding original
has not changed.

It also refuses to overwrite an index.html file not created by this script.

Requirements:
  - You must have pbmplus installed.  It's available at
    http://www.acme.com/software/pbmplus/
  - If your images include JPEGs, you must also have the IJG package
    installed.  It's available at ftp://ftp.uu.net/graphics/jpeg/

Installation:
  - Edit Makefile and change the installation directories if necessary.
  - Make install.
That's all!

Comments to:
    Jef Poskanzer  jef@acme.com  http://www.acme.com/jef/
