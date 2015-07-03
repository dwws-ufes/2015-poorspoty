PoorSpoty
==============

O PoorSpoty é um sistema de recomendação de bandas musicais. Nele você realiza um rápido cadastro e posteriormente, baseado no seus dados
fornecidos, o sistema faz a recomendação de novas bandas além de fornecer dados de suas bandas prediletas.

## Como implantar
O PoorSpoty é desenvolvido na plataforma Java. Para mais informações de instalações da mesma visite a primeira parte do tutorial do 
([Nemo Utils](https://github.com/nemo-ufes/nemo-utils/wiki/Tutorial%3A-a-Java-EE-Web-Profile-application-with-nemo-utils%2C-part-1)).

O projeto tem as seguintes dependencias:
* Primefaces 5.1 ([Download](http://www.primefaces.org/))
* Apache Jena 2.1 ([Download](https://jena.apache.org/))
Se você utiliza o Maven 2, as dependencias serão baixadas automaticamente.

O banco de dados utilziado se encontra no servidor do Nemo. Para utilizá-lo:
* Hostname: dev.nemo.inf.ufes.br
* Port: 3306
* Username: dwws2015
* Password: dwws2015
* Default Schema: dwws2015_poorspoty

## Como utilizar
Para utilizar é simples. Basta se cadastrar, efeturar login e usufruir das novas bandas sugeridas.

## Fonte de dados
O PoorSpoty utiliza dados da dbpedia. Logo, é essencial para o seu funcionamento, que o dbpedia esteja online.

## Autores
* André Pacheco
* Isaque Rocha


