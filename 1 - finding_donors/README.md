# Nanodegree Engenheiro de Machine Learning
## Aprendizagem supervisionada
## Projeto: Encontrando doadores para a CharityML

## Sobre o Projeto

Este projeto foi desenvolvido para prática de algoritmos de aprendizagem supervisionada disponíveis em sklearn e também para mostrar como cada modelo funciona e performa em um determinado tipo de dado. É importante em machine learning compreender exatamente quando e onde um determinado algoritmo deve ser usado e quando deve ser evitado.

Objetivos de aprendizado:

- Como identificar se o pré-processamento é necessário e como aplicá-lo.
- Como estabelecer uma referência para uma solução do problema.
- O que cada um dos vários algoritmos de aprendizagem supervisionada realiza, considerando um conjunto de dados específico.
- Como avaliar se um candidato a modelo de solução é adequado ao problema.

## Software e bibliotecas

Este projeto requer **Python 3.7** e as seguintes bibliotecas Python instaladas:

- [Python 3.x](https://www.python.org/downloads/release/python-374/)
- [NumPy](http://www.numpy.org/)
- [pandas](http://pandas.pydata.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)
- [Jupyter Notebook](http://ipython.org/notebook.html)

## Dados

O conjunto de dados do censo consiste em 32.000 registros, sendo que cada registro possui 13 atributos. Este conjunto de dados é uma versão modificada do que foi publicado no artigo *"Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid",* de Ron Kohavi. Você pode encontrar este artigo [online](https://www.aaai.org/Papers/KDD/1996/KDD96-033.pdf), com o conjunto de dados original hospedado em [UCI](https://archive.ics.uci.edu/ml/datasets/Census+Income).

**Atributos**

- `age`: Idade
- `workclass`: Classe trabalhadora (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
- `education_level`: Nível de educação (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
- `education-num`: Número de anos de estudo concluídos
- `marital-status`: Estado civil (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
- `occupation`: Ocupação profissional (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
- `relationship`: Status de relacionamento (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
- `race`: Raça (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
- `sex`: Sexo (Female, Male)
- `capital-gain`: Ganhos de capital monetário
- `capital-loss`: Perdas de capital monetário
- `hours-per-week`: Média de horas trabalhadas por semana
- `native-country`: País de origem (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)

**Variável-alvo**
- `income`: Classe de renda (<=50K,>50K)</=50K,>
