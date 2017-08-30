# Exercice d'entraînement aux requêtes MYSQL.

A partir de la [BDD d'entraînement proposée par w3school](https://www.w3schools.com/sql/trysql.asp?filename=trysql_select_all) (aussi connue comme la BDD Northwind sample database), vous devez créer un ensemble de requêtes MYSQL qui répondront aux besoins énumérés dans ce readme.  

Les requêtes ainsi créées devront être consignées dans un document et un screen (correctement rogné) des derniers résultats obtenus devra accompagner chaque requête. Le format de ce document sera réutilisé pour la certif, alors soignez la présentation, c'est du temps de gagner.

## Les besoins

**1) Affichez tous les employés**  
**2) Affichez uniquement les ProductID et les ProductName de la table product**  
**4) Affichez les Orders du client "Around the Horn"**  
**5) Affichez les détails des commandes du client "B's Beverages"**  
**6) Ajoutez vos infos dans la table des employés**  
**7) Ajoutez un champ pour un nouveau collègue fictif dans la table des employés, mais attention, celui-ci refuse de mettre sa photo**  
**8) Il y a une faute de frappe dans le numéro de téléphone du Shipper "Federal shipping", le bon est le : (503) 555-9935. Mettez ses données à jour**  
**9) Nous venons de perdre le client "Du monde entier" supprimez manuellement toutes les infos le concernant dans notre BDD (les commandes, les détails de commandes et ses infos de clients)**  
**10) Donnez le prix moyen de leurs produits**  
**11) Faîtes une requête qui affiche dans une nouvelle colonne (attention, cela ne veut pas dire en insérer une nouvelle) le total dépensé dans chaque commande dans la table OrderDetails.**  
**12) Affichez le produit "vache à lait" c.a.d. le produit qui a le chiffre d'affaires le plus important**  

## Bonus

Si les deux dernières questions ne vous ont pas achevées... Modélisez la base de données sur laquelle vous venez de travailler ! (Avec MYSQL Workbench).

Vous avez déjà fait une modélisation, mais cette fois-ci vous faîtes en plus : 

- Le dictionnaire de données (exemple : Nom du client => CustomerName; tout ça consigner dans un tableau. Dans votre cas, il s'agit plus de passer du nom des champs au nom réel)
- Le schéma entité/association (le nom des tables + colonnes et les cardinalités) 
- Le schéma physique (les types de données en prime, ce que vous créer sur workbench). 

C'est certes un bonus, mais ceux qui étaient pas à l'aise avec l'exercice de modélisation qu'on a fait précédemment, je vous recommande de le faire. 

N'oubliez pas que c'est un exercice d'entrainement et non un challenge. Nous répondrons à vos questions si vous en avez, mais nous vous courrirons pas après si vous nous demander rien...
