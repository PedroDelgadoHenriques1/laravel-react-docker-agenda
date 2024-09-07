# Agenda de contatos - Laravel

<!-- <p align="center">
  <img alt="Preview" src="public/preview.png" width="100%">
</p> -->

## Índice
* [Introdução](#%EF%B8%8F-introdução)
* [Tecnologias utilizadas](#%EF%B8%8F-tecnologias-utilizadas)
* [Ferramentas utilizadas](#%EF%B8%8F-ferramentas-utilizadas)
* [Serviços utilizados](#-serviços-utilizados)
* [Funcionalidades do projeto](#-funcionalidades-do-projeto)
* [Contato](#%EF%B8%8F-contato)

## ⚙️ Introdução

Projeto feito utilizando o Laravel para a construção de um sistema de cadastro, edição, visualização e remoção de contatos.  

## 🖥️ Tecnologias utilizadas

- ``Laravel``
- ``PHP``
- ``React``
- ``TailwindCSS``
- ``Inertia``

## 🛠️ Ferramentas utilizadas

- ``Docker``
- ``PhpStorm``

## 🧰 Serviços utilizados

- ``Github``

## 🪚 Funcionalidades do projeto

- ``Funcionalidade 1:`` Sistema de login e cadastro
- ``Funcionalidade 2:`` Visualização dos contatos cadastrados
- ``Funcionalidade 3:`` Exclusão de contatos cadastrados
- ``Funcionalidade 4:`` Cadastro de novos contatos
- ``Funcionalidade 5:`` Edição de contatos cadastrados


## ✉️ Contato

Entre em contato via e-mail: pedrodelgadohenriques1@gmail.com


## PASSO A PASSO DO PROJETO
    
Clone o Projeto 
🛠️ Passo a Passo de Configuração do Projeto Laravel
Instalar Dependências com Composer Certifique-se de ter o Composer instalado. No diretório raiz do projeto, execute:


composer install
Configurar o Arquivo de Ambiente Copie o arquivo .env.example para criar um novo arquivo .env:


cp .env.example .env
Gerar a Chave de Aplicação Gere uma nova chave de aplicação para o Laravel com:


php artisan key:generate
Executar Migrações do Banco de Dados Crie as tabelas necessárias no banco de dados com:


php artisan migrate
Iniciar os Contêineres com Docker Compose Se estiver usando Docker, inicie os contêineres em segundo plano:


docker-compose up -d
Iniciar o Servidor Laravel Inicie o servidor de desenvolvimento do Laravel:

php artisan serve