---
title: accueil
layout: accueil
---

## Prochaines dates

- `19 août`
*[balade contée](spectacle/balade-contee)  à la pointe du Millier  
rendez-vous au parking de la poiunte du Millier un peu avant 20h  
réservation via l['Office de tourisme d'Audierne](https://www.capsizuntourisme.fr/) ou l'association [la Obra](http://https://laobra.bzh/)*

- `26 septembre`
*[contes tirés du sac](spectacle/contes-et-chansons-tirees-sac)  chez l'habitant.e à Braspart*

- `10 octobre`
*contes de bretagne à Pouldreuzic, dans le cadre de son [festival de contes](https://festivalduconte.sitew.fr/)*

- `23 octobre`
*[contes tirés du sac](spectacle/contes-et-chansons-tirees-sac)  dans le cadre d'un séjour vacances  à Primelin*

## Souvenirs
          
<ul>

  {% for date in site.dates %}
    {% include date.html past='true'%}
  {% endfor %}
</ul>
