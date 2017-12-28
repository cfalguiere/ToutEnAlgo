---
layout: post
title: Le robot qui dessine V2
date: '2017-12-27 20:30:00 CET'
category: Blog
tags: ['Mindstorms', 'Demo']
published: true
assetsFolder: /ToutEnAlgo/assets/le-robot-qui-dessine-v2
---

### Le plan de montage

Le robot qui dessine est construit sur une base de rover. Un  moteur annexe est placé dans le rover pour poser/lever le stylo à l'avant.

![Rover Monté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-all.png)

Ce moteur va actionner

![Liner actuator]({{page.assetsFolder}}/0-ensemble/linear-actuator.png)

![Porte-stylo Monté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-all-avec-porte-stylo.png)

Dans la conception il est important que le stylo se trouve entre les roues avant. De cette manière lorsque le robot pivote, le stylo peut dessiner un angle. 

Après plusieurs essai ratés nous avons constaté le robot ne doit pas avoir pas être trop lourd (il emporte la feuille) et ne doit pas avoir trop de poids à l'arrière (il pivote sur la roue folle à l'arrière au lieu de pivoter sur les roues avant)

Le rover va être construit en quatre parties : 

- le support du moteur annexe, 
- le porte-stylo,
- les roues 
- le support de la brique de contrôle.

![Rover Eclaté]({{page.assetsFolder}}/0-ensemble/dessinateurv2-avec-porte-stylo-exploded.png)

