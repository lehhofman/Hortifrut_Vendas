# Hortifrut_Vendas
 - Projeto Full stack (MySQL, NodeJS, JS).
  
## Sobre o Projeto Hortifrut

- Esse projeto foi pensado para uso de pequenos empreendedores, visando auxiliá-los em suas vendas. Em um formulário irão registar **CPF, Nome Completo, Selecionar Produto, Quantidade**,  o formulário ainda contará com o **Valor Unitário, Valor Total, Data e Hora da compra**, esses valores são calculados com base na seleção do **produto e na quantidade**, pois os produto já são cadastrados com seus determinados valores. Com isso irá aparecer uma **tabela com todas as compras cadastradas**.

## Técnologias
- NodeJS;
- Mysql / MariaDB (XAMPP);
- Live Server.

## Como testar
- **1.** Clone este repositório;
- **2.** Abra com VsCode;
- **3.** Abra o XAMPP e clique em Start no MySQL;
- **4.** Abra o banco de dados via shell ou phpMyadmin e rode o **script.sql** para criar e popular o banco de dados;
- **5.** Abra o terminal (CMD ou BASH);
    - **5.1** Naveque até a pasta **./back** e instale as dependências
```bash
- cd back
- npm i
```
- **6.** Inicie o Back-End, com um dos comandos abaixo;
```bash
- node server.js
- nodemon
- npx nodemon
```
**7.** - Acesse a pasta **front** e execute o index.html via Live Server.
