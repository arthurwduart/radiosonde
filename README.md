# Radiossondagens no Brasil

Este repositório reúne dados e arquivos de apoio para visualizar estações de radiossondagem no Brasil a partir da lista de estações do conjunto **IGRA v2**. O foco do projeto é identificar as estações brasileiras, separar as estações operacionais e apresentar sua distribuição em um mapa interativo.

## O que há neste projeto

- `igra2-station-list.txt`: lista original de estações do IGRA.
- `filter_brazil_radiosonde.py`: script em Python para ler a lista do IGRA e filtrar as estações brasileiras.
- `estacoes_brasil_radiossonda.csv`: tabela com todas as estações brasileiras encontradas na base.
- `estacoes_operacionais.csv`: subconjunto com as estações brasileiras operacionais.
- `index.html`: mapa interativo com a localização das estações operacionais no Brasil.
- `station_radiosonde.ipynb`: notebook usado para análise e exploração dos dados.

## Sobre radiossondagens

As radiossondagens são medições atmosféricas realizadas com balões meteorológicos equipados com sensores. Esses sensores registram variáveis como:

- temperatura
- umidade
- pressão atmosférica
- direção e velocidade do vento

Essas observações são importantes para previsão do tempo, monitoramento climático, estudos atmosféricos e validação de modelos numéricos.

## Resumo dos dados

Com base nos arquivos deste repositório:

- `estacoes_brasil_radiossonda.csv` contém **62 estações brasileiras** identificadas na base.
- `estacoes_operacionais.csv` contém **28 estações operacionais**.
- o mapa em `index.html` mostra a distribuição espacial dessas estações operacionais no território brasileiro.

As colunas principais dos arquivos CSV são:

- `station_id`: identificador da estação
- `latitude` e `longitude`: coordenadas geográficas
- `elevation_m`: altitude da estação em metros
- `station_name`: nome da estação
- `start_year` e `end_year`: período de operação registrado
- `nobs`: número de observações disponíveis

## Mapa das estações de radiossondagem no Brasil

O arquivo [index.html](https://arthurwduart.github.io/radiosonde/) contém um mapa interativo gerado com Leaflet/Folium. Nele, cada marcador representa uma estação operacional de radiossondagem no Brasil.

No mapa é possível visualizar:

- a localização geográfica das estações
- o nome de cada estação
- o identificador da estação
- altitude
- período de operação
- quantidade de observações

Algumas estações presentes no mapa:

- Belém
- Boa Vista
- Brasília
- Campo Grande
- Curitiba
- Manaus
- Natal
- Porto Velho
- Rio Branco
- Vitória

## Como visualizar o mapa

Abra o arquivo [index.html](https://arthurwduart.github.io/radiosonde/) diretamente no navegador.

## Fonte dos dados

Os dados de estações utilizados aqui derivam da lista do **IGRA v2 (Integrated Global Radiosonde Archive)**, amplamente utilizada em estudos atmosféricos e climatológicos.
