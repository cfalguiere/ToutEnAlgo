---
layout: post
title: Le robot qui dessine V2
date: '2017-12-27 20:30:00 CET'
category: Blog
tags: ['Mindstorms', 'Demo']
published: true
assetsFolder: /ToutEnAlgo/assets/le-robot-qui-dessine-v2
---

### Les principes de fonctionnement

Le robot qui dessine est construit sur une base de rover. Un petit moteur annexe est placé dans le rover pour poser/lever le stylo.

![Rover Monté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-all.png)

Ce moteur va actionner un bras mobile à l'avant. Lorsque le bras est en position basse le robot peut écrire. Quand il est en position haute le stylo ne touche plus la feuille.

Dans la conception il est important que le stylo se trouve entre les roues avant. De cette manière lorsque le robot pivote, le stylo peut dessiner un angle. 

![Porte-stylo Monté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-all-avec-porte-stylo.png)

Comme le moteur tourne sur un plan horizontal et que l'on veut convertir ce mouvement en déplacement vertical linéaire on va utiliser deux mécanismes.

Les deux engrenages (le petit jaune et le grand noir) font tourner un axe qui est perpendiculaire au moteur.

![Linear actuator 1]({{page.assetsFolder}}/0-ensemble/linear-actuator-1.png)

Le bras à l'avant convertit la rotation en mouvement de haut en bas. Lorsque l'axe tourne les barres di bas tournent avec l'axe. Le reste des barres suit le mouvement.

![Linear actuator 2]({{page.assetsFolder}}/0-ensemble/linear-actuator-2.png)

Après plusieurs essai ratés nous avons constaté le robot ne doit pas avoir pas être trop lourd (il emporte la feuille de papier) et ne doit pas avoir trop de poids à l'arrière (il pivote sur la roue folle à l'arrière au lieu de pivoter sur les roues avant)


### Le plan de montage

Le rover va être construit en quatre parties : 

- le support du moteur annexe, 
- le porte-stylo,
- les roues 
- le support de la brique de contrôle.

![Rover Eclaté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-avec-porte-stylo-exploded.png)

