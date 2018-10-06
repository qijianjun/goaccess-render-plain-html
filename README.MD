# README

This script generate plain html report from goaccess json file, the template is from goaccess bright theme, and the css are already compressed.

```
$ python goaccess-render-plain-html.py -h
usage: render.py [-h] -i INPUT -o OUTPUT [-l LIMIT] [-c] [-s STYLE] [-t TITLE]

optional arguments:
  -h, --help            show this help message and exit
  -i INPUT, --input INPUT
                        path of json file
  -o OUTPUT, --output OUTPUT
                        path of output html file
  -l LIMIT, --limit LIMIT
                        limit of data rows in panel table, default 100
  -c, --child           whether generate the child items of a data row in
                        panel table, default not
  -s STYLE, --style STYLE
                        embed the css in html file with "inline"(default), or
                        specify a path
  -t TITLE, --title TITLE
                        the page title, default "Server Statistics"
```