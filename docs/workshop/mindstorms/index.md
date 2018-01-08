---
layout: workshop
title: Atelier Mindstorms
date: '2017-12-27 09:30:00 CET'
category: Mindstorms
tags: ['Mindstorms', 'Atelier']
published: true
assetsFolder: /ToutEnAlgo/assets/workshop/mindstorms
---

>    Robotique

>    à partir de 9 ans

>    programmation par bloc ou langage de programmation

>    un peu moins de 300€ par robot
    

Le Kit Lego® Mindstorms EV3 est composé de pièces Lego® Technic et de composants robotique : 
- une brique de contrôle, 
- des moteurs, 
- des capteurs 
- et une balise/télécommande infrarouge 

![Kit]({{page.assetsFolder}}/kit-mindstorms.png)

<br>
Le site officiel [Lego® Mindstorms](https://www.lego.com/fr-fr/mindstorms)


---

### Qu'est ce qu'on peut faire avec ?

Le kit Lego® Mindstorms EV3 Home permet de construire des véhicules, des robots, des machines inutiles, des instruments de musique farfelus, des installations artistiques et tout ce que votre imagination trouvera à faire avec des moteurs, des capteurs et une télécommande.

Le kit peut être étendu avec des pièces Lego® Technic et d'autres capteurs. Par exemple, les capteurs fournis avec le kit Lego® Mindstorms EV3 Education comme le capteur ultrason peuvent être achetés à l'unité. Des partenaires vendent également des capteurs compatibles (accéléromètre, capteur de son, capteur de température, ...). A noter, les capteurs de l'ancien modèle ((NXT) sont généralement compatibles.

Avec plus d'expérience, il est possible de participer à différentes compétitions de robots ou aux FLL (First Lego League)

---

### Comment ça marche 

Les programmes sont écrits en utilisant des blocs avec un des logiciels de programmation EV3 téléchargeavble sur le site

![Programme]({{page.assetsFolder}}/mindstorms-programme.png)

C'est un moyen amusant est d'apprendre les bases de la programmation et de la robotique au travers de modèles fournis avec le kit, par la communauté, ou en faisant ses propres expérimentations. 

Il est aussi possible de programmer en C, Python, Java et l'intégrer avec d'autres systèmes électroniques ou de traitement de données. Il faut pour cela installer l'outillage nécessaire sur une carte SD et la placer dans le robot.  

---

### Comment préparer un atelier ?

Le kit est fourni avec des modèles complètement documenté. Ces modèles sont assez longs à construire. Il faut compter une dizaine d'heure pour chaque. 

Pour faire les ateliers de 1 ou 2 heures, on utilise des modèles plus simples et modulables. 

Le but est d'apprendre à programmer et concevoir des mécanismes, pas de monter des legos.  Il est utile d'avoir  des robots déjà montés car le montage d'une base simple prend environ 30 mn. 

Le modèle le plus simple pour commencer un projet est le rover. Il est simple et rapide à monter conçu pour intégrer facilement les divers capteurs.

[![Rover]({{page.assetsFolder}}/rover.png)](rover/index.html) 

[Monter le Rover](rover/index.html) 

Les questions pratiques 
- un mentor par groupe de 4, plus si vous pouvez au début quand les enfants ne maîtrisent pas encore. Il n'est pas nécessaire d'avoir une connaissance approfondie de la programmation ou de la robotique. En revanche, un peu de pratique du Minsdtorms est nécessaire.
- un kit Mindstorms et un ordinateur par groupe, des rallonges
- un espace assez grand avec une table par groupe et beaucoup d'espace au sol dans la salle ou proche pour les déplacements des robots
- n'oubliez pas les questions d'assurance propres à tous les ateliers en dehors du contexte scolaire

---

### Démarrer l'atelier

Pour la programmation par blocs, il faut installer le [logiciel Mindstorms](https://www.lego.com/fr-fr/mindstorms/downloads/download-software). Il est gratuit.

---

### Les tutoriaux et les idées d'atelier

Le tutorial fourni avec le logiciel est assez rudimentaire.
- [Tutorial Lego® officiel](https://www.lego.com/fr-fr/mindstorms/learn-to-program)

Des associations ou des organismes ont fait des tutoriaux plus complets en français :
- [Tutorial EduScol](http://eduscol.education.fr/sti/ressources_techniques/tutoriel-brique-legor-mindstormsr-ev3#description)
- [Tutorial Generation Robot (PDF)](https://www.generationrobots.com/media/ev3_user_guide.pdf)

Vous trouverez plus de ressources en anglais :
- [Tutorial STEM Centric](http://www.stemcentric.com/ev3-tutorial/)
- [Tutorial Lego Engineering](http://www.legoengineering.com/ev3-tutorials-by-students-for-students/)
- [Tutorial FLL Cast](https://www.fllcasts.com/search/ev3+programming)
- [Tutorial Carnegy Mellon Robotics Academy (PDF)](http://education.rec.ri.cmu.edu/wp-content/uploads/2015/03/EV3-teachers-guideWEB.pdf)

---

### Tous les articles du site sur ce thème 

<ul>
  {% for post in site.tags.Mindstorms %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
