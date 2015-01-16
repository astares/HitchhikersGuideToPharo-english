The Hitchhiker's Guide to Pharo (english version)
=================================================



How to build the book
=====================

You first have to download this project:

```bash
# if you have commit access:
git clone git@github.com:astares/HitchhikersGuideToPharo-english.git
# if you don't
git clone git://github.com/astares/HitchhikersGuideToPharo-english.git
```
 
As a next step you must download the Pharo virtual machine (VM) and image.

```bash
./download.sh
```

Finally to build the book use

```bash
./compile.sh
```

The `compile.sh` script will only compile the files that are included
from the `pillar-conf.ston` file. If you write a new chapter, don't
forget to reference it in this file to have it compiled.

How to build a PDF
==================

On Ubuntu you can install texlive

```bash
sudo apt-get install texlive
```

Also install the extra package for textlive 

```bash
sudo apt-get install texlive-latex-extra
```

```bash
sudo apt-get install texlive-bibtex-extra
```




