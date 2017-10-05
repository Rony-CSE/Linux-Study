To install git:

#// $ sudo apt-get install git (optional)

To install curl (if not):

#// $ sudo apt-get install curl (optional)

To install composer:

goto->https://getcomposer.org/download/

copy and paste the command into the Terminal..

or,

#// $ curl -sS http://getcomposer.org/installer | php

#// $ php -r "readfile('https://getcomposer.org/installer');" | php

make the composer globally:

#$ sudo mv composer.phar /usr/local/bin/composer
#$ sudo chmod 777 /usr/local/bin/composer



via laravel installer:

#$ composer global require "laravel/installer"
#$ nano ~/.bashrc

add export PATH="$HOME/.config/composer/vendor/bin:$PATH"

Crtl+X

#$ source ~/.bashrc
#$ laravel
#$ laravel new <project name>



or,


via Composer Create project:

#$ composer create-project laravel/laravel laravel-practise --prefer-dist

enable mods:

#$ sudo phpenmod mcrypt
#$ sudo phpenmod mbstring
#$ sudo a2enmod rewrite
#$ sudo systemctl restart apache2

#$ cd laravel-practise
#$ php artisan serve


goto browser and type "localhost:8000" and press 'Enter'




