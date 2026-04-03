# ⚡ Elektroprivreda Brojilo (EPBiH Vrijeme)

Jednostavna web aplikacija koja prikazuje trenutno vrijeme i vrijeme na brojilu elektroprivrede, s vizualnim indikatorom jeftine/skupe tarife.

## 📋 Opis

Aplikacija pomaže korisnicima da prate tarifno vrijeme na elektroprivredi BiH. Brojilo elektroprivrede ima odstupanje (offset) od stvarnog vremena, pa ova aplikacija automatski računa i prikazuje:

- **Trenutno vrijeme** — tačno sistemsko vrijeme
- **Vrijeme na satu brojila** — prilagođeno za offset (0h17m ljeti / 1h17m zimi), automatski detektuje ljetno/zimsko računanje vremena (DST)
- **Trenutni dan** — prikaz dana u sedmici

## 🎨 Tarife (vizualni prikaz)

| Boja | Tarifa | Periodi |
|------|--------|---------|
| 🟢 Zelena | Jeftina (niža) tarifa | 13:00–16:00 i 22:00–06:00 |
| 🔴 Crvena | Skupa (viša) tarifa | 06:00–13:00 i 16:00–22:00 |

## 🚀 Pokretanje

Otvorite `index.html` u bilo kojem modernom web pregledniku. Nema potrebe za instalacijom ili serverom.

```
# Ili jednostavno dvaput kliknite na index.html
```

## 🛠️ Tehnologije

- HTML5
- CSS3 (responzivni dizajn)
- Vanilla JavaScript

## 📱 Responzivni dizajn

Aplikacija je optimizirana za mobilne uređaje s velikim, čitljivim fontovima (`8vw`), ali se jednako dobro prikazuje i na desktop ekranima zahvaljujući media query prilagodbi.

## 📄 Licenca

Ovaj projekat je otvorenog koda.
