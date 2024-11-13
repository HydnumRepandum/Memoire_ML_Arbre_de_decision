# Mémoire_ML

Vous retrouvez ici l'ensemble du code R qui m'a permis l'élaboration de mon mémoire dans le cadre de la validation de mon master en Politique et management publics dispensé par l'IDHEAP

## Structure du dépot:

Dans la branche principale, vous trouverez le code R (au format Markdown) pour chaque domaine de politique publique analysé, ainsi qu'une analyse commune intégrant tous les domaines lorsque ceux-ci sont fusionnés.

__sante.Rmd__: Pour le domaine de la santé  
__banque.Rmd__: Pour le domaine bancaire  
__security.Rmd__: Pour le domaine sécuritaire  
__social.Rmd__: Pour le domaine de l'aide sociale  
__tous_secteurs.Rmd__: Lorsque que tous les domaine précédemment sont fusionnés ensemble  

## Résumé du mémoire:

Ce mémoire présente un cas d’application du modèle d’apprentissage automatique des arbres de décisions dans les champs des sciences sociales. Il présente de manière technique et précise le fonctionnement de cette méthode et les résultats obtenus.

En mobilisant des arbres de classifications (arbres élagués, et forêt aléatoire) sur une base de données issue d’un sondage en ligne, nous avons essayé de prédire le profil des citoyens suisses qui seraient potentiellement susceptibles de partager leurs données personnelles avec le gouvernement. Parvenir à la réalisation de ces profils permettrait, in fine, d’améliorer le développement et la mise en œuvre de grands nombres de politiques publiques.

Nous comparons les résultats obtenus par cette méthode (arbres élagués, et forêt aléatoire) à ceux des régressions statistiques habituelles (régression logistique ordinale, régression linéaire).

Notre recherche démontre les avantages et les inconvénients de notre méthode. Ainsi nous avons montré que les arbres ont permis de révéler des phénomènes d’interactions complexes intéressant des variables indépendantes. Ces résultats auraient été très difficilement observables par les régressions statistiques habituelles.

La comparaison de nos modèles à ceux habituels, retrouve peu de différence entre eux. Néanmoins, la performance des différents modèles reste mauvaise en absolu, nous amenant à dire que, dans notre cas d’étude, nos analyses amènent à peu de réelles implications pratiques.

Nous concluons notre travail en relevant que loin d’être une méthode miracle, les arbres de décisions et plus précisément de classification, se montrent avant tout comme un outil complémentaire dans la palette qui est offerte aux chercheurs. Elle peut apporter une approche intéressante dans le champ d’étude des sciences sociales, notamment dans une perspective exploratoire.
