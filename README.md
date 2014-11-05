eoa-cookiecutter
================

A template for starting an [Edition Open Access](http://www.edition-open-access.de/) Repository to begin typesetting a book.

### Requirements

* [cookiecutter](https://github.com/audreyr/cookiecutter)
* XeLaTeX (from MacTex - mac or TexLive - windows)

### Instructions

    $ pip install cookiecutter
    $ cookiecutter https://github.com/ouinformatics/eoa-cookiecutter/
    short_title (default is "shortname")? sometitle
    long_title (default is "Full Book Title")? A Longer Name for the Book
    author (default is "Author Name")? Firstname Lastname
    date (default is "2014")? 2014
    
This leaves you with a directory called `sometitle` (or whatever you named the `short_title` variable) containing the skeleton of a EOA textbook.

