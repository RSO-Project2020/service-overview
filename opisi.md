# Opisi mikrostoritev

## Upravljanje uporabnikov

Skrbi za hrambo podatkov o uporabnikih in uporabniških računih.

- avtentikacija (prijava v vmesnik?)
- hramba podatkov o računu (uporabniško ime, notranji ID, mail, geslo?)
- spreminjanje podatkov o računu

## Baza uporabnik - karte

Hrani podatke o tem, kateri uporabniki imajo katere karte.

- vnesi nov podatek o uporabniku in karti
- za ID uporabnika vrni seznam kart
- za ID karte vrni seznam uporabnikov, ki imajo karto
- za ID karte vrni seznam uporabnikov, ki želijo karto

## Matching imam - želim

Posluša nove vnose v bazo, tvori matche med uporabniki.

- poslušanje vnosov
- iskanje matchev imam - želim
- obveščanje uporabnikov o matchu

## Sporočila

Omogoča tekstovno komunikacijo med uporabniki.

- pošiljanje novih sporočil
- hramba sporočil
- označevanje prebranih/neprebranih sporočil
- _opcionalno:_ pošiljanje obvestil prek elektronske pošte

## Določanje vrednosti kart

Zbira in hrani tržne vrednosti kart.

- za ID karte vrni vrednost ali zgodovino vrednosti
- _opcionalno:_ zapiši transakcijo v zgodovino

## Podatki o kartah

Za vsak primerek karte hrani podatke o primerku.

- vnos in urejanje podatkov o primerku (ID karte, starost, stanje, ...)
- _opcionalno:_ hramba povezave do slike primerka

# Opcionalne mikrostoritve

## Obveščanje po elektronski pošti

Posluša za novo sporočilo, pošlje obvestilo prejemniku po elektronski pošti.

## Hramba slik

Hrani slike kart.
_Opcionalno:_ Omogoča uporabnikom nalaganje slik lastnih primerkov kart.
