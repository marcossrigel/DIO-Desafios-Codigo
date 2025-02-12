## Descrição

Implemente um programa que simula a busca de um artigo de blog baseado no **ID** e retorna o título correspondente. Cada artigo possui um **ID**, um **título**, um **autor** e uma **data de publicação**. Caso o usuário informe um ID que não exista no banco, o programa deve exibir a mensagem **"Erro: Artigo nao encontrado!"**.

### **Requisitos**

Você deverá criar um **banco de artigos** utilizando uma estrutura de dados apropriada. O banco deve conter os seguintes artigos:

| ID   | Título                             |
| :--- | :--------------------------------- |
| 1    | Introducao ao Angular              |
| 2    | Como usar Services                 |
| 3    | Rotas no Angular                   |
| 4    | Criando Pipes                      |
| 5    | Gerenciamento de Estado no Angular |
| 6    | Lazy Loading e Performance         |

Para armazenar os artigos, utilize uma **estrutura de chave-valor**, onde o ID do artigo será a **chave** (`Integer`) e o título será o **valor** (`String`).

## Entrada

Um número inteiro representando o **ID do artigo**.

## Saída

O título do artigo no formato **"Artigo: {título}"**. Caso o ID não exista, exibir **"Erro: Artigo nao encontrado!"**.

## Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada | Saída                         |
| :------ | :---------------------------- |
| 3       | Artigo: Rotas no Angular      |
| 2       | Artigo: Como usar Services    |
| 1       | Artigo: Introducao ao Angular |
