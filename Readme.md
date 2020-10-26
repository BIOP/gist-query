[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/BIOP/gist-query/master)

# Parse GISTS from BIOP and create Markdown table

## Installation
Create a virtual environment and use
```
pip install -r gistreqs.txt
```
After that you can access the `Query Gists BIOP` notebook and run it

## Use

## Notes

This is a very simple demo on how to get Gists. It parses all gists from the users at the BIOP, and if the gist contains a `#BIOP` tag, will add it to a growing string.

The string gets copied to the clipboard and you can then paste it in your C4Science page

## Todo

It will be nice to automate this so that when new Gists are made, the C4Science page get updated automatically, but this is not a critial project right now. 
