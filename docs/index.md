
{% include header.ext %}

<h1>
Nouveaux articles
</h1>

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

# Articles

[![Rover](blog/images/rover.png)](workshops/mindstorms/rover)
[![Concepteur](blog/images/concepteur.png)](workshops/mindstorms/concepteur)
[![Smiley](blog/images/robot-qui-dessine.png)](workshops/mindstorms/robot-qui-dessine/smiley.html)


## Les ateliers

[![Mindstorms](images/mindstorms-200-200.jpeg)](workshops/mindstorms)
[![Arduino](images/arduino-200-200.jpeg)](workshops/arduino)
[![Esplora](images/esplora-200-200.jpeg)](workshops/esplora)
[![Processing](images/processing-200-200.jpeg)](workshops/processing)


