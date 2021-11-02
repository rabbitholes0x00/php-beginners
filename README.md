# README!
* Name: `PHP`
* Designed by: `Rasmus Lerdorf` at `Home` originally used for tracking visits to his online resume, he named the suite of scripts `Personal Home Page` tools
* First appeared: `1995`
* Developer: `The PHP Development Team`, `Zend Technologies`
* Paradigm:  `imperative`, `functional`, `object-oriented`, `procedural`, `reflective`
* Typing and types discipline: `dynamic` and `strict`
* Package manager: `composer`
* Total keywords in PHP 8: -`
* Official sites: `https://www.php.net`

## LAMPP, Installations
Follow [this](https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-20-04) awesome instructions

## XAMPP, Installations
Download at [XAMPP - Apache Friends](https://www.apachefriends.org/download.html), after download you must install xampp by executable file. Change file to executable with this command `chmod +x xampp-linux-x64-x.x.x-x-installer.run` and run `sudo ./xampp-linux-x64-x.x.x-x-installer.run` then you can and then next until it's finished. after success installed your xampp folder at `/opt/lampp/` and u can't write `.php` code on folder called `htdocs`, for this solutions change access folder with `sudo chmod 755 /opt/lampp/htdocs/ -R`

## LAMPP, Commands
```zsh
sudo /opt/lampp/lampp status
sudo /opt/lampp/lampp start
sudo /opt/lampp/lampp restart
sudo /opt/lampp/lampp stop
```

Create $PATH on `~/.zshrc` for XAMPP `export PATH=$PATH:/opt/lampp/bin`
