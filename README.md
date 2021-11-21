# IOV
Titre de mémoire : Distribution géographique des données dans l’internet des véhicules.

Solution proposée se présente en 2 : 

1- le clustering: division des véhicules en des groupes, chaque groupe dans un cluster, dans chaque cluster on a un cluster head c’est Le chef de cluster, une ou plusieurs passerelles pour assurer la communication entre les clusters et finalement les membres de cluster. 
Le clustering est réaliser en : 
   1.1- Initialisation des paramètres et calcul des métriques(pages 47/49)pour obtenir la valeur du poids W (page 52)
   1.2- élection du chef de cluster : comparaison des valeurs de poids W pour choisir le chef de cluster (page 54)
   1.3- élection des passerelles : le nœud qui a la plus faible valeur de mobilité M est sélectionné comme nœud passerelle (page 55)
   1.4- Processus de jointure de nœud de cluster (page 56)
   1.5- Phase de maintenance Locale du cluster (page 58) 

2- l’algorithme de routage : l’approche de routage utilisée est une approche de routage glouton fiable basée sur la position qui utilise la position, la vitesse, la direction du mouvement et la stabilité de la liaison de leurs voisins pour sélectionner le prochain nœud de transfert le plus approprié. 3 métriques utilisées ici : vitesse de noeud , stabilité du lien et le score potentiel (pages 61/62) , le pseudo code pour l’algorithme de routage se trouve dans la page 63.

Maintenant il faut transformer les algorithmes cités en un programme exécutable pour faire la simulation et dégager des résultats pour faire la comparaison avec les solutions existantes pour montrer l’efficacité de ma proposition. 

