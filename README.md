# Aurora — mises à jour

> **Téléchargement rouvert en phase de test (18 septembre 2026).** Windows Defender avait signalé l'installeur à
> tort ; ses dernières mises à jour ne le signalent plus. Si ton antivirus réagit quand même, ne force rien et
> préviens Denis.

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
