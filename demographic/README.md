# Fonti Dati Demografici

## Livello Nazionale

### ISTAT Censimento
#### Censimento 2021
- **URL**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni`
- **Affidabilità**: Alta
- **Completezza**: Completa
- **Sistema**: EPSG:32632/33

##### Dataset Principali
- **Popolazione**:
  - Residenti per sezione
  - Fasce d'età
  - Cittadinanza
- **Abitazioni**:
  - Edifici residenziali
  - Stato di occupazione
  - Epoca di costruzione

#### Sezioni di Censimento 2021
- **Totale sezioni**: 756.000+ (incremento 88% dal 2011)
- **Sistema**: WGS 84 UTM Zona 32n
- **Formato**: Shapefile
- **Encoding**: UTF-8

##### Dataset per Macro-aree
- **M01**: [BT21_sez_M01.zip](https://www.istat.it/storage/sezioni-censimento/Geografici%20zip/BT21-sez-M01.zip)
- **M02**: [BT21_sez_M02.zip](https://www.istat.it/storage/sezioni-censimento/Geografici%20zip/BT21-sez-M02.zip)
  - Ospedali, Rettorati, Penitenziari
- **M03**: Impianti industriali
- **M04**: Trasporti
- **M06-M10**: Ambiente e Territorio

#### Serie Storiche Censimenti
- **2021**: 
  - [Dati regionali](https://esploradati.censimentopopolazione.istat.it/databrowser/DWL/PERMPOP/SUBCOM/Dati_regionali_2021.zip)
  - [Dati Città Metropolitane](https://esploradati.censimentopopolazione.istat.it/databrowser/DWL/PERMPOP/SUBCOM/Comuni_2021.zip)
- **2011**: [dati-cpa_2011.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_2011.zip)
- **2001**: [dati-cpa_2001.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_2001.zip)
- **1991**: [dati-cpa_1991.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_1991.zip)

### ISTAT Demografia
- **URL**: `http://demo.istat.it/`
- **API**: `http://apistat.istat.it/`
- **Aggiornamento**: Mensile/Annuale

#### Dataset Principali
- Popolazione residente
- Bilancio demografico
- Previsioni demografiche (2020-2070)

## Livello Regionale

### Sistema Integrato Territoriale
#### Registri Statistici Base
- **RBI**: Registro Base Individui
  - Anagrafe popolazione residente
  - Permessi di soggiorno
  - Posizioni previdenziali

- **RSBL**: Registro Statistico Base Luoghi
  - Geo-localizzazione famiglie
  - Collegamenti con edifici
  - Proiezione territoriale dati

### Censimento Industria e Servizi
- **2011**: [dati-sce_2011.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-sce_2011.zip)
- **2001**: [dati-cis_2001.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cis_2001.zip)
- **1991**: [dati-cis_1991.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cis_1991.zip)

### Strutture e Infrastrutture
#### Servizi Pubblici
- Strutture ospedaliere (633)
- Sedi universitarie
- Strutture penitenziarie
- Centri commerciali

#### Infrastrutture di Trasporto
- Porti (88)
- Aeroporti
- Stazioni ferroviarie
- Interporti
- Rete stradale

#### Strutture Speciali
- Impianti sportivi
- Fiere e outlet
- Strutture turistiche
- Aree industriali

## Strumenti e Servizi

### API e Servizi Web
- **ISTAT API**: `http://apistat.istat.it/`
- **WFS**: `http://wfs.istat.it/geoserver/ows`
- **GIS Portal**: `https://gisportal.istat.it`
- **IstatViewer**: Confronto 1991-2021

### Documentazione
- **Censimento**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni/documentazione`
- **Basi Territoriali**: `https://www.istat.it/it/archivio/104317`
- **Variabili**: `https://www.istat.it/it/archivio/471540`

### Visualizzazione
- [Storia geografica delle macro-aree](https://gisportal.istat.it/portal/apps/MapSeries/index.html?appid=e8601c3731ea44ffb12f848d6d5f004f)
- [IstatViewer](https://gisportal.istat.it/IstatViewer/)

### Standard e Formati
#### Formati Supportati
- CSV (dati tabulari)
- Shapefile (dati geografici)
- JSON/GeoJSON (web services)

#### Requisiti Dataset
- Data di riferimento
- Livello territoriale
- Variabili disponibili 
- Formato dati
- Licenza d'uso
- Collegamenti a metadati
