
## Descrição do Projeto

Este projeto implementa um blog com funcionalidades de CRUD, permitindo a criação, visualização, edição e exclusão de posts. O objetivo principal é compreender na prática como o padrão MVC organiza a aplicação, separando as responsabilidades entre Modelos, Visões e Controladores.

![image](https://github.com/user-attachments/assets/258b32d3-36d8-4723-a014-7eaab020fd5d)

## Estrutura do Projeto

A estrutura do projeto é organizada da seguinte forma:

-   **src/**: Contém os arquivos principais da aplicação.
    -   **models/**: Define as estruturas de dados e a lógica de negócios.
    -   **views/**: Contém os templates EJS para renderização das páginas.
    -   **controllers/**: Gerencia a lógica de controle, manipulando as requisições e definindo quais dados serão exibidos nas views.
    -   **routes/**: Define as rotas da aplicação, conectando URLs específicas aos controladores correspondentes.

## Tecnologias Utilizadas

-   **Node.js**: Ambiente de execução para JavaScript no servidor.
-   **Express.js**: Framework web para Node.js, facilitando a criação de aplicações web robustas.
-   **EJS (Embedded JavaScript Templates)**: Motor de templates para gerar HTML com JavaScript.


## Funcionalidades

-   **Criar Post**: Permite adicionar um novo post ao blog.
-   **Listar Posts**: Exibe todos os posts existentes.
-   **Editar Post**: Possibilita a edição de um post existente.
-   **Excluir Post**: Permite a remoção de um post.

## Instalação e Execução

1.  **Clone o repositório**:
    
    
    `git clone https://github.com/lucas0LC/mvc.git` 
    
2.  **Navegue até o diretório do projeto**:
    
    
3.  **Instale as dependências**:
    
    `npm install` 
    

5.  **Inicie a aplicação**:
    
    `npm run dev` 
    
6.  **Acesse o blog**:
    
    -   Abra o navegador e vá para `http://localhost:3000`.
