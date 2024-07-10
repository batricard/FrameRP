# FrameRP

**FrameRP** est un framework pour serveur RP Minecraft réalisé en Skript. Ce projet vise à fournir une base solide pour la création de serveurs roleplay en intégrant les systèmes principaux nécessaires au gameplay RP.

## Fonctionnalités

### Jobs
Le système de jobs permet de créer et de gérer divers métiers pour les joueurs. Chaque métier peut avoir des tâches spécifiques, des récompenses et des responsabilités uniques, ajoutant une dimension immersive au gameplay.

### Économie
L'économie est au cœur de tout serveur RP. FrameRP propose un système économique robuste, permettant des transactions entre joueurs, des systèmes bancaires, et la gestion de devises virtuelles.

### Chat de Proximité Écrit
Pour renforcer l'immersion, le chat de proximité écrit permet aux joueurs de communiquer uniquement avec ceux qui se trouvent à proximité d'eux dans le jeu. Cela ajoute une couche de réalisme en imitant les limitations de la communication dans le monde réel.

### Addons et Personnalisation
FrameRP est conçu pour être 100% configurable. Les administrateurs peuvent ajuster chaque aspect du framework selon leurs besoins spécifiques. De plus, il est possible de créer des addons simplement, permettant d'étendre les fonctionnalités de base sans modifier le code source principal.

## Installation

1. **Téléchargez le projet** : Clonez ce dépôt ou téléchargez le zip du projet.
   ```sh
   git clone https://github.com/votre-utilisateur/FrameRP.git
   ```
2. **Installation de Skript** : Assurez-vous d'avoir Skript installé sur votre serveur Minecraft. Vous pouvez le télécharger depuis [Skript Hub](https://skripthub.net/downloads).
3. **Ajout de FrameRP** : Placez le dossier `FrameRP` dans le répertoire `plugins/Skript/scripts/` de votre serveur Minecraft.
4. **Chargement des scripts** : Rechargez Skript ou redémarrez votre serveur pour que FrameRP soit pris en compte.
   ```sh
   /sk reload all
   ```

## Configuration

Tous les fichiers de configuration se trouvent dans le dossier `config` de FrameRP. Vous pouvez modifier les paramètres pour ajuster les systèmes de jobs, d'économie, de chat, etc., selon vos besoins.

## Création d'Addons

FrameRP permet la création d'addons personnalisés pour étendre les fonctionnalités existantes. Voici un exemple de la structure d'un addon simple :
```skript
# Nom de l'addon : ExampleAddon
on load:
    broadcast "ExampleAddon chargé avec succès!"
    
command /exemple:
    trigger:
        send "Commande d'exemple exécutée!"
```

Placez votre addon dans le répertoire `addons` de FrameRP et rechargez Skript pour l'activer.

## Contribution

Les contributions sont les bienvenues! Si vous souhaitez contribuer à FrameRP, veuillez suivre les étapes suivantes :
1. **Fork le dépôt**
2. **Créez une branche feature**
   ```sh
   git checkout -b feature/NouvelleFonctionnalité
   ```
3. **Commitez vos changements**
   ```sh
   git commit -m "Ajout d'une nouvelle fonctionnalité"
   ```
4. **Poussez votre branche**
   ```sh
   git push origin feature/NouvelleFonctionnalité
   ```
5. **Ouvrez une Pull Request**

## License

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus de détails.

---

Merci d'avoir choisi FrameRP! Pour toute question ou assistance, n'hésitez pas à ouvrir une issue ou à rejoindre notre communauté Discord. Bon jeu!
