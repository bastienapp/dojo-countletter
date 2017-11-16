# Compte les occurrences d'une lettre dans une chaîne

Ecrire une méthode qui, pour une chaîne de caractère donnée, compte le nombre d'occurence d'une lettre donnée.

Par exemple :

* pour "a" et 'a', la méthode doit retourner 1.
* pour "aaaaabbbaa" et 'a', la méthode doit retourner 7.
* pour "bbacbaaa" et 'c', la méthode doit retourner 1.
* pour "bbcc" et 'a', la méthode doit retourner 0.

Avant de commencer l'exercice, pose-toi les questions suivantes :

* Quelles sont le ou les arguments de ma méthode, et son ou leurs types respectifs ?
* Quel est le type attendu en sortie ?

Essaie de réfléchir à l'algorithme sans même écrire de code, en te posant la question : comment trouver le nombre d'occurrence d'un caractère dans une chaîne ? Fait un schéma si nécessaire.

Maintenant, avant de commencer à écrire la méthode, écrit un cas de test simple (le premier cas présenté en exemple semble approprié).

Compile et corrige les erreurs s'il y en a, jusqu'à ce que la dernière erreur trouvée soit le fait que la méthode n'existe pas. L'erreur devrait ressembler à ça :

	symbol:   method ....
	location: class CountLetter

Maintenant écrit la signature de la méthode dans la classe appropriée, et fait le nécessaire pour répondre au premier cas de test. Tu n'as pas besoin de faire tout le traitement final du premier coup, pour le moment l'important est de répondre au premier test, afin que la compilation et l'exécution fonctionne.

Enfin, ajoute d'autres tests, et modifie ta méthode pour répondre à tous les cas de tests présentés en exemple.

Tu peux connaître la longueur d'une chaîne avec la méthode length(), par exemple : machaine.length(), si machaine contient "abcd", retournera 4.

Tu peux trouver le caractère d'une chaîne à une position particulière avec la méthode charAt(), par exemple : machaine.charAt(3) te donnera la quatrième lettre (car ça commence à zéro). Si machaine contient "abcd", le retour sera donc 'd'.

Rappel des commande junit :

    javac -cp .:junit-4.12.jar CountLetterTest.java
    java -cp .:junit-4.12.jar:hamcrest-core-1.3.jar org.junit.runner.JUnitCore CountLetterTest
