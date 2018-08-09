# How To Use

# How to create this project

**htop**

mkdir -p  provisioning/roles/htop/tasks

touch  provisioning/roles/htop/tasks/main.yml



**tmux**

mkdir -p  provisioning/roles/tmux/tasks

touch  provisioning/roles/tmux/tasks/main.yml

**zsh**

mkdir -p  provisioning/roles/zsh/tasks

touch  provisioning/roles/zsh/tasks/main.yml

**apt**

mkdir -p  provisioning/roles/base/tasks

touch  provisioning/roles/base/tasks/main.yml

**pydf**

mkdir -p  provisioning/roles/pydf/tasks

touch  provisioning/roles/pydf/tasks/main.yml

**zsh**-autosuggestions

mkdir -p  provisioning/roles/zsh-autosuggestions/tasks

touch  provisioning/roles/zsh-autosuggestions/tasks/main.yml

**postgres**

mkdir -p  provisioning/roles/postgres/tasks

touch  provisioning/roles/postgres/tasks/main.yml

**mysql**

mkdir -p  provisioning/roles/mysql/tasks

touch  provisioning/roles/mysql/tasks/main.yml

mkdir -p  provisioning/roles/mysql/vars/

touch  provisioning/roles/mysql/vars//main.yml

mkdir -p  provisioning/roles/mysql/templates

touch provisioning/roles/mysql/templates/.my.cnf
---

**rvm**

mkdir -p  provisioning/roles/rvm/tasks

touch  provisioning/roles/rvm/tasks/main.yml


php

mkdir -p  provisioning/roles/php/tasks

touch  provisioning/roles/php/tasks/main.yml



nginx

mkdir -p  provisioning/roles/nginx/tasks

touch  provisioning/roles/nginx/tasks/main.yml

mkdir -p  provisioning/roles/nginx/vars/

touch  provisioning/roles/nginx/vars//main.yml

mkdir -p  provisioning/roles/nginx/templates

touch provisioning/roles/nginx/templates/default



wordpress

mkdir -p  provisioning/roles/wordpress/tasks

touch  provisioning/roles/wordpress/tasks/main.yml

mkdir -p  provisioning/roles/wordpress/templates

touch provisioning/roles/wordpress/templates/wp-config.php 



ruby

rails

nvm

nodejs



reddis

elastic search

nginx/apache

monitor



How to Encrypt password
ansible-vault encrypt provisioning/roles/mysql/vars/main.yml
password: changeit

