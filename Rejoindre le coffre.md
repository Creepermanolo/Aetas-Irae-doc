# Rejoindre le coffre (pas-à-pas pour un nouveau PC)

## 1. Installer Git
Télécharge Git pour Windows sur **git-scm.com**, puis installe-le avec les options par défaut.

## 2. Récupérer le coffre
Ouvre PowerShell et tape :
```powershell
git clone https://github.com/Creepermanolo/Aetas-Irae-doc.git C:\Coffre-Partage
```
(Une fenêtre de connexion GitHub peut s'ouvrir : connecte-toi.)

Indique à Git qui tu es (une seule fois) :
```powershell
git -C C:\Coffre-Partage config user.name "TonPseudo"
git -C C:\Coffre-Partage config user.email "ton-email-github@exemple.com"
```

## 3. Ouvrir le coffre dans Obsidian
Obsidian → **Ouvrir un dossier comme coffre** → `C:\Coffre-Partage`.

## 4. Installer le plugin Git
Paramètres → **Plugins communautaires** → Activer → **Parcourir** → cherche « Git » (auteur : Vinzent) → **Installer** → **Activer**.

Les réglages de synchro sont déjà dans le coffre (toutes les 10 min + au démarrage).

## 5. Vérifier
`Ctrl+P` → **Git: Commit-and-sync**. S'il n'y a pas d'erreur, c'est bon.

Voir aussi [[Bienvenue]] pour les règles anti-conflits.
