# Modelagem de biblioteca 

## Regra de negocio / Requesitos

Uma biblioteca deseja manter informações sobre seus livros.
Inicialmente, quer armazenar para os livros as seguintes características:
ISBN, título, ano editora e autores deste livro. Para os autores, deseja
manter: nome e nacionalidade. Cabe salientar que um autor pode ter
vários livros, assim como um livro pode ser escrito por vários autores.
Cada livro da biblioteca pertence a uma categoria. A biblioteca deseja
manter um cadastro de todas as categorias existentes, com informações
como: código da categoria e descrição. Uma categoria pode ter vários
livros associados a ela.

## Modelo conceitual (DER 1.0)

![Diagrama ER](../../imagens/DER/biblioteca.PNG)

## Modelo conceitual (DER 1.1)

incluindo cardinalidades pertinentes a regra de negocio, atender os requisitos do sistema com o objetivo de atender o mundo real.

![Diagrama DER 1.1](../../imagens/DER/biblioteca2.PNG)

## Modelo conceitual (DER 1.2)

incluindo entidades associativas pertinentes a suas cardinalidades com o objetivo de atender os requisitos do sistema.

![Diagrama DER 1.2](../../imagens/DER/biblioteca3.PNG)

[voltar](../../README.md)