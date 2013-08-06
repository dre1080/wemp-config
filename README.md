# WEMP development server

1. First download and install the latest of:
  + [PHP NTS] (http://windows.php.net)
  + [MySQL] (http://www.mysql.com/downloads/mysql)
  + [MySQL Workbench] (http://www.mysql.com/downloads/workbench)
  + [Nginx] (http://wiki.nginx.org)

2. Run Easy_WEMP-1.13-win32.exe

3. Uncheck all values when asked to install any of the above packages.

4. Read `EWEMP-README.txt`

5. Edit `ewemp.ini` file in install directory, replace with the example one in this repo.

6. Replace values in `ewemp.ini` with values corresponding to the installed packages above.

7. Check out example nginx config to work with php-cgi. `fastcgi.conf` & `nginx.conf`.

8. Edit your nginx config in your nginx installation directory.

9. Check your `php.ini` in your php installation directory. If it doesn't exist, rename `php.ini-production` to `php.ini`

10. Check your `my.ini` in your mysql installation directory.

11. Run `Easy WEMP` from the start menu.

12. Go to http://localhost/index.php to make sure its working.

13. Voila! A monitored WEMP server.
