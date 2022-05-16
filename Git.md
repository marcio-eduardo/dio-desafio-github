#Git

Criando chaves SSH

> ssh-keygen -t ed25519 -c marcioeduardo.ti@gmail.com

Abrindo a pasta pelo git bash

> cd ~/c/users/marci/.ssh/

validando chave

> eval $(ssh-agent -s)

adicionando identidade da chave

> ssh-add id_ed25519

