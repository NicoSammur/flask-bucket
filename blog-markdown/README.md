# Blog Markdown using Flask

### Setup
* ``$ sudo apt-get install python3-venv``
* ``$ python3 -m venv venv``
* ``$ source venv/bin/activate``
* ``$pip install -r requirements.txt``

## Usage
* Add .md files into ``/pages`` folder, and index and the html files will be available on ``/build`` once completed
*
```markdown
title: topic
date: yyyy-mm-dd
category: category

Something
- a
- b
- c```


### Generate html
* ``$ python3 sitebuilder.py build``
