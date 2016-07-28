#Validação
Re-interpretação de dados de bancos de dados biológicos anotados com classes ontologias 

##Conteúdo:

###Dados
Planilha com dados utilizados para exemplificação

###Ontologias Amplificadas
Registro de BD amplificado utilizado para avaliação de escalabilidade.

###Script
Script em Clojure que lê um código OWL de exemplo em que as anotações incluídas nos BDs são substituídas. Esse procedimento
é realizado para permitir a criação do arquivo de interpretação de um conjunto de dados anotados.
Classes utilizadas como anotações e incluídas em campos de um único registro de BD são substituídas em posições correspondentes no código OWL. A substituição é realizada mediante o nome atribuído ao campo.
Para que o script seja processado, é importante ter instalado o [Leiningen](https://github.com/technomancy/leiningen) e o [Java JDK](http://www.oracle.com/technetwork/pt/java/javase/downloads/index.html) 8 ou posterior.
