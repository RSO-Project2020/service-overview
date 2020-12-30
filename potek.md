# Potek dela

## Implementacije mikrostoritev

Upravljanje uporabnikov: deluje

Baza uporabnik - karte: deluje

Matching imam - želim: ni implementirana

Sporočila: deluje

Slike kart: ni implementirana

Podatki o kartah: deluje

## Naloge

**2**: ✔

**3**: ✔

**4**: delno, uporabljajo se okoljske spremenljivke, ne pa konfiguracijski strežnik

**5**: `google-login` je LoadBalancer, MS so NodePort, ClusterIP nimamo, ker ni internih storitev

**6**: liveness ja, readiness ja, metrike ne (Monitoring na GCP?)

**7**: ✔

**8**: logging je že v google cloud, kako uporabiti? toleranca napak ne

**9**: zunanji API ja, napredni komunikacijski protokoli ne, frontend WIP

**zagovor**:

- 5 primerov z več mikrostoritvami: ne
- število mikrostoritev: 4/6

## Drugo

- povezava spletnega vmesnika na mikrostoritve
- integracija z Google OAuth
