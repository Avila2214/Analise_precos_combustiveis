# Preços de Combustíveis Data Lake

## Sobre o Projeto

Este projeto utiliza um datalake com camadas **Bronze**, **Silver** e **Gold** para a manipulação e organização eficiente dos dados de preços de combustíveis no Brasil (2004-2019). O objetivo principal é tratar, limpar e analisar os dados de diferentes regiões do país, facilitando a obtenção de insights relevantes para análise dos preços de combustíveis ao longo do tempo.

## Estrutura do Projeto

- **Bronze**: Contém os dados brutos conforme recebidos das fontes originais, sem qualquer transformação.
- **Silver**: Dados parcialmente limpos e organizados, prontos para análises exploratórias.
- **Gold**: Dados totalmente refinados e transformados, prontos para dashboards, relatórios e machine learning.

## Tecnologia Utilizada

- **Linguagem**: Python
- **Biblioteca**: Pandas - para manipulação de dados
- **Ferramentas**: Jupyter Notebook - para análise exploratória

## Funcionalidades

- **Extração de dados**: Coleta de dados de preços de combustíveis para diferentes regiões do Brasil.
- **Limpeza e transformação incremental de dados**: Processamento e transformação dos dados para garantir qualidade e consistência.
- **Armazenamento de dados organizados em camadas**: Organiza os dados em camadas (Bronze, Silver e Gold) para facilitar análise e visualização.

## Instruções para Execução

**Clonar ou repositório**

**Instale as dependências necessárias**

**Execute os scripts na ordem para simular o pipeline de ETL**:

scripts python/camada_bronze.py scripts python/camada_prata.py scripts python/camada_ouro.py
