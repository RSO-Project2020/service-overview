# Za naredit

## /mycards

- pod `samples` isto še za `wishes` (če zamenjaš `/v1/samples` na `/v1/wishes` bi moglo delat)
- naslova nad `samples` in `wishes` (lahko kar h1, glej "Covid 19 daily stats for Slovenia:")
- polja za vnos novih samplov in wish-ov (glej pošiljanje sporočil)
  - `curl -X POST "https://api.cardmatching.ovh/v1/samples" -H  "accept: application/json" -H "Authorization: Bearer $TOKEN" -d "{\"user_id\":2,\"card_id\":1,\"state\":\"njoh\",\"wts\":true}"`
  - `curl -X POST "https://api.cardmatching.ovh/v1/samples" -H  "accept: application/json" -H "Authorization: Bearer $TOKEN" -d "{\"user_id\":2,\"card_id\":1}"`

## /allcards

- kliči `curl -X GET "https://api.cardmatching.ovh/v1/card-images" -H "Authorization: Bearer $TOKEN"`
- dobiš seznam objektov o slikah
- vsako prikažeš v svojem okvirčku
  - slika je podana kot povezava v "url"
  - ime in serijo potegneš iz `/v1/cards`

# Opcionalno

- Google login

## /messages

- spremeni CSS, da se malo lepše vidi

## /home

- `Total cards` in `Unread messages` naj izpišeta actual število, `New matches` za odstranit
