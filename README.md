#Test Driving Developpement <h2>(développement piloté par les tests)</h2>

[schema du cycle](http://www.elinext.com/images/articles/1330077259jpg)

##Definition:

 C’est une technique de développement de logiciel qui préconise d'écrire les tests unitaires avant d'écrire le code source d'un logiciel.
 
 <p>Le TDD se divise en 6 étapes distinctes:
 
- écrire un test
- vérifier qu’il échoue (car le code que l’on teste n’existe pas)
- écrire juste le code suffisant pour passer le test
- vérifier que le test passe
- Checker le source pour que les autres développeurs puissent l’utiliser
- Refactoriser le code</p>

##A qui sert-il ?

Ce mode de fonctionnement sert a tout développeur connaissant déjà la finalité de son projet. De plus le fait d’avoir des tests augmentent la confiance en sois du programmeur. Par exemple, le célèbre groupe AMAZON utilise se mode de fonctionnement.

##A quoi sert-il ?

Le TDD est souvent associé à la méthode XP, qui est rapprochée de la méthode en binôme:</br>
- premier test écris pas le premier programmeur</br>
- premier code écris par le deuxieme programmeur</br>
- premier “reusinage” du code écris par le premier programmeur</br>
- deuxieme test écris par le deuxieme programmeur</br>
- deuxieme code écris par le premier programmeur</br>
- deuxieme “reusinage” du code écris par le deuxieme programmeur</br>
-..etc</br>

##Code propre:
	
<p>Le code propre c’est du code :

- qui passe ses tests</br>
- qui est minimal</br>
- qui est explicite</br>

Pour réussir à créer du code propre, il faut tout simplement essayer de le pratiquer le plus possible. En passant du temps a lire du code, on peu comprendre comment fonctionne le code “propre”. En rendant un code facile a lire, on le rend plus facile à écrire.</p>

Dans un code propre on trouve généralement:

-pas de commentaire</br>
-max 20 lignes par methodes</br>
-des noms de variables explicites</br>
-pas de variable globale</br>

##Lien avec git:

Grâce à git, il est beaucoup plus facile de pouvoir envoyer son code et ainsi  travailler en équipe. 
