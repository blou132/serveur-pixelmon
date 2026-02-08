# Serveur Pixelmon (NeoForge 1.21.1)

Ce depot sert de pense-bete pour installer/reinstaller le serveur.

Note importante:
- Le mod Pixelmon et le modpack ne sont pas versionnes ici (fichiers lourds + licences). On utilise le server pack officiel.

## Versions (serveur)

- Minecraft: `1.21.1`
- Modloader: `NeoForge 21.1.200`
- Pixelmon: `9.3.14`
- Java: `21`

## Installation serveur (Linux)

1. Telecharge le server pack officiel:
```txt
https://edge.forgecdn.net/files/7454/494/serverpack9314.zip
```

2. Dezippe le contenu dans le dossier du serveur (ex: `/opt/minecraft/forge/servers`).

3. Verifie que `start.sh` est executable:
```bash
chmod +x start.sh
```

4. (Optionnel) Ajuste la RAM dans `variables.txt`:
```txt
JAVA_ARGS="-Xmx10G -Xms10G"
```

5. Lance le serveur:
```bash
./start.sh
```

## Installation client

Option la plus simple: installer "The Pixelmon Modpack" en version `9.3.14` via un launcher compatible (CurseForge/Prism).

Le client doit etre sur:
- Minecraft `1.21.1`
- NeoForge `21.1.200`
- Pixelmon `9.3.14`

