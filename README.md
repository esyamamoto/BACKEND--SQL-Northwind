# Projeto SQL Northwind

<details>
<summary><strong>👨‍💻</strong></summary><br />

banco de dados: `Northwind`, usado neste projeto. 

 </details>

<details>
  <summary><strong>:memo: Habilidades</strong></summary><br />

  Neste projeto:

- As queries que foi desenvolvido devem retornar exatamente a quantidade de colunas e registros esperados, dentro do que foi pedido.
- Organização do código. Deixe sempre as palavras-chave em CAIXA ALTA e os nomes de tabelas e colunas em caixa baixa.
- Desafios de SELECT e criação de dados;
- Desafios sobre filtragem de dados;
- Desafios de manipulação de tabelas.
- testar suas funções com Jest.

</details>

<details>
  <summary><strong>🗒️ Instruções para restaurar o banco de dados `Northwind`</strong></summary><br />

1. Faça o download do arquivo de backup [aqui](northwind.sql) clicando em "Raw", depois clicando com botão direito e selecionando "Salvar como" para salvar o arquivo em seu computador.

2. Abra o arquivo com algum editor de texto e selecione todo o conteúdo do arquivo usando `CTRL-A`.

3. Abra o MySQL Workbench.

4. Abra uma nova janela de query e cole dentro dela todo o conteúdo do arquivo `northwind.sql`.

5. Selecione todo o código com o atalho `CTRL-A` e depois clique no ícone de raio para executar a query.

    ![Restaurando o banco Northwind](images/restore_northwind.png)
6. Aguarde alguns segundos (espere em torno de 30 segundos antes de tentar fazer algo).

7. Clique no botão apontado na imagem a seguir para atualizar a listagem de banco de dados.

    ![Tabelas do banco Northwind](images/refresh_databases.png)
8. Verifique se o banco restaurado possui todas as seguintes tabelas:

    ![Tabelas do banco Northwind](images/northwind.png)
9. Clique com botão direito em cada tabela e selecione "Select Rows" e certifique-se que todas as tabelas possuem registros. Caso tenha alguma faltando, faça o passo a seguir. Caso contrário, pode ir para próxima seção.

10. Caso existam tabelas faltando, drope o banco de dados clicando com o botão direito em cima do banco de dados northwind e selecionando "Drop Schema" e refaça os passos novamente, dessa vez aguardando um tempo maior quando executar o script de restauração.

    ![Drop Schema](images/drop_database.png)

</details>
