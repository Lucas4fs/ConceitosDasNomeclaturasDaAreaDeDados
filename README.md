# Conceitos das Nomenclaturas da Área de Dados

## Dataset vs. DataFrame

Dataset é o conceito geral do conjunto de dados, o arquivo em si com as informações (como um arquivo CSV ou JSON).

DataFrame é a representação desse Dataset dentro de um código (em linguagens como Python e R), facilitando a manipulação e a análise dos dados.

## Data Warehouse vs. Data Lake

Data Warehouse é como um armário de arquivos altamente organizado: ele armazena dados limpos, estruturados e prontos para relatórios. É ideal para análises rápidas e consistentes.

Data Lake é como um grande depósito de arquivos: ele guarda dados de todos os tipos (estruturados, semi-estruturados, não estruturados) da maneira que chegam, sem precisar de uma organização prévia. É perfeito para exploração e análises mais complexas.

## Data Lakehouse vs. Delta Lake

Data Lakehouse é a arquitetura completa. Ele combina a flexibilidade de um Data Lake com a estrutura e o desempenho de um Data Warehouse.

Delta Lake é a tecnologia que torna o Data Lakehouse possível. É a camada de software que você aplica a um Data Lake para adicionar confiabilidade e recursos de estrutura, fazendo com que ele se comporte como um Data Lakehouse.

## Resumo

Dataset: É o arquivo de dados.

DataFrame: É como você manipula o arquivo no código.

Data Warehouse: Dados limpos e prontos para análise.

Data Lake: Dados brutos para exploração.

Data Lakehouse: A junção dos dois.

Delta Lake: A tecnologia que cria o Data Lakehouse.
