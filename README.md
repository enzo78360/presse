# Presse

**L'historique du presse-papiers qui manque à macOS**, dans la barre des menus.

Tu copies un lien, puis un texte, puis un autre… et le premier est perdu. Avec Presse, tes 50 dernières copies restent à portée de main.

- `⌃⌘V` n'importe où ouvre l'historique, puis `1` à `9` pour recopier un élément.
- **⌥ clic** sur un élément pour l'**épingler** (adresse, IBAN, signature… toujours en haut, jamais effacé).
- **Respecte tes mots de passe** : les copies marquées comme confidentielles par 1Password, Bitwarden, le Trousseau, etc. ne sont jamais enregistrées.
- **Pause** pour arrêter l'enregistrement le temps de copier quelque chose de sensible.
- Historique conservé entre les redémarrages, dans un fichier lisible par toi seul (`~/Library/Application Support/Presse`).
- Option « Ouvrir au démarrage ».
- Aucune connexion réseau, aucune dépendance, ~200 lignes de Swift.

## Installer

Il faut les outils de développement d'Apple (`xcode-select --install` si ce n'est pas déjà fait).

```bash
./build.sh --install
```

L'app est compilée, copiée dans `/Applications` et lancée. Une icône de presse-papiers apparaît dans la barre des menus.

## Désinstaller

Quitte Presse depuis son menu, puis supprime `/Applications/Presse.app` et `~/Library/Application Support/Presse`.

## Licence

MIT
