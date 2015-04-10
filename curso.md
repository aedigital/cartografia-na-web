# Curso: Cartografia na Web


### Formatos de dados

* [Shapefile](http://en.wikipedia.org/wiki/Shapefile)
* [GeoJSON](http://en.wikipedia.org/wiki/GeoJSON)
* [CSV](http://en.wikipedia.org/wiki/Comma-separated_values)

### Ferramentas

* [QGIS]
* [CartoDB]
* [TileMill]
* [Mapbox Studio]
* [JEO]
* [JEO Community]


### Projetos de referência

* [Infoamazonia]
* [Política do Desmatamento]
* [Viságuas]
* [Ekuatorial]
* [Oxpeckers]
* [Landquest]

### Exercícios

### Mapa de pontos no CartoDB

Um mapa de pontos no CartoDB, representando as cidades onde houve libertação de trabalhadores escravos no Brasil.


Subindo dados no [CartoDB]:

* [Crie uma conta](http://http://cartodb.com/signup) no [CartoDB]
* Vá para a vista de tabelas em *"Your datasets"*
* Envie o arquivo de [trabalhadores libertados por cidade]
* Acerte o nome da tabela para algo como *trabalhadores_libertados-2003_2012*
* Clique *Map view* para ver todos os pontos sobre um mapa

Criando um mapa:

* Clique em *"Visualize"* e dê um nome para o mapa, por exemplo: *Trabalhadores libertados entre 2003 e 2012, por município*

### Mapa cloropédico no CartoDB

Um mapa cloropédico de libertação de trabalhadores escravos por estados.

* Vá para a vista de tabelas em *"Your datasets"*
* Envie o arquivo de [trabalhadores libertados por estado], sem habilitar o reconhecimento automático de tipos do CartoDB
* Envie o arquivo de [fronteiras dos estados]
* Faça a junção das tabelas, criando uma terceira
* Configure o estilo do mapa



### Publicando com o JEO

* Comece um novo site no [JEO Community]
* Crie novas camadas com os mapas do CartoDB
* Adicione as camadas base da Mapbox:
  * `infoamazonia.map-xs56h3ri`
  * `infoamazonia.amazonia_cows_noInteract_4-6,infoamazonia.amazonia-cows`

* Em appearence, escolha o mapa inicial e salve
* Crie um mapa para cada camada, e um mapa com as duas camadas
* Crie os posts que aparecerão sobre o mapa


<!-- LINKS  -->

<!-- data  -->
[fronteiras dos estados]: data/brasil-estados-fronteiras.csv
[Trabalhadores libertados por cidade]: data/brasil-cidades-trabalhadores_libertados-2003_2012.csv
[Trabalhadores libertados por estado]: data/brasil-estados-trabalhadores_libertados-2003_2012.csv

<!-- tools  -->
[CartoDB]: http://www.cartodb.com
[QGIS]: http://www.qgis.org
[TileMill]: http://www.mapbox.com/tilemill
[Mapbox Studio]: http://www.mapbox.com/mapbox-studio
[JEO]: https://cardume.github.io/jeo
[JEO Community]: http://jeo.cardume.art.br/community

<!-- projects  -->
[Infoamazonia]: http://www.infoamazonia.org
[Política do Desmatamento]: http://desmatamento.infoamazonia.org
[Viságuas]: http://visaguas.infoamazonia.org
[Ekuatorial]: http://ekuatorial.com
[Oxpeckers]: http://oxpeckers.org
[Landquest]: http://landquest.internewskenya.org/
