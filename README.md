# Developer Backend Challenge

## Desafio
Digamos que você trabalha para uma Livraria Online, onde é possível verificar todos dados dos livros que você está emprestado ou livros que gostaria de realizar uma reserva. Nosso tempo de reserva do livro é 3 dias.

### Operações esperadas no nosso backend:

Listagem de livros emprestados:
- /client/{id_client}/books
    - Lista de livros emprestados

Ao retornar os livros emprestados, verificar de acordo com a regra sobre dias de atraso:
| Dias em atraso | Multa | Juros ao Dia |
| ------ | ------ | ------ |
| Sem atraso | 0% | 0% |
| Até 3 dias | 3% | 0.2% |
| Acima 3 dias | 5% | 0.4% |
| Acima 5 dias | 7% | 0.6% |

#### Reserva de Livro:
- /books/{id}/reserve
    - Reserva de livro

Reserva de livro passando o id do livro que gostaria de fazer a reserva.

#### Listagem de livros:
- /books
    - Retornar todos livros

Deve retornar todos livros cadastrados e também o seu status, o livro pode estar “disponível”, “emprestado”.

Informações devem ser persistidas em um banco de dados da sua preferência.

## O que entregar?
* Uma API Rest desenvolvida em Python ou Java.
* Entregar **um arquivo instrucoes.txt ou README.md** do processo para executar a
aplicação localmente.

## Como entregar?
O código deve ser entregue em um repositório GIT, deve conter um arquivo de como executar a aplicação (exemplo: README.md).

## Prazo de entrega?
48 horas

## O que estamos avaliando?
Sua capacidade de analisar, projetar e codificar uma solução guiando-se com Design Orientado a Objetos e Princípios de Orientação a Objetos.

**Outras coisas:**
- Apresentação das informações solicitadas de forma clara e objetiva
- Organização do código
- Flexibilidade do sistema para adição/remoção de funcionalidades - Testes
