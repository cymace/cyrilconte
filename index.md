---
title: accueil
layout: accueil
---

## Prochaines dates

- `10 octobre`
*contes de bretagne à Pouldreuzic, dans le cadre de son [festival de contes](https://festivalduconte.sitew.fr/)*

- `23 octobre`
*[contes tirés du sac](spectacle/contes-et-chansons-tirees-sac)  dans le cadre d'un séjour vacances  à Primelin*

- `30 octobre`
*[contes mortels](spectacle/contes-mortels)  au café SuperFlux à Quimper*


[-> voir toutes les dates ](dates) 

<br>

## Souvenirs
          
<ul>

  {% for date in site.dates %}
    {% include date.html past='true'%}
  {% endfor %}
</ul>
