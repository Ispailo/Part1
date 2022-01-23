# capstone_project_Part1
Docker est une plateforme permettant de lancer certaines applications dans des conteneurs logiciels.

Selon la firme de recherche sur l'industrie 451 Research, « Docker est un outil qui peut empaqueter une application et ses dépendances dans un conteneur isolé, qui pourra être exécuté sur n'importe quel serveur ». Il ne s'agit pas de virtualisation, mais de conteneurisation, une forme plus légère qui s'appuie sur certaines parties de la machine hôte pour son fonctionnement. Cette approche permet d'accroître la flexibilité et la portabilité d’exécution d'une application, laquelle va pouvoir tourner de façon fiable et prévisible sur une grande variété de machines hôtes, que ce soit sur la machine locale, un cloud privé ou public, une machine nue, etc.1

####################Partie 1 : Comment construire une application Node.js avec Docker####################

Pour cette partie j'ai entamé la création d'une image d'application pour un site web statique qui utilise le cadre Express et Bootstrap. J'ai construis ensuite un conteneur en utilisant cette image et la pousserez vers Docker Hub.

Pour la réalisation j'ai suivi les étapes citer ci-dessous: 

  * Installation des dépendances de votre application
  * Création des fichiers d'application
  * Rédaction du Dockerfile
  * Utilisation d'un répertoire pour travailler avec des images
  
![image](https://user-images.githubusercontent.com/80095967/150679030-ced42b86-5ef3-487d-93e4-d1f38e8aa9a4.png)
![image](https://user-images.githubusercontent.com/80095967/150679053-c7d347f5-5b22-4776-a260-74b999ee937e.png)
