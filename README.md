# WEMP development server

- First download and install the latest of:

+ [PHP NTS] (http://windows.php.net)
+ [MySQL] (http://www.mysql.com/downloads/mysql)
+ [MySQL Workbench] (http://www.mysql.com/downloads/workbench)
+ [Nginx] (http://wiki.nginx.org)

- Run Easy_WEMP-1.13-win32.exe

- Uncheck all values when asked to install any of the above packages.

- Read EWEMP-README.txt

- Edit ewemp.ini file in install directory, replace with the example one in this repo.

- Replace values in ewemp.ini with values corresponding to the installed packages above.

- Check out example nginx config to work with php-cgi. `fastcgi.conf` & `nginx.conf`.

- Edit your nginx config in your nginx installation directory.

- Check your php.ini in your php installation directory. If it doesn't exist, rename php.ini-production to php.ini

- Check your my.ini in your mysql installation directory.

- Run `Easy WEMP` from the start menu.

- Go to http://localhost/index.php to make sure its working.

- Voila! A monitored WEMP server.