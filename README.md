
<h1 align="center">
les bases de données SQL
</h1>

## Definition :

SQL (sigle pour Structured Query Language, « langage de requêtes structurées ») est un langage informatique normalisé servant à exploiter des bases de données relationnelles. La partie langage de manipulation des données de SQL permet de rechercher, d'ajouter, de modifier ou de supprimer des données dans les bases de données relationnelles.

On utilise un SGBD (systeme de gestion de base de données ) pour manipuler des bases de données.

## Le SGBD

Le systeme de gestion de bases de données pour SQL s'appelle mysql. Pour connaitre notre version de mysql il faut ecrire le code dans un CMD (Console) :

```
mysql --version
```
nous obtenons ce resultat : 

![Capture ecran CMD](/img/capture1.png)

Pour utiliser mysql dans notre CMD il faudrait ecrire le code suivant :

```
mysql -u root -p
```
Nous obtenons ce resultat : 

![Capture ecran CMD](/img/capture2.png)

Nous sommes pret à taper du code SQL.

## Creation de notre premiere base de données.

Pour crée ma base de donnée via le CMD nous ecrivons le code suivant :

![Capture ecran CMD](/img/capture3.png)

CREATE DATABASE Toujours en MAJUSCULE car se sont des mots reservés mysql, pour nommer notre base de données on choisira les miniscules et faudra finir chaque instruction sql par un point-virgule (;)