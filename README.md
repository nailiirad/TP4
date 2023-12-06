# Système de Gestion de Magasin
Ce projet Java englobe un système simple de gestion de magasin, comprenant des classes pour les employés, les produits et les magasins.

* Les principales classes comprennent :

1. `Employe`: Une classe de base pour tous les employés avec des attributs tels que l'identifiant, le nom, l'adresse et les heures travaillées par mois. Elle inclut une méthode pour afficher les informations de l'employé.
2. `Caissier`: Étend la classe Employe et représente un caissier avec des attributs supplémentaires tels que le numéro de caisse. Il calcule le salaire en fonction des heures travaillées.
3. `Responsable`: Étend la classe Employe et représente un responsable avec un attribut supplémentaire pour une prime. Il calcule le salaire en fonction des heures travaillées.
4. `Vendeur`: Étend la classe Employe et représente un vendeur avec un attribut supplémentaire pour le taux de vente. Il calcule le salaire en fonction du taux de vente.
5. `Magasin`: Représente un magasin avec des attributs tels que l'adresse, l'identifiant, la capacité, les produits, les employés et le nom. Elle inclut des méthodes pour ajouter des employés, afficher les informations du magasin et afficher les informations des employés.
6. `Produit`: Représente un produit avec des attributs tels que l'identifiant, le libellé, la marque, le prix et la date d'expiration. Elle inclut des méthodes pour définir et obtenir des attributs, afficher les informations du produit et comparer des produits.
7. `Main`: Contient la méthode principale pour démontrer la fonctionnalité des classes. Elle crée des instances de produits, d'employés et de magasins, ajoute des employés aux magasins et calcule et affiche leurs salaires.


Le projet vise à présenter la conception d'un système simple de gestion de magasin en Java, avec des classes représentant différents rôles au sein d'un magasin. Il démontre des principes de base de la programmation orientée objet tels que l'héritage, l'encapsulation et le polymorphisme. Les utilisateurs peuvent interagir avec le système en définissant les prix des produits, en ajoutant des employés aux magasins, et en calculant et affichant leurs salaires. Le code inclut également des exemples de gestion des dates et de saisie utilisateur à l'aide de la classe Scanner.