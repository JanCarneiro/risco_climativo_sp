## Painel de Monitoramento de Risco Climático para Incêndios no Estado de São Paulo

Projeto desenvolvido em grupo para o Projeto Integrador IV da Universidade Virtual do Estado de São Paulo. 

Nesse projeto, o grupo desenvolveu um painel de monitoramento para o risco de incêncio no estado de São Paulo. Foi utilizado datasets públicos do INPE e INMET, além do desenvolvimento de um algoritimo de machine learning para predição do risco de fogo com RandomForestRegressor.

Nesse projeto fiquei responsável pela coleta e tratamento dos dados, etapa importante para resolver problemas encontrados nos dados como duplicados, nulos, fora de escala e padrão. Realizei a coleta manualmente dos arquivos csv, importei no Databricks Community Edition e criei um script com Python, SQL e PySpark para transformação.

## Como executar:

Basta criar uma conta no Databricks Community Edition, importar os notebooks, criar um cluster Spark e executar o algoritmo.

Os Datasets estão disponíveis nos links abaixo:

###### INPE (últimos 10 anos): https://terrabrasilis.dpi.inpe.br/queimadas/bdqueimadas/#exportar-dados
###### INMET (Estações de SP): https://bdmep.inmet.gov.br/

#### Grupo desenvolvedor:

Amanda Sayuri Kuroiva,
Ebian Junior,
Fabiano Cavalcante,
Gustavo Camargo,
Hugo Mendes,
Janderson Silva,
Josué Silva,
Tiago Silva.
