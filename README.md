# wings
Pterodactyl® is a free, open-source game server management panel built with PHP, React, and Go. Designed with security in mind, Pterodactyl runs all game servers in isolated Docker containers while exposing a beautiful and intuitive UI to end users.
# gh
bash <(curl -s https://pterodactyl-installer.se)

panel install

bash <(curl -s https://raw.githubusercontent.com/freediamodns/sanjitpanel/refs/heads/main/panel)

wings

sudo su
bash <(curl -s https://raw.githubusercontent.com/freediamodns/sanjitpanel/refs/heads/main/wings)

cmds

cd pterodactyl

sudo su

nano /etc/pterodactyl/config.yml

paste you config

cd wings

docker-compose up -d --force-recreate
