🌐 NetPractice : Initiation au Réseau Informatique

NetPractice est un projet d'apprentissage interactif conçu pour vous initier aux concepts fondamentaux des réseaux informatiques, en se concentrant sur le protocole IPv4. À travers une série d'exercices pratiques, vous développerez une compréhension solide de l'adressage, du masquage de sous-réseau (subnetting) et du routage.
🎯 Objectif du Projet

L'objectif principal de ce projet est de rendre les concepts réseau abstraits concrets. En interagissant avec des scénarios simulés, vous apprendrez à :

    Configurer correctement les adresses IP et les masques de sous-réseau (subnet masks).

    Comprendre les mécanismes de communication entre machines sur un réseau.

    Analyser et corriger des scénarios réseau défectueux pour rétablir la connectivité.

    Maîtriser les bases du subnetting (découpage en sous-réseaux) et du routage (utilisation de tables de routage).

🚀 Contenu et Fonctionnement

Le projet se présente sous la forme d'une application web interactive composée de plusieurs niveaux progressifs.

Pour chaque niveau, vous devez suivre les étapes ci-dessous :

    Examiner le schéma réseau proposé (machines, routeurs, passerelles).

    Configurer les adresses IP, les masques de sous-réseau et les routes nécessaires sur les différentes machines/routeurs.

    Vérifier la connectivité : assurez-vous que toutes les machines requises peuvent communiquer entre elles.

    Valider le niveau une fois que toutes les connexions sont fonctionnelles (le succès est généralement indiqué par un changement de couleur au vert).

📚 Concepts Clés à Maîtriser
Concept	Description
Adresse IPv4	Composée d'une partie réseau et d'une partie hôte.
Masque de Sous-réseau	Détermine quelle partie de l'adresse IP appartient au réseau (bits à 1) et quelle partie appartient à l'hôte (bits à 0).
Communication Directe	Deux machines communiquent directement si elles ont la même partie réseau (c'est-à-dire, si elles sont sur le même sous-réseau).
Routage / Passerelle	Si deux machines ne sont pas sur le même réseau, elles doivent communiquer via une passerelle (un routeur) qui transmet le paquet.
🛠️ Installation (Mode Local)

Si vous souhaitez exécuter NetPractice en local :

    Clonez le dépôt du projet en utilisant git:
    Bash

    git clone https://github.com/myc42/netpratice.git

    Ouvrez l'application : Lancez simplement le fichier HTML fourni (index.html ou similaire, selon le dépôt) dans votre navigateur web préféré.

    💡 Note : Le projet étant interactif, aucune compilation ou dépendance complexe n'est généralement requise, car il fonctionne directement dans le navigateur.

✔️ Validation

La validation d'un niveau est obtenue lorsque l'interface graphique confirme que toutes les connexions requises sont établies et fonctionnelles. Dans l'outil, cela se manifeste par le passage de l'indicateur de connexion (souvent un cercle ou un trait) au vert

👨‍💻 Auteur

  Myc42 - Initiateur du projet/Réalisation

📝 Licence

Ce projet est distribué sous la [Ecole 42 MIT License].
