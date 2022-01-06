# budg_eat
Voici le projet Python Ensae 2021 réalisés par Maxime Urban et Théo Vanneufville. 
Nous avons souhaités réaliser une interface permettant à l'utilisateur d'obtenir les données macro-nutritionnelles d'un aliment. 

Notre démarche s'est faite en quatre temps : 

1) Création de deux databases grâce au scrapping : 
- **Database Yazio **: une database contenant plus de 1000 aliments 
-** Database Conversion** : une database contenant des aliments et leur poids, utile pour éviter à l'utilisateur de devoir trouver le poids de ses aliments lui-même (par exemple le poids d'une tomate ou d'un oeuf). 
- Outils : BeautifulSoup, Pandas

2) Utilisation de **NLP** afin de rendre nos deux databases exploitables par l'utilisateur 
- Créer la correspondance entre ce que l'utilisateur va entrer et ce qui se trouve dans notre base
- Par exemple : l'utilisateur entre "Tomates cerises" mais notre base contient "tomate-cerise"
- Outil : Tokenisation

3) Codage d'une **fonction finale** qui renvoie les données macro-nutritionnelles d'un aliment

4) Réalisation d'une **interface graphique** rendant cette fonction accessible pour l'utilisateur
- Outil : PySide2

