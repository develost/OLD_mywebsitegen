{{ website.cell('6','') }}
Tython is a standalone software, it produces html pages out of text documents.

Is a static CMS with the following features:

- is written in python and makes you capable to use python in your pages
- can use multiple templates
- a template is an html page, you can open it in a browser
- produces rewrite rules: seo friendly
- can build rules for external resources
- has custom functions for dlMetro
- uses an XML for the cunfiguration
- handle Error 404 page \(and other errors\)
- clear distinction between content, template and configuration

You can use user demo \(password demo149\) for evaluation.

{{ website.endCell() }}

{{ website.cell('6','') }}
# Getting started

1. Get or install a python 2.7.x from [here](https://www.python.org/downloads/release/python-279/).
1. Get last tython version from [here](https://codeload.github.com/develost/pyApps/zip/master) and unpack it.
1. Get the example from [here](https://raw.githubusercontent.com/develost/pyApps/master/examples/tython-example.zip) and unpack it.
1. Edit genereate.bat, pointing to your actual python executable and your actual tython.py file.
1. Run generate.bat.
1. Browse output folder, open index.html with a browser.
1. Congratulation! You used tython effectively.

##Optional
1. Get an apache httpd server up and running
1. Copy output folder into website root folder
1. Go to (http://localhost/output) and see the example page

Now your are ready to build your own website

{{ website.endCell() }}

{{ website.cell('3','') }}
#Suggested directory structure

- a folder named content (where to put markdown files)
- a folder named template (where to put html templates for your pages)
- config.xml (an empty file for now)
- generate.bat (or .sh this file will trigger website generation)
 

{{ website.endCell() }}

{{ website.cell('3','last') }}
#Coming soon: 

- commands available
- setup config.xml

## This website is made with tython

Browse this repository on [github](https://github.com/develost/_mywebsitegen) to see how.

{{ website.endCell() }}
