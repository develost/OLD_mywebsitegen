{{ website.cell('366666','') }}
# Parameters file for websu
Now you have both websu.php and parameters.php into the same folder. You parameters file looks like this:
<pre class="code-block"><span>if(count(get_included_files()) == 1) exit("Direct access not permitted.");</span><span>define('_CUSTOM_REDIRECT_', '');</span><span>class Parameters{</span><span>    const WEBSITE_ZIP_URL = 'https://raw.githubusercontent.com/develost/websu/master/example/example_website.zip';</span><span>    const WEBSITE_ZIP_TEMP_NAME = 'example_website.zip';</span><span>    const WEBSITE_VERSION_CHECK_URL = 'https://raw.githubusercontent.com/develost/websu/master/example/example_version.txt';</span><span>    const WEBSITE_VERSION_TEMP_NAME = 'version.txt';</span><span>    const WEBSITE_ROOT = '/';</span><span>    const WEBSITE_UPDATE_USER = 'example';</span><span>    const WEBSITE_UPDATE_PASSWORD = 'secret';</span><span>    const WEBSITE_CUSTOM_REDIRECT = _CUSTOM_REDIRECT_;</span><span>    const WEBSITE_CRYPTO_KEY = '';</span><span>    const GENERAL_DECODE_SUFFIX = '.enc';</span><span>    const GENERAL_DATE_FORMAT = 'Y';</span><span>    const GENERAL_USER_PARAM = 'user';</span><span>    const GENERAL_PASSWORD_PARAM = 'password';</span><span>    const GENERAL_WHAT_PARAM = 'what';</span><span>    const GENERAL_WHAT_MYWEBSITE = 'mywebsite';</span><span>    const GENERAL_WHAT_WEBSU = 'websu';</span><span>    const GENERAL_HTACCESS_FILE = '.htaccess';</span><span>};</span></pre>
You have to modify rows 4 to 14.
{{ website.endCell() }}

{{ website.cell('366666','') }}
<table>
    <tr><td>WEBSITE_ZIP_URL</td><td>Points to a zip file. The zip file should contain all your website</td></tr>
    <tr><td>WEBSITE_ZIP_TEMP_NAME</td><td>When updating your website, websu creates this file on your webserver, is a copy of your website zip</td></tr>
    <tr><td>WEBSITE_VERSION_CHECK_URL</td><td>Points to a text file, containng the version of your website. Prevents update of same version.</td></tr>
    <tr><td>WEBSITE_VERSION_TEMP_NAME</td><td>Webu stores this file on your webserver. Used to check if the version is changed.</td></tr>
    <tr><td>WEBSITE_ROOT</td><td>root of the resulting website<td></td></tr>
    <tr><td>WEBSITE_UPDATE_USER</td><td>This should be keept secret.</td></tr>
    <tr><td>WEBSITE_UPDATE_PASSWORD</td><td>This should be keept secret.</td></tr>
    <tr><td>WEBSITE_CUSTOM_REDIRECT</td><td>You can add more rules into the root htaccess file, yust put here the rules.</td></tr>
    <tr><td>WEBSITE_CRYPTO_KEY</td><td>This should be keept secret. Is the secrey key for blowfish cipher</td></tr>
    <tr><td>GENERAL_DECODE_SUFFIX</td><td>Websu decodes all files having this suffix using the crypto key and blowfish cipher</td></tr>
    <tr><td>GENERAL_DATE_FORMAT</td><td>Control timestamp of new versions</td></tr>
</table>
{{ website.endCell() }}


{{ website.cell('6','last') }}
[websu]({{ website.getPageById('websu').link }})
{{ website.endCell() }}

