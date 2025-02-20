# ISTAT - Dati Censimento

## Censimento 2021
- **URL**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni`
- **Affidabilità**: Alta
- **Completezza**: Completa
- **Aggiornamento**: Decennale

### Dataset Disponibili
- **Popolazione**:
  - Residenti per sezione
  - Fasce d'età
  - Cittadinanza
- **Abitazioni**:
  - Edifici residenziali
  - Stato di occupazione
  - Epoca di costruzione

### Servizi
- **WFS**: `http://wfs.istat.it/geoserver/ows`
- **Download Base**: `https://www.istat.it/it/archivio/104317`
- **Formato**: Shapefile, CSV, XLSX
- **Sistema**: EPSG:32632/33

### Accesso ai Dati
- **Censimento 2021**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni/documentazione`
- **Basi Territoriali**: `https://www.istat.it/it/archivio/104317`
- **Variabili Censuarie**: `https://www.istat.it/it/archivio/471540`

## Metodologia
### Censimento Permanente
- Avviato nel 2018
- Indagini annuali su campione
- Integrazione con registri statistici
- Consultare [census_history.md](./census_history.md) per dettagli

### Sistema Integrato
- **RBI**: Registro Base Individui
- **RSBL**: Registro Statistico Base Luoghi
  - Geo-localizzazione famiglie
  - Collegamento con edifici
  - Proiezione territoriale dati

### Serie Storiche
- [Dati 1991-2021](https://www.istat.it/storage/cartografia/variabili-censuarie/)
- Formati: CSV, XLS, TXT
- Comparazione intercensuaria
- Documentazione metodologica

## Sezioni di Censimento 2021

### Innovazioni
- Incremento da 403.000 a 756.000+ sezioni
- Miglioramento qualità geometrica
- Maggiore omogeneità interna
- 53 codici speciali per classificazione

### Caratteristiche
- Profili demografici omogenei
- Aspetti socio-economici
- Caratteristiche urbanistiche
- Elementi ambientali

Per i dettagli completi delle sezioni e macro-aree, consultare [sections_2021.md](./sections_2021.md)

### WebGIS e Visualizzazione
- Navigazione interattiva
- Confronto storico 1991-2021
- Sovrapposizione tematica
- Download dati geografici
