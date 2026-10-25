# Salmer og sanger for barn og ungdom

En sangbok som webapp, med de 159 salmene og sangene fra heftet *Salmer og sanger for barn og ungdom* (1995) og Tysfjordsangen. Den kjøres fra GitHub Pages og virker i moderne nettlesere på mobil, nettbrett og datamaskin. Den kan installeres som en app (PWA) og brukes helt uten nett.

**Åpne sangboken:** https://salmer-og-sanger.github.io/

## Funksjoner

- **Søk på nummer:** skriv f.eks. `49` og trykk Enter, så åpnes sangen.
- **Søk på ord:** skriv ett eller flere ord, f.eks. `nåde` eller `graven brast`. Treffene viser hvilket vers ordet står i, og ordene er uthevet i sangen. Svensk ö/ä finnes også når du skriver ø/æ.
- **Hele sangen** vises med nummererte vers, omkved (Kor) markert og repetisjonstegn (:/:).
- **Bla** til forrige og neste sang, og velg **tekststørrelse** (A / A).
- **Innhold** etter seksjon: Barn, Salmer og sanger, 17. mai, Advent, Jul, Påske, Pinse, Konfirmasjon og Tysfjordsangen.
- **Sist åpnet** blir husket på enheten.
- **Direkte lenke** til en sang: https://salmer-og-sanger.github.io/#49
- **Offline:** etter første besøk kan sangboken brukes uten nett.

## Bruk og installering

| Enhet | Slik installerer du |
|---|---|
| **iPhone / iPad** | Åpne adressen i Safari, trykk **Del** (firkant med pil opp) og velg **Legg til på Hjem-skjerm** |
| **Android** | Åpne adressen i Chrome, åpne menyen **⋮** og velg **Installer app** eller **Legg til på startsiden** |
| **Mac / Windows / Linux** | Åpne adressen i Chrome eller Edge og klikk installer-ikonet i adressefeltet. I Safari på Mac: **Fil → Legg til i Dock** |

Åpne sangboken én gang mens du har nett. Etter det virker den offline.

## Om filene

Appen bygges med et Python-skript fra PDF-utgaven av heftet. Alt (tekst, skrift, kode) ligger i `index.html`, uten eksterne avhengigheter. Skrifttypen er Source Sans 3 (SIL Open Font License).
