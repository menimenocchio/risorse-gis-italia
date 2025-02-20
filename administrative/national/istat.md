# ISTAT - Dati Nazionali

## Servizi Principali
- **API**: `http://apistat.istat.it/`
- **WMS**: `http://wms.istat.it/geoserver/ows`
- **WFS**: `http://wfs.istat.it/geoserver/ows`
- **Affidabilità**: Alta
- **Licenza**: CC BY 3.0

## Dataset Territoriali
### Confini Amministrativi
- **URL**: `https://www.istat.it/storage/cartografia/confini_amministrativi/`
- **Aggiornamento**: Annuale
- **Formato**: Shapefile, GeoJSON
- **Sistemi**: EPSG:32632/33, EPSG:4326
- **Completezza**: Completa

### Basi Territoriali
- **URL**: `https://www.istat.it/it/archivio/104317`
- **Aggiornamento**: Decennale
- **Formato**: Shapefile, KML
- **Completezza**: Completa

Per i dati territoriali dettagliati, inclusi tutti i download per regione e anno, consultare [istat_territorial.md](./istat_territorial.md)

### Formato Dati
- **Sistema**: WGS 84 UTM Zona 32n
- **Encoding**: UTF-8
- **Formati**: Shapefile, KMZ
- **Anni**: 1991, 2001, 2011, 2021

### Visualizzazione
- **WebGIS**: [gisportal.istat.it](https://gisportal.istat.it)
- **Storia geografica**: [Macro-aree](https://gisportal.istat.it/portal/apps/MapSeries/index.html?appid=e8601c3731ea44ffb12f848d6d5f004f)
- **Viewer**: [IstatViewer](https://gisportal.istat.it/IstatViewer/)

## Dati Demografici
### Censimento 2021
- **URL**: `https://www.istat.it/it/censimenti/popolazione-e-abitazioni`
- **Dataset**: 
  - Popolazione residente
  - Abitazioni
  - Edifici
- **Formato**: CSV, XLSX, Shapefile

### Statistiche Demografiche
- **URL**: `http://demo.istat.it/`
- **Aggiornamento**: Mensile/Annuale
- **Dataset**:
  - Bilancio demografico
  - Popolazione residente
  - Stranieri residenti
  - Previsioni demografiche

## Sezioni di Censimento 2021
- **Totale sezioni**: 756.000+ (incremento 88% rispetto al 2011)
- **Sistema**: WGS 84 UTM Zona 32n
- **Formato**: Shapefile (encoding UTF-8)
- **Download Base**: `https://www.istat.it/it/archivio/104317`
- **Visualizzazione**: 
  - [GIS Portal](https://gisportal.istat.it)
  - [IstatViewer](https://gisportal.istat.it/IstatViewer/)
  - [Storia Geografica](https://gisportal.istat.it/portal/apps/MapSeries/index.html?appid=e8601c3731ea44ffb12f848d6d5f004f)

### Macro-aree Territoriali
1. **M01 - Area residenziale**
   - URL: `https://www.istat.it/storage/sezioni-censimento/Geografici%20zip/BT21-sez-M01.zip`
   - [Metadati](https://www.istat.it/storage/sezioni-censimento/Pdf/M01-META21.pdf)

2. **M02 - Servizi pubblici e amministrativi**
   - URL Base: `https://www.istat.it/storage/sezioni-censimento/Geografici zip/`
   - Dataset specifici:
     - Ospedali (633 strutture)
     - Rettorati
     - Penitenziari
     - Fiere e outlet

3. **M03 - Impianti industriali ed energia**
4. **M04 - Trasporti e comunicazioni**
   - Porti (88 porti statistici)
   - Aeroporti
   - Stazioni
   - Interporti
   - Strade

5. **M05 - Turismo e attività ricreative**
6. **M06 - Agricoltura**
7. **M07 - Trattamento acque e rifiuti**
8. **M08 - Aree naturali**
9. **M09 - Luoghi culturali**
10. **M10 - Corpi idrici**
11. **M99 - Altro**

### Caratteristiche
- 53 codici speciali (Cod_Tipo_S)
- 11 macro-aree di classificazione
- Omogeneità interna delle sezioni
- Caratterizzazione uso/copertura suolo
