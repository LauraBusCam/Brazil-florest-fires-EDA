# Brazil-florest-fires-EDA
Este Readme fornece uma visão geral do projeto de análise exploratória de dados sobre incêndios no Brasil. Este projeto tem como objetivo explorar e analisar dados relacionados a incêndios florestais no Brasil, visando compreender padrões, tendências e possíveis causas desses eventos.

## Introdução
Os incêndios florestais são uma preocupação ambiental significativa em todo o mundo, e o Brasil não é exceção. Este projeto se propõe a examinar dados sobre incêndios florestais no Brasil, a fim de fornecer insights sobre sua distribuição geográfica, sazonalidade, magnitude e possíveis fatores contribuintes.

## Conjunto de Dados
Os dados utilizados nesse projeto tem como origem:
**Queimadas:** https://dados.gov.br/dados/conjuntos-dados/snif - Que compreendem variáveis como: ['Estado', 'Quantidade de incêndios', 'Data']

**Informações do clima:** https://www.kaggle.com/datasets/fabiojorge/brazil-temperature-2012-2019 - Que compreendem variáveis como:
['Estado', 'Data', 'Precipitacao', 'TempMaxima', 'TempMinima', 'UmidadeRelativa']

## Objetivos
Os principais objetivos deste projeto são:

##### Identificar áreas geográficas com maior incidência de incêndios florestais.
##### Analisar padrões sazonais de ocorrência de incêndios.
##### Investigar correlações entre condições climáticas e incidência de incêndios.
##### Explorar a diferença do comportamento de fatores climáticos que estão correlacionados com os incêndios entre as regiões do Brasil.

## Metodologia
O projeto de análise exploratória será conduzido em etapas, utilizando técnicas de visualização de dados, estatísticas descritivas e análise exploratória. As etapas incluirão:

##### Preparação dos Dados: Limpeza e pré-processamento dos dados, incluindo tratamento de valores ausentes e inconsistências.
##### Análise Descritiva: Exploração inicial dos dados através de estatísticas descritivas e visualizações básicas para entender a distribuição e características dos incêndios.
##### Análise de Correlação: Avaliação das relações entre variáveis, como condições meteorológicas e tamanho dos incêndios.
##### Identificação de Fatores Contribuintes: Exploração de possíveis fatores climáticos que influenciam na ocorrência de incêndios.
##### Análise Temporal: Investigação de padrões temporais na ocorrência de incêndios, incluindo análise sazonal.

## Resultados Esperados
Espera-se que este projeto forneça insights valiosos sobre a dinâmica dos incêndios florestais no Brasil, identificando regiões de maior incidência, padrões sazonais e possíveis fatores contribuintes. Esses resultados podem ser úteis para o desenvolvimento de estratégias de prevenção e mitigação de incêndios, bem como para a conscientização pública sobre a importância da preservação ambiental.

## Ferramentas Utilizadas
##### Python: Pandas, Statsmodels, Matplotlib para manipulação e visualização de dados.
##### Jupyter Notebook para desenvolvimento e documentação do projeto.
##### Estrutura do Repositório
##### /data: Pasta contendo os conjuntos de dados utilizados no projeto.
##### /src: Notebooks Jupyter contendo o código fonte e a documentação do projeto.
##### README.md: Este arquivo que fornece uma visão geral do projeto.

# Como Executar o Projeto
Para executar este projeto localmente, siga estas etapas:

Clone este repositório para o seu ambiente de desenvolvimento.
Instale as dependências listadas no arquivo requirements.txt.
Execute os notebooks Jupyter 'main.ipynb' na pasta /src.


## Autores
Este projeto foi desenvolvido por:
- Glaydson Gonçalo dos Santos Almeida;
- Guilherme Araújo Mendes de Souza;
- Laura Busin Campos;
- Miller Machado Monteiro;
Como projeto de conclusão do módulo de 'Técnicas de Programação' proporcionado por ADA Tech, no programa 'Santander Coders 2023.2 / Data Science' datado em 27/02/2024.
Licença
Este projeto é distribuído sob a licença [MIT License]. Consulte o arquivo LICENSE para obter mais detalhes.