{{ website.cell('6','') }}
How can i update my website easily minimizing offline time?
### **Websu** is designed specifically for this:
 - it prepares a fresh copy of your website
 - and switches to the new version only when the copy of all the files is done
 - it works under *apache httpd*, does not work for IIS
 - everything done graphically in a (protected) web page
{{ website.endCell() }}

{{ website.cell('6','') }}
### Some capabilities
 - autoupdate: only few clicks and get last version
 - update webite only in case of new version available
 - user/password protection
 - shows nicely on mobile
 - encrypt/decrypt files with blowfish cipher
{{ website.endCell() }}

{{ website.cell('333663','') }}
# Main page
![websu main page](https://github.com/develost/websu/raw/master/websu_main_page.jpg "websu main page")
{{ website.endCell() }}


{{ website.cell('333663','') }}
# Report page
![websu file page](https://github.com/develost/websu/raw/master/websu_file_page.jpg "websu file page")
{{ website.endCell() }}

{{ website.link('github-websu','')}}
{{ website.cell('222662','') }}
# How to get it
Check and download last version on GitHub
### Last version is **0.1.0**
{{ website.endCell() }}
{{ website.endLink() }}

{{ website.cell('444664','last') }}
# Getting started
 1. zip your website and put somewhere, can be a dropbox link or whatever
 1. prepare parameters.php file following [this tutorial]({{ website.getPageById('websu-params').link }})
 1. put both websu.php and parameters.php into your website folder
 1. go to https://your website/websu.php you should see websu page. Https is **highly suggested** otherwise credentials passes in clear text
 1. authenticate and update your website
 1. check if websu creates new files/folders into your website folder
 1. browse your website and be happy!
{{ website.endCell() }}
