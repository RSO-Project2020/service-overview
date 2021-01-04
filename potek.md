# Potek dela

## Implementacije mikrostoritev

Upravljanje uporabnikov: deluje

Baza uporabnik - karte: deluje

Matching imam - želim: deluje

Sporočila: deluje

Slike kart: deluje

Podatki o kartah: deluje

## Naloge

**2**: ✔

**3**: ✔

**4**: delno, uporabljajo se okoljske spremenljivke, ne pa konfiguracijski strežnik

**5**: `google-login` je LoadBalancer, MS so NodePort, ClusterIP bi lahko bil matching?

**6**: liveness ja, readiness ja, metrike ne (Monitoring na GCP?)

**7**: ✔

**8**: logging ja, toleranca napak ne

**9**: zunanji API ja, napredni komunikacijski protokoli ne, frontend WIP

**zagovor**:

- 5 primerov z več mikrostoritvami: za zdaj matching: POST/PATCH sample/wish (technically 4?)
- število mikrostoritev: 6/6 (samo 5 naenkrat lahko na ingressu)

## Drugo

- povezava spletnega vmesnika na mikrostoritve
- integracija z Google OAuth
