### Documentation
[Read online documentation](https://vuefilemanager.com/docs/)

### Demo & dev preview links
* For visit demo version click here [demo.vuefilemanager.com](https://demo.vuefilemanager.com/) 
* For visit dev version click here [dev.vuefilemanager.com](https://dev.vuefilemanager.com/) (It's auto deployed dev branch. Can be unstable and not ready for production)

### Installation setup

Run these commands to install vendors:
```
composer install
```
```
npm install
```

Setup your database in .env and run this command:
```
php artisan setup:prod
```

It automatically:
* Migrate database
* Generate Application key
* Create Passport Encryption keys
* Create Password grant client
* Create Personal access client

Then, copy generated password grant client `Client ID`, `Client secret` and paste it to .env files here:
```
PASSPORT_CLIENT_ID=<your_passport_client_id>
PASSPORT_CLIENT_SECRET=<your_passport_client_secret>
```
For sending forgoten password request via email, fill your mail driver in .env

### Run Application
To start server on your localhost, run this command
```
php artisan serve
```

To compiles and hot-reloads for development, run this command
```
npm run hot
```

To compiles for production, run this command
```
npm run prod
```
That's all, happy coding! :tada: :tada: :tada:
```
1  sudo amazon-linux-extras | grep PHP
    2  sudo amazon-linux-extras | grep PHPamazon-linux-extras0  ansible2
    3  amazon-linux-extras0  ansible2
    4  sudo yum install -y amazon-linux-extras
    5  amazon-linux-extras0  ansible2
    6  amazon-linux-extras  ansible2
    7  amazon-linux-extras php
    8   sudo amazon-linux-extras enable php7.4
    9  yum clean metadata
   10  sudo  yum install php-cli php-pdo php-fpm php-json php-mysqlnd
   11  sudo amazon-linux-extras | grep PHP
   12  php -v
   13  sudo yum install php
   14  sudo yum install php-{pear,cgi,common,curl,mbstring,gd,mysqlnd,gettext,bcmath,json,xml,fpm,intl,zip,imap}
   15  php -v
   16  sudo yum install mariadb-server
   17  sudo systemctl start mariadb
   18  sudo systemctl enable mariadb
   19  sudo mysql_secure_installation
   20  sudo systemctl status mariadb
   21  sudo yum install epel-release
   22  sudo yum install phpmyadmin
   23  sudo yum install httpd
   24  sudo systemctl status httpd
   25  sudo systemctl enable httpd
   26  sudo systemctl status httpd
   27  sudo systemctl start httpd
   28  sudo systemctl status httpd
   29  sudo systemctl enable httpd
   30  sudo yum install phpmyadmin
   31  sudo usermod -a -G apache ec2-user
   32  groups
   33  sudo chown -R ec2-user:apache /var/www
   34  sudo chmod 2775 /var/www && find /var/www -type d -exec sudo chmod 2775 {} \;
   35  find /var/www -type f -exec sudo chmod 0664 {} \;
   36  echo "<?php phpinfo(); ?>" > /var/www/html/phpinfo.php
   37  sudo yum install php-mbstring php-xml -y
   38  sudo systemctl restart httpd
   39  sudo systemctl restart php-fpm
   40  cd /var/www/html
   41  wget https://www.phpmyadmin.net/downloads/phpMyAdmin-latest-all-languages.tar.gz
   42  mkdir phpMyAdmin && tar -xvzf phpMyAdmin-latest-all-languages.tar.gz -C phpMyAdmin --strip-components 1
   43  rm phpMyAdmin-latest-all-languages.tar.gz
   44  sudo systemctl start mariadb
   45  ls
   46  git clone https://github.com/shub6059/vuefilemanager-new.git
   47  sudo yum install git
   48  git clone https://github.com/shub6059/vuefilemanager-new.git
   49  ls
   50  cd vuefilemanager-new/
   51  cd 
   52  php -r "copy('https://getcomposer.org/installer', 'composer-setup.php');"
   53  php -r "if (hash_file('sha384', 'composer-setup.php') === 'e21205b207c3ff031906575712edab6f13eb0b361f2085f1f1237b7126d785e826a450292b6cfd1d64d92e6563bbde02') { echo 'Installer verified'; } else { echo 'Installer corrupt'; unlink('composer-setup.php'); } echo PHP_EOL;"
   54  php composer-setup.php
   55  php -r "unlink('composer-setup.php');"
   56  composer 
   57  sudo mv composer.phar /usr/local/bin/composer
   58  composer 
   59  cd /var/www/html
   60  ls
   61  cd vuefilemanager-new/
   62  composer install
   63  php artisan setup:prod
   64  ls
   65  nano .env
   66  php artisan setup:prod
   67  nano .env
   68  php artisan serve
     php artisan serve --host=0.0.0.0 --port=8000
     cd /var/www/html
     cd vuefilemanager-new/
     php artisan serve --host=0.0.0.0 --port=8000
   ```
