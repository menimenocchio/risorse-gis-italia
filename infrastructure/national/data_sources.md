# Fonti Dati Infrastrutturali Nazionali

## Edifici

### Protezione Civile
- **URL**:
  - Nord-Est: `https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITH-NordEst`
  - Nord-Ovest: `https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITC-NordOvest`
  - Centro: `https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITI-Centro`
  - Sud: `https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITF-Sud`
  - Isole: `https://github.com/pcm-dpc/DPC-Aggregati-Strutturali-ITG-Isole`
- **Dataset**: Dati vettoriali OSM per zona/regione/comune
- **Licenza**:  Attribuzione 4.0 Internazionale
- **Aggiornamento**: 2022
- **Formati**: Shapefile

### Microsoft ML Building Footprints
- **URL**: `https://minedbuildings.z5.web.core.windows.net/global-buildings/dataset-links.csv`
- **Licenza**: Open Data Commons Open Database License (ODbL).
- **Aggiornamento**: Mensile (ma dataset globale)
- **Formati**: csv

### OpenStreetMap
- **URL**: `https://s3.dualstack.us-east-1.amazonaws.com/production-raw-data-api/ISO3/ITA/buildings/polygons/hotosm_ita_buildings_polygons_gpkg.zip`
- **Licenza**: ODbL (Open Database License)
- **Aggiornamento**: Settimanale
- **Formati**: gpkg

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


## Cartografia Catastale

### Agenzia delle Entrate
- **WMS**: `https://wms.cartografia.agenziaentrate.gov.it/inspire/wms/ows01.php?SERVICE=WMS&VERSION=1.3.0&REQUEST=GetCapabilities`
- **WFS**: `https://wfs.cartografia.agenziaentrate.gov.it/inspire/wfs/owfs01.php?SERVICE=WFS&REQUEST=GetCapabilities&VERSION=2.0.0`
- **Download**: `https://wfs.cartografia.agenziaentrate.gov.it/inspire/wfs/GetDataset.php?dataset=ITALIA.zip`
- **Licenza**: CC BY 4.0
- **Formato**: Shapefile, WMS, WFS, GML
- **Aggiornamento**: Giornaliero per WFS e WMS, semestrale per il link di download diretto
- **Sistema**: EPSG:6706


## Trasporti e Viabilità

### Mase - Rete Ferroviaria Italiana
- **WMS**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/WMS_v1.3/Vettoriali/Rete_ferroviaria.map&service=wms&request=getCapabilities&version=1.3.0/`
- **Dataset**: 
  - Rete ferroviaria nazionale
  - Stazioni
  - Passaggi a livello
- **Formato**: Shapefile
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

### Limiti Amministrativi
- **2020**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/LimitiAmministrativi_2020.map`
- **2011**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/LimitiAmministrativi_2011.map`

### Edifici e Strutture
- **Edificato Capoluoghi**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Edifici.map`
- **Numeri Civici**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Numeri_Civici.map`
- **Scuole**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Scuole_statali_paritarie.map`

### SAR e Monitoraggio
- **COSMO-SkyMed**:
  - **Ascending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_COSMOSKYMED_Ascending.map`
  - **Descending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_COSMOSKYMED_Descending.map`
- **ENVISAT**:
  - **Ascending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_ENVISAT_Ascending.map`
  - **Descending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_ENVISAT_Descending.map`
- **ERS**:
  - **Ascending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_ERS_Ascending.map`
  - **Descending**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_ERS_Descending.map`

### LiDAR e DTM
- **Quadro Unione LiDAR**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/QU_Lidar.map`
