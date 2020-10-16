<!-- .slide: class="slide" -->
## Projet de statistique exploratoire

Clément Dufaure

formation.dufau.re/projet-ensai/




<!-- .slide: class="slide" -->
## Rappels fonctionnement

- Des données communes (Observatoire des territoires)
- Un sujet différent par groupe
- Une problématique à définir





<!-- .slide: class="slide" -->
## Rappels fonctionnement

- Au premier semestre : Réponse avec statistiques uni et bi variées
- Au second semestre : Réponse avec statistiques multivariées (en complément)






<!-- .slide: class="slide" -->
# Les grandes étapes






<!-- .slide: class="slide" -->
## Bibliographie 

- Principe : se renseigner sur le sujet
- En rester à des publications statistiques, notemment des analyses sociologiques (un bon article de presse va s'appuyer sur une publication)
- Définition approfondie de la problématique
- Ce qui se sait déjà => le rapport pourra confirmer ou infirmer
- Des éléments sur ce que ne couvre pas vos données => ouverture
- Toujours citer la provenance dans une bibliographie  !






<!-- .slide: class="slide" -->
## Problématique
- Définir une problématique, ce n'est pas "juste" trouver une jolie question
- C'est toute la démarche de réflexions autour essentiellement de la bibliographie pour affiner les pistes de recherche
- Va structurer le choix de variable, les méthodes chosies, éventuellement le plan
- Possibilité de sous problématiques (attention à ne pas trop élargir)
- Attention : vous ne pourrez pas détecter de *causalité*. C'est un projet de statistique *descriptives*, on peut "juste" trouver les variables qui fonctionnent ensemble.





<!-- .slide: class="slide" -->
## Choix des variables
- Sélectionner dès maintenant toute variable pouvant avoir un rapport plus ou moins éloignée avec votre sujet
- Pour le premier semestre, réeffectuer une sélection plus fine ne conservant que des variables en lien direct : les méthodes uni/bivariées ne vous permettrons que de gérer un nombre limité de variables
- Au second semestre vous aurez vu des méthodes multivariées qui sont conçues pour gérer beaucoup de variables





<!-- .slide: class="slide" -->
## Choix des variables
- Une connaissance du stock de variables peut aider à orienter correctement votre problématique (éviter de se focaliser sur un élément dont on a aucune mesure)
- La définition de la problématique (et des "sous problématiques") guide le choix final des variables
- La problématique pourra être élargie si nécessaire au second semestre






<!-- .slide: class="slide" -->
## Choix des variables
- Attention au format du site
- Récupération "par variable"
- Ne pas négliger le temps de construction de votre table de données







<!-- .slide: class="slide" -->
## Choix de la (des) population, du (des millésimes)
- Quel est votre individu statistique ? Votre population ?
- Commune ? 
- Faire bien attention à associer les variables issues des mêmes tables (Par exemple systématiquement Commune 2020)







<!-- .slide: class="slide" -->
## L'analyse uni/bi variée

- Des statistiques univariées pour connaitre la composition de la population
- Sélectionner en fonction de votre bibliographie par exemple des croisements a priori pertinents pour l'analyse
- Rester concis sur les résultats
   - Ne pas oublier les indicateurs de base (moyenne, variance, médiane, mode, etc.) sur vos variables d'intêret
   - Choix d'un tableau ou d'un graphique (avec son titre, champ, source, note de lecture,... )
   - Préciser ce qui est à remarquer dans le résultats staistique en faisant attention à ne pas surinterpréter
   - On ne vous reprochera pas de ne pas avoir de réultats sensationnels s'il n'y en a pas à trouver, on vous reprochera des résultats issus de surinterprétation







<!-- .slide: class="slide" -->
## L'analyse uni/bi variée : outil cartographique

- Outil de cartographie intégré au site
   - Outils de visualisation des données sous forme de carte
   - Possibilité d'importer des variables calculées par vos soins
   - Pertinent pour un sujet sur les territoires






<!-- .slide: class="slide" -->
## L'analyse uni/bi variée : outil cartographique
   - Attention à ne pas le surutiliser : une carte proposée dans le rapport DOIT être lisible et DOIT porter une information
   - Rappel : Ce projet est là pour vous évaluer sur les statistiques descriptives
   - Exemple : 2 variables liées peuvent être détectées en observant que les cartes des deux variables "se ressemblent", mais il utiliser des outils plus précis pour le montrer (coefficient de correlation, tableau de contingence, ...)






<!-- .slide: class="slide" -->
# Questions récurrentes






<!-- .slide: class="slide" -->
## Questions sur les indicateurs du site

https://www.observatoire-des-territoires.gouv.fr/donnees_ouvertes


- Des descriptions sur chaque indicateur
- En particulier *la source*

**Je ne suis pas un expert de ces données, je n'aurai aucune plus-value par rapport à ces informations !**





<!-- .slide: class="slide" -->
## Public

Le rapport s'adresse à un statisticien et non au grand public

- Ne pas hésiter à utiliser les méthodes vues en cours
- On peut réintroduire les méthodes pour justifier l'utilisation par exemple mais il ne faut pas refaire le cours dans le rapport
- Un bon tableau vaut mieux qu'un graphique illisible...






<!-- .slide: class="slide" -->
## Public

Le rapport s'adresse à un statisticien qui NE connait PAS le domaine d'étude

- Présenter les données, les variables choisies avec un nom *en clair* (ne pas utiliser d'éventuels nommages)
- Il faut détailler un minimum le sens des variables quand ce n'est pas évident






<!-- .slide: class="slide" -->
## Les variables créées

- Il sera parfois plus simple de travailler sur une variable recalculée, avec des regroupements de modalité, des transformations en classes, ou sur des variables agrégées, etc
- Il faut TOUJOURS préciser ce qui a été fait. Même si le code est fourni, la simple lecture du rapport DOIT suffire à comprendre tout ce qui a été fait depuis les données brutes jusqu'à votre analyse
- Attention à être cohérent dans le passage d'une variable quanti en classes
- Il faut TOUJOURS justifier le pourquoi de ce recalcul







<!-- .slide: class="slide" -->
## Le code / les sorties brutes en annexes

*annexe = le rapport doit être lisible sans ses annexes*

*annexe = ce qui ne figurerait pas forcément dans le rapport s'il était vraiment publié*

- Il vous est demandé de fournir le code SAS ou R utilisé pour obtenir vos résultats
- Il faut mettre en annexe les sorties brute des logiciels qui vous ont servi mais ne peuvent figurer telles quelles dans le rapport (et uniquement ce qui a servi !)
   - Pour le premier semestre, ce ne sera pas nécessaire normalement car ce sont quasiment les sorties brutes qui seront utilisées (NE PAS mettre le tableau correspondant aux graphiques par exemple)
   - Pour le second semestre, ce sera nécessaire






<!-- .slide: class="slide" -->
## Remarques diverses
- Mettre le titre du sujet sur tous les livrables (et numero de groupe et noms)
- La rédaction n'est pas le premier critère de notation mais un minimum est attendu (orthographe, titre explicite de préférence informatif par exemple)
- Relisez vous
> Le clustering est une méthode de classification, qui consiste à construire ou constituer des classes






<!-- .slide: class="slide" -->
## Remarques diverses
- Détecter des sur/sous représentativités NE VEUT PAS DIRE effets de structure
- Attention à l'utilisation de mots réservés à l'interprétation statistique (sur/sous représenté à utiliser avec leur sens exact dans un rapport statistique)






<!-- .slide: class="slide" -->
## Remarques diverses
- Un élément non lisible est inutile (cette remarque est valable pour les annexes !)
- Lorsque des interprétation font appels à des choix arbitraire (choix de seuil, ...) précisez les explicitement ou restez en à des comparaisons
- Souvent utiliser des effectifs n'est pas une bonne idée, il vaut mieux des fréquences







<!-- .slide: class="slide" -->
## Second semestre
- Maintien de la mise en problématique, données, démarche, choix de variables, etc
- Les stats univariées restent nécessaires pour du cadrage (notemment recherche de modalité rares)
- Idée générale : remplacer la partie bivariée un peu lourde par du multivarié plus synthétique
- Utiliser une méthode de classification dans le même esprit (le cours arrive bientôt)







<!-- .slide: class="slide" -->
## Second semestre
Analyse factorielle 
- Pensez au déroulé de la méthode : choix de la méthode, paramétrage, actives/supplémentaires
- Représentations graphiques en analse factorielle : dessin de l'axe et de se qui s'oppose suffit
- Les représentations des plans factoriels s'adaptent mal à un résultat d'étude généralement (illisibles et parfois trompeurs)






<!-- .slide: class="slide" -->
## Second semestre
Classification
- Choix de la méthode, paramétrage,... Rester cohérent avec les choix de l'analyse factoriel ou justifier
- Si CAH, utiliser les résultats de l'analyse factorielle
- Ce qui est surtout attendu : analyse de la partition retenue
- La classification crée une nouvelle variable qualitative (appartenance à la classe C)
- Les résultats se basent essentiellement sur des statistiques bivariée (tableaux et graphiques de la statistique bivariée peuvent alors être utilisés en complément)
