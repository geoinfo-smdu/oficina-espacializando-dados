# Oficina de Espacialização de dados com Python e Geopandas

É possível levantar diversos argumentos sobre a necessidade de espacializar os dados, no entanto, se echegou até aqui, vamos considerar que já esteja ciente da importância disso. No entanto, muitos conjuntos de dados que trabalhamos no cotidiano tem relações geográficas e acabamos lidando com eles de forma tabular, como se fossem planilhas, sem utilizar o potencial das análises espaciais. 

## Objetivo

Essa oficina pretende compartilhar experiências de espacialização de conjuntos de dados da Prefeitura de São Paulo que foram espacializados por GeoInfo. Os resultados serão publicados na pasta `resultados` aqui deste repositório.

## Materiais e Métodos

Vamos utilizar basicamente Python e GeoPandas para sugerir caminhos e estratégias para a espacialização da informação e assim abrir possilibades, discutir as vantagens, implicações e as limitações desses recursos.

Pretendemos começar a partir da última oficina, relembrando um pouco do Pandas e utilizando o conjunto de dados do IPTU, mesclando a camada de lotes aos dados do IPTU. E seguir demonstrando a estratégia utilizada para o Georeferenciamento da base de dados de atendimentos do SP156 e por último vamos transformar juntos as variáveis de indicadores do ObservaSampa em um conjunto de dados espaciais.

## Resultados

Além do compartilhamento do processo para espacialização dos dados do IPTU, os resultados podem ser obtidos na pasta `resultados` aqui deste repositório. São 96 arquivos GeoPackage, contendo, para cada distrito, a geometria dos lotes e informações agregadas do IPTU de 2020.

Caso esta seja a primeira vez que utiliza o GitHub, vc pode fazer o download de todo esse contúdo e acessar a pasta de resultados, basta clicar em um botão verde, escrito 'Code' no canto superior esquerdo deste quadro, e utilizar a opção 'Download Zip ...'

## Como colaborar

Existem diversas maneiras de colcaborar com esse repositório, é possível abrir um chamado em Issues, contanto algo pra gente, sugerir modificações e novas funcionalidades ou mesmo se for alguém mais 'Old School (Old is cool!)' manda um email pra gente (geosampa@prefeitura.sp.gov.br) contando os seus achados, adoramos saber.

## Próximos passos 

Para a próxima oficina temos algumas possibilidades:

* Série histórica do IPTU
* Espacializando dados tabulados, exemplo SP156
* HTML básico
* HTML/JavaScript para visualização de dados (ObservaSampa)
* GitHub
* Introdução ao GeoProcessamento com Python e GeoPandas
* GeoPandas avançado, polígono de vias
* Automatização de tarefas
* LiDAR 3D e Python
* Consumindo Serviços Geo(Sampa) com Python
* Geocodificação de endereços com Pelias, dados abertos e Software Livre
