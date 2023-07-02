# What is a patient's health level?

## Cenário

Uma operadora de saúde enfrenta um desafio crescente com clientes com sobrepeso e colesterol alto. Para lidar com essa situação, a empresa busca realizar uma análise exploratória dos dados existentes dos clientes. O objetivo é identificar as principais causas e fatores de risco, a fim de desenvolver estratégias preventivas e de tratamento adequadas.

## Objetivo

Neste repositório, realizaremos uma análise exploratória dos dados da operadora de saúde, com foco em problemas de sobrepeso e colesterol alto entre os clientes. Nosso objetivo é identificar as causas possíveis desses problemas e fornecer insights para tratamento e cuidados preventivos, visando melhorar a saúde dos pacientes e promover seu bem-estar. Através dessa análise, buscamos contribuir para a compreensão mais aprofundada dessas questões e proporcionar informações valiosas que possam orientar a tomada de decisões e ações para promover uma vida mais saudável.

Além de responder as seguintes perguntas:

- Quais são as principais causas do colesterol alto nos clientes? O peso tem influência significativa?
- A idade do cliente tem relação com a probabilidade de problemas de saúde?
- Quais clientes devem receber tratamento prévio para evitar problemas de saúde futuros?
- Existe alguma correlação entre o Índice de Massa Corporal (IMC) e os níveis de colesterol?

## Organização do projeto 

O projeto está organizado da seguinte forma:

            What_is_a_patients_health_level
            ┣ data
            ┃ ┣ clientes_operadora_saude.xlsx
            ┃ ┣ estados_brasileiros.csv
            ┃ ┗ idade_clientes.csv
            ┃
            ┣ imag
            ┃ ┣ Kmeans.png
            ┃ ┗ WCSS.png
            ┃
            ┣ main
            ┃ ┗ classificação_clientes_cluster.csv
            ┃
            ┣ tratativa
            ┃ ┣ merged_operadora_saude.csv
            ┃ ┗ Tratativa_op_saude.ipynb
            ┃
            ┣ Eda_Operadora_de_saude.ipynb
            ┗ README.md

O diretório [data](data) contém os dados utilizados neste projeto. O arquivo [clientes_operadora_saude.xlsx](data/clientes_operadora_saude.xlsx) contém os dados dos clientes da operadora de saúde. O arquivo [estados_brasileiros.csv](data/estados_brasileiros.csv) contém os dados dos estados brasileiros. O arquivo [idade_clientes.csv](data/idade_clientes.csv) contém os dados da idade dos clientes.

## Ferramentas utilizadas

Para realizar a análise exploratória dos dados, foram utilizadas as seguintes ferramentas:

- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Análise exploratória dos dados

A análise exploratória dos dados foi realizada no arquivo [Eda_Operadora_de_saude.ipynb](Eda_Operadora_de_saude.ipynb). Neste arquivo, foram realizadas as seguintes etapas:

- Importação das bibliotecas
- Importação dos dados
- Análise exploratória dos dados
- Tratamento dos dados
- Análise exploratória dos dados tratados
- Análise de correlação


## Metodologia

A metodologia utilizada neste projeto foi a CRISP-DM, que é uma metodologia de mineração de dados que descreve as etapas comuns encontradas por cientistas de dados ao lidar com problemas de mineração de dados. A metodologia consiste em seis etapas:

- Entendimento do negócio
- Entendimento dos dados
- Preparação dos dados
- Modelagem
- Avaliação

## Resultados

Após a análise exploratória dos dados, foi possível identificar que o peso dos clientes tem influência significativa no nível de colesterol, sendo que os clientes com sobrepeso e obesidade possuem níveis de colesterol mais altos. Além disso, foi possível identificar que a idade do cliente também tem relação com o nível de colesterol, sendo que os clientes com mais de 40 anos possuem níveis de colesterol mais altos.

Com isso, foi possível identificar que os clientes com sobrepeso e obesidade e com mais de 40 anos são os que possuem maior probabilidade de problemas de saúde futuros, sendo que estes clientes devem receber tratamento prévio para evitar problemas de saúde futuros.

Além disso, foi possível identificar que existe uma correlação entre o Índice de Massa Corporal (IMC) e os níveis de colesterol, sendo que os clientes com sobrepeso e obesidade possuem níveis de colesterol mais altos.

## Como executar o projeto

Para executar o projeto, você deve ter o Python instalado em sua máquina. Além disso, você deve instalar as bibliotecas necessárias, que estão listadas no arquivo [requirements.txt](requirements.txt). Para instalar as bibliotecas, execute o seguinte comando no terminal:

```bash
pip install -r requirements.txt
```

Após instalar as bibliotecas, você deve executar o arquivo [Eda_Operadora_de_saude.ipynb](Eda_Operadora_de_saude.ipynb) no Jupyter Notebook.

## Referências

- [CRISP-DM](https://pt.wikipedia.org/wiki/Cross_Industry_Standard_Process_for_Data_Mining)
- [Pandas](https://pandas.pydata.org/)
- [Numpy](https://numpy.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)
- [Scikit-learn](https://scikit-learn.org/stable/)
- [K-means](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [Elbow Method](https://www.geeksforgeeks.org/elbow-method-for-optimal-value-of-k-in-kmeans/)


## LICENÇA

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.