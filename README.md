# Serveur Pixelmon (NeoForge 1.21.1)

Ce depot sert de pense-bete pour installer/reinstaller le serveur, et contient aussi un petit pack de mods **cote client** (dossier `mods/`).

Note importante:
- Le mod Pixelmon (jar universal) et le modpack ne sont pas versionnes ici (fichiers lourds + licences). On utilise le server pack officiel / le modpack officiel.

## Telechargement rapide (mods client)

- ZIP (contient le dossier `mods/`) : https://github.com/blou132/serveur-pixelmon/archive/refs/heads/main.zip

## Versions (serveur)

- Minecraft: `1.21.1`
- Modloader: `NeoForge 21.1.200`
- Pixelmon: `9.3.14`
- Java: `21`

## Mods serveur (stabilite / performance)

Sur le serveur (dans `/opt/minecraft/forge/servers/mods`), on utilise en plus des mods gameplay/worldgen une selection de mods perfs/stabilite:

- ModernFix, Lithium, FerriteCore, Alternate Current
- ServerCore, Saturn, Ksyxis, Noisium, ScalableLux
- Let Me Despawn (+ Almanac), Clumps, Get It Together Drops, Leaves Be Gone (+ Puzzles Lib)
- Structure Layout Optimizer (+ Resourceful Config)
- Chunky (pregeneration), spark (profiling)
- CrashExploitFixer, Achievements Optimizer

Note:
- WonderTrade a ete desactive car il faisait crasher le serveur (probleme de driver SQLite/H2).

## Installation client

Option la plus simple: installer "The Pixelmon Modpack" en version `9.3.14` via un launcher compatible (CurseForge/Prism).

Le client doit etre sur:
- Minecraft `1.21.1`
- NeoForge `21.1.200`
- Pixelmon `9.3.14`

### Installer NeoForge (client) manuellement

Si tu passes par le modpack CurseForge/Prism, NeoForge est generalement installe automatiquement. Sinon:

1. Telecharge l'installer NeoForge (jar) en version `21.1.200` (pour Minecraft `1.21.1`).
2. Lance l'installer:
```bash
java -jar neoforge-21.1.200-installer.jar
```
3. Choisis "Install client".
4. Ouvre le Minecraft Launcher, va dans "Installations", puis lance le profil NeoForge une premiere fois.
5. Ensuite seulement, ajoute les mods dans `.minecraft/mods/`.

### Mods client additionnels (ce depot)

Le dossier `mods/` de ce depot contient des mods QOL (carte, JEI, inventaire, etc.).

1. Installe le modpack Pixelmon `9.3.14` normalement.
2. Copie les `.jar` de `mods/` vers `.minecraft/mods/`.
3. Lance le jeu.

Important:
- Ne copie pas le jar Pixelmon universal dans ce depot (trop lourd + licence). Garde-le via le modpack.
