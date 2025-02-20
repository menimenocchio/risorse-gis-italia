# Fonti Dati Infrastrutturali Nazionali

## Istituto Geografico Militare (IGM)

### Prodotti Cartografici
#### Carte Topografiche
- **Serie 25V**: Scala 1:25.000 (storica)
  - **URL**: `https://www.igmi.org/it/carte-topografiche`
  - **Formato**: TIFF, PDF
  - **Copertura**: Nazionale

#### Database Geotopografico
- **DB25**: Database scala 1:25.000
  - **Formato**: Shapefile, GeoPackage
  - **Sistema**: ETRF2000/WGS84
  - **Aggiornamento**: Continuo

#### Reti Geodetiche
- **Rete GPS/GNSS**:
  - **URL**: `https://www.igmi.org/it/reti-geodetiche`
  - **Formato**: RINEX
  - **Aggiornamento**: Real-time

#### Modelli del Terreno
- **DTM Nazionale**:
  - **Risoluzione**: 10m
  - **Formato**: ASCII GRID
  - **Sistema**: ETRF2000

## Cartografia Catastale

### Agenzia delle Entrate
- **WMS**: `https://wms.cartografia.agenziaentrate.gov.it/inspire/wms/ows01.php`
- **Download**: `https://www.gisinfrastrutture.it/2025/02/la-cartografia-catastale-italiana`
- **Licenza**: CC BY 4.0
- **Formato**: Shapefile, WMS, WFS

### Dataset Disponibili
#### Particelle Catastali
- **Aggiornamento**: Mensile
- **Sistema**: ETRF2000
- **Scala**: 1:2.000
- **Formato**: SHP, DXF

#### Fabbricati
- **Aggiornamento**: Mensile
- **Formato**: SHP, DXF
- **Attributi**: Foglio, Particella, Subalterno

#### Servizi OGC
- **WMS**: Visualizzazione
- **WFS**: Download features
- **Sistema**: EPSG:4258/ETRS89

### API e Servizi Web
- **WMS**: `https://wms.cartografia.agenziaentrate.gov.it/inspire/wms/ows01.php`
- **WFS**: `https://wfs.cartografia.agenziaentrate.gov.it/inspire/wfs`
- **Autenticazione**: Basic HTTP
- **Formato risposte**: GML, JSON, SHP

## Trasporti e Viabilità

### RFI - Rete Ferroviaria Italiana
- **WMS**: `https://webgis.rfi.it/arcgis/services/`
- **Dataset**: 
  - Rete ferroviaria nazionale
  - Stazioni
  - Passaggi a livello
- **Formato**: Shapefile, KML
- **Aggiornamento**: Trimestrale

### ANAS - Strade Statali
- **WFS**: `http://wasservice.anas.it/services/`
- **Dataset**:
  - Rete stradale nazionale
  - Opere d'arte
  - Cantieri
- **Formato**: Shapefile, GeoJSON
- **Aggiornamento**: Settimanale

### OpenTransportMap
- **WMS**: `http://opentransportmap.info/geoserver/wms`
- **Download**: `https://opentransportmap.info/download`
- **Formato**: OSM XML, GeoJSON
- **Aggiornamento**: Mensile

## Portali e Repository Nazionali

### Italia/Public-Opendata-Sources
- **URL**: `https://github.com/italia/public-opendata-sources`
- **Tipo**: Repository GitHub
- **Contenuto**: Indice di fonti dati pubblici
- **Licenza**: Varie per dataset
- **Aggiornamento**: Continuo

### Dati.gov.it
- **URL**: `https://www.dati.gov.it/geodati`
- **API**: `https://dati.gov.it/api/3/action/`
- **Formato**: CSV, JSON, XML, SHP
- **Licenza**: CC-BY 4.0 (prevalente)

### NextGIS Data - Italia
- **URL**: `https://data.nextgis.com/en/region/IT/base/`
- **Dataset**:
  - Confini Amministrativi
  - Trasporti
  - POI
- **Formato**: GeoPackage, Shapefile, PostGIS
- **Licenza**: ODbL
- **Aggiornamento**: Variabile per dataset

## Geoportale Nazionale

### WMS/WMTS
- Base URL: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/WMS_v1.3/raster/`
- Servizi:
  - **Ortofoto**: `/ms_ogc/WMS_v1.3/raster/ortofoto_colore_12/`
  - **DTM 20m**: `/ms_ogc/WMS_v1.3/raster/DTM_20M/`
  - **Carta geologica**: `/ms_ogc/WMS_v1.3/raster/carta_geologica/`

### Download Services
- **DTM Nazionali**: `http://www.pcn.minambiente.it/mattm/servizio-wcs/`
- **Ortofoto**: `http://www.pcn.minambiente.it/mattm/servizio-wms/`

### Dataset Principali
- **DTM**: 20m, 75m (ASCII GRID, GeoTIFF)
- **Ortofoto**: 1988-2023 (ECW, JPG)
- **Sistema di riferimento**: EPSG:32632/33
