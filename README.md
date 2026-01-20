# google-drive-downloader

# Download di file da URL direttamente su Google Drive tramite Google Colab

> **Un notebook Google Colab per scaricare file da Internet direttamente sul tuo Google Drive senza occupare spazio locale**

**[🇮🇹 Italiano](#-italiano) | [🇬🇧 English](#-english)**

---

## 🇮🇹 Italiano

### 📖 Panoramica

Questo progetto fornisce un **notebook Google Colab** che permette di scaricare file da URL direttamente sul tuo **Google Drive**. Ideale per chi ha ampio spazio di archiviazione su Drive e vuole automatizzare il download di file di grandi dimensioni senza occupare banda o spazio sul dispositivo locale.

### Architettura del Sistema

```
┌─────────────┐      ┌──────────────┐      ┌─────────────────┐
│     URL     │─────▶│   Google     │─────▶│  Google Drive   │
│   Sorgente  │      │    Colab     │      │   (Storage)     │
└─────────────┘      └──────────────┘      └─────────────────┘

```

### 📦 Struttura del Progetto

```
google-drive-downloader/
├── code/
│   └── URLDownloader.ipynb        # Notebook principale Google Colab
└── README.md
```

---

## 🚀 Caratteristiche Principali

* ✅ **Download diretto su cloud** - I file vengono scaricati direttamente su Google Drive
* ✅ **Nessun consumo di banda locale** - Utilizza la connessione di Google
* ✅ **Supporto file di grandi dimensioni** - Nessun limite di storage locale
* ✅ **Autenticazione sicura** - OAuth 2.0 di Google
* ✅ **Compatibile con vari protocolli** - HTTP, HTTPS, FTP
* ✅ **Completamente gratuito** - Utilizza le risorse gratuite di Google Colab

---

## 📋 Requisiti

* **Account Google** con accesso a Google Drive
* **Spazio su Google Drive** - Consigliato almeno 15 GB disponibili (ideale per account Google One da 100 GB o superiore)
* **Browser web** moderno
* **Connessione internet** stabile

> ⚠️ **Nota**: Questo progetto è particolarmente adatto per account con ampio spazio Google Drive disponibile.

---

## 🎯 Installazione e Utilizzo

### Passo 1: Apertura del Notebook

1. Clicca su questo link per aprire direttamente il notebook in Google Colab:
   
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GianlucaBevilacqua93/google-drive-downloader/blob/main/code/URLDownloader.ipynb)

2. Oppure apri manualmente:
   * Vai su [Google Colab](https://colab.research.google.com/)
   * `File` → `Apri notebook` → `GitHub`
   * Incolla: `https://github.com/GianlucaBevilacqua93/google-drive-downloader/blob/main/code/URLDownloader.ipynb`

### Passo 2: Autorizzazione Google Drive

Quando esegui il notebook per la prima volta:

1. Esegui la prima cella del notebook
2. Clicca sul link di autorizzazione
3. Accedi con il tuo account Google
4. Concedi i permessi richiesti
5. Il tuo Drive sarà montato nella sessione Colab

### Passo 3: Inserire gli URL

Inserisci l'URL del file da scaricare alla richiesta runtime

### Passo 4: Avviare il Download

Esegui le celle del notebook e attendi il completamento. I file verranno salvati nella cartella specificata del tuo Google Drive.

---


## 💡 Vantaggi

* 🚀 **Velocità** - Sfrutta l'infrastruttura cloud di Google
* 💾 **Risparmio spazio** - Non occupa memoria sul dispositivo locale
* 🌐 **Accessibile ovunque** - Funziona da qualsiasi dispositivo con browser
* 📱 **Multi-dispositivo** - I file restano sul cloud accessibili da ovunque

---

## ⚠️ Limitazioni

* 🔒 **File protetti** - Non funziona con contenuti che richiedono autenticazione specifica
* 🌐 **Dipendenza connessione** - Richiede connessione internet stabile
* 💾 **Spazio disponibile** - Necessita di spazio sufficiente su Google Drive

---

## 🔮 Sviluppi Futuri

### Versione 2.0
- [ ] Interfaccia grafica user-friendly
- [ ] Sistema di gestione code per download multipli
- [ ] Ripresa automatica in caso di interruzione
- [ ] Sincronizzazione con altre piattaforme cloud
- [ ] Verifica integrità
- [ ] Sistema di logging avanzato

---

## 🤝 Contribuire

I contributi sono benvenuti! Per contribuire:

1. Fork del progetto
2. Crea un branch (`git checkout -b feature/NuovaFeature`)
3. Commit delle modifiche (`git commit -m 'Aggiunta NuovaFeature'`)
4. Push sul branch (`git push origin feature/NuovaFeature`)
5. Apri una Pull Request

### Linee Guida

* Segui lo stile di codice esistente
* Aggiungi commenti esplicativi
* Testa accuratamente le modifiche
* Aggiorna la documentazione

---

## ✉️ Contatti e Supporto

* **Email**: [gianlucabevilacqua.93@gmail.com](mailto:gianlucabevilacqua.93@gmail.com)
* **GitHub Issues**: [Segnala un problema](https://github.com/GianlucaBevilacqua93/google-drive-downloader/issues)

---

**Made with ❤️ by the Open Source Community**

*Star ⭐ questo repository se lo trovi utile!*

---

## 🇬🇧 English

### 📖 Overview

This project provides a **Google Colab notebook** that allows downloading files from URLs directly to your **Google Drive**. Ideal for those with ample Drive storage space who want to automate downloading large files without consuming local bandwidth or storage.

### System Architecture

```
┌─────────────┐      ┌──────────────┐      ┌─────────────────┐
│     URL     │─────▶│   Google     │─────▶│  Google Drive   │
│   Source    │      │    Colab     │      │   (Storage)     │
└─────────────┘      └──────────────┘      └─────────────────┘
    
```

### 📦 Project Structure

```
google-drive-downloader/
├── code/
│   └── URLDownloader.ipynb        # Main Google Colab notebook
└── README.md
```

---

## 🚀 Key Features

* ✅ **Direct cloud download** - Files downloaded directly to Google Drive
* ✅ **No local bandwidth consumption** - Uses Google's connection
* ✅ **Large file support** - No local storage limitations
* ✅ **Secure authentication** - Google OAuth 2.0
* ✅ **Multi-protocol compatible** - HTTP, HTTPS, FTP
* ✅ **Completely free** - Uses free Google Colab resources

---

## 📋 Requirements

* **Google Account** with Google Drive access
* **Google Drive space** - At least 15 GB recommended (ideal for Google One 100 GB+ accounts)
* **Modern web browser**
* **Stable internet connection**

> ⚠️ **Note**: This project is particularly suitable for accounts with ample Google Drive storage.

---

## 🎯 Installation and Usage

### Step 1: Opening the Notebook

1. Click this link to open the notebook directly in Google Colab:
   
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GianlucaBevilacqua93/google-drive-downloader/blob/main/code/URLDownloader.ipynb)

2. Or open manually:
   * Go to [Google Colab](https://colab.research.google.com/)
   * `File` → `Open notebook` → `GitHub`
   * Paste: `https://github.com/GianlucaBevilacqua93/google-drive-downloader/blob/main/code/URLDownloader.ipynb`

### Step 2: Google Drive Authorization

When running the notebook for the first time:

1. Run the first cell of the notebook
2. Click the authorization link
3. Sign in with your Google account
4. Grant the required permissions
5. Your Drive will be mounted in the Colab session

### Step 3: Enter URLs

Enter the URL of file to download at runtime.

### Step 4: Start Download

Run the notebook cells and wait for completion. Files will be saved in the specified Google Drive folder.

---

## 💡 Advantages

* 🚀 **Speed** - Leverages Google's cloud infrastructure
* 💾 **Space saving** - Doesn't occupy local device memory
* 🌐 **Accessible anywhere** - Works from any device with browser
* 📱 **Multi-device** - Files remain on cloud accessible anywhere

---

## ⚠️ Limitations

* 🔒 **Protected files** - Doesn't work with content requiring specific authentication
* 🌐 **Connection dependency** - Requires stable internet connection
* 💾 **Available space** - Requires sufficient Google Drive space

---

## 🔮 Future Development

### Version 2.0
- [ ] User-friendly graphical interface
- [ ] Queue management system for multiple downloads
- [ ] Automatic resume on interruption
- [ ] Synchronization with other cloud platforms
- [ ] Multi-threaded parallel downloads
- [ ] Integrity verification
- [ ] Advanced logging system

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the project
2. Create a branch (`git checkout -b feature/NewFeature`)
3. Commit your changes (`git commit -m 'Add NewFeature'`)
4. Push to the branch (`git push origin feature/NewFeature`)
5. Open a Pull Request

## ✉️ Contacts and Support

* **Email**: [gianlucabevilacqua.93@gmail.com](mailto:gianlucabevilacqua.93@gmail.com)
* **GitHub Issues**: [Report an issue](https://github.com/GianlucaBevilacqua93/google-drive-downloader/issues)

---

**Made with ❤️ by the Open Source Community**

*Star ⭐ this repository if you find it useful!*
