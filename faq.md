<!-- .slide: class="slide" -->
# FAQ





<!-- .slide: class="slide" -->
# Analyse factorielle :  quelles variables acives retenir ?

- Vu en cours/TD : CTR>CTR moyenne, n premières les plus contributives, ...
- Se baser sur ces critères (et annoncer comment vous avez choisi) pour filtrer mais rester souple. On peut par exemple conserver une variable avec une CTR plus faible si elle est juste en dessous de la moyenne et que l'on conserve un variable juste au dessus.





<!-- .slide: class="slide" -->
# Analyse factorielle :  quelles variables supplémentaires retenir ?

- En général on se base sur la qualité de représentation
- Mais attention en ACM, elle est mécaniquement très faible
- Il faut *impérativement* utiliser la valeur test (VT, p-value) et conserver par exemple les VT, |VT|>2





<!-- .slide: class="slide" -->
# Les données manquantes ?

- Dans tous les cas une première analyse sans aucun traitement : on peut à ce moment détecter des comportements de non réponse (par exemple les non réponds ont l'air d'être associé à un revenu élevé)
- Lorsque la non réponse est une modalité rare (*et seulement si*), elle va perturber l'analyse, il faut alors regrouper la non réponse avec les autres modalités :
   - en utilisant la première analyse et l'affecter "au plus proche voisin"
   - en utilisant la ventilation aléatoire (level.ventil de FactomineR) : le comportement est parfois surprenant, on peut le faire à la main de façon plus sûre et le fixer pour les analyses suivantes.
   - en utilisant les fonctions d'imputation de FactomineR : MissMDA
   - (remarque : il existe une méthode, COREM, permettant de mettre en supplémentaire des modalités. Le TDC est alors à marge non constante)

- Attention, on ne peut pas mettre en supplémentaire les individus avec de la non réponse ! (zero frequencies)
- On peut aussi éliminer toute observation avec au moins une donnée manquante, mais c'est un peu dommage...






<!-- .slide: class="slide" -->
# Les modalités rares ?

- Dans tous les cas une première analyse sans aucun traitement : on peut à ce moment remarque que la modalité rare X se comporte comme la modalité Y
- On effectue alors un regroupement :
   - par le sens : deux modalités nominales proches (niveau d'études école ou collège) ou deux modalités ordinales successives (3 enfants et 4 enfants ou plus devient 3 enfants ou plus)
   - en utilisant la première analyse et l'affecter "au plus proche voisin"
   - en utilisant la ventilation aléatoire (level.ventil de FactomineR) : le comportement est parfois surprenant, on peut le faire à la main de façon plus sûre et le fixer pour les analyses suivantes.
   - (remarque : il existe une méthode, COREM, permettant de mettre en supplémentaire des modalités. Le TDC est alors à marge non constante)

- Attention, on ne peut pas mettre en supplémentaire les individus avec la modalité rare ! (zero frequencies)






<!-- .slide: class="slide" -->
# Le eta2 dans les listings de classification

- Pour l'analyse de variables *quantitatives* sur les classes, il permet de dire si la variable permet de bien décrire la partition (équivalent du chi2 pour une variable qualitative). C'est la statistique du test de fisher, elle vaut (Vinter/n-k)/(Vintra/k-1) et suit une loi de fisher (k-1,n-k) avec n le nombre d'individu, k le nombre de classes.
- Rappel : vos variables sont essentiellement des qualitatives ordinales et je vous conseille de les laisser ainsi, vous pouvez cependant les interpréter comme des quanti.






<!-- .slide: class="slide" -->
# Rappel démarche d'une classification
1) Statistiques descriptives (nbr obs, type de données, nbr variables...)
2) Choix des éléments actifs (obs et vbles)
3) Choix de la métrique et des critères d'agrégation (si CAH)
4) Choix du nombre de groupes et de la méthode de clustering sélectionnée (si plr méthodes utilisées)
5) Interprétation des classes pour la méthode sélectionnée à partir des paramètres (centres des classes...)
6) Si les données sont continues, visualisation par AFD. Si les données sont quali, ACM sur les données actives et on indique l'appartenance aux classes des observations par une couleur ou symbole.








<!-- .slide: class="slide" -->
# Mais pourquoi fait-on une classification ? Ca ne sert à rien les individus sont anonymes.
- ...
- Profils-types
- Adapté à la vulgarisation







<!-- .slide: class="slide" -->
# La classification
- il ne s'agit pas juste de trouver de bonnes classes, il faut aussi (et surtout) bien analyser les classes !

