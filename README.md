# Usynlig Nynorsk Oversetter
Et enkelt Python skript som oversetter utklippstavlen din til Nynorsk. Fungerer ideelt med AutoHotKey slik at man kan aktivere skriptet ved et enkelt tastetrykk. Skriptet sender API call til apertium.org som returnerer oversatt tekst. Dermed er man avhengig av åpent nett.
## Installasjon og Bruk
- Last ned [filene.](https://github.com/cheval-constipe/Usynlig-Nynorsk-Oversetter/archive/refs/tags/v2.0.zip)

- Sørg for at du har den nyeste versjonen av [Python 3](https://www.python.org/downloads/) (Husk å velge "Add Python to PATH").

- Vi bruker følgende eksterne pakker. Åpne et terminalvindu og installer disse:
```
python -m pip install pyperclip
python -m pip install requests
```
Du kan nå kjøre `script.py`. Når skriptet kjører dukker det opp et svart terminalvindu som lukker seg igjen etter et øyeblikk. Da er utklippstavlen din oversatt (eller noe har gått galt). Prøv selv! Apertium markerer ord som ikke kan oversettes med * . Se gjennom oversettelsen etter disse før du leverer.

**OBS!** Ved å bruke oversetteren deler du innholdet i utklippstavlen med Apertium.

### Med AutoHotKey
Man kan kjøre skriptet ved et tastetrykk med [AutoHotKey](https://www.autohotkey.com).
- Installer programmet
- Last ned [denne filen](https://github.com/cheval-constipe/Usynlig-Nynorsk-Oversetter/blob/main/oversett.ahk) og plasser i samme mappe som Python-skriptet.
- Kjør med AutoHotKey.

Du skal nå kunne starte skriptet med Home knappen. Du kan endre `Home` til hvilken tast du ønsker. Du kan finne en liste med forskjellige taster [her](https://www.autohotkey.com/docs/KeyList.htm).
