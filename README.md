# PHP Mikrotik Billing 
----

@ibnux notes:
----
> The project maybe has been abandoned,
> maybe the dev busy,
> and nobody donate to him,
> i will try to update as far as i can,
> any Modification will be update in here. 

### iBNuX Todos

 - Self registration, user must have voucher before registration
 - SMS Notification for expired account
 - PUSH Notification using onesignal
 - embedable for mikrotik login template

----

![N|phpmixbill](http://4.bp.blogspot.com/-3OWL5OI7pqU/VjocUDdzMDI/AAAAAAAAAiA/s_XJN0_mDlk/s640/Screenshot_8.png)

www.phpmixbill.com
by Ismail Marzuqi

New Features:
----
- New Coding (ORM & Smarty)
- New Design (responsive)
- NEW API Mikrotik (PEAR2_Net_RouterOS)
- Multi Router Mikrotik
- Hotspot & PPPOE
- Easy Installation
- Multi Language
and many more...

STEPS: Installation
----
Auto Installer:
1. Unzip the contents of the zip file to a folder on your computer.
2. Upload the Entire phpmixbill folder to your website / server
3. Next you can rename the folder to whatever you like (billing, finance, manage etc..)
4. Now visit the uploaded location using your web browser to run the installer process.
5. Follow the instructions on screen to install PHPMixBill
6. For security, Delete the install directory inside system folder.
7. If you see blank page after installation, it might be your compiled folder permissoon is not writable. Please make permission 755 compiled directory inside ui folder to store the generated contents from theme.

Manual Install:
To install manually, follow this steps-

1. Unzip the contents of the zip file to a folder on your computer.
2. Upload the Entire phpmixbill folder to your website / server
3. Next you can rename the folder to whatever you like (billing, finance, manage etc..)
4. Sample config file is available here- system/config.sample.php . Rename it to config.php & put it in same location (/system/config.php) Open config file using a text editor & Put the database info and url.
5. Import database. Database file is located here- system/install/phpmixbill.sql
6. For security, Delete the install directory inside system folder.

CRON JOBS
----
Run Every 4 Hours
```sh
crontab -e
0 0,4,8,12,16,20 * * * /usr/bin/php -f /path/to/phpmixbill/system/cron.php
```
Every system have different configuration for crontab

System Requirements
----
Most current web servers with PHP & MySQL installed will be capable of running PHPMixBill v5.0.

Minimum Requirements
- Linux or Windows OS
- PHP Version 5.3+
- Both PDO & MySQLi Support
- GD2 Image Library
- MySQL Version 4.1.x and above

copyright
----
(C) 2014-2015 PHP Mikrotik Billing

License
----

GNU General Public License version 2 or later

see LICENSE file

Donate to first Developer
----

PayPal: iesien22@yahoo.com 

Bank Mandiri: 130.00.1024957.4

Donate to ibnux
----

[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=6RBNGRJMZVV7C)

BCA: 5410454825

Mandiri: 163-000-1855-793

a.n Ibnu Maksum