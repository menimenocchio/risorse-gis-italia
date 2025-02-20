# 🗺️ GIS Italia Resources

Una raccolta curata di risorse GIS per l'Italia, categorizzate per tipologia, completezza e affidabilità.

## 📑 Struttura Repository

```
gisitalia/
├── administrative/          # Confini e dati amministrativi
│   ├── national/           # Dati nazionali (ISTAT, etc.)
│   └── regional/           # Geoportali regionali
├── environmental/          # Dati ambientali
│   ├── climate/           # Dati climatici
│   ├── geology/           # Dati geologici
│   ├── nature/            # Parchi e aree protette
│   └── water/             # Risorse idriche
├── infrastructure/         # Infrastrutture
│   ├── buildings/         # Edifici e urbanistica
│   ├── cadastral/         # Dati catastali
│   ├── energy/            # Reti energetiche
│   └── transport/         # Trasporti
├── demographic/           # Dati demografici
│   ├── census/            # Dati censimento
│   └── statistics/        # Statistiche demografiche
└── topographic/           # Dati topografici
    ├── dem/               # Modelli di elevazione
    ├── imagery/           # Ortofoto e immagini
    └── maps/              # Carte topografiche
```

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
