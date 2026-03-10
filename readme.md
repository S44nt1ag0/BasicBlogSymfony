# 🚀 Symfony Social Blog

Um motor de blog moderno com interface inspirada em feeds de redes sociais (X/Instagram), construído com **Symfony 7**, **PostgreSQL** e **Tailwind CSS**.

Este projeto foca em uma experiência de leitura imersiva, sistema de autenticação robusto e gestão de mídias.

<img width="1088" height="903" alt="login" src="https://github.com/user-attachments/assets/85e3b5f7-36bf-43bb-be78-6b260cc412fe" />
<img width="1165" height="943" alt="feed" src="https://github.com/user-attachments/assets/37b3df27-4933-4ddb-bcd0-7069594ab873" />
<img width="995" height="941" alt="create" src="https://github.com/user-attachments/assets/1f2bb84e-fc58-459e-af36-9a5194bb28a3" />
<img width="1048" height="942" alt="post" src="https://github.com/user-attachments/assets/464eade3-05d2-4b77-b7bc-682eee4449c7" />
<img width="980" height="940" alt="registro" src="https://github.com/user-attachments/assets/421b6da3-1d5c-476e-b520-70c0d14ba117" />


## ✨ Funcionalidades

* **Feed "For You":** Visualização de posts em cards verticais com design limpo.
* **Gestão de Conteúdo (CRUD):** Criação, edição e exclusão de posts com suporte a quebras de linha (`nl2br`).
* **Upload de Imagens:** Sistema de upload de fotos de capa com validação de tipo e tamanho.
* **Autenticação:** Sistema de login e cadastro integrado ao Security Bundle do Symfony.
* **Proteção de Rotas:** Acesso ao feed e criação de posts restrito a usuários autenticados.
* **UI/UX Moderna:** Desenvolvido com **DaisyUI** e efeito de *Glassmorphism* (desfoque) na barra de navegação.

## 🛠️ Tecnologias

* **Backend:** PHP 8.2+ & Symfony 7
* **Banco de Dados:** PostgreSQL 16
* **Frontend:** Twig, Tailwind CSS & DaisyUI
* **Estilização:** @tailwindcss/typography (para leitura de artigos)

## 🚀 Como Rodar o Projeto

### 1. Requisitos Pró-Instalação
Certifique-se de ter instalado:
* PHP 8.2 ou superior
* Composer
* PostgreSQL
* Symfony CLI (opcional, mas recomendado)

### 2. Instalação
Clone o repositório e instale as dependências:
```bash
git clone [https://github.com/seu-usuario/seu-projeto.git](https://github.com/seu-usuario/seu-projeto.git)
cd seu-projeto
composer install
