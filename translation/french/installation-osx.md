# OS X AIDE INSTALLATION

## NOTE

Si vous avez [homebrew](https://brew.sh) installé, vous pouvez facilement installer Go comme ceci:

```
# si vous n'avez pas git d'installé, installé le comme ceci:
brew install git

# puis installer go
brew install go

# ajouter un chemin GOBIN à votre PATH dans ~/.bash_profile
export PATH=${HOME}/go/bin:$PATH
```

## 1- Installer l’éditeur de code Visual Studio

1. Installez-le, mais ne l’ouvrez pas encore.
2. Allez à : [https://code.visualstudio.com](https://code.visualstudio.com)
3. Sélectionnez OS X (Mac) et commencez le téléchargement
4. Décompressez le fichier téléchargé et déplacez-le dans votre répertoire ~ /Applications.

## 2- Installer Git

1. Saisissez et exécutez l’installateur. Allez à : [https://git-scm.com/downloads](https://git-scm.com/downloads)
2. Sélectionnez VSCode comme éditeur par défaut

## 3- Installation du lancement

1. Allez à [https://golang.org/dl](https://golang.org/dl)
2. Sélectionnez OS X (Mac)
3. Démarrer l’installateur

## 4- Configurer VS Code

1. Ouvrez VS Code ; à partir de l’onglet extensions à gauche, recherchez "go" et installez-le
2. Fermez complètement VS Code et ouvrez-le à nouveau

3. Accédez au menu Affichage ; sélectionnez **Palette de commandes**
    1. Ou appuyez simplement sur `cmd+shift+p`.
    2. Tapez `go install`.
    3. Sélectionnez _"Go: Installation/Mise à jour"_
    4. Cochez toutes les cases

4. Après avoir terminé, ouvrez à nouveau la **palette de commandes**
    1. Type: `shell`
    2. Sélectionnez: _"Installer 'code' commande dans le PATH"_
        1. **REMARQUE:** Vous n’avez pas à le faire si vous utilisez Windows.

## C’est tout! Amusez-vous! 🤩

<div style="page-break-after: always;"></div>

> Pour d’autres tutoriels : [https://blog.learngoprogramming.com](https://blog.learngoprogramming.com)
>
> Copyright © 2018 Inanc Gumus
>
> Cours de programmation Learn Go
>
> [Cliquez ici pour lire la licence. ](https://creativecommons.org/licenses/by-nc-sa/4.0/)