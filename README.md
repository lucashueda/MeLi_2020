# Mercado Libre Data Challenge 2020

Solução do MeLi Challenge 2020 (https://ml-challenge.mercadolibre.com/)

## Overview

Basicamente o desafio é prever a compra do cliente dado um histórico de atividades de 7 dias do cliente. 

## Estrutura do repositório

**Pastas**
- data/ -> Pasta onde devera estar os dados
- utils/ -> Pasta onde estão os scripts de utilidade (data parsers, métricas, preprocessamento de dados)
- train/ -> Pasta onde estão scripts de treinamento (dataloaders, kfolds, train pipeline)
- experiments/ -> Pasta onde serão armazenados os logs de experimentos (dentro haverá uma pasta para cada experimentos realizado)
- api/ -> Pasta onde estará os scripts da API em flask para deploy de modelo
- debug/ -> Pasta com scripts para testagem da pipeline

**Arquivos**
- train.py -> Script de treinamento
- evaluate.py -> Scripts de avaliação de modelo
- api_predict.py -> Aplicação da API para uso
- dockerfile -> Arquivo para gerar a imagem docker
- requeriments.txt -> Versionamento dos pacotes utilizados

## Estrutura da solução

- Data:
  - 


## Autor

- Lucas Hideki Ueda (lucashueda@gmail.com)

## Licença

Atualmente GNU v3

## Observação quanto a competição

Em momento de competição o repositório estara sempre defasado em um commit.
