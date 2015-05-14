charsetconv.py
==============

This is a simple tool to recursively convert files from one charset to another.

Example usage:

    python charsetconv.py myProject/ iso-8859-1 utf-8 "*.txt" "*.html" "*.php"

This will recursively look in to myProject directory, for text, HTML and PHP files, and convert them from iso-8859-1 to utf-8.

