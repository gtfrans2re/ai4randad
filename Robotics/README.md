# Partie 1 : Fondamentaux de la robotique

![Couverture Robotics 101](images/roboticsCoverImage.png)

## Présentation
Ce volet offre une introduction aux fondamentaux de la robotique

## Objectif
- Fournir un aperçu général de la robotique ;

## Programme

### Partie 0 : Introduction
- **Robot(ique)** :
  - **Historique** : [Origines du « robot » et de la « robotique »](https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/robotics/history.html#:~:text=Origins%20of%20%22robot%22%20and%20%22robotics%22) ;
  - **Définition** : [Définitions de « robot »](https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/robotics/history.html#:~:text=Definitions%20of%20%22robot%22) ;
  - **Loi d'Assimov** : [Les lois de la robotique](https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/robotics/history.html#:~:text=Asimov%20also%20proposed%20three%20%22Laws%20of%20Robotics%22%20that%20his%20robots%2C%20as%20well%20as%20sci%2Dfi%20robotic%20characters%20of%20many%20other%20stories%2C%20followed%3A) ;
  - **Robotique Responsable** : [https://responsiblerobotics.eu](https://responsiblerobotics.eu) ;
  - **Le robot idéal** : [Dix principales capacités d’un robot idéal](https://cs.stanford.edu/people/eroberts/courses/soco/projects/1998-99/robotics/) ;
 
- **Anatomie des robots** :
  - **Anatomie d'un robot** : [https://motion.cs.illinois.edu/RoboticSystems/AnatomyOfARobot.html](https://motion.cs.illinois.edu/RoboticSystems/AnatomyOfARobot.html) ;
  - **Anatomie des robots : hardware** :
    - **Unité Centrale de Traitement (CPU)**: Le cerveau du robot, responsable du traitement des instructions, de la prise de décisions et de l'exécution des commandes.
    - **Capteurs**: Ce sont les équivalents des sens humains pour un robot. Ils comprennent des caméras (vision), des microphones (ouïe) et divers capteurs environnementaux pour détecter la température, la proximité et la pression.
    - **Actionneurs**: Ils fonctionnent comme des muscles, permettant au robot de se mouvoir. Cela inclut des moteurs pour le mouvement des membres, des roues ou d'autres parties.
    - **Alimentation**: C'est la source d'énergie du robot, souvent des batteries ou des cellules d'énergie, qui doivent être régulièrement rechargées ou remplacées.
    - **Stockage de Mémoire**: Semblable à la capacité humaine de se souvenir, cela stocke les données et instructions nécessaires au fonctionnement du robot.
    - **Interfaces d'Entrée/Sortie**: Elles sont utilisées pour communiquer avec d'autres appareils ou systèmes, comme des ports USB, des modules de communication sans fil (comme le Wi-Fi ou le Bluetooth), et parfois des interfaces spécialisées pour des tâches spécifiques.
    - **Carte Mère**: Le centre de connexion où tous les autres composants sont reliés, leur permettant de communiquer entre eux.
    - **Effecteurs Finaux**: Ce sont les outils ou dispositifs situés à l'extrémité d'un bras robotique, tels que des pinces, des caméras ou des outils spécialisés pour des tâches comme le soudage ou la peinture.
    - **Système de Navigation**: Cela inclut le GPS et d'autres technologies pour aider le robot à comprendre sa position et à se déplacer.
    - **Systèmes de Refroidissement**: Pour éviter la surchauffe, surtout dans les robots qui effectuent des tâches de haute intensité ou qui fonctionnent dans des environnements chauds.
    - **Boîtier de Protection et Structure**: La structure qui maintient tous les composants ensemble et les protège des facteurs environnementaux.
    - **Logiciel et Firmware**: Cela inclut le système d'exploitation et le logiciel qui fonctionne sur le matériel, contrôlant les actions et les réponses du robot.
  - **Anatomie des robots : Software** : 
    - **Système d'exploitation (OS) :**
      - Logiciel principal qui gère les ressources matérielles du robot.
      - Fournit des services communs pour d'autres logiciels.
      - Crucial pour coordonner les tâches et gérer les ressources efficacement.
  
  - **Logiciel de système de contrôle :**
      - Responsable de l'interprétation des commandes et de leur traduction en actions.
      - Comprend des algorithmes pour le contrôle des mouvements, la gestion des capteurs et des actionneurs.
      - Assure que le robot peut se déplacer et fonctionner comme prévu.
  
  - **Logiciel de navigation et de cartographie :**
      - Aide les robots mobiles à comprendre et à naviguer dans leur environnement.
      - Inclut des algorithmes pour la planification de trajets et l'évitement d'obstacles.
      - Peut impliquer la localisation et la cartographie simultanées (SLAM).
  
  - **Logiciel de fusion de capteurs :**
      - Intègre les données de différentes sources sensorielles.
      - Fournit une compréhension complète des environs.
      - Essentiel pour la détection d'objets et la surveillance de l'environnement.
  
  - **Modules d'intelligence artificielle (IA) et d'apprentissage automatique (ML) :**
      - Utilisés pour des capacités de prise de décision et d'apprentissage avancées.
      - Peuvent inclure des réseaux neuronaux, des arbres de décision et d'autres algorithmes d'IA.
      - Permettent au robot de s'adapter à de nouvelles situations et de prendre des décisions complexes.
  
  - **Logiciel de communication :**
    - Permet au robot de communiquer avec d'autres systèmes, dispositifs ou réseaux.
    - Essentiel pour recevoir des commandes et envoyer des données.
    - Important pour l'intégration à d'autres systèmes dans un environnement intelligent.
  
  - **Logiciel d'interface utilisateur (UI) :**
    - Conçu pour l'interaction homme-robot.
    - Peut inclure des interfaces graphiques, des modules de reconnaissance vocale.
    - Facilite la télécommande et d'autres formes d'interaction.
  
  - **Logiciel de diagnostic et de maintenance :**
    - Aide à surveiller la santé du robot et à diagnostiquer les problèmes.
    - Parfois utilisé pour effectuer des tâches de maintenance automatique.
    - Crucial pour la fonctionnalité et la fiabilité à long terme.
  
  - **Logiciel de sécurité :**
    - Essentiel pour protéger contre les accès non autorisés et les menaces cybernétiques.
    - Important étant donné la connectivité croissante des robots.
  
  - **Logiciel d'application personnalisé :**
    - Dépend de l'objectif spécifique du robot.
    - Conçu pour des tâches particulières comme la fabrication, les procédures médicales ou le service à la clientèle.

  - **Analogy humain-robot** : [Description 3](#)
 
- **Types de robots** :
  - **Robots terrestres** : [Description 1](#)
  - **Robots aériens** : [Description 2](#)
  - **Robots sous-marins** : [Description 3](#)
  - **Bras robotisés** : [Description 4](#)
 
- **Domaines d'application** :
  - **Armée** : [Description 1](#)
  - **Automobile** : [Description 2](#)
  - **[TBC]** : [Description 3](#)
 
### Partie 1 : Robotique & IoT
- **Cartes de microcontrôleur** :
  - **Arduino** : [Description 1](#)
  - **Microcontrôleurs compatibles Wifi** :
    - **esp32** : [Description 1](#)
    - **esp8266** : [Description 2](#)
  - **Raspberry Pi** : [Description 3](#)
 
- **Composantes physiques** :
  - **Capteurs** : [Description 1](#)
  - **Actionneurs** : [Description 2](#)
  - **Suppléments** :
    - **LEDs** : [Description 1](#)
    - **Buzzers** : [Description 2](#)
    - **Autres** : [Description 3](#)
  - **Virtualisation & Plateformes** :
    - **Tinkercad** : [Description 1](#)
    - **Circuito.io** : [Description 2](#)
    - **hackster.io** : [Description 3](#)
  - **Communication** :
    - **Serial** : [Description 1](#)
    - **Parallèle** : [Description 2](#)
  - **Pins** :
    - **Digital** : [Description 1](#)
    - **Analog** : [Description 2](#)
   
- **Construction d'un robot** :
  - **Collecte de composants électroniques** : [Description 1](#)
  - **Assemblage desdits composants** : [Description 2](#)
  - **Mouvements du robot** : [Description 3](#)
  - **Codage du robot** : [Description 4](#)
  - **Téléversement du code** : [Description 5](#)
 
- **Internet des Objets** :
  - **Définition** : [Description 1](#)
  - **Microcontrôleur activé par Wifi** : [Description 2](#)
  - **Indicator LEDs** : [Description 3](#)
  - **Architecture cloud IoT** : [Description 4](#)
  - **Connection Microcontrôleur & Cloud** : [Description 5](#)
 
### Partie 2 : Fondation du code pour ROS ou Robot Operating System (Système d'Exploitation pour la Robotique)
- **Linux pour ROS** :
  - **Navigation à travers un système de fichiers Linux** : [Description 1](#)
  - **Interagir avec le système de fichiers Linux** : [Description 2](#)
  - **Editer des fichiers à l'aide du shell (Emacs/Vi/Vim)** : [Description 3](#)
  - **Managing access to files (permissions)** : [Description 4](#)
  - **Shell / bash scripting** : [Description 5](#)
  - **Gérer les exécutions de programmes Linux (Processes)** : [Description 6](#)
  - **Se connecter à l'ordinateur distant d'un robot (ssh)** : [Description 7](#)
 
- **Python (3) for ROS** :
  - **Stockage des données dans des variables** : [Description 1](#)
  - **Operating with data in the variables** : [Description 2](#)
  - **Modifier le comportement en fonction des conditions** : [Description 3](#)
  - **Création de fonctions pouvant être appelées depuis d'autres endroits du code** : [Description 4](#)
  - **Comment encapsuler le code dans des classes** : [Description 5](#)
  - **Avoir un code propre et robuste** : [Description 6](#)
 
### Partie 3 : Robotique & Open Source
- **Organisations majeures** :
  - **OSRF (Open Source Robotics Foundation)** : [https://www.openrobotics.org](https://www.openrobotics.org)
  - **JdeRobot** : [https://jderobot.github.io](https://jderobot.github.io)
