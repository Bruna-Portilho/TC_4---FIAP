# FIAP - PÓS GRADUAÇÃO DATA ANAYTICS
# TECH CHALLENGE - MÓDULO 4
## PREVISÃO DO PREÇO DO BARRIL DE PETRÓLEO

![imagem_capa_barril_petroleo](https://github.com/Bruna-Portilho/TC_4---FIAP/assets/85244180/6ef8422a-b57c-4b9a-a65e-9253628cc918)

## TURMA 3DTAT

## GRUPO 12 
## Bruna Santiago Dias Portilho - RM 353113

## JULHO - 2024



## DESCRIÇÃO TECH CHALLENGE

Utilizando os dados do IPEA (Instituto de Pesquisa Econômica Aplicada) de histórico do preço do barril de petróleo brent, construir um modelo de machine learning que preveja diariamente o preço do barril.
O trabalho deve contar uma análise exploratória de dados, apresentada na forma de um dashboard, baseada em situações geopolíticas, crises econômicas e demanda globla de energia.
A análise deve conter pelo menos quatro "insights".
Adicionalmente, deve ser apresentado um plano para fazer o deploy com as ferrramentas necessárias além de um MVP do modelo em produção utilizando o Streamlit.


## PREMISSAS

- A base utilizada contém dados de 1986 - 2024. O período determinado obtenção do modelo de previsão foi de 2018 a 2023. Para realização da análise dos dados, avaliou-se um período maior, de 2013 a 2023.
- Os valores vazios foram preenchidos com o último valor preenchido.
- Foram testados dois modelos, o Sarimax e o Prophet.


## ANÁLISE EXPLORATÓRIA


Com base no gráfico do preço do barril de petróleo ao longo do tempo apresentado abaixo, pode-se destacar alguns pontos importantes, tais como:

- 2014: observa-se queda acentuada no preço. A hipótese sugerida é um decréscimo do consumo de energia em função do baixo crescimento da economia mundial associado à manutenção da produção de petróleo.
- 2020: observa-se queda significativa no preço, chegando a valores negativos (vale ressaltar que o preço "negativo" do barril de petróleo não tem significado econômico). Esse período é marcado pelo início da Pandemia do Covid-19, onde houve uma redução brusca do consumo, afetando diretamente o preço do barril de petróleo.
- Início de 2022: observa-se um aumento progressivo no preço do barril a partir do final de 2021. Esse comportamento pode estar associado à retomada do consumo associada ao final do período de Pandemia.
- Junho de 2022: observa-se uma queda gradativa no preço do barril. Esse efeito pode ser associado ao início da guerra da Ucrânia, o que impacta diretamente no valor do barril de petróleo.

  ![image](https://github.com/Bruna-Portilho/TC_4-FIAP/assets/85244180/8873bd6f-490e-4eb8-bc2c-871e07a9f434)



  

