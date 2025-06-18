Projet SAE 2.03
--------------------------------------------------------------------------------------------------------------

Presentation de l'arborescence :

dossier(SAE2.03)
	dossier(img)
		toutes les images
	SAE2.03.md
	SAE2.03.pdf
	SAE2.03.html
	README.md
	markdown.css


Bienvenue dans notre README ! Ce document présente le projet de la SAE 2.03, que nous avons réalisé en groupe de trois : Oussama Houaidj, Salah Eddine Houaidj, et Isshak Abdelali.

Ce README a pour objectif de vous guider à travers le processus de compilation de notre projet, en détaillant les méthodes et les outils que nous avons utilisés.

Le but de ce projet était de créer un rapport à l'aide d'un langage de balisage léger de notre choix, AsciiDoc ou Markdown. Nous avons donc choisi Markdown, sur lequel nous avons réalisé l'intégralité de notre projet.

Le rapport devait porter sur différentes tâches à réaliser durant quatre semaines, telles que l'installation d'une machine virtuelle ou de divers outils, comme Gitea par exemple. Nous vous expliquerons en détail comment nous avons abordé ce défi et quelles étapes ont été nécessaires pour mener à bien cette réalisation.

Ce README présentera également le moyen de compiler notre projet et d'exporter notre source Markdown en fichiers HTML et PDF.

Convertir en PDF et HTML --------------------------------------------------------------------------------------

Commençons par expliquer dans un premier temps comment obtenir les fichiers HTML et PDF.
Installer pandoc si ce n'est pas deja fait avec la commande : 

sudo apt install pandoc

C'est Pandoc qui va nous permettre de convertir nos fichiers.

pandoc SAE2.03.md -o SAE2.03.html
xdg-open SAE2.03.html (pour ouvrir)


Voici la commande pour convertir en HTML

pandoc SAE2.03.md -o SAE2.03.pdf
xdg-open SAE2.03.pdf (pour ouvrir)

Et voici la commande pour convertir en PDF
Ce sont deux commandes très simples qui nous permettent, grâce à Pandoc, de convertir aisément notre fichier source.

Bien sûr, ce n'est pas le seul moyen de convertir le fichier. On peut, par exemple, installer des extensions présentes sur VS Code qui font tout le travail pour nous et qui convertissent notre fichier immédiatement.

Mais l'intérêt ici est d'utiliser Pandoc pour comprendre comment fonctionne le convertisseur associé à Markdown.
-------------------------------------------------------------------------------------------------------------

Détail de notre rapport

Nous avons commencé, dans un premier temps, la conception de notre rapport sur le site dillinger.io, qui nous permettait aisément de convertir sans Pandoc et d'avoir un site à portée de main, ce qui facilitait notre travail.
Après avoir échangé avec notre enseignant et reçu un feedback, nous avons conclu que, pour des raisons évidentes de sécurité, il valait mieux changer de méthode en nous dirigeant vers autre chose.
Nous avons donc continué notre rapport sur VS Code, ce qui a été très agréable grâce aux différentes extensions qui nous ont facilité la vie et amélioré la clarté visuelle de notre projet.
Nous sommes donc reconnaissants d'avoir eu cette discussion avec notre enseignant, qui nous a permis d'améliorer notre travail.

Pour ce qui est de notre rapport, chaque mot qui apparaît en bleu et qui est cliquable nous renvoie vers la source qui nous a permis de répondre à la question et d'en apprendre plus sur le sujet.
C'est donc en quelque sorte la source de la réponse.

Pour ce qui est du sommaire, il vous renverra automatiquement, en cliquant dessus, vers le titre et l'endroit souhaité du rapport.
Cependant, un problème se pose avec celui-ci. En raison du YAML, lors de la sauvegarde du fichier source (Ctrl+S), le sommaire se génère automatiquement, ce qui rajoute un "-" en fin de phrase (visible dans la barre d'URL).
Il vous suffit de retirer le dernier "-" et le sommaire fonctionnera correctement.
Nous ne comprenons pas comment résoudre ce problème, c'est pourquoi nous vous en faisons part dans notre README.

Pour la partie CSS, assurez-vous que les fichiers sont bien liés les uns aux autres.
faite cette commande :
pandoc SAE2.03.md -o SAE2.03.html --css=markdown.css

-----------------------------------------------------------------------------------------------------------------------------------------------
Fin

Il se peut que pour le rendu final, certains détails ne soient pas comme nous l'espérions en raison de problèmes de dernière minute, mais nous avons mis notre cœur à l'ouvrage.

Nous avons pris la liberté d'ajouter un petit GIF de Goku, car nous le trouvions adapté pour dire au revoir au lecteur de notre rapport, et aussi parce que nous l'aimons beaucoup :)

Je pense que tout a été dit concernant notre rapport, en espérant n'avoir rien oublié.

Merci d'avoir lu, et j'espère que vous apprécierez notre rapport ainsi que tout le travail fourni :