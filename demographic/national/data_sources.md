# Fonti Dati Demografici Nazionali

## Censimento Nazionale
### Censimento 2021
- **URL**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni`
- **Affidabilità**: Alta
- **Completezza**: Completa
- **Sistema**: EPSG:32632/33

#### Dataset Principali
- **Popolazione**:
  - Residenti per sezione
  - Fasce d'età
  - Cittadinanza
- **Abitazioni**:
  - Edifici residenziali
  - Stato di occupazione
  - Epoca di costruzione

### Evoluzione Storica
#### Censimento Tradizionale (fino al 2011)
- Rilevazione universale "porta a porta"
- Cadenza decennale
- Copertura completa del territorio

#### Censimento Permanente (dal 2018)
- Indagini campionarie annuali
- Sistema Integrato dei Registri Statistici
- Utilizzo di archivi amministrativi

### Dataset Storici
- **1991**: [dati-cpa_1991.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_1991.zip)
- **2001**: [dati-cpa_2001.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_2001.zip)
- **2011**: [dati-cpa_2011.zip](https://www.istat.it/storage/cartografia/variabili-censuarie/dati-cpa_2011.zip)
- **2021**: [Dati_regionali_2021.zip](https://esploradati.censimentopopolazione.istat.it/databrowser/DWL/PERMPOP/SUBCOM/Dati_regionali_2021.zip)

## Sezioni di Censimento 2021
### Statistiche Generali
- **Totale sezioni**: 756.000+ (incremento 88% dal 2011)
- **Sistema**: WGS 84 UTM Zona 32n
- **Formato**: Shapefile
- **Encoding**: UTF-8

### Macro-aree Dataset
#### Aree Residenziali e Servizi
- **M01**: [BT21_sez_M01.zip](https://www.istat.it/storage/sezioni-censimento/Geografici%20zip/BT21-sez-M01.zip)
- **M02**: [BT21_sez_M02.zip](https://www.istat.it/storage/sezioni-censimento/Geografici%20zip/BT21-sez-M02.zip)
  - Ospedali, Rettorati, Penitenziari

#### Infrastrutture e Trasporti
- **M03**: Impianti industriali
- **M04**: Trasporti
  - Porti, Aeroporti, Stazioni, Interporti

#### Ambiente e Territorio
- **M06**: Agricoltura
- **M07**: Acque e rifiuti
- **M08**: Aree naturali
- **M10**: Corpi idrici

## ISTAT Demografia
- **URL**: `http://demo.istat.it/`
- **API**: `http://apistat.istat.it/`
- **Aggiornamento**: Mensile/Annuale

### Dataset Principali
- **Popolazione residente**
  - Comune, Età, Stato civile, Cittadinanza
- **Bilancio demografico**
  - Nati, Morti, Migrazioni
- **Previsioni demografiche**
  - Proiezioni 2020-2070
  - Scenari alternativi

## Standard e Formati
### Requisiti Dataset
- Data di riferimento
- Livello territoriale
- Variabili disponibili 
- Formato dati
- Licenza d'uso
- Collegamenti a metadati

### Formati Supportati
- CSV (dati tabulari)
- Shapefile (dati geografici)
- JSON/GeoJSON (web services)

## Servizi Web
- **ISTAT API**: `http://apistat.istat.it/`
- **WFS**: `http://wfs.istat.it/geoserver/ows`
- **GIS Portal**: `https://gisportal.istat.it`
- **IstatViewer**: Confronto 1991-2021
