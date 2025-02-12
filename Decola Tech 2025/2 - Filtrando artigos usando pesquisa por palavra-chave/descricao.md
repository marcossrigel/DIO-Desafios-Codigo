## Descrição

Implemente um programa que **receba um termo de pesquisa** e retorne todos os **títulos de artigos** que contenham esse termo.

### **Regras da busca**

- A busca deve ser **case insensitive**, ou seja, **não deve diferenciar maiúsculas e minúsculas**.
- Se houver correspondências, a saída deve listar os artigos encontrados no formato esperado.
- Se **nenhum artigo for encontrado**, o programa deve exibir uma mensagem indicando que não houve resultados.

### **Lista de Artigos Disponíveis**

Implemente a base de dados contendo os seguintes artigos:

- **Introducao ao Angular**
- **Como usar Services**
- **Rotas no Angular**
- **Criando Pipes**

Cada título deve ser armazenado e pesquisado de forma que a busca não diferencie maiúsculas e minúsculas.

## Entrada

O programa recebe **uma única linha de entrada**, contendo um termo de pesquisa (**string**) que pode ter uma ou mais palavras.



## Saída

1. Se houver correspondências, exibir os artigos no formato:

```
Artigos encontrados:- {Título do Artigo 1}- {Título do Artigo 2}
```

2. Se nenhum artigo corresponder ao termo pesquisado:

```
Nenhum artigo encontrado para o termo: {termo}
```

## Exemplos

A tabela abaixo apresenta exemplos com alguns dados de entrada e suas respectivas saídas esperadas. Certifique-se de testar seu programa com esses exemplos e com outros casos possíveis.

| Entrada  | Saída                                                        |
| -------- | ------------------------------------------------------------ |
| Angular  | Artigos encontrados:<br />- Introducao ao Angular<br />- Rotas no Angular |
| Services | Artigos encontrados:<br /> - Como usar Services              |
| Pipes    | Artigos encontrados:<br />-  Criando Pipes                   |
