🔧 OficinaTech — Sistema de Assistência Técnica

Sistema web desenvolvido para auxiliar no gerenciamento de uma assistência técnica, centralizando o cadastro de clientes, dispositivos e registros de consertos em um único lugar.

O projeto foi desenvolvido como prática de desenvolvimento web, aplicando conceitos de PHP, banco de dados MySQL, HTML e CSS.

📌 Sobre o projeto

O OficinaTech tem como objetivo organizar as informações de uma assistência técnica, facilitando o controle dos clientes, dos dispositivos cadastrados e do histórico de serviços realizados.

A aplicação possui uma interface simples e organizada, com páginas próprias para cada funcionalidade e estilos CSS separados para facilitar a manutenção do sistema.

✨ Funcionalidades

👤 Cadastro de clientes: registro e gerenciamento dos dados dos clientes.

📱 Cadastro de dispositivos: associação de dispositivos aos respectivos clientes.

🔍 Busca de registros: pesquisa para facilitar a localização de clientes e dispositivos.

🛠️ Registro de consertos: gerenciamento dos serviços realizados.

📋 Histórico de consertos: consulta dos registros de serviços.

🔐 Login e controle de sessão: acesso ao sistema por meio de autenticação.

🎨 Interface personalizada: estilização das páginas com CSS.

📂 Organização dos arquivos: separação dos estilos por página.

💻 Tecnologias utilizadas

Tecnologia

Utilização

PHP

Lógica da aplicação e processamento dos dados

MySQL

Armazenamento das informações

HTML5

Estrutura das páginas

CSS3

Estilização e responsividade

XAMPP

Ambiente de desenvolvimento local

phpMyAdmin

Administração do banco de dados

📁 Estrutura do projeto

oficina/
├── css/
│   ├── style.css
│   ├── cliente.css
│   └── dispositivos.css
├── login.php
├── principal.php
├── clientes.php
├── dispositivos.php
├── concertos.php
├── historico.php
├── logout.php
└── README.md

Observação: a estrutura acima é ilustrativa. Ajuste os nomes dos arquivos conforme a organização atual do seu repositório.

⚙️ Como executar o projeto

1. Instale o ambiente

Instale o XAMPP, que disponibiliza o Apache, o PHP e o MySQL para desenvolvimento local.

2. Configure os arquivos

Coloque a pasta oficina dentro do diretório htdocs do XAMPP.

3. Inicie os serviços

Abra o painel do XAMPP e inicie:

Apache

MySQL

4. Configure o banco de dados

Acesse o phpMyAdmin pelo endereço http://localhost/phpmyadmin.

Crie ou importe o banco de dados utilizado pelo projeto.

Confira se as tabelas necessárias estão criadas.

Verifique as credenciais de conexão com o banco nos arquivos PHP responsáveis por essa configuração.

5. Acesse o sistema

No navegador, entre em:

http://localhost/oficina/login.php

🔒 Segurança

O projeto utiliza autenticação e controle de sessão para restringir o acesso às páginas internas.

Em futuras melhorias, podem ser aplicados recursos adicionais, como validação de dados no servidor, consultas preparadas, tratamento de erros e aprimoramentos na proteção das sessões.

🚀 Melhorias futuras

Aprimorar a responsividade para dispositivos móveis.

Melhorar a validação dos formulários.

Implementar filtros e pesquisas avançadas.

Aprimorar a organização visual das telas.

Adicionar indicadores e relatórios de serviços.

Expandir os recursos de segurança.

📚 Objetivo educacional

Este projeto tem finalidade educacional e prática, contribuindo para o desenvolvimento de conhecimentos em programação web, integração com banco de dados, organização de código e criação de interfaces.

👩‍💻 Desenvolvido por

Mariana Ribeiro

Estudante de Desenvolvimento de Sistemas.

⭐ Projeto desenvolvido para praticar e aprimorar habilidades em desenvolvimento web.
