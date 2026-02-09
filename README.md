# Serveur Pixelmon (NeoForge 1.21.1)

Ce depot contient les **mods cote client** (dossier `mods/`) et un ZIP pret a telecharger.

## Adresse du serveur

- `90.59.218.80:25565`

## Telechargement (mods client)

1. ZIP des mods additionnels (28 mods, sans Pixelmon):
   https://github.com/blou132/serveur-pixelmon/raw/main/client-mods.zip

2. Pixelmon `9.3.14` (jar universal) doit etre telecharge a part depuis le site officiel Pixelmon.
   Important: Pixelmon n'est pas inclus dans ce depot (fichier tres lourd + regles de distribution).
   Site officiel: https://reforged.gg/

Au final, ton dossier `.minecraft/mods/` doit contenir 29 mods:
- 28 jars venant de `client-mods.zip`
- + `Pixelmon-1.21.1-9.3.14-universal.jar`

## Versions

- Minecraft: `1.21.1`
- NeoForge: `21.1.200`
- Java: `21`
- Pixelmon: `9.3.14`

## Installation (client)

1. Installe Minecraft Java `1.21.1`.
2. Installe NeoForge `21.1.200` (installer -> "Install client").
3. Lance Minecraft avec le profil NeoForge une premiere fois (pour creer `.minecraft/mods/`).
4. Ajoute `Pixelmon-1.21.1-9.3.14-universal.jar` dans `.minecraft/mods/`.
5. Dezippe `client-mods.zip` dans `.minecraft/mods/` (ne supprime pas Pixelmon).
6. Lance le jeu.

## RAM (client)

Si tu as des crash `OutOfMemoryError: Java heap space`, augmente la RAM dans le launcher (ex: `-Xmx6G` ou `-Xmx8G`).
