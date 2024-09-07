Agenda de Contatos - Laravel

⚙️ Introdução
Este projeto foi desenvolvido com Laravel para gerenciar contatos, permitindo criar, editar, visualizar e excluir registros de contatos.

🖥️ Tecnologias utilizadas
Laravel
PHP
React
TailwindCSS
Inertia
🛠️ Ferramentas utilizadas
Docker
PhpStorm
🧰 Serviços utilizados
GitHub

🪚 Funcionalidades do projeto
Funcionalidade 1: Autenticação de usuários (login e cadastro)
Funcionalidade 2: Visualização de todos os contatos cadastrados
Funcionalidade 3: Remoção de contatos
Funcionalidade 4: Inserção de novos contatos no sistema
Funcionalidade 5: Atualização dos dados dos contatos

✉️ Contato
Entre em contato através do e-mail: pedrodelgadohenriques1@gmail.com


## PASSO A PASSO DO PROJETO - RODANDO COMANDOS
    
## Clone o Projeto 
🛠️ Passo a Passo de Configuração do Projeto Laravel
Instalar Dependências com Composer Certifique-se de ter o Composer instalado. No diretório raiz do projeto, execute:


## composer install
Configurar o Arquivo de Ambiente Copie o arquivo .env.example para criar um novo arquivo .env:


## cp .env.example .env
Gerar a Chave de Aplicação Gere uma nova chave de aplicação para o Laravel com:


## php artisan key:generate
Executar Migrações do Banco de Dados Crie as tabelas necessárias no banco de dados com:


## php artisan migrate
Iniciar os Contêineres com Docker Compose Se estiver usando Docker, inicie os contêineres em segundo plano:


## docker-compose up -d
É usado para iniciar containers definidos em um arquivo docker-compose.yml


## php artisan serve
Iniciar servidor
