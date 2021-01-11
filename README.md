# Настройка терминала
Переходим в меню Терминала Правка > Параметры > Комбинация клавиш > Вставить (для удобства задаём клавиши CTR+V).
Открытие нового окна терминала в новой вкладке: Правка > Параметры > Основное > Открывать новые терминалы в Вкладка.

# Дальше

> sudo apt update

> sudo apt-get install dkms broadcom-sta-dkms broadcom-sta-common

> sudo apt upgrade

> sudo apt update && sudo apt dist-upgrade

> sudo dpkg --add-architecture i386

> sudo apt install --reinstall intel-microcode

> sudo apt-get install python3-nautilus

> sudo apt-get install python-nautilus

> sudo apt install python-nautilus python3-gi

> sudo apt-get install python3-gi python3-nautilus python3-pip

> pip3 install --user git-nautilus-icons


> sudo apt install exe-thumbnailer nautilus-sendto nautilus-share nautilus-admin nautilus-font-manager nautilus-ideviceinfo ooo-thumbnailer p7zip-full

> nautilus -q


 
> sudo apt install libavcodec-extra58  ubuntu-restricted-extras libavcodec-extra libdvd-pkg



> gsettings set org.gnome.gedit.preferences.encodings candidate-encodings "['UTF-8', 'WINDOWS-1251', 'KOI8-R', 'CURRENT', 'ISO-8859-15', 'UTF-16']"

> sudo apt install synaptic gdebi

> sudo apt install gnome-tweak-tool

> sudo apt install chrome-gnome-shell

> sudo apt install gnome-clocks

> sudo apt install sshfs

> sudo apt install gir1.2-gtop-2.0 gir1.2-nm-1.0 gir1.2-clutter-1.0

> sudo snap install htop

> sudo apt install mc

https://extensions.gnome.org/

https://extensions.gnome.org/extension/1036/extensions/

https://extensions.gnome.org/extension/1319/gsconnect/

https://extensions.gnome.org/extension/750/openweather/

https://extensions.gnome.org/extension/517/caffeine/

https://extensions.gnome.org/extension/307/dash-to-dock/

RESTART

https://extensions.gnome.org/extension/120/system-monitor/

https://extensions.gnome.org/extension/1034/services-systemd/

https://extensions.gnome.org/extension/2159/application-view-columns/

https://extensions.gnome.org/extension/19/user-themes/

https://extensions.gnome.org/extension/2872/activities-icons/




> sudo apt install lm-sensors hddtemp psensor

> sudo sensors-detect

> sudo systemctl enable lm-sensors

https://extensions.gnome.org/extension/1145/sensory-perception/

> sudo apt-get update

> sudo apt-get install grub-customizer

PHPStorm, DataGrip
https://forum.losper.net/topic/90-aktivatory-jetbrains-agent-dlya-ide-ot-jetbrains/?tab=comments#comment-238



https://www.pling.com/p/1175480/

https://www.pling.com/p/1228228/



https://extensions.gnome.org/extension/723/pixel-saver/



> sudo apt install git

> git config --global user.email "bubnov.alexey@gmail.com"

> git config --global user.name "Alex Venga"



> sudo gedit /usr/share/X11/xkb/rules/evdev.xml

`<shortDescription>en</shortDescription>`

`<shortDescription>🇺🇸️</shortDescription>`

`<shortDescription>ru</shortDescription>`

`<shortDescription>🇷🇺️</shortDescription>`

перезагрузите оболочку Gnome: Alt+F2, введите латинскую r и Enter.



https://docs.docker.com/engine/install/ubuntu/

> sudo apt install openssl php php-fpm php-common php-curl php-json php-mbstring php-mysql php-xml php-zip

> sudo apt remove apache2

> sudo apt autoremove

> sudo apt install nginx

> sudo apt install mariadb-server

> sudo mysql_secure_installation

create symlinks for webserver

/etc/php/7.0/fpm/pool.d/www.conf

owner = alex

group = alex

listen.owner = alex

listen.group = alex


> sudo mysql

`GRANT ALL ON *.* TO 'alex'@'localhost' IDENTIFIED BY 'Qwerty100$' WITH GRANT OPTION;`

`GRANT ALL PRIVILEGES ON *.* TO 'alex'@'localhost';`

`FLUSH PRIVILEGES;`

`use mysql;`

`update user set plugin='' where User='root';`

`flush privileges;`

`exit`

> curl -sS https://getcomposer.org/installer -o composer-setup.php

> sudo php composer-setup.php --install-dir=/usr/local/bin --filename=composer

> rm composer-setup.php

https://habr.com/ru/post/85067/

https://www.8host.com/blog/nastrojka-bind-kak-keshiruyushhego-ili-perenapravlyayushhego-dns-servera-v-ubuntu-14-04/


> dpkg --get-selections | grep node

> sudo apt purge nodejs

> curl -sL https://deb.nodesource.com/setup_14.x | sudo bash -

> sudo apt-get install -y nodejs

## Run `sudo apt-get install -y nodejs` to install Node.js 14.x and npm

## You may also need development tools to build native addons:

> sudo apt-get install gcc g++ make

## To install the Yarn package manager, run:

> curl -sL https://dl.yarnpkg.com/debian/pubkey.gpg | sudo apt-key add -

> echo "deb https://dl.yarnpkg.com/debian/ stable main" | sudo tee /etc/apt/sources.list.d/yarn.list

> sudo apt-get update && sudo apt-get install yarn

> sudo apt install npm


Google Chrome > Settings > Apearance > Default theme

> sudo snap install vlc

> sudo apt install rar unrar p7zip-full p7zip-rar

> apt install flameshot


