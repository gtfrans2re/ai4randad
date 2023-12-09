# Partie 2 : Technologie des drones

![Couverture Drone Technology](images/DronetechnologyCoverImage.png)

## Présentation
Ce volet offre une introduction aux bases de la technologie des drones

## Objectifs
- Fournir un aperçu général de la technologie des drones ;

## Programme

### Partie 0 : Principes de base de la technologie des drones
- **Drone** :
  - **Définition** : [https://fr.wikipedia.org/wiki/Drone](https://fr.wikipedia.org/wiki/Drone)
  - **Types** :
    - **Drones multirotors** : [https://en.wikipedia.org/wiki/Multirotor](https://en.wikipedia.org/wiki/Multirotor)
    - **Drones à ailes fixes** ;
    - **Drones hélicoptères monorotor** ;
    - **Drones hybrides VTOL à voilure fixe** ;
  - **Applications** :
    - **Levés avec Photos Orthographiques** ;
    - **Inspection Industrielle** ;
    - **Photographie Aérienne** ;
    - **Vidéographie Aérienne** ;
    - **Services de Surveillance** ;
- **Drones quadricoptères / quadrirotors** :
  - **Définition** : [Description 1](#)
  - **Principe de fonctionnement** : [https://www.dronetechplanet.com/physics-behind-how-drones-fly/](https://www.dronetechplanet.com/physics-behind-how-drones-fly/)
  - **Pièces du quadricoptère et leurs fonctions** :
    - **Quatre hélices** ;
    - **Quatre moteurs BLDC sans balais** ;
    - **Quatre contrôleurs de vitesse électroniques (ESC)** ;
    - **Châssis de drone quadrirotors** ;
    - **Train d'atterrissage** ;
    - **Carte de distribution d'énergie pour drone quadricoptère** ;
    - **Contrôleur de vol** ;
    - **Émetteur et récepteur** ;
    - **Batterie au lithium polymère (LiPo) & chargeur** ;
    - **GPS Module & Laser** ;
    - **Capteurs de bord (e.g. Camera Infrarouge)** ;
  - **Autonomie de la batterie et temps de vol du quadricoptère** :
    - **Autonomie d'une batterie LiPo** ;
    - **Temps de vol du quadricoptère muni d'une LiPo** ;
  - **En savoir plus** : [dronelife.com](dronelife.com)
  - **Simulation / Virtualisation** :
    - **Drone Demo by OSRF** : [https://github.com/osrf/drone_demo](https://github.com/osrf/drone_demo)
    - **DroneViz** : [https://jderobot.github.io/projects/robots_programming_tools/](https://jderobot.github.io/projects/robots_programming_tools/)

### Partie 1 : Drones autonomes ou véhicules aériens sans pilote
- **Système aérien sans pilote (UAS)** :
  - **Définition** :
    - Un Système d'Aérien sans Pilote (UAS) est un ensemble intégré comprenant un Véhicule Aérien sans Pilote (UAV), un système de contrôle au sol (Ground-based Control System, GCS), et un système de communication reliant les deux. Ce système permet la conduite de missions aériennes sans la présence physique d'un pilote dans l'aéronef. Les UAS sont utilisés dans diverses applications, allant de la surveillance à la recherche et sauvetage, et peuvent fonctionner sous différents niveaux d'autonomie, allant du contrôle à distance manuel à l'autonomie complète basée sur des algorithmes informatiques embarqués. Leur utilisation est réglementée pour assurer la sécurité et l'intégrité de l'espace aérien et des autres utilisateurs.
  - **Composition d'un UAS:**
    - **Véhicule aérien sans pilote (UAV):** C'est un avion sans pilote humain à bord, conçu pour effectuer des missions avec divers niveaux d'autonomie. Il peut être contrôlé à distance ou fonctionner de manière autonome grâce à des ordinateurs embarqués.
    - **Contrôleur au sol (GSC):** Un système de commande au sol permet de piloter l'UAV à distance. Il s'agit d'une interface utilisateur permettant à un opérateur humain de contrôler et de surveiller le vol de l'UAV.
    - **Système de Communication:** Ce système établit une connexion entre l'UAV et le GSC, permettant le transfert d'informations de commande et de données de vol en temps réel.
  
  - **Nécessité d'un UAS:**
    - **Niveau d'Autonomie:** Les UAVs peuvent fonctionner sous divers degrés d'autonomie, depuis le contrôle manuel par un opérateur humain jusqu'à l'autonomie complète, où l'UAV prend des décisions basées sur les algorithmes de l'ordinateur de bord.
    - **Applications:** Les UAS sont utilisés dans de nombreux domaines, tels que la surveillance, la photographie aérienne, l'agriculture de précision, les inspections d'infrastructures, et les opérations de recherche et de sauvetage.
    - **Considérations réglementaires:** Les opérations des UAS sont soumises à des réglementations qui varient selon les pays. Ces réglementations peuvent inclure des restrictions sur les zones de vol, les hauteurs de vol, et l'enregistrement des UAVs.
  
