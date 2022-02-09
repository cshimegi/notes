# Installation
- Enable in Apache
```
To enable PHP in Apache add the following to httpd.conf and restart Apache:
    LoadModule php_module /usr/local/opt/php/lib/httpd/modules/libphp.so

    <FilesMatch \.php$>
        SetHandler application/x-httpd-php
    </FilesMatch>

Finally, check DirectoryIndex includes index.php
    DirectoryIndex index.php index.html

The php.ini and php-fpm.ini file can be found in:
    /usr/local/etc/php/8.0/

To start php:
  brew services start php
Or, if you don't want/need a background service you can just run:
  /usr/local/opt/php/sbin/php-fpm --nodaemonize
```