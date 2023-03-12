# What is a patient's health level?

## Cenário

Uma operadora de saúde tem recebido muitos clientes com problemas de sobrepeso e colesterol alto. A empresa quer realizar uma análise exploratória dos dados existentes dos clientes, a fim da possibilidade de algum cliente ter indicios à colesterol alto e realizar um pré tratamento e cuidados, cuidando da saúde do seu paciente e trazendo bem estar a este.

## Objetivo


Com isso pretende-se neste projeto realizar uma análise exploratória dos dados da operadora de saúde, a fim de enetnder as causas do colesterol alto e realizar uma predição de situação do paciente à eventuais problemas de saúde.

Além de responder as seguintes perguntas:

- Quais as causas do colesterol alto no cliente? O peso interfere?
- A idade influencia na probabilidade de um cliente ter problemas de saúde?
- Quais clientes deveriam realizar um pré tratamento evitando problemas de saúde futuros?
- Há alguma relação entre o IMC e o nível de colesterol?

## Organização do projeto 

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