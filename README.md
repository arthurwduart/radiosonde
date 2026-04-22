# Radiossondagens no Brasil

Este repositório reúne dados e arquivos de apoio para visualizar estações de radiossondagem no Brasil a partir da lista de estações do conjunto **IGRA v2**. O foco do projeto é identificar as estações brasileiras, separar as estações operacionais e apresentar sua distribuição em um mapa interativo.

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

Os dados de estações utilizados aqui derivam da lista do **IGRA v2 (Integrated Global Radiosonde Archive)** (https://www.ncei.noaa.gov/data/integrated-global-radiosonde-archive/doc/igra2-station-list.txt), amplamente utilizada em estudos atmosféricos e climatológicos.
