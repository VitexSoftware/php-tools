php-tools
==================

![php-tools](php-tools.svg "Package Logo")

Debian package that contains additonal tools for PHP development using.

Installation:
-------------

```shell
sudo apt install lsb-release wget
echo "deb http://repo.vitexsoftware.cz $(lsb_release -sc) main" | sudo tee /etc/apt/sources.list.d/vitexsoftware.list
sudo wget -O /etc/apt/trusted.gpg.d/vitexsoftware.gpg http://repo.vitexsoftware.cz/keyring.gpg
sudo apt update
sudo apt install php-tools
```

Commands included
-----------------

 * **add-sury-debian-sources** - Add additonal php versions install sources
 * **disable-all-php-modules** - make no optional modules enabled

 * **installphp** - check current installed php modules and install same modules in other choosen php version
 * **php-modules** - list of avilble php modules

 * **usephp-5.6** - swith current webserver and commandline php to php5.6
 * **usephp-7.0** - swith current webserver and commandline php to php7.0
 * **usephp-7.1** - swith current webserver and commandline php to php7.1 
 * **usephp-7.2** - swith current webserver and commandline php to php7.2
 * **usephp-7.3** - swith current webserver and commandline php to php7.3
 * **usephp-7.4** - swith current webserver and commandline php to php7.4 
 * **usephp-8.0** - swith current webserver and commandline php to php8.0 
 * **xdebug-mode** - set xdebug mode "debug" or "profile"


usephp
------

Simply run **usephp** command to choose from availble versions

![usephp](usephp.png?raw=true)


installphp
----------

1) Choose PHP versions you want install:

![installphp version chooser](installphp-choose.png?raw=true)

2) Choose packages 

![installphp choose](installphp-check.png?raw=true)

3) Customize selection

![installphp customize](installphp-confirm.png?raw=true)

4) Confirm instalation

![installphp final](installphp-itself.png?raw=true)



