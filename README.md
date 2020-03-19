Package name : huynd/url_helper.
Feature :
Valid 1 string is a valid url
Connect 1 path with 1 base url. For example http://google.com/a/ connected with xyz.html to http://google.com/a/xyz.html but connected to /xyz.html to http://google.com/xyz.html
Retrieve information: protocol, port, domain
Installing :
use command:
composer require huynd/url_helper
to load package to your project.
On index file of Project need the autoload file:
requirec_one './vendor/autoload';
use PackageUrlHelper\UrlHelper;
$urlHelp = new UrlHelper();