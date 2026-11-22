# Bienvenue dans le coffre partagé

Ce coffre est synchronisé entre nous deux via **GitHub** et le plugin **Obsidian Git**.

## Comment ça marche
- Le plugin **récupère** (pull) les modifs de l'autre au démarrage d'Obsidian, puis toutes les 10 minutes.
- Il **enregistre et envoie** (commit + push) tes modifs toutes les 10 minutes.
- Pour forcer une synchro tout de suite : `Ctrl+P` → **Git: Commit-and-sync**.

## Règles d'or pour éviter les conflits
1. Fais une synchro (`Ctrl+P` → *Git: Pull*) **avant** de commencer à bosser.
2. Évitez d'éditer **la même note en même temps**.
3. Avant de fermer Obsidian : `Ctrl+P` → *Git: Commit-and-sync*.
4. Si un conflit apparaît, le fichier contient des marqueurs `<<<<<<<`, `=======`, `>>>>>>>` : garde le bon texte, supprime les marqueurs, puis resynchronise.

## Rangement
| Dossier | Usage |
|---|---|
| `00 - Boîte de réception` | Notes rapides, à trier plus tard |
| `01 - Notes` | Notes permanentes |
| `02 - Projets` | Un sous-dossier par projet |
| `Modèles` | Modèles de notes (`Ctrl+P` → *Insérer un modèle*) |
| `Pièces jointes` | Images et fichiers collés (rangés automatiquement) |

> [!warning] Fichiers lourds
> GitHub refuse les fichiers de plus de 100 Mo, et un dépôt trop gros devient lent. Évitez d'y mettre des vidéos ou des gros PDF.
