# projet-du-semestre
On va développer une application cloud qui permet de convertir des documents  en proposant au moins deux types de conversions pour le client.
Les applications cloud sont mieux déployées en tant que collection de services cloud ou d’Interface de Programmation Applicative (API) c'est pour cette raison qu'on a préféré de concevoir notre application sous la forme d'un ensemble de services-web. C’est une architecture basée essentiellement sur le service.Lorsque on développe une architecture d’application pour le cloud, on traite des systèmes distribués complexes qui peuvent tirer parti des applications faiblement couplées basées sur de nombreux services pouvant également être dissociés des données . On peut séparer physiquement les services d’application, les exécuter sur les instances de machine appropriées, et les gestionnaires de service/API ainsi que la technologie de gouvernance qui fournissent des répertoires de services pouvant nous être utiles dans le suivi des nombreux services qui composent notre application.
Des avantages supplémentaires peuvent inclure la réutilisation du service des autres applications ou des services avec une granularité plus large. On peut diviser les applications en centaines de services sous-jacents qui ont de la valeur lorsqu’ils sont utilisés par d’autres applications. De cette façon, nous ne réinventons pas la roue chaque fois que nous voulons créer une application. 
Pour la gestion de plusieurs demandes de clients en même temps, on a décidé d'utiliser des threads. 
Un thread est une unité d'exécution faisant partie d'un programme, cette unité fonctionne de façon autonome et parallèlement a d'autre threads. Le principal avantage est de pouvoir répartir différent traitement d'un même programme en plusieurs unités distinctes poir permettre leur exécutions simultanées ce qui garantie la synchronisation de plusieurs demandes de clients de notre application
Pour implémenter notre travail, on va utiliser le langage java qui permet de mieux structurer notre application et une plate forme javaEE
