## Descrição

Você foi designado para desenvolver um programa que armazena dados de usuários e permite verificar se um usuário existe no sistema. O programa deve seguir os seguintes passos:

1. **Cadastrar um número fixo de usuários**, onde cada usuário possui um **ID único** e uma **idade**.
2. **Verificar a existência de usuários** no banco de dados com base em uma lista de IDs fornecida.
3. **Exibir mensagens apropriadas** indicando se o usuário foi encontrado ou não.

## Entrada

O programa recebe os seguintes dados na entrada:

1. Um número inteiro **N** representando o número de usuários a serem cadastrados.
2. Para cada um dos N usuários, dois números inteiros:
   - O primeiro número representa o **ID do usuário**.
   - O segundo número representa a **idade do usuário**.
3. Um número inteiro **M** representando a quantidade de IDs que serão verificados.
4. **M números inteiros**, representando os IDs a serem verificados no banco de dados.



## Saída

**1. Cadastro de usuários** → `"user {ID} OK"`

**2.** **Verificação de usuários**:

- `"ID registered user"` → Se o ID for encontrado.
- `"ID invalid user"` → Se o ID **não** for encontrado.

**Observação:** A idade do usuário é informada no cadastro, mas não é utilizada durante a verificação de IDs.

## Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada                                              | Saída                                                        |
| ---------------------------------------------------- | ------------------------------------------------------------ |
| 2<br />1 62<br />2 12 <br />2<br />3<br />2          | user 1 OK<br />user 2 OK<br />3 invalid user<br />2 registeres user |
| 3<br />3 25<br />4 30<br />5 35<br />2<br />7<br />4 | user 3 OK<br />user 4 OK<br />user 5 OK<br />7 invalid user<br />4 registered user |
| 3<br />6 70<br />7 10<br />8 15<br />2<br />7<br />8 | user 6 OK<br />user 7 OK<br />user 8 OK<br />7 registered user<br />8 registered user |
