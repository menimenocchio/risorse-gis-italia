# Fonti Dati Nazionali

## ISPRA - Servizi Cartografici

### Endpoints e Servizi

#### WMS
- URL: `http://geoservices.isprambiente.it/arcgis/services/`
- Servizi principali:
  - Geologia
  - Pericolosità idraulica
  - Consumo di suolo
  - Coste
  - Acque

#### Download Diretto
- [Geoportale ISPRA](http://www.sinanet.isprambiente.it/it/sia-ispra/download-mais)
- [Cartografia Geologica](https://www.isprambiente.gov.it/it/servizi/carta-geologica-ditalia)

### Datasets Principali

#### Cartografia Geologica
- **URL WMS**: `http://geoservices.isprambiente.it/arcgis/services/Geologia/geologica_italia/ImageServer/WMSServer`
- **Formato**: WMS, Shapefile
- **Scala**: 1:100.000, 1:50.000
- **Sistema di riferimento**: EPSG:25832

#### Consumo di Suolo
- **URL WMS**: `http://geoservices.isprambiente.it/arcgis/services/Consumo_suolo/Consumo_suolo_2020/MapServer/WMSServer`
- **Formato**: WMS, Raster
- **Aggiornamento**: Annuale
- **Risoluzione**: 10m

#### Rischio Idrogeologico
- **URL WMS**: `http://geoservices.isprambiente.it/arcgis/services/Pericolosita/Alluvioni_PericolositaIdraulica/MapServer/WMSServer`
- **Formato**: WMS, Shapefile
- **Aggiornamento**: Variabile per zona

#### Acque
- **WMS**: `http://geoservices.isprambiente.it/arcgis/services/Acque/`
- **Dataset**:
  - Reticolo idrografico
  - Bacini idrografici
  - Monitoraggio acque sotterranee
  - Qualità acque superficiali

## Geoportale MASE

### Servizi di Scaricamento
- **URL**: `https://gn.mase.gov.it/portale/servizi-di-scaricamento`
- **Catalogo**: `https://gn.mase.gov.it/portale/`

### Dataset Disponibili

#### Dati Ambientali
- **WFS**: `https://gn.mase.gov.it/geoserver/wfs`
- **Dataset**:
  - Aree protette
  - Rete Natura 2000
  - Rischio ambientale
  - Zone marine protette

#### Cartografia di Base
- **WMS**: `https://gn.mase.gov.it/geoserver/wms`
- **Dataset**:
  - Ortofoto
  - DTM
  - Uso del suolo
- **Formato**: GeoTIFF, ECW

#### API e Servizi
- **CSW**: `https://gn.mase.gov.it/geonetwork/srv/ita/csw`
- **INSPIRE**: `https://gn.mase.gov.it/inspire/`
- **Formati**: GML, SHP, GeoJSON, KML

## TINITALY - Modello Digitale di Elevazione

### Servizio Principale
- **URL**: `https://tinitaly.pi.ingv.it/`
- **Licenza**: CC BY 4.0
- **Risoluzione**: 10 metri
- **Copertura**: Nazionale

### Dataset Disponibili

#### DTM 10m
- **Download**: `https://tinitaly.pi.ingv.it/download.html`
- **Formato**: ASCII GRID, GeoTIFF
- **Sistema**: ETRF2000 (EPSG:7792)
- **Accuratezza verticale**: 1.5m-2.5m

#### Prodotti Derivati
- Hillshade
- Slope
- Aspect
- **Formato**: GeoTIFF
- **Risoluzione**: 10m, 25m

### Metadati
- **DOI**: 10.13127/TINITALY/1.0
- **Documentazione**: [Technical documentation](https://tinitaly.pi.ingv.it/documentation.html)

## Copernicus Services - Italia

### Land Monitoring Service

#### CORINE Land Cover
- **WMS**: `https://land.copernicus.eu/pan-european/corine-land-cover/clc2018`
- **Download**: `https://land.copernicus.eu/pan-european/corine-land-cover/clc2018?tab=download`
- **Risoluzione**: 100m/25ha MMU
- **Anni**: 1990, 2000, 2006, 2012, 2018

#### High Resolution Layers
- **Imperviousness**: `https://land.copernicus.eu/pan-european/high-resolution-layers/imperviousness`
- **Forest**: `https://land.copernicus.eu/pan-european/high-resolution-layers/forests`
- **Water & Wetness**: `https://land.copernicus.eu/pan-european/high-resolution-layers/water-wetness`

### Marine Service
- **Mediterranean Sea**: `https://resources.marine.copernicus.eu/products`
- **Parametri**: Temperature, Salinità, Correnti
- **Formato**: NetCDF, CSV
- **Aggiornamento**: Giornaliero/Mensile

### Climate Change Service
- **ERA5**: Dati climatici storici
- **Seasonal Forecast**: Previsioni stagionali
- **URL API**: `https://cds.climate.copernicus.eu/api/v2/`

## Dati Agricoltura Nazionali

### SIAN - Sistema Informativo Agricolo Nazionale
- **WMS**: `https://agriGIS.sian.it/geoserver/wms`
- **Dataset**:
  - Particelle catastali agricole
  - Uso del suolo agricolo
  - Zone vulnerabili ai nitrati
  - Aree biologiche

### AGEA - Agenzia per le Erogazioni in Agricoltura
#### Fascicolo Aziendale
- **WFS**: `https://sian.it/geoservices/fascicolo/wfs`
- **Dataset**:
  - Appezzamenti
  - Colture
  - Irrigazione
- **Aggiornamento**: Annuale

### Carta dei Suoli
- **Base URL**: `http://www.pedologia.net/geoserver/`
- **Dataset**:
  - Carte pedologiche regionali
  - Capacità d'uso dei suoli
  - Rischio erosione
- **Scale**: 1:250.000, 1:50.000

## Mareografico Nazionale
- **API**: `https://www.mareografico.it/api/v1/`
- **Dataset**:
  - Livelli marea
  - Temperature acqua
  - Moto ondoso
- **Aggiornamento**: Real-time

### Idrologia e Bacini
- **Reticolo Idrografico**
  - **WFS**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Aste_fluviali.map`
- **Bacini Idrografici**
  - **WFS**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Bacini_idrografici.map`
- **Specchi d'Acqua**
  - **WFS**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Specchi_Acqua.map`

### Rischio Idrogeologico
- **Piano Assetto Idrogeologico (PAI)**
  - **Pericolosità**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/PAI_pericolosita.map`
  - **Rischio**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/PAI_rischio.map`
- **Alluvioni PGRA 2021**:
  - **Estensione**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Alluvioni_Estensione.map`
  - **Elementi a Rischio**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Alluvioni_Elementi_a_Rischio.map`
  - **Caratteristiche Idrauliche**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Alluvioni_Caratteristiche_Idrauliche.map`
  - **Classi di Rischio**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Alluvioni_Classi_di_Rischio.map`

### Uso del Suolo
#### Corine Land Cover
- **1990**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover1990.map`
- **2000**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2000.map`
- **2006**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2006.map`
- **2012**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2012.map`

#### Corine Land Cover IV Livello
- **2000**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2000_IVliv.map`
- **2006**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2006_IVliv.map`
- **2012**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Corine_Land_Cover2012_IVliv.map`

### Aree Protette
- **Rete Natura 2000**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/SIC_ZSC_ZPS.map`
- **EUAP**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/EUAP.map`
- **Zone Ramsar**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/RAMSAR.map`
- **IBA**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/IBA.map`
- **ZPE**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/ZPE.map`
- **Santuario Pelagos**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Santuario_Pelagos.map`

### Geologia e Rischio Sismico
- **Carta Geologica**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Carta_geologica.map`
- **Carta Geolitologica**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Carta_geolitologica.map`
- **Zone Sismogenetiche**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Zone_sismogenetiche_ZS9.map`
- **Pericolosità Sismica**:
  - **0.02°**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Pericolosita_sismica_002.map`
  - **0.05°**: `http://wms.pcn.minambiente.it/ogc?map=/ms_ogc/wfs/Pericolosita_sismica_005.map`
