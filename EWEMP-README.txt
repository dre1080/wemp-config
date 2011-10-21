**********************************************************************
* Easy WEMP
**********************************************************************
Easy WEMP Home : http://projects.javatic.net/p/easywemp

**********************************************************************
* License
**********************************************************************
Easy WEMP is tool to manage NgInx, php-fastcgi and mysql daemons under windows.
Copyright (C) 2010  Yann Le Moigne

Easy WEMP is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

Easy WEMP is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Easy WEMP. If not, see <http://www.gnu.org/licenses/>.

**********************************************************************
* Command line options
**********************************************************************
Currently, there is no command line options

**********************************************************************
* Easy WEMP test
**********************************************************************
Just open http://localhost/index.php and you should see the phpinfo()

**********************************************************************
* Easy WEMP configuration
**********************************************************************
Easy WEMP should work out-of-the-box.

All parameter can be modified, you'll found them in ewemp.ini
This is the default full ini file :
[path]
nginx=nginx-0.7.66
php=php
mysql="C:\Program Files\MySQL\MySQL Server 5.5"
mysqlworkbench=MySQL Workbench 5.2.22 OSS
[manage]
nginx=true
php=true
mysql=true
mysqlworkbench=true
[nginx]
exec=/nginx.exe
sites=/html
config=/conf
logs=/logs
[php]
exec=/php-cgi.exe
fastcgi-bindaddress=localhost
fastcgi-bindport=9000
[mysql]
exec=/bin/mysqld.exe
config=/my.ini
clientExec=/bin/mysql.exe
[mysqlworkbench]
exec=/MySQLWorkbench.exe
[global]
autostartdaemons=true

