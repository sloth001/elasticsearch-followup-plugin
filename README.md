# ElasticSearch FollowUp Plugin 

The plugin tracks CRUD changes made in an ElasticSearch index.

## Installation

Target folder contains compiled binaries ready for use. The first 3 numbers of the version tag refers to the version of ElasticSearch the plugin built for.

* ElasticSearch 6.3.2

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.3.2.1.zip
```

* ElasticSearch 6.3.1

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.3.1.1.zip
```

* ElasticSearch 6.3.0

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.3.0.1.zip
```

* ElasticSearch 6.2.4

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.2.4.1.zip
```

* ElasticSearch 6.2.3

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.2.3.1.zip
```

* ElasticSearch 6.2.2

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.2.2.1.zip
```

* ElasticSearch 6.2.1

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.2.1.1.zip
```

* ElasticSearch 6.2.0

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.2.0.1.zip
```

* ElasticSearch 6.1.4

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.1.4.1.zip
```

* ElasticSearch 6.1.3

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.1.3.1.zip
```

* ElasticSearch 6.1.2

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.1.2.1.zip
```

* ElasticSearch 6.1.1

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.1.1.1.zip
```

* ElasticSearch 6.1.0

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.1.0.1.zip
```

* ElasticSearch 6.0.1

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.0.1.1.zip
```

* ElasticSearch 6.0.0

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-6.0.1.1.zip
```

* ElasticSearch 5.6.10

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.6.10.1.zip
```

* ElasticSearch 5.6.9

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.6.9.1.zip
```

* ElasticSearch 5.6.8

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.6.8.1.zip
```

* ElasticSearch 5.5.3

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.5.3.1.zip
```

* ElasticSearch 5.4.3

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.4.3.1.zip
```

* ElasticSearch 5.3.3

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.3.3.1.zip
```

* ElasticSearch 5.3.0

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.3.0.1.zip
```

* ElasticSearch 5.2.2

``` bash
elasticsearch-plugin install   https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-5.2.2.1.zip
```

* ElasticSearch 2.4.6

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.4.6.1.zip
```

* ElasticSearch 2.4.5

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.4.5.1.zip
```

* ElasticSearch 2.4.4

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.4.4.1.zip
```

* ElasticSearch 2.4.1

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.4.1.2.zip
```

* ElasticSearch 2.4.0

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.4.0.2.zip
```

* ElasticSearch 2.3.5

``` bash
plugin install https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-2.3.5.1.zip
```

* ElasticSearch 1.7.6

``` bash
plugin -u https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-1.7.6.1.zip -i followup
```

* ElasticSearch 1.4.4

``` bash
plugin -u https://github.com/artcomventure/elasticsearch-followup-plugin/raw/master/target/elasticsearch-followup-plugin-1.4.4.2.zip -i followup
```


Restart ElasticSearch.

## Usage

Track changes in myindex:

```
http://localhost:9200/myindex/_followup?start
```

Get changes:

```
http://localhost:9200/myindex/_followup
```

Stop tracking: 

```
http://localhost:9200/myindex/_followup?stop
```

Clear changes: 

```
http://localhost:9200/myindex/_followup?clear
```

The tracking buffer is only limited by heap size, don't forget to turn it off. :)
