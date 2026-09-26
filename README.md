<p align="center">
  <img alt="Rubis Launcher" src="/program_info/rubis.png" width="42%">
</p>

<h1 align="center">Rubis Launcher</h1>

<p align="center">
  Un launcher Minecraft moderne, rapide et facile à utiliser, pensé pour gérer plusieurs installations de Minecraft en un seul endroit.<br>
  Fork de <a href="https://prismlauncher.org">Prism Launcher</a>, avec une identité visuelle Rubis et des fonctionnalités orientées joueurs.
</p>

## Présentation

Rubis Launcher est un launcher Minecraft open source qui permet de :

- gérer plusieurs instances Minecraft,
- lancer des versions Java avec configuration simplifiée,
- installer rapidement des mods et des packs,
- jouer avec un compte Microsoft ou un compte offline/crack,
- héberger un serveur local ou utiliser un tunnel public,
- bénéficier d'une expérience plus simple et plus rapide qu'un launcher traditionnel.

Le projet est basé sur l'écosystème Prism Launcher, mais réadapté avec un design et des fonctionnalités spécifiques.

## Pourquoi Rubis Launcher ?

- Compatible avec les comptes Microsoft premium
- Compatible avec les comptes offline / crack
- 100 % open source
- Aucune pub
- Aucun virus
- Gestion multiple d'instances Minecraft
- Support de Fabric, Forge, Quilt et NeoForge
- Installation automatique de mods de performance
- Hébergement de serveur intégré
- Tunnel public intégré via playit.gg
- Mise à jour automatique
- Thème rouge Rubis personnalisé

## Fonctionnalités

- Gestion de plusieurs profils / instances Minecraft
- Support des versions modées et Vanilla
- Installation de Fabric, Forge, Quilt et NeoForge
- Optimisation automatique des instances avec mods de performance
- Gestion des comptes Microsoft et offline
- Gestion des skins pour comptes offline
- Lancement de serveurs locaux
- Accès rapide aux packs et ressources
- Interface moderne et personnalisable
- Thème visuel Rubis
- Système de mise à jour intégré

## Installation

### Télécharger la dernière version

Téléchargez la dernière version depuis la page des releases :

- [GitHub Releases](https://github.com/layanfibw-maker/RubisLauncher/releases)

### Étapes rapides

1. Téléchargez le fichier .zip ou l'archive de la version souhaitée
2. Extrayez le dossier
3. Lancez `RubisLauncher.exe` sous Windows
4. Ajoutez votre compte Microsoft ou utilisez un compte offline
5. Créez ou chargez une instance Minecraft et jouez

## Prérequis

Pour utiliser le launcher :

- Windows, Linux ou macOS
- Java installé ou géré automatiquement par le launcher
- Accès internet pour télécharger les ressources Minecraft et les mods

## Développement / compilation

Pour compiler le projet depuis les sources, il faut généralement :

- CMake 3.25+
- Qt 6.4+
- compilateur compatible (GCC, Clang, MSVC)
- dépendances du projet (voir `CMakeLists.txt` et les sous-dossiers du projet)

### Exemple de build

```bash
cmake -S . -B build
cmake --build build
```

Le projet utilise plusieurs bibliothèques internes et externes, notamment pour :

- Qt
- libarchive
- zlib
- toml++
- cmark
- libqrencode
- support Minecraft et gestion des instances

## Structure du dépôt

```text
.
├── buildconfig/          # Configuration de build
├── cmake/                # Modules CMake
├── docs/                 # Documentation
├── launcher/             # Code principal du launcher
├── libraries/            # Bibliothèques tierces et internes
├── nix/                  # Packaging Nix
├── program_info/         # Informations et ressources du programme
├── scripts/              # Scripts utilitaires
├── tests/                # Tests
├── CMakeLists.txt        # Configuration générale du projet
├── README.md             # Documentation principale
├── LICENSE               # Licence du projet
├── CHANGELOG.md          # Journal des changements
├── flake.nix             # Configuration Nix
├── vcpkg.json            # Dépendances vcpkg
└── ...
```

## Comparaison

| Fonctionnalité | Rubis Launcher | TLauncher | SKlauncher |
|---|---|---|---|
| Open source | Oui | Non | Non |
| Sans virus | Oui | Non | ? |
| Instances multiples | Oui | Non | Oui |
| Mods auto-installés | Oui | Non | Non |
| Serveur intégré | Oui | Non | Non |
| Tunnel public | Oui | Non | Non |

## Mots-clés

launcher minecraft crack gratuit, launcher minecraft sans virus, launcher minecraft premium crack, meilleur launcher minecraft 2025, alternative tlauncher, launcher minecraft français

## Contribuer

Les contributions sont les bienvenues. Si vous souhaitez participer au projet :

- proposez une amélioration,
- signalez un bug,
- ajoutez une fonctionnalité,
- contribuez à la documentation,
- testez les builds sur plusieurs plateformes.

Merci de garder le code lisible, bien structuré et compatible avec les conventions de projet.

## Licence

Rubis Launcher est distribué sous licence [GPL-3.0](LICENSE).

## Contact et liens

- GitHub : [layanfibw-maker/RubisLauncher](https://github.com/layanfibw-maker/RubisLauncher)
- Site web : [rubislauncher.org](https://rubislauncher.org)
- Discord : [Rejoindre le serveur](https://discord.gg/EAq2s4QMpk)
- Issues : [Signaler un bug](https://github.com/layanfibw-maker/RubisLauncher/issues)

---

Rubis Launcher est un projet open source pour les joueurs qui veulent un launcher Minecraft simple, rapide, moderne et accessible, sans les limites des launchers traditionnels.
