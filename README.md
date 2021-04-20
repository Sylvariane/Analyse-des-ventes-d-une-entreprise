# Analysez les ventes de votre entreprise <br>
(Projet OpenClassrooms)

*Notebooks du projet disponible ici :* [Notebook nettoyage](https://github.com/Sylvariane/Analyse-des-ventes-d-une-entreprise/blob/master/P04_01_scriptdonn%C3%A9es.ipynb) & [Notebook analyse](https://github.com/Sylvariane/Analyse-des-ventes-d-une-entreprise/blob/master/P04_02_scriptanalyse.ipynb)


## Résultats de l'analyse

La partie nettoyage a permis d'isoler les sessions de tests du site qui auraient parasité l'analyse des ventes. Une partie des données est manquante pour le mois d'octobre (disparition des ventes d'une catégorie), il faudra donc prendre en compte cette disparition lors de l'analyse des données de ventes. <br>

Dans un premier temps, l'analyse a porté sur les clients et leurs profils.
![2 - Répartition des âges](https://user-images.githubusercontent.com/64648386/115453149-94db0680-a21f-11eb-95e7-8d20a4e2d292.jpg)
L'échantillon comporte presque autant d'hommes que de femmes. On remarque en revanche qu'il existe un plafond pour l'âge minimum qui peut s'expliquer par le fait de devoir avoir au moins 18 ans pour faire des achats sur Internet. Les clients de plus de 80 ans sont, quant à eux, les moins nombreux. 

Ensuite, il a fallu se pencher sur l'un des indicateurs importants : le chiffre d'affaires.
![6 - CA mensuel](https://user-images.githubusercontent.com/64648386/115453391-de2b5600-a21f-11eb-9660-d977bd62e9be.jpg)<br>
Ici, le chiffre d'affaire montre une anomalie sur le mois d'octobre. Cette anomalie s'explique par la perte des données de vente de la catégorie 1 sur certaines semaines du mois d'octobre. 

Enfin, on a étudié les comportements clients.
![17 - categ_age_anova](https://user-images.githubusercontent.com/64648386/115453605-1df23d80-a220-11eb-98b7-8b1a717568e8.jpg)
Par exemple, l'âge moyen des client avait un impact sur la catégorie des achats. 


## Syllabus du projet

Ce projet a été réalisé dans le cadre de ma formation de Data Analyst. Le but de ce projet était de mettre en lumière plusieurs compétences : 
- La connaissance des tests statistiques fondamentaux (ANOVA, Chi-2 de conformité, coefficient de corrélation, régression linéaire)
- Le nettoyage d'un jeu de données
- La description d'un jeu de données à l'aide de statistique descriptive (indices de tendances centrales, indices de dispersion, analyse de concentration, analyse de la symétrie d'une distribution).
Les documents à rendre pour ce projet prennent la forme de deux Notebook, un fichier ReadMe et une présentation sous forme de slides : 
- Un Notebook contenant le code du nettoyage des données
- Un Notebook contenant le code avec les différences analyses statistiques
- Un fichier ReadMe expliquant le rôle de chacun des Notebook
- Une présentation au format Powerpoint présentant l'analyse du point de vue du Data Analyst.

Ce projet a été évalué le 14 août 2020 et a été validé par un évaluateur. 
