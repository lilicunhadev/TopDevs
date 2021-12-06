## DESAFIO KZAS - TOP DEVELOPERS OF GITHUB

### Requisitos do Projeto
- Instale o PHP 7.3+ e o Laravel 8 em sua máquina;
- Instale Node 16+;
- Faça o clone desse repositório em sua máquina local.

### Como iniciar a aplicação
- Entre na pasta do projeto;
- Abra um terminal e digite:
- "Composer install"
- Copie ".env.example" para ".env"
- Crie um banco de dados e passe as credenciais
- Rode "php artisan migrate"
- "php artisan key:generate"
- No seu perfil do Github, clique em Settings
- Depois em Developer Settings
- E em Personal Access Tokens
- Clique no botão "Generate new token"
- Crie um nome e sete todas as permissões
- Clique em "Generate Token"
- Copie o código do token criado
- Cole em "'access_token' => " no arquivo DevController.php
- Caminho: <app/Http/Controllers/DevController.php>
- Cole nas linhas 35 e 45
- Esse token permite um maior número de requisições à API do Github
- Depois disso digite no terminal:
- "php artisan serve"
- O projeto está rodando!
- É só se registrar ^^

