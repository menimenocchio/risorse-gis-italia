# GIS Italia - Catalogo Risorse Territoriali

Repository contenente un catalogo strutturato di risorse GIS per l'Italia, organizzato per tipologia di dato e copertura territoriale.

## 📂 Struttura Repository

```
/gisitalia/
├── administrative/       # Confini amministrativi e dati catastali
│   ├── national/        # ISTAT, ANNCSU, confini nazionali
│   └── regional/        # Limiti amministrativi regionali
├── demographic/         # Dati demografici e statistici
│   ├── national/        # Censimenti nazionali, statistiche ISTAT
│   └── regional/        # Statistiche regionali
├── environmental/       # Dati ambientali
│   ├── national/        # ISPRA, MASE, INGV
│   └── regional/        # Autorità di bacino, dati regionali
├── infrastructure/      # Infrastrutture e servizi
│   ├── national/        # IGM, RFI, ANAS
│   └── regional/        # Infrastrutture regionali
└── topographic/        # Dati topografici e rilievi
    ├── national/        # DTM nazionali, ortofoto
    └── regional/        # LiDAR e DTM regionali
```

## 🎯 Obiettivi
- Fornire un punto di accesso unificato alle risorse GIS italiane
- Documentare fonti dati ufficiali e loro caratteristiche
- Facilitare l'accesso ai dati territoriali
- Mantenere informazioni aggiornate su servizi e dataset

## 📊 Categorie di Dati

### Dati Amministrativi
- Confini amministrativi (ISTAT)
- Dati catastali (Agenzia Entrate)
- Indirizzi e stradari (ANNCSU)

### Dati Demografici
- Censimenti popolazione
- Statistiche demografiche
- Dati socio-economici

### Dati Ambientali
- Geologia e rischi naturali
- Idrografia e bacini
- Aree protette
- Uso del suolo

### Infrastrutture
- Cartografia IGM
- Reti trasporto
- Servizi e utilities
- POI

### Dati Topografici
- DTM e DSM
- Ortofoto
- LiDAR
- Immagini satellitari

## 🔍 Standard Documentazione

Ogni risorsa include:
- **Fonte**: Ente/organizzazione responsabile
- **URL**: Endpoint di accesso
- **Servizi**: WMS/WFS/Download
- **Formato**: Formati disponibili
- **Licenza**: Tipo di licenza
- **Aggiornamento**: Frequenza
- **Affidabilità**: Valutazione qualità
- **Completezza**: Copertura territoriale

## 🚀 Come Utilizzare

1. Navigare nelle directory per categoria
2. Consultare i README specifici
3. Accedere ai link delle risorse
4. Verificare requisiti e licenze

## 👥 Come Contribuire

1. Fork del repository
2. Creazione branch (`git checkout -b feature/NuovaRisorsa`)
3. Commit modifiche (`git commit -m 'Aggiunta nuova risorsa'`)
4. Push al branch (`git push origin feature/NuovaRisorsa`)
5. Apertura Pull Request

## 📝 Licenza

Questo catalogo è distribuito sotto licenza MIT. I singoli dataset mantengono le proprie licenze originali.

## 📧 Contatti

Per segnalazioni o contributi, aprire una Issue su GitHub.
