# Notepad++ AppModule pour NVDA

## Description
Cet add-on améliore l'accessibilité de **Notepad++ 32 bits** sous **NVDA**, en apportant des fonctionnalités avancées pour la navigation et l'édition de code Python. Il est conçu pour fonctionner avec **Python 32 bits**, garantissant une compatibilité optimale avec NVDA.

### Fonctionnalités
- Navigation améliorée dans le code Python (déplacements entre fonctions et classes).
- Sélection et suppression rapides des classes et fonctions.
- Exécution directe du code Python dans un terminal.
- Gestion avancée de l'indentation (déplacement et sélection selon le niveau d'indentation).

## Installation
1. Téléchargez le fichier `.nvda-addon`.
2. Ouvrez NVDA et accédez à `Outils > Gérer les extensions`.
3. Cliquez sur `Installer`, sélectionnez le fichier téléchargé et suivez les instructions.

## Utilisation
### Raccourcis Clavier
- **NVDA+F2** : Aller à la fonction suivante.
- **Shift+F2** : Aller à la fonction précédente.
- **F7** : Aller à la classe suivante.
- **Shift+F7** : Aller à la classe précédente.
- **Ctrl+Shift+R** : Sélectionner une classe.
- **Ctrl+R** : Sélectionner une fonction.
- **Ctrl+Shift+Suppr** : Supprimer une classe après confirmation.
- **Ctrl+Suppr** : Supprimer une fonction après confirmation.
- **F5** : Exécuter le code dans un terminal.
- **Alt+Flèche Bas** : Aller au prochain niveau d'indentation.
- **Alt+Flèche Haut** : Aller au niveau d'indentation précédent.
- **Ctrl+Alt+Flèche Bas** : Aller à la ligne indentée suivante.
- **Ctrl+Alt+Flèche Haut** : Aller à la ligne indentée précédente.
- **Shift+Alt+Flèche Bas** : Sélectionner jusqu'au niveau d'indentation suivant.
- **Shift+Alt+Flèche Haut** : Sélectionner jusqu'au niveau d'indentation précédent.
- **Alt+Home** : Aller à la première ligne du niveau d'indentation actuel.
- **Alt+End** : Aller à la dernière ligne du niveau d'indentation actuel.

## Développement
Pour compiler cet add-on à partir du code source :
1. Assurez-vous que **SCons** est installé (`pip install scons`).
2. Naviguez dans le dossier du projet et exécutez :
   ```sh
   scons dist
   ```
3. Le fichier `.nvda-addon` généré pourra être installé directement dans NVDA.

## Licence
Cet add-on est sous licence GPLv2.

