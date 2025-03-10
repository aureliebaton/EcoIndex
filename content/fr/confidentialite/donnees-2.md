+++
title= "Utilisation des données des URL renseignées"
date= 2020-12-03T12:22:02+01:00
draft= false
widget= "text"
headless= true  # This file represents a page section.
active= true
weight= 30
+++

Nous collectons des informations au sujet des URL renseignées dans notre barre de test et les stockons dans notre base
de données. Les informations collectées sont les suivantes :

- URL, poids de la page testée, nombre de requêtes de la page testée, nombre d’éléments du DOM de la page testée.
- Ces informations sont stockées sans limite de temps afin de permettre des comparatifs dans le temps en cas de requête
  postérieure sur la même URL, ce qui nous semble être une donnée pertinente d’analyse et de suivi.
- Ces informations sont hébergées auprès du prestataire décrit dans les [Mentions légales](/mentions-legales/).
- Les informations collectées servent uniquement au calcul de la performance environnementale de la page testée et à la
  constitution d’une base de données sur l’état actuel des URL testées par les utilisateurs. Question LB: A quoi sert
  cette base de données ainsi constituée: uniquement rappeler les scores précédents en cas de nouvelle requête sur une
  même URL? ou potentiellement des analyses au sein de la base de données -- synthèses, extractions, analytics, etc. sur
  l’ensemble de la base consolidée? Dans ce dernier cas, il faut expliquer par qui, quel objet/but/finalité, etc.
