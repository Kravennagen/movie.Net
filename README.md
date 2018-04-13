<h1>IDV-NET4 - Movie.Net</h1>
Le but de ce projet est de développer un logiciel permettant de consulter et de modifier une bibliothèque contenant des fiches de films.
<h2>Spécifications fonctionnelles :</h2>
<h3>Gestion des fiches de films :</h3>
La fiche d'un film est composée de son titre, de son genre (action, horreur, aventure, etc.), d'un résumé et de notes/commentaires donnés par les utilisateurs de l'application.

Votre logiciel doit fournir une fonction de recherche avancée permettant d'effectuer une recherche par critères sur les films: titre et genre au minimum. Pour cette partie, l'utilisation de Linq est obligatoire.

<h3>Gestion des utilisateurs :</h3>
Vous devez mettre en place un système d'authentification permettant aux utilisateurs de créer un compte, de pouvoir le modifier et s’authentifier sur le logiciel pour pouvoir utiliser ce dernier.

Consulter la fiche d'un film.
Ajouter, supprimer et modifier un film.
Noter et commenter celui-ci.
Effectuer des recherches.
<h3>Gestion des notes et des commentaires :</h3>
Les utilisateurs doivent pouvoir ajouter des commentaires sur la fiche d'un film et attribuer une note à celui-ci. L'ensemble des commentaires et la moyenne des notes d'un film doivent apparaitre sur la fiche du film en question.

<h2>Spécifications techniques :</h2>
<h3>Architecture :</h3>
<h4>Votre logiciel devra être composé (au minimum) de deux projets:</h4>

Un projet WPF qui contiendra l'interface du logiciel.
Un projet qui servira à manipuler les données.
Interface graphique :
Votre projet WPF devra utiliser le pattern MVVM (le code-behind étant interdit).

<h3>Manipulation des données :</h3>
La manipulation des données doit se faire grâce à une base de données MSSQL, manipulée via Entity Framework.
Pour chaque type de données (utilisateurs, films) vous devez mettre en place un DAO. Ces DAO devront encapsuler tous les appels à Entity Framework et doivent être internes au projet de manipulation des données.
L'appel aux DAO doit se faire à travers une façade, cette façade doit être une classe publique singleton	et le point d'accès unique à vos données.
<h2>Bonus</h2>
Pouvoir ajouter une image à la fiche d'un film ou des informations supplémentaires comme la liste des acteurs, le réalisateur, la durée du film, etc.
Apporter un effort particulier sur l'interface graphique.
Utiliser un service WCF comme façade pour consommer les données.
Développer d'autres clients en utilisant les technologies XAML (Silverlight, Windows phone, Application Universelle).
