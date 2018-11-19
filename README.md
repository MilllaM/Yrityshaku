TEHTÄVÄ:
Tavoitteena on luoda simppeli kyselyliittymä, johon voi kirjoittaa yrityksen nimeä. Kun kentässä on yli 3 merkkiä ja viimeisestä näppäimenpainalluksesta on kulunut 0,5 sekuntia, voi sovellus kysyä sopivia vaihtoehtoja YTJ:n API:lta ja tarjota nämä AJAX-tyylisenä dropdownina käyttäjälle. Käyttäjä valitsee vaihtoehdoista oikean firman, jonka jälkeen sovellus hakee ja näyttää yrityksen tiedot hakukentän alla. API: http://avoindata.prh.fi/ytj.html

Norsu syödään pala kerrallaan, joten tässä käytössä "phased approach", joka etenee kutakuinkin näin:

## step1.html

Perustestaus API-kutsun toimintaan.

## step2.html

Syötteen testaus.

## step3.html

Ajoituksen testaus (syötteen viive >0,5sec).

## step4.html

Ehtojen tarkistus + tietojen haku API:n kautta.

## step5.html

Muualta kopiotua (varastettua) koodia + CSS kokeilu.

## step6.html

dropdownin luonti

## step7.html /Final

Lopullisten tietojen esitys (ja vähän CSS:ää) 
