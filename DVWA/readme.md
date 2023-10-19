# DVWA

* **Official Web page : https://dvwa.co.uk/**
* **Official Github** : https://github.com/digininja/DVWA

## 📢 Little tutorial if official Github doesn't work. :

**1. Install a web server and a database like XAMPP : https://www.apachefriends.org/en/xampp.html**

**2. Download DVWA : https://github.com/digininja/DVWA/archive/master.zip**

**3. Extract the dvwa folder to this location "C:\xampp\htdocs\dvwa\".**

**4. On XAMPP Control Panel start Apache and MySQL modules.**

**5. Open our webrowser and enter "localhost/dvwa" (127.0.0.1/dvwa) into the url bar.**

**6. If you have a "mysql.error()" read the error and correct it.** 
  * Warning, this is often an error related to the creation of the database.
  * If that is the case, go to the following file "config.inc.php" which by default is set like this:
```php
$_DVWA[ 'db_server'] = '127.0.0.1';
$_DVWA[ 'db_database' ] = 'dvwa';
$_DVWA[ 'db_user' ] = 'dvwa';
$_DVWA[ 'db_password' ] = 'p@ssw0rd';
$_DVWA[ 'db_port'] = '3306';
```
Change the "db_user" and the "db_password" like this:
```php
$_DVWA[ 'db_server'] = '127.0.0.1';
$_DVWA[ 'db_database' ] = 'dvwa';
$_DVWA[ 'db_user' ] = 'root';
$_DVWA[ 'db_password' ] = '';
$_DVWA[ 'db_port'] = '3306';
```

**7. If you have another error read it, it's probably related to the creation of the database. To correct the error point your browser to : http://127.0.0.1/dvwa/setup.php (if necessary change the IP Adress and port).**

**8. Default username and password for the authentication web page**    
  * username: **admin**
  * password: **password**
 
**9. Others informations :**    
  * Remember to change the "Security Level" by clicking on "DVWA Security" on the left panel.
  * Starts from "Low" level to "Impossible" level.
