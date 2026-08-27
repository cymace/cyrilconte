---
title: accueil
layout: accueil
---

## Prochaines dates

- `26 septembre`
*[contes tirés du sac](spectacle/contes-et-chansons-tirees-sac)  chez l'habitant.e à Braspart*

- `10 octobre`
*contes de bretagne à Pouldreuzic, dans le cadre de son [festival de contes](https://festivalduconte.sitew.fr/)*

- `23 octobre`
*[contes tirés du sac](spectacle/contes-et-chansons-tirees-sac)  dans le cadre d'un séjour vacances  à Primelin*


[-> voir toutes les dates ](dates) 

<br>

## Souvenirs
          
<ul>

  {% for date in site.dates %}
    {% include date.html past='true'%}
  {% endfor %}
</ul>
