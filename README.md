Duplicate Finder
================

A dirty python script to find duplicate files in a list of mp3's

Usage
-----

finder.py --outfile outfile [--verbose] file1 [file2, ...]

outfile will contain a pretty printed list with all the duplictaes

There is NO ERROR checking. Be prepared to be disappointed if you ask to process
a file that isn't a valid mp3

Requirements
------------
pyacoustid
mutagen

