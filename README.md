# lab18

## Objectif

Une fonction `Password()` existe dans l'application Android mais n'est jamais appelée dans le flux normal. L'objectif est de la forcer à s'exécuter avec Frida pour obtenir le mot de passe Firebase, puis récupérer le flag.

##  Étape 1 — Installation de l'APK et vérification ADB

![ADB installation](images/image1.png)

---
## Étape 2 — Analyse statique avec Jadx

### Ouverture de l'APK

![Jadx ouverture APK](images/image2.png)

### Méthode Password() dans MainActivity

![Méthode Password](images/image3.png)

### strings.xml avec configuration Firebase

![strings.xml](images/image4.png)

---

## Étape 3 — Installation de Frida Server

### Upload et lancement sur l'émulateur

![Frida server](images/image5.png)

### Vérification frida-ps -U

![frida-ps](images/image6.png)

---

##  Étape 4 — Script Frida

### Lancement du script

![Frida script](images/image7.png)

### Mot de passe obtenu

![Password result](images/image8.png)

---

---

## Étape 5 — Flag

![Flag](images/image10.png)

---
auteur: FATIMAEZZAHRA ENNASSIRI

