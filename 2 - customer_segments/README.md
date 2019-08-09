# Nanodegree Engenheiro de Machine Learning

## Aprendizagem não supervisionada

## Projeto: Criando Segmentação de Clientes

## Sobre o projeto

Este projeto foi desenvolvido para ter experiência prática com aprendizagem não supervisionada e trabalhar desenvolvendo conclusões para um cliente em potencial com um conjunto de dados do mundo real. Muitas empresas, hoje, colhem uma vasta quantidade de dados sobre clientes, e eles têm um forte desejo de entender o significado das relações escondidos em sua clientela. Ter essa informação pode ajudar o engenheiro da empresa com futuros produtos e serviços que melhor satisfazem as demandas ou necessidades de seus clientes.

O que você aprenderá ao concluir este projeto:

- Como aplicar técnicas de pré-processamento, como dimensionamento de atributos e detecção de valores aberrantes.
- Como interpretar dados que foram dimensionados, transformados ou reduzidos por meio de PCA.
- Como analisar as dimensões de PCA e construir um novo espaço de atributos.
- Como agrupar de forma ótima um conjunto de dados para encontrar padrões ocultos.
- Como avaliar informações dadas pelos dados segmentados e utilizá-los de maneira significativa.

## Software e bibliotecas

Este projeto usará o seguinte software e bibliotecas de Python:

- [Python 3.x](https://www.python.org/downloads/release/python-374/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [Jupyter Notebook](http://ipython.org/notebook.html)

## Começando o projeto

Este projeto contém dois arquivos:

- `customer_segments_PT.ipynb`: este é o arquivo principal em que você irá executar sua tarefa do projeto.
- `customers.csv`: o conjunto de dados do projeto. Você carregará esses dados no notebook.
- `visuals.py`: este script de Python contém funções auxiliares que criarão as visualizações necessárias.



## Meta Dados

Segue os meta dados  do arquivo `customers.csv`:

1. `Fresh`: Gasto anual em produtos frescos (Continuo);
2. `Milk`: Gasto anual em produtos derivados do leite (Continuo);
3. `Grocery`: Gasto anual em produtos em mercearia (Continuo);
4. `Frozen`: Gasto anual em produtos congelados (Continuo);
5. `Detergents_Paper`: Gasto anual em produtos de limpeza  (Continuo);
6. `Delicatessen`: Gasto anual em produtos em delicatessen (Continuo);
7. `Channel`:  (Nominal)
8. `Region`: (Nominal)