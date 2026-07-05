# Taquin

Ce dépôt contient deux applications Flutter indépendantes (chacune avec son propre `pubspec.yaml`) :

- `exercices/` : les exercices du TP (Exercice 1, 2, 4, 5, 5b, 5c, 6 et 7), accessibles depuis un menu commun.
- `taquin/` : le jeu du taquin (15-puzzle) qui constitue le livrable final du TP.

## Attention à la version de flutter !
Nous avons codé l'application avec flutter en mode master, ne pas oublier de vérifier le mode de son flutter avant de lancer le code, pour cela il faut cette commande :
```bash
flutter channel master
```
De plus, nous avons codé cette application avec la version 3.30 de flutter donc pour qu'elle puisse se lancer, verifier votre version :
```bash
flutter --version
```
Si cette version est différente de 3.30 n'hésitez pas à upgrade sous peine de ne pas pouvoir run l'application:
```bash
flutter upgrade
```

## Lancement de l'application
Pour lancer l'application, vous devez ouvrir un terminal et lancer les commandes suivantes :

### Cloner le repository github
```bash
git clone https://github.com/Gytan1/Taquin.git
```
### Rentrer dans le dossier

```bash
cd Taquin
```

### Si vous voulez voir les exercices
```bash
cd exercices
```

### Si vous voulez lancer directement le jeu de taquin
```bash
cd taquin
```

### Installer les dépendances
Une fois dans le dossier choisi (`exercices` ou `taquin`), installez les paquets Flutter/Dart nécessaires :
```bash
flutter pub get
```

### Lancer l'application
```bash
flutter run
```
