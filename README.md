# **Project - Book Depository dataset**


## BASES
Para esta análise foi utilizado o seguinte dataset https://www.kaggle.com/sp1thas/book-depository-dataset, considerando os arquivos listados a seguir:

* authors.csv: Contém o nome dos autores e o id que o representa no arquivo “dataset”;
* categories.csv: Contém as categorias e o id que a representa no arquivo “dataset”;
* formats.csv: Contém o formato em que os livros são disponibilizados (papel, para download,
áudio, etc) e o id que o representa no arquivo “dataset”;
* dataset.csv: Contém a lista de livros e suas informações;


## PREPARAÇÃO DOS DADOS
* Cruzamento dos dados do arquivo “authors” com o “dataset”, de forma a incluir o nome dos
autores de acordo com os ids dos autores para cada livro da base “dataset”;
* Cruzamento dos dados do arquivo “categories” com o “dataset”, de forma a incluir o nome de
todas as categorias a que o livro pertence de acordo com os ids das categorias da base
“dataset”;
* Cruzamento dos dados do arquivo “formats” com o “dataset”, de forma a incluir o nome do
formato do livro de acordo com id do formato da base “dataset”;


## PERGUNTAS
1. Qual a quantidade total de livros da base?
2. Qual a quantidade de livros que possuí apenas 1 autor?
3. Quais os 5 autores com a maior quantidade de livros?
4. Qual a quantidade de livros por categoria?
5. Quais as 5 categorias com a maior quantidade de livros?
6. Qual o formato com a maior quantidade de livros?
7. Considerando a coluna “bestsellers-rank”, quais os 10 livros mais bem posicionados?
8. Considerando a coluna “rating-avg”, quais os 10 livros mais bem posicionados?
9. Quantos livros possuem “rating-avg” maior do que 3,5?
10. Quantos livros tem data de publicação (publication-date) maior do que 01-01-2020?
