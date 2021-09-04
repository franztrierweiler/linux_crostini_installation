# linux_crostini_installation
Ensemble d'outils et de notes pour installer diverses application sur Chromebook/crostini

## Etape 1: activer tout simplement Crostini sur le Chromebook

## Etape 2: Pré-configuration pour l'installation de VSCode

* Mettre à jour le système de paquets
> `sudo apt-get update`

* Installer quelques dépendances
> `sudo apt-get install -y gnome-keyring`

* Pour installer VSCode, il est nécessaire de connaître l'architecture de sa machine
> `dpkg print-architecture`

* Aller sur https://code.visualstudio.com/download pour récupérer le paquet deb (double cliquer sur le .deb, Crostini l'installera tout seul).
