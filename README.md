# PHP-Javascript_disabled_detector
To check if javascipt is disabled
include the script by using 
```php
include 'path/to/Fagbemi-Jeremiah-noscript-detect-serverside.php';
```
whenever javascript is disabled the url would contain
~~~
noscript=yes
~~~

if you would not like to noscript=yes then set the $Fagbemi-Jeremiah-noscript-detect-serverside-link_to_use to "foo=bar"
Example
```php
//the equals sign is compulsory and there should be no space
$Fagbemi-Jeremiah-noscript-detect-serverside-link_to_use = "my_site_has_javascript_disabled=true";
//include the file after declaring the variable
include 'path/to/Fagbemi-Jeremiah-noscript-detect-serverside.php';
```
