### Depuis 2017, Google annonce Kotlin reconnu comme langage de base pour Android.

## Qu’est-ce qui différencie le développement desktop du développement mobile ?

| Critère | Développement Desktop 💻 | Développement Mobile 📱 |
| --- | --- | --- |
| **Plateforme** | Windows, macOS, Linux | iOS (Swift), Android (Kotlin/Java), cross-platform (Flutter, React Native) |
| **Affichage** | Écrans larges (1080p, 1440p, 4K) | Petits écrans (5"-7" pour smartphones, 7"-12" pour tablettes) |
| **Navigation** | Souris, clavier | Doigt, gestes, stylet |
| **Fonctions natives** | Accès complet aux ressources système (CPU, GPU, disque, multitâche) | Accès limité et contrôlé au matériel (caméra, capteurs, GPS, Bluetooth) |
| **Mises à jour** | Automatiques, souvent gérées par l’OS | Dépend du store (Google Play, App Store), validation requise |
| **Coût** | Développement généralement moins cher, pas de frais de store, mais potentiellement plus long pour la compatibilité multi-OS | Développement plus cher si natif (iOS + Android séparés), frais pour publier sur l'App Store (99$/an) et Google Play (25$ une fois) |
---

</br>

---

## Quand on crée un projet / application :

### 📌 Développement d’un site web ou d’une application mobile

| Étape | **Desktop 💻** | **Mobile 📱** |
| --- | --- | --- |
| | Définition des besoins et spécifications. | Comprendre les besoins des utilisateurs mobiles. |
| | - Dictionnaire de données.<br>- MCD.<br>- MLD.<br>- Use Cases > Fonctionnalités.<br>- Maquettage UI/UX. | Définition des objectifs et des contraintes spécifiques à la mobilité. |
| | **CI/CD** - Développement  | **UI/UX** - Concevoir UI & Concevoir UX |
| | **CI/CD** - Test Unitaire | Prototype et test utilisateur |
| | **CI/CD** - Test Qualité | Modeliser |
| | Distribution via **installeurs, package managers ou Windows Store**. | Dévelopement |
| | | Tester , déboguer et déployer ( CI / CD )
---

## IDE : Android Studio est spécialisé dans la programmation d'applications mobiles.



---
## Installation :

```bash
# Installation avec APT (Debian/Ubuntu) pour Java
sudo apt update
sudo apt install openjdk-17-jdk kotlin

# Installation avec SDKMAN (Solution recommandée)
curl -s "https://get.sdkman.io" | bash
source "$HOME/.sdkman/bin/sdkman-init.sh"
sdk install kotlin

# Vérification de l'installation
kotlin -version  # Vérifier que Kotlin est bien installé
java -version    # Vérifier que Java est bien installé
```

---

## Commandes pour compiler :

```bash
# Compilation du fichier Kotlin en un JAR exécutable
kotlinc a.kt -include-runtime -d a.jar

# Exécution du JAR avec Java
java -jar a.jar
```
---





