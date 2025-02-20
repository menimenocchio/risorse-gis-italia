# Fonti Dati Nazionali

## Principali Fornitori
- [ISTAT](istat.md) - Istituto Nazionale di Statistica
### Servizi Principali
- **API**: `http://apistat.istat.it/`
- **WMS**: `http://wms.istat.it/geoserver/ows`
- **WFS**: `http://wfs.istat.it/geoserver/ows`
- **Affidabilità**: Alta
- **Licenza**: CC BY 3.0

### Dataset Territoriali
#### Confini Amministrativi
- **URL**: `https://www.istat.it/storage/cartografia/confini_amministrativi/`
- **Aggiornamento**: Annuale
- **Formato**: Shapefile, GeoJSON
- **Sistemi**: EPSG:32632/33, EPSG:4326
- **Completezza**: Completa

#### Basi Territoriali
- **Sistema**: WGS 84 UTM Zona 32n
- **Formato**: Shapefile, KMZ
- **Anni**: 1991, 2001, 2011, 2021

##### Dataset Nazionali
- **Limiti Amministrativi (KMZ)**:
  - 2011: [Limiti-Amministrativi-kmz.zip](https://www.istat.it/storage/cartografia/basi_territoriali/Limiti-Amministrativi-kmz.zip)
  - 2021: [Limiti_21-kmz.zip](http://www.istat.it/storage/cartografia/basi_territoriali/2021/Limiti_21-kmz.zip)

- **Località Italiane**:
  - KMZ 2011: [Localita-italiane-kmz.zip](https://www.istat.it/storage/cartografia/basi_territoriali/Localita-italiane-kmz.zip)
  - KMZ 2021: [Località_21-Kmz.zip](http://www.istat.it/storage/cartografia/basi_territoriali/2021/Località_21-Kmz.zip)
  - SHP 2021: [Località_21.zip](http://www.istat.it/storage/cartografia/basi_territoriali/2021/Località_21.zip)

#### Sezioni di Censimento 2021
- **Totale sezioni**: 756.000+ (incremento 88% rispetto al 2011)
- **Download Base**: `https://www.istat.it/it/archivio/104317`
- **Visualizzazione**: 
  - [GIS Portal](https://gisportal.istat.it)
  - [IstatViewer](https://gisportal.istat.it/IstatViewer/)

##### Download per Regione
1. **Nord**
   - [Piemonte](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R01_21.zip)
   - [Valle d'Aosta](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R02_21.zip)
   - [Lombardia](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R03_21.zip)
   - [Trentino-Alto Adige](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R04_21.zip)
   - [Veneto](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R05_21.zip)
   - [Friuli-Venezia Giulia](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R06_21.zip)
   - [Liguria](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R07_21.zip)
   - [Emilia-Romagna](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R08_21.zip)

2. **Centro**
   - [Toscana](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R09_21.zip)
   - [Umbria](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R10_21.zip)
   - [Marche](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R11_21.zip)
   - [Lazio](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R12_21.zip)

3. **Sud e Isole**
   - [Abruzzo](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R13_21.zip)
   - [Molise](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R14_21.zip)
   - [Campania](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R15_21.zip)
   - [Puglia](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R16_21.zip)
   - [Basilicata](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R17_21.zip)
   - [Calabria](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R18_21.zip)
   - [Sicilia](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R19_21.zip)
   - [Sardegna](http://www.istat.it/storage/cartografia/basi_territoriali/2021/R20_21.zip)

## ANNCSU - Archivio Nazionale Numeri Civici Strade Urbane

### Informazioni Generali
- **Fonte**: Agenzia delle Entrate
- **Base legale**: DPCM 12 maggio 2016
- **Aggiornamento**: Mensile
- **Licenza**: CC BY 4.0
- **Formato**: CSV
- **Sistema di riferimento**: RDN2008/UTM32N (EPSG:6705)

### Dataset Disponibili

#### Dataset Nazionali
- **Stradario Italia**: [STRAD_ITA](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ITA)
- **Indirizzi Italia**: [INDIR_ITA](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ITA)

#### Dataset Regionali
Ogni regione ha due dataset separati per stradario e indirizzi:

##### Nord Italia
- **Valle d'Aosta**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_VALL) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_VALL)
- **Piemonte**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_PIEM) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_PIEM)
- **Lombardia**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_LOMB) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_LOMB)
- **Veneto**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_VENE) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_VENE)
- **Trentino-Alto Adige**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_TREN) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_TREN)
- **Friuli-Venezia Giulia**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_FRIU) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_FRIU)
- **Liguria**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_LIGU) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_LIGU)
- **Emilia-Romagna**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_EMIL) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_EMIL)

##### Centro Italia
- **Toscana**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_TOSC) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_TOSC)
- **Umbria**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_UMBR) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_UMBR)
- **Marche**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_MARC) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_MARC)
- **Lazio**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_LAZI) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_LAZI)

##### Sud e Isole
- **Abruzzo**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_ABRU) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_ABRU)
- **Molise**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_MOLI) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_MOLI)
- **Campania**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_CAMP) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_CAMP)
- **Puglia**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_PUGL) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_PUGL)
- **Basilicata**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_BASI) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_BASI)
- **Calabria**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_CALA) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_CALA)
- **Sicilia**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_SICI) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_SICI)
- **Sardegna**: [Stradario](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?STRAD_SARD) | [Indirizzi](https://anncsu.open.agenziaentrate.gov.it/age-inspire/opendata/anncsu/getds.php?INDIR_SARD)

### Contatti ANNCSU
- **Email**: dc.sccpi.relentieistituzioni@agenziaentrate.it
- **Website**: http://www.agenziaentrate.gov.it/
