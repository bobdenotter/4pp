4pp
===

4PP database - plaatsnamen, postcodes, geolocatie (latitude x longitude)
---------------------------------

Deze 4PP (4-cijferige postcodes) tabel ontsluit vrije geografische gegevens in Nederland.
Plaatsen, postcodes, netnummers en geo-coördinaten (lengtegraad / breedtegraad)
zijn opgenomen als afzonderlijke rijen.

De tabel is beschikbaar als (mysql) `.sql` en generiek `.csv` bestand.

Deze database / tabel is samengesteld, omdat de oude versie op
http://kvdb.net/projects/6pp niet meer beschikbaar is. In tegenstelling tot de
oorsronkelijke tabel bevat deze versie betere geo-locatie. Zo zitten niet meer alle
postcodes in Den Haag op hetzelfe coördinaat, maar zijn ze verschillend. Zie bijv:

Oud:

```
postcode   woonplaats     latitude   longitude
2511       Den Haag       52.0767    4.2986
2512       Den Haag       52.0767    4.2986
2513       Den Haag       52.0767    4.2986
2514       Den Haag       52.0767    4.2986
2515       Den Haag       52.0767    4.2986
2516       Den Haag       52.0767    4.2986
2517       Den Haag       52.0767    4.2986
2518       Den Haag       52.0767    4.2986
````

Nieuw:

```
postcode   woonplaats     latitude       longitude
2511       Den Haag       52.0790863     4.3190482
2512       Den Haag       52.0742791     4.3052854
2513       Den Haag       52.0797955     4.299635
2514       Den Haag       52.084722      4.3101618
2515       Den Haag       52.0711662     4.3178146
2516       Den Haag       52.0663158     4.3414621
2517       Den Haag       52.0895671     4.2865074
2518       Den Haag       52.0801488     4.2899304
```

Ben je op zoek naar een 6pp database (dus, alle combinaties van 4 cijfers plus 2 letters), kijk dan hier: http://www.postcodedata.nl/download/

