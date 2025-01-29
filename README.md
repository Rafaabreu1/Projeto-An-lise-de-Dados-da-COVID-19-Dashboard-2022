### **1.1. TLDR**
- **Dashboard**:
  - Google Data Studio ([link](https://lookerstudio.google.com/reporting/33ff63e8-4724-48df-b93b-59c6dbbc824a)).
 - **Processamento**:
  - Kaggle Notebook ([link](https://www.kaggle.com/code/rafaeldeabreu/notebook19411c4008/edit)).
 - **Fontes**:
  - Casos pela universidade John Hopkins ([link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports));
  - Vacinação pela universidade de Oxford ([link](https://covid.ourworldindata.org/data/owid-covid-data.csv)).

  - ## Objetivo
    O objetivo deste projeto foi desenvolver um dashboard interativo para visualizar e analisar a evolução da COVID-19 ao longo de 2022. Através da consolidação de dados diários sobre casos confirmados, óbitos e vacinação, o painel permite identificar tendências, comparar períodos e obter insights sobre o impacto da pandemia.
  - ## Dataset
    Os dados utilizados neste projeto foram extraídos de duas fontes confiáveis:

    Casos confirmados e óbitos: Obtidos a partir do repositório do GitHub ([link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)), que disponibiliza relatórios diários sobre a pandemia.
    Dados de vacinação: Coletados do dataset do Kaggle ([link](https://covid.ourworldindata.org/data/owid-covid-data.csv)), que contém registros detalhados sobre a evolução da vacinação global.
    Essas fontes permitiram a construção de um painel interativo para acompanhar a evolução da pandemia ao longo de 2022.

   
  - ## Tecnologias utilizadas
  - Jupyter
  - python (Math, Typing, Datetime, Numpy, Pandas)
  - BI (Looker studio)
  - 
  - ## Metodologia
  ETL (Extração, Transformação e Carregamento de Dados)
 Extração:

Os dados de casos confirmados e óbitos foram coletados do repositório do GitHub ([link](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_daily_reports)).
Os dados de vacinação foram extraídos do dataset do Kaggle ([link](https://covid.ourworldindata.org/data/owid-covid-data.csv)).

Transformação:

Utilização de bibliotecas como Pandas, NumPy, Datetime e Typing para processar os dados.
Filtragem e organização das colunas para manter apenas as informações relevantes.
Padronização dos formatos de data e remoção de dados irrelevantes  nos datasets.
Carregamento:

Os dados transformados foram salvos em formato CSV para facilitar a importação e visualização no Looker Studio.

 Construção do Dashboard

Importação dos dados no Looker Studio para criação de visualizações dinâmicas.
Desenvolvimento de gráficos interativos, incluindo:
Evolução diária dos casos confirmados.
Número de mortes ao longo do tempo.
Progresso da vacinação diária por país.
Ajustes e refinamento para garantir que os insights fossem apresentados de forma clara e objetiva.
  

  - ## Resultado
Total de 480.332.769 doses de vacinas aplicadas no Brasil em 2022, incluindo primeira, segunda e terceira doses.

Análise detalhada do número de casos confirmados e óbitos por dia, permitindo acompanhar a evolução da pandemia.

Cálculo da porcentagem da população vacinada ao longo do tempo, demonstrando o impacto da vacinação.

Identificação de tendências, como estabilidade, aumento ou queda nos casos e óbitos ao longo dos meses.

Cálculo da média móvel de mortes e casos a cada sete dias, representado em gráficos que mostram a curva de evolução desses indicadores.

    ## Próximos passos

    ## Como executar

    ## Licença
  - 
