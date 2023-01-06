# Xibo Docker

[Docker](https://docker.com/)é um aplicativo para empacotar e executar qualquer
aplicativo em um contêiner pré-configurado, tornando muito mais fácil implantar um Xibo
CMS com configuração recomendada.

Este repositório contém as definições do contêiner docker para Xibo e o docker-compose
configuração, que é usada para inicializar, iniciar, parar e destruir a instalação.

## Instalação
Instruções completas de instalação para uso suportado desses contêineres podem ser
encontrado no [Xibo
Manual](http://xibo.org.uk/manual-tempel/en/install_cms.html)
utilize o usuário root
baixe o arquivo direto na pasta /opt
renomeie a pasta para xibo-docker utilizando o comando mv
na pasta contem um arquivo chamado config.env.template renomeie ele para config.env e deixe o outro como Backup e faça suas configurações
agora no arquivo docker-compose.yml use o nano e configure a senha e usuário do banco de dados Mysql e a porta do serviço web a padrão é 80

pronto após isso utilize o comando docker-compose -up -d
# o up é para subir e -d é para rodar em background e liberar o terminal 

agora para ver os serviços utilize o docker ps
