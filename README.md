# Projet 5 : Produisez une étude de marché
-------------------

Projet réalisé dans le cadre de mes études de _data analyst_.

Mise en situation
-------------------

Dans ce projet, nous avons intégré une entreprise agroalimentaire, elle se spécialise dans le poulet et ces produits. Elle souhaite maintenant se développer à l'étranger, mais son champ de possibilités est large, aucun pays n'est pour le moment choisi et ils sont tous envisageables.

Notre mission est de produire une étude qui cible certains pays, dans le but d'approfondir par la suite l'étude de marché.

Processus
------------

Dans un premier temps, j'ai commencé par nettoyer et contrôler les données dans le fichier `P5_Nettoyage.ipynd` qui nous renvoie un fichier *set_nourritureTotale.csv* prêt pour analyse.

Ensuite, j'ai réalisé une analyse globale des données, dans `P5_Analyse.ipynd`, j'ai dans un premier temps fait une étude généraliser. J'ai par la suite créé des groupes de pays pour une meilleure sélection, j'ai testé que les groupes que j'ai créés sont bien distincts.

Finalement, j'ai sélectionné quelque pays et justifier ce choix.
 
Données utilisées et sources
-------------------

Dans ce projet nous allons utiliser, differentes données issus de la  [Food and Agriculture Organization of the United Nations (FAO)](https://fr.wikipedia.org/wiki/Organisation_des_Nations_unies_pour_l%27alimentation_et_l%27agriculture),

* `set_pib.csv` -- PIB par pays et par années
* `set_pop.csv` -- Population par pays et par années
* `set_nourritureViande.csv` -- Diverses informations sur la quantité de nourriture par pays et par années, spécifiquement pour la viande.
* `set_nourritureTotal.csv` -- Diverses informations sur la quantité de nourriture par pays et par années, pour tout les aliments d'un pays.



Le fichier P5_Nettoyage.ipynb prend tous ces fichiers et les combine en un unique

* `set_etudeFinal.csv` -- Regroupe différentes informations pour chaque pays.


Projet réalisé en python en utilisant Jupyter, ainsi que les librairies suivantes :

* `matplotlib`
* `pandas`
* `datetime`
* `seaborn`
* `sklearn`
* `scipy`
* `numpy`
* `re`

Plus quelques fonctions personnel dans le fichier **fonction.py*

