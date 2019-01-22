# Projeto 6 - Udacity (Configuração do Servidor Linux)
Este projeto consiste em uma instalação de referência de uma distribuição Linux em uma máquina virtual e prepará-la para hospedar aplicações web, para incluir atualizações de instalação, para oferecer segurança diante de um número de vetores de ataque, e para instalar/configurar servidores web e de banco de dados.
Dentre as tarefas de configuração:
- Configuração de um servidor na AWS;
- Atualizar todos os pacotes instalados;
- Mudança de porta SSH de 22 para 2200;
- Configuração da Porta HTTP (porta 80);
- Configuração da Porta NTP (porta 123);
- Criação de usuário (grader);
- Permissão "sudo" para usuário criado;
- Criação de chaves SSH;
- Instalação e configuração do Apache com aplicação mod_wsgi-py3;
- Instalação e configuração do PostgreSQL;
- Instalação do GIT e clonagem de repositório do GITHUB.

## Inicio
- Esta aplicação foi desenvolvida em Python 3.7 usando o módulo psycopg2 para se conectar ao banco de dados PostgreSQL.

## Endereço WEB
- http://54.86.174.251.xip.io/
- Foi utilizado o serviço da xip.io para criar rapidamente um nome de domínio para a aplicação.

## Acesso ao servidor
- $ ssh grader@54.86.174.251 -p 2200 -i <path>/<chave privada>

## Autores
- Desenvolvido por Flavio André Virgilio
