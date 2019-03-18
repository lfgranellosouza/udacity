# Conteúdo: Aprendizado Não Supervisionado
## Projeto II: Criando Segmentos de Clientes

### Instalação

Este projeto requer **Python 2.7** ou superior e as seguintes bibliotecas de Python instaladas:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)

Você também precisará ter o software instalado para executar um [Jupyter Notebook](http://ipython.org/notebook.html)

### Código

O código template é fornecido no arquivo notebook `customer_segments.ipynb`. Também será necessário usar o arquivo Python `visuals.py`e o conjunto de dados `customers.csv` para completar o trabalho.

## Dados

Os dados de segmentação de clientes contém uma seleção de 440 pontos coletados a partir de dados de cliente de um distribuidor de atacado em Lisboa, Portugal. Mais informação pode ser encontrada em [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Wholesale+customers).

Nota: (m.u.) é a abreviação de *monetary units*.

**Características**
1) `Fresh`: gasto anual spending (m.u.) em produtos frescos (Contínua); 
2) `Milk`: gasto anual (m.u.) em laticínios (Contínua); 
3) `Grocery`: gasto anual (m.u.) em produtos de mercearia (Contínua); 
4) `Frozen`: gasto anual (m.u.) em produtos congelados (Contínua);
5) `Detergents_Paper`: gasto anual (m.u.) em detergentes e produtos de escritório (Contínua);
6) `Delicatessen`: gasto anual (m.u.) em produtos de padaria (Contínua); 
7) `Channel`: {Hotel/Restaurant/Cafe - 1, Retail - 2} (Nominal)
8) `Region`: {Lisbon - 1, Oporto - 2, or Other - 3} (Nominal) 
