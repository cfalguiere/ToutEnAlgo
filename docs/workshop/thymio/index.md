---
layout: workshop
title: Atelier Thymio
date: '2017-01-10 11:30:00 CET'
category: Thymio
tags: ['Thymio', 'Atelier']
published: true
assetsFolder: /ToutEnAlgo/assets/workshop/thymio
---

{% include workshop-icons.ext selected="decouvrir" workshop="Thymio" %}

---

>    Robotique

>    à partir de 4 ans

>    modes préprogrammés, programmation par bloc ou texte

>    environ 150€ par robot


Thymio est un robot conçu pour l'initiation. Il possède plusieurs niveaux d'utilisation
- le mode préprogrammé avec des modes correspondant à différentes activité (le robot suit ce qu'il voit, ou l'évite, ...)
- la programmation visuelle en choisissant des images
- la programmation par blocs
- la programmation en texte avec un langage spécifique

Le robot ne se démonte pas.

![Kit]({{page.assetsFolder}}/thymio2.png)

<br>
Le site officiel [Thymio®](https://www.thymio.org/home-fr:home)


---

### Qu'est ce qu'on peut faire avec ?

Le robot permet de découvrir les interactions avec un robot et l'usage des capteurs.

Avec plus de pratique et le logiciel Aseba, il est possible de programmer le robot avec des outils qui vont du plus simple à un langage de programmation

---

### Comment ça marche

Le robot a différents modes qui peuvent être choisis en utilisant les flèches sur le dessus du robot.
La couleur change selon le mode.
Pour cet usage, il n'est pas nécessaire d'avoir un ordinateur. Les modes fonctionnent en utilisant les flèches du robot.

- [Les modes préprogrammés](https://www.thymio.org/fr:thymiostarting)

En utilisant le logiciel Aseba, il est possible d'écrire des programmes.

- [Des exemples de programmes](https://www.thymio.org/fr:thymio)
- [L'introduction à Aseba](https://www.thymio.org/fr:start)

C'est un moyen amusant est d'apprendre progressivement les bases de la programmation et de la robotique au travers deds exemples.

---

### Comment préparer un atelier ?

Le site de Thymio [Thymio®](https://www.thymio.org/home-fr:home) est assez bien documenté et présente des exemples d'ateliers.

Ces robots sont destinés à des enfants jeunes. Il faut prévoir des activités de 30 minutes environ et chenger d'activité si besoin.

Les questions pratiques
- un mentor par groupe de 4, plus si vous pouvez au début quand les enfants ne maîtrisent pas encore. Il n'est pas nécessaire d'avoir une connaissance approfondie de la programmation ou de la robotique. Il faut connaître un peu le produit et avoir des idées d'animation
- un Thymio, un ordinateur par groupe si on veut programmer, des rallonges
- un espace assez grand avec une table par groupe et beaucoup d'espace au sol dans la salle ou proche pour les déplacements des robots
- n'oubliez pas les questions d'assurance propres à tous les ateliers en dehors du contexte scolaire
- il faut recharger les robots avant les ateliers. Le cable usb est fourni dans le pack.

---

### Démarrer l'atelier de programmation

Pour débuter avec le robot vous pouvez commencer par la description des modes et des ateliers sur chacun des modes

- [Les modes préprogrammés](https://www.thymio.org/fr:thymiostarting)


Pour la programmation, il faut installer le [logiciel Aseba](https://www.thymio.org/fr:start). Il est gratuit.

Les documentations des différents types de programmes se trouvent sur le site de Thymio.

- [L'introduction à Aseba](https://www.thymio.org/fr:start)

---

### Les tutoriaux et les idées d'atelier

Vous pourrez trouver des idées d'atelier sur YouTube.


### Tous les articles du site sur le même thème

<ul>
  {% for post in site.tags.Thymio %}
    {% if post.url %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endif %}
  {% endfor %}
</ul>
