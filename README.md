## TALEBROOK ROLEPLAY - ÚTMUTATÓ

Ez a Github projekt a Talebrook RedM játékszerver közösségének a szerverútmutatójának automatikus, felhőből történő adatszolgáltatása miatt jött létre.

Weboldalak, ahonnan lekérhetőek illusztrációk a menüpontokhoz: 
- https://www.rockstargames.com/reddeadredemption2/screens

## Új guide menü és szövegrörzs létrehozása

1. [primary.json](https://github.com/talebrook/tbrp_guides/blob/main/categories/primary.json) fájl konfigurálása

# Új elem felvételére példa:
```
      {
        "title"       : "ÚJ VAGY A SZERVEREN?",
        "desc"        : "Olvasd el a részletes útmutatót, majd berülj el a többi kategóriában!",
        "pict"        : "https://rockstargames.su/wp-content/uploads/2020/08/51a2d7a2c56839df54a30bcc24e3c021220760ee.jpg",
        "id_associed" : 1
      },
```

2. [html fájlok](https://github.com/talebrook/tbrp_guides/tree/main/guides) létrehozása

# Adatok és jelentései:

Youtube link felépítése: `https://www.youtube-nocookie.com/embed/<VIDEO_AZONOSITO>?controls=0'`

title: `Nem szükséges kitölteni, de általában a videó címe lehet.`

```
<iframe class='mb-2' width='100%' height='315' 
src='https://www.youtube-nocookie.com/embed/VXusKSzV2as?controls=0' 
title='Talebrook Intro #1' 
frameborder='0' allow='accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture' allowfullscreen></iframe>
```

# Szövegtörzs minta és magyarázat:

- Piros betűtípushoz használd ezt a struktúrát: `<b class='text-danger'> SZÖVEG </b>`
- Sortöréshez használd ezt a kódot: `<br>`

# Példa:
```
<b class='text-danger'>Előszöris köszöntelek itt közöttünk! </b> <br><br> 
Most érkeztél a városba, idegen? A Talebrook nem egy sima szerver, hanem élő vadnyugati világ. 
Mielőtt nyeregbe pattansz, nézz körül az útmutatók között: megtalálod, hogyan működnek a boltok, a munkák, a túlélés, a törvény és az alvilág. 
Kattints végig a kategóriákat és gyűjts be minden információt a kezdéshez: 'A kezdet', 'A túlélés alapjai', 'Banditák és veszélyek', 
'Tárgyak, tárolás és a ló szerepe', 'Szállás és pihenés', 'Orvosok és gyógyulás', továbbá kezdő tippek, szabályok, pénzkereset, frakciók, bizniszek és sok más egyedi rendszerek várnak rád! <br><br> 
Minél többet tudsz, annál mélyebb szerepjáték vár rád!
```

# Fejlesztők
- Szileni
