# GIS Italia - Documentazione Risorse Territoriali

## Struttura Repository
```
/gisitalia/
├── administrative/       # Dati amministrativi
│   ├── national/        # Fonti nazionali (ISTAT, etc)
│   └── regional/        # Geoportali regionali
├── demographic/         # Dati demografici
│   └── census/         # Dati censimenti
├── environmental/      # Dati ambientali
└── infrastructure/     # Dati infrastrutture
```

## Standard Dataset
Ogni risorsa deve includere:
- **Fonte**: Organizzazione/Ente responsabile
- **Affidabilità**: Bassa/Media/Alta
- **Aggiornamento**: Frequenza
- **Licenza**: Tipo licenza
- **Formato**: Formati disponibili
- **Sistema**: Sistema di riferimento

## Convenzioni
- File in formato Markdown
- Nome file in minuscolo
- Cartelle per categoria
- README in ogni cartella
- Collegamenti verificati

## Contribuire
Vedere [CONTRIBUTING.md](CONTRIBUTING.md) per le linee guida.

## 🔍 Indice delle Risorse

### Fonti Nazionali Ufficiali

- **[ISTAT](./administrative/istat.md)**
  - Confini amministrativi
  - Dati demografici e censimenti
  - [Affidabilità: Alta] [Aggiornamento: Annuale]

- **[Geoportale Nazionale](./infrastructure/geoportale.md)**
  - Cartografia di base
  - Ortofoto
  - DTM e DSM nazionali
  - [Affidabilità: Alta] [Aggiornamento: Variabile]

- **[INGV](./environmental/ingv.md)**
  - Dati sismici
  - Dati vulcanologici
  - [Affidabilità: Alta] [Aggiornamento: Continuo]

- **[ISPRA](./environmental/ispra.md)**
  - Geologia
  - Rischio idrogeologico
  - Consumo di suolo
  - [Affidabilità: Alta] [Aggiornamento: Variabile]

### Geoportali Regionali

- **[Geoportale Lombardia](./administrative/lombardia.md)**
- **[Geoportale Piemonte](./administrative/piemonte.md)**
- **[Geoportale Emilia-Romagna](./administrative/emilia-romagna.md)**
// ...altri geoportali regionali...

### Dataset Open e Collaborativi

- **[OpenStreetMap Italia](./infrastructure/osm.md)**
- **[Copernicus Services](./environmental/copernicus.md)**
- **[CORINE Land Cover](./environmental/corine.md)**

Consulta le directory specifiche per i dettagli tecnici di ogni fonte.

## 📊 Valutazione Dataset

Ogni dataset è valutato secondo i seguenti criteri:
- **Affidabilità**: Bassa | Media | Alta
- **Completezza**: Parziale | Buona | Completa
- **Aggiornamento**: Frequenza di aggiornamento
- **Formato**: Formati disponibili
- **Licenza**: Tipo di licenza

## 📊 Valutazione Standard Dataset

### Livelli di Affidabilità
- **Alta**: Fonti ufficiali, dati validati
- **Media**: Fonti verificabili, aggiornamento regolare
- **Bassa**: Fonti non verificate o datate

### Livelli di Completezza
- **Completa**: Copertura nazionale totale
- **Buona**: Copertura > 80%
- **Parziale**: Copertura < 80%

### Frequenze di Aggiornamento
- **Continuo**: Aggiornamento in tempo reale
- **Periodico**: Aggiornamento programmato
- **Statico**: Dato non aggiornato

## 📑 Licenze Dataset

### Creative Commons Attribution 4.0 (CC BY 4.0)
- Agenzia delle Entrate (Cartografia Catastale)
- TINITALY (Modello Digitale di Elevazione)
- Alcune regioni italiane

### Open Database License (ODbL)
- OpenStreetMap Italia
- NextGIS Data
- OSM Today

### CC BY 3.0
- ISTAT (alcuni dataset)

### Licenze Multiple/Non Specificate
- Geoportale Nazionale (MASE)
- DIVA-GIS
- IGISMAP
- Portali regionali

## 🔄 Frequenza Aggiornamenti

### Continuo/Real-time
- OpenStreetMap
- Dati sismici INGV

### Semestrale
- Cartografia Catastale
- Alcuni geoportali regionali

### Annuale
- ISTAT (confini amministrativi)
- Dati ambientali ISPRA

## 🤝 Contributing

Consulta [CONTRIBUTING.md](CONTRIBUTING.md) per le linee guida su come contribuire.

## 📜 License

Questo repository è distribuito sotto licenza MIT. Vedi [LICENSE](LICENSE) per maggiori dettagli.
