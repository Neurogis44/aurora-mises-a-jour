# Aurora — mises à jour

> **Aurora 1.0.13 (9 octobre 2026)** : **la grande revue**. Tout le code ajouté depuis la 1.0.9 relu avant de
> présenter Aurora au monde : plus de 70 corrections. Ta pompe toujours protégée, les fichiers en double qui regardent
> enfin OneDrive (jamais les autres comptes du PC), Windows bien suivi (Aurora te dit quand ta version n'est plus
> suivie par Microsoft), un rapport pour ton technicien plus discret, et un bandeau de mise à jour qui revient chaque
> jour tant qu'elle n'est pas installée.
>
> Depuis la 1.0.12 : des ventilateurs qui ne disparaissent plus. Depuis la 1.0.11 : les fichiers en double, en toute
> sécurité. Depuis la 1.0.10 : les mises à jour de Windows en clair et le rapport pour ton technicien. Depuis la
> 1.0.9 : les skins et un tableau de bord fluide.
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
   et télécharge `Aurora-Setup-<version>.exe` (`Aurora-Setup.exe`, à côté, est le même fichier sous un nom fixe :
   [ce lien](https://github.com/Neurogis44/aurora-mises-a-jour/releases/latest/download/Aurora-Setup.exe) donne
   toujours la dernière version).
2. L'installeur est **signé électroniquement** : Windows affiche « Éditeur vérifié : Denis Desbiens ».
   Une version toute neuve peut encore déclencher SmartScreen les premiers jours : clique
   **Informations complémentaires**, vérifie le nom de l'éditeur, puis **Exécuter quand même**. Au téléchargement,
   Edge peut aussi dire que le fichier « n'est pas fréquemment téléchargé » : la marche à suivre, avec les vraies
   fenêtres, est sur https://auroraapp.ca/#installer.
3. L'installation demande les droits administrateur (nécessaires pour lire les capteurs) et
   installe au besoin Microsoft .NET 10 et le pilote PawnIO.

Le fichier `Lisez-moi.txt` joint à chaque version (`Readme.txt` en anglais) explique tout en détail,
y compris comment vérifier l'empreinte du fichier téléchargé.

## Bon à savoir

- Aurora ne crée aucun compte et n'envoie aucune mesure : la vérification de version est sa seule
  connexion sortante automatique, et elle se coupe dans **Réglages → Démarrage et mises à jour**.
- Les PC d'une même maison qui se suivent dans l'onglet « Mes PC » se passent les nouvelles versions,
  sans passer par Internet, et chacun vérifie la signature de l'installeur avant de le lancer. Ils peuvent
  aussi s'envoyer des fichiers, de la même façon : chiffrés, sans passer par Internet.
- L'onglet Windows ne change que ce que tu coches, par les moyens officiels de Windows, et jamais ses protections
  (Defender, pare-feu, contrôle de compte, mises à jour) : chaque réglage se remet d'un clic, et la désinstallation
  remet tout.
- La recherche des fichiers en double lit tes fichiers sur ton PC seulement, quand tu la lances : leurs noms ne vont
  nulle part, et seulement ce que tu coches part à la corbeille.
- Projet personnel, offert tel quel et sans garantie. Pour m'écrire : dans Aurora, **Réglages → Support**, ou
  contact@auroraapp.ca

## Licence

Aurora est gratuite, sous sa propre licence : tu peux l'utiliser partout, à la maison comme au travail, et
partager son installeur tel quel, mais pas la vendre ni la modifier. Texte complet : [LICENSE](LICENSE), et
https://auroraapp.ca/licence.
