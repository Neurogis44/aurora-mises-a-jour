# Aurora — mises à jour

> **Aurora 0.11.0 (18 septembre 2026)** : place pour Aurora IA, l'assistant local de Denis (programme à part, non
> inclus : sans lui, rien ne change). Version précédente, 0.10.0 : thème Carbone, débits en Mbit/s, numéro de version. Si ton antivirus prétend que l'installeur est un virus, ne force rien et préviens Denis : c'est une
> fausse alerte connue pour les programmes neufs non signés.

Aurora est un moniteur matériel pour Windows : températures, charge du processeur et de la carte
graphique, ventilateurs, disques, réseau, FPS en jeu et lecteur multimédia, dans un tableau de bord.

Ce dépôt sert seulement à **diffuser les versions**. Il contient :

- `version.json` : le numéro de la dernière version publiée, qu'Aurora consulte une fois par jour ;
- les **Releases** : l'installeur `Aurora-Setup-<version>.exe` de chaque version.

## Installer ou mettre à jour

1. Ouvre la [dernière version](https://github.com/Neurogis44/aurora-mises-a-jour/releases/latest)
   et télécharge `Aurora-Setup-<version>.exe`.
2. Windows affiche « Windows a protégé votre ordinateur » : l'installeur n'est pas signé
   électroniquement. Clique sur **Informations complémentaires**, puis **Exécuter quand même**.
3. L'installation demande les droits administrateur (nécessaires pour lire les capteurs) et
   installe au besoin Microsoft .NET 10 et le pilote PawnIO.

Le fichier `Lisez-moi.txt` joint à chaque version explique tout en détail, y compris comment
vérifier l'empreinte du fichier téléchargé.

## Bon à savoir

- Aurora ne crée aucun compte et n'envoie aucune mesure : la vérification de version est sa seule
  connexion sortante, et elle se coupe dans **Réglages → Démarrage et mises à jour**.
- Les PC d'une même maison qui se suivent dans l'onglet « Mes PC » se mettent à jour entre eux,
  sans passer par Internet.
- Projet personnel, offert tel quel, sans garantie ni support.
