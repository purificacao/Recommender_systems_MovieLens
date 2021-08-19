# Recommender Systems



## Métodos utilizados

Os dois tipos de sistemas de recomendações mais comuns são os baseados em conteúdo e baseados em filtragem colaborativa.

 * Filtragem colaborativa é baseada no julgamento dos usuários frente aos itens; ou seja; utiliza a "sabedoria popular" para fazer recomendações dos itens.
 
 * Baseados em conteúdos, focam em características dos itens, de modo que as recomendações são realizadas com base nas similaridades entre eles.
 
 
 ## Filtragem colaborativa
 
De modo geral, filtragem colaborativa (FC) é mais comumente utilizada que sistemas baseados em conteúdo, justamente porque normalmente fornece melhores resultados, além de ser relativamente fácil de entender (do ponto de vista do programador). O algoritmo tem a abilidade de realizar aprendizagem de características nele próprio, o que significa dizer que ele aprende "por conta própria" quais características utilizar.

FC pode ser dividida em **Filtragem Colaborativa Baseada em Memória** e **Filtragem Colaborativa Baseada em Modelo**.

Aqui, implementaremos FC baseada em modelo, fazendo uso de decomposição em valores singulares (SVD) e FC baseada em memória, fazendo uso da similaridade entre os cossenos.


## Dados utilizados


Faremos uso do dataset  [MovieLens](http://files.grouplens.org/datasets/movielens/), composto por 100 mil filmes, com avaliações de 944 usuários e uma seleção de 1682 filmes.

[GitHub Pages](https://pages.github.com/).
