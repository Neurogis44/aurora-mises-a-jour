# Aurora — mises à jour

> **Aurora 1.0.3 (26 septembre 2026)** : **de nouvelles mesures, et ton PC au fil des semaines**. Le point chaud et
> la mémoire de la carte graphique, tes barrettes, la mémoire engagée de Windows et le 12 V du bloc d'alimentation
> suivi sous la charge ; des graphiques semaine après semaine dans l'onglet Santé ; un enregistreur de mesures qui
> s'ouvre dans Excel ; et, à télécharger à part, **Aurora sur ton Stream Deck**.
> Le site : **https://auroraapp.ca**

Aurora est un moniteur matériel pour Windows : températures, charge du processeur et de la carte
graphique, ventilateurs, disques, réseau, FPS en jeu et lecteur multimédia, dans un tableau de bord —
et un bilan de santé qui dit ce qui cloche.

Ce dépôt sert seulement à **diffuser les versions**. Il contient :

- `version.json` : le numéro de la dernière version publiée, qu'Aurora consulte une fois par jour ;
- les **Releases** : l'installeur `Aurora-Setup-<version>.exe` de chaque version, avec sa notice ;
- la Release **Aurora sur le Stream Deck** : le module `Aurora.streamDeckPlugin`, à télécharger à part.

## Installer ou mettre à jour

1. Ouvre la [dernière version](https://github.com/Neurogis44/aurora-mises-a-jour/releases/latest)
   et télécharge `Aurora-Setup-<version>.exe`.
2. L'installeur est **signé électroniquement** : Windows affiche « Éditeur vérifié : Denis Desbiens ».
   Une version toute neuve peut encore déclencher SmartScreen les premiers jours : clique
   **Informations complémentaires**, vérifie le nom de l'éditeur, puis **Exécuter quand même**.
3. L'installation demande les droits administrateur (nécessaires pour lire les capteurs) et
   installe au besoin Microsoft .NET 10 et le pilote PawnIO.

Le fichier `Lisez-moi.txt` joint à chaque version (`Readme.txt` en anglais) explique tout en détail,
y compris comment vérifier l'empreinte du fichier téléchargé.

## Bon à savoir

- Aurora ne crée aucun compte et n'envoie aucune mesure : la vérification de version est sa seule
  connexion sortante automatique, et elle se coupe dans **Réglages → Démarrage et mises à jour**.
- Les PC d'une même maison qui se suivent dans l'onglet « Mes PC » se passent les nouvelles versions,
  sans passer par Internet, et chacun vérifie la signature de l'installeur avant de le lancer.
- Projet personnel, offert tel quel et sans garantie. Pour m'écrire : dans Aurora, **Réglages → Support**, ou
  contact@auroraapp.ca
