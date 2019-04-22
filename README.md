# Prevendo Demanda de Estoque com Base em Vendas

>Fui apresentado a esse desafio pela *Data Science Academy* como parte de seu programa curricular.

O Grupo Bimbo (https://www.grupobimbo.com), se esforça para atender a demanda diária dos consumidores por produtos frescos de panificação nas prateleiras de mais de 1 milhão de lojas ao longo das suas 45.000 lojas em todo o México.

Atualmente, os cálculos diários de estoque são realizados por funcionários de vendas de entregas diretas, que devem, sozinhos, prever a necessidade de estoque dos produtos e demanda com base em suas experiências pessoais em cada loja. Como alguns pães têm uma vida útil de uma semana, a margem aceitável para o erro é pequena.

Neste projeto de aprendizado de máquina, você deve desenvolver um modelo para prever com precisão a demanda de estoque com base nos dados
históricos de vendas. Isso fará com que os consumidores dos mais de 100 produtos de panificação não fiquem olhando para as prateleiras vazias, além de reduzir o valor gasto com reembolsos para os proprietários de lojas com produtos excedentes impróprios para venda.

### Divisão do projeto

Esse projeto está dividido em 3 notebooks:
#### EDA
https://nbviewer.jupyter.org/github/marcoayamada/bimbo_sales/blob/master/EDA.ipynb - [[Github](https://github.com/marcoayamada/bimbo_sales/blob/master/EDA.ipynb)]

#### XGBoost ~ msle=1.767
https://nbviewer.jupyter.org/github/marcoayamada/bimbo_sales/blob/master/%5B4%5D%20Bimbo%20(xgboost).ipynb - [[Github](https://github.com/marcoayamada/bimbo_sales/blob/master/%5B4%5D%20Bimbo%20(xgboost).ipynb)]

#### Apenas a média das semanas anteriores ~ msle=1.622
https://nbviewer.jupyter.org/github/marcoayamada/bimbo_sales/blob/master/%5B5%5D%20Bimbo%20(medians).ipynb - [[Github](https://github.com/marcoayamada/bimbo_sales/blob/master/%5B5%5D%20Bimbo%20(medians).ipynb)]
