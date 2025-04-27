# Variable-Display-Mechanical-Keyboard

This keyboard can change its layout (AZERTY, QWERTY) or language using small screens on each key.

# Florian Bonnet--Galand - ENSEA - 2025

# Le Clavier Reconfigurable

Ce projet s'inscrit dans l'option Maker de deuxième année à l'ENSEA. Il a été réalisé par Florian Bonnet--Galand.

---

#### Petite présentation vidéo du projet :

[![YouTube Video](https://img.youtube.com/vi/67zuaiWLCbI/0.jpg)](https://www.youtube.com/watch?v=67zuaiWLCbI)

---

#### Le PCB

La première étape fut le design d'une PCB, intégrant les switchs Cherry MX RED, une STM32G474RET6, 4 multiplexeurs I2C TCA9548A, ainsi que des connecteurs 4 pins pour les écrans MCOT064032A1V-YI. Toutes les documentations et les fichiers du PCB sont à retrouver sur le GitHub du projet, juste en dessous.

👉 [**Le GitHub du Projet**](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard.git)

| ![Schéma PCB](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/Sch%C3%A9ma_PCB.png?raw=true) | ![Routage PCB](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/Routage_PCB.png?raw=true) |
|:---:|:---:|

Ce premier design a été fait pour accueillir 30 touches, toutes similaires pour plus de modularité et accessoirement pour gagner du temps.

| ![Photo PCB](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/PCB.jpg?raw=true) |
|:---:|

---

#### Les Keycaps

Un autre axe de travail sur lequel il a fallu plancher est celui des Keycaps.  
Il ne suffisait pas d'en trouver des correspondants sur Internet, mais bien de les faire sur mesure afin de les adapter aux écrans et aux switchs.  
Ils ont été imprimés en PLA sur des imprimantes Bambu Lab.

| ![Keycaps1](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/keycaps3.png?raw=true) | ![Keycaps2](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/keycaps4.png?raw=true) |
|:---:|:---:|

| ![Keycaps3](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/keycaps1.png?raw=true) | ![Keycaps4](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/keycaps2.png?raw=true) |
|:---:|:---:|

Ces Keycaps présentent un espace libre pour y placer l'écran, ainsi qu'une ouverture vers le dessous pour faire passer la nappe de connexion.

Au final, le modèle est assez satisfaisant :  
Ils s'adaptent parfaitement, aussi bien à la taille des écrans qui passent bien et surtout aux switchs.  
Les caps ne se retirent pas si facilement, bien que le modèle soit assez variable en fonction de la qualité d'impression.  
De plus, l'enlèvement du support était assez fastidieux et complexe sans endommager les keycaps.

| ![Photo Keycaps 1](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/photos_keycaps.jpg?raw=true) | ![Photo Keycaps 2](https://github.com/FlorianBnGld/Variable-Display-Mechanical-Keyboard/blob/main/Images/photos_keycaps%20(1).jpg?raw=true) |
|:---:|:---:|

---

#### Ce qu'il reste à faire et potentielles améliorations futures

Afin de proposer un réel produit fini :
- Développer une interface utilisateur sur PC pour modifier ce que les touches tapent et ce qui s'affiche sur les écrans. (Actuellement géré par CubeIDE)
- Faire une V2 du PCB avec une alimentation plus viable (par exemple, un port USB au lieu d'un simple port JST).
- Commander des écrans similaires à celui des tests réussis (difficile à obtenir hors AliExpress).
- Créer une box imprimée en 3D ou découpée au laser pour accueillir le PCB (ce qui dépend de nombreux paramètres et n'a pas été réalisé par manque de temps).

---

