# Carovana 53 - progetto (bozza 25/10/2026)

Sito di **viaggi di gruppo per la fascia 53 in su anni**, ispirato al modello WeRoad: persone che non si conoscono partono insieme con un coordinatore.
Fa parte di una famiglia di tre siti con la stessa struttura: `carovana18` (18-35), `carovana35` (35-53), `carovana53` (53 in su).

## Idea in una riga
Un gruppo di coetanei, un coordinatore che pensa alla logistica, un gruppo WhatsApp prima di partire, condizioni chiare prima di prenotare.

## Tono e partenze di questa fascia
- ritmo comodo, comfort e compagnia; camera singola o doppia.
- Esempi: città d'arte, terme e relax, mare slow, natura facile.

## Come funziona (logica)
1. Si sceglie la partenza (destinazione, mese, tipo di viaggio).
2. Si prenota il posto: pre-iscrizione senza anticipo, poi caparra online.
3. Circa 15 giorni prima il coordinatore crea il gruppo WhatsApp.
4. Si parte: il coordinatore gestisce spostamenti, orari e alloggi.
5. Dopo il viaggio il gruppo resta e si organizzano reunion.

## Pagine previste
Home, Partenze (elenco + filtri), Scheda viaggio, Destinazioni, Coordinatori, Come funziona, Blog/diario di viaggio, Chi siamo, Contatti.

## Fatto
- Repo creata dal template `mistraltemplate1` (IT+EN, colore proprio, shop spento).
- Bozza della home in italiano (`_data/blocks_home.json`): hero, partenze, chi viaggia, come funziona. Blocco "contesto" spento (niente numeri finti).

## Da fare
1. Home in inglese (`_data/i18n/en/blocks_home.json` resta ancora il testo segnaposto del template).
2. Pagina Partenze e schede viaggio di esempio, coordinatori, Chi siamo.
3. Compilare email, whatsapp e contact_endpoint in `_config.yml`.
4. Collegare le altre due fasce con un blocco "Altre fasce d'eta" in home: `carovana18` e `carovana35`.

## Regole
- Solo maggiorenni; niente contenuti per minori.
- NON copiare testi, foto, loghi o nomi di WeRoad: tutto originale nostro. Prezzi, date e partner sono dati demo finche' non ci sono accordi.
- Colori solo da `_data/tema.json`; commit selettivi; pubblicare con `..\pubblica.ps1`.
