# Tutorial GIT pour la section INF ETML
## 1. Mise en place
### 1.1 Créer un compte sur la plateform [GITHUB](www.github.com)
### 1.2 Télécharger [GIT portable](https://github.com/git-for-windows/git/releases/download/v2.8.3.windows.1/PortableGit-2.8.3-64-bit.7z.exe)
* Décompresser l'archive
* Lancer `gitbash.exe`

### 1.3 Cloner le [depôt](https://github.com/diurnambule/fileDev)
    git clone https://github.com/diurnambule/fileDev
## 2. Modification d'un fichier
### 2.1 Ouvrir le fichier fileDev\Hello.txt
### 2.2 Ajouter une ligne Hello XXX (et sauvegarder)
### 2.3 Valider les changement
    cd fileDev; git commit Hello.txt -m "ajout de mon nom"
### 3. Reporter les modifications sur le dépôt central
    git push
*En cas de problème (erreur 403) c'est que je dois vous autoriser à pusher sur le dépôt et pour cela j'ai besoin de votre login github*
### 4. Vérifier sur la [plateforme](https://github.com/diurnambule/fileDev/blob/master/Hello.txt) si le fichier contient bien votre nom
