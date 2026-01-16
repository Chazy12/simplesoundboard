# 🎵 Soundboard

Una soundboard professionale con 48 pad personalizzabili, trimming audio integrato, effetti di fade in/out e supporto multilingua.

![Soundboard](logo.png)

## ✨ Caratteristiche

### 🎛️ 48 Pad Personalizzabili
- **4 Categorie**: Intro, Suoni, Musiche, Effetti
- **12 pad per categoria** con colori personalizzabili
- **Assegnazione audio** con nomi custom

### ✂️ Audio Trimmer Integrato
- **Visualizzazione waveform** in tempo reale
- **Selezione precisa** di inizio e fine tramite slider
- **Anteprima** della porzione selezionata
- **Timer durata** aggiornato dinamicamente
- **Salvataggio automatico** solo della porzione tagliata

### 🎚️ Controllo Volume
- **Sidebar volume** sempre visibile
- **Regolazione master** per tutti i pad
- **Mute rapido** con un click

### 🎭 Effetti Audio Professionali
- **Fade In** di 1 secondo all'avvio
- **Fade Out** di 3 secondi allo stop
- **Transizioni fluide** tra tracce

### 🌍 Multilingua
- **Italiano** 🇮🇹
- **English** 🇬🇧
- Selezione lingua al primo avvio

### 📱 Design Responsivo
- **Desktop**: Vista a griglia completa (4 categorie visibili)
- **Tablet**: Vista paginata con navigazione a pallini
- **Mobile**: Vista a colonne ottimizzata

### 💾 Salvataggio Locale
- **localStorage**: Tutti i dati salvati localmente
- **Audio base64**: Nessun bisogno di server
- **Persistenza**: I tuoi pad rimangono anche dopo il riavvio

## 🎮 Come Usare

### Aggiungere Audio a un Pad

1. **Click su pad vuoto** → Si apre il configuratore
2. **Inserisci nome** del pad
3. **Scegli colore** dalla palette
4. **Seleziona file audio** (MP3, WAV, OGG, etc.)
5. **(Opzionale) Taglia audio**:
   - Muovi lo slider **Inizio** per impostare il punto di partenza
   - Muovi lo slider **Fine** per impostare il punto finale
   - Clicca **▶️ Anteprima** per ascoltare la selezione
   - Visualizza la **durata** in tempo reale
6. **Clicca Salva**

### Riproduzione Audio

- **Click singolo su pad popolato** → 
  - ▶️ **Avvia audio** con fade in di 1 secondo
  - ⏹️ Se già in riproduzione: **Stop con fade out** di 3 secondi

- **Long press (tieni premuto)** → 
  - Apre il **modal di modifica**
  - Puoi cambiare nome, colore, audio

### Gestione Pad

- **Svuota**: Rimuove tutto dal pad
- **Annulla**: Chiudi senza salvare
- **Salva**: Conferma modifiche

### Controllo Volume

- **Slider verticale** a destra dello schermo
- **🔊 Click icona** per mute/unmute rapido
- **Percentuale** visualizzata in tempo reale

## 📋 Requisiti di Sistema

- **Sistema Operativo**: Linux (Ubuntu 20.04+, Debian 10+, Linux Mint 20+)
- **Browser**: Chromium, Chrome, o Firefox
- **RAM**: 512 MB minimo
- **Storage**: 50 MB per l'applicazione + spazio per audio

## 🚀 Installazione

### Metodo 1: Pacchetto .deb (Consigliato)

```bash
# Scarica l'ultima release da GitHub
wget https://github.com/tuousername/soundboard/releases/download/v1.0.0/soundboard_1.0.0_amd64.deb

# Installa
sudo dpkg -i soundboard_1.0.0_amd64.deb

# Lancia l'applicazione
soundboard
```

### Metodo 2: Eseguibile Standalone

```bash
# Scarica index.html e logo.png
# Apri index.html con il tuo browser preferito
xdg-open index.html
```

## ⌨️ Scorciatoie da Tastiera

| Azione | Tasto |
|--------|-------|
| Chiudi modal | `ESC` |
| Salva pad | `Enter` (nel modal) |

## 🛠️ Tecnologie Utilizzate

- **HTML5**: Struttura
- **CSS3**: Styling responsivo
- **JavaScript Vanilla**: Logica applicazione
- **Web Audio API**: Processing e trimming audio
- **localStorage API**: Persistenza dati
- **Canvas API**: Visualizzazione waveform

## 📊 Limiti

- **Dimensione audio**: Max 5 MB per file (limitazione localStorage)
- **Numero pad**: 48 fissi (12 per categoria)
- **Formati audio**: Quelli supportati dal browser (MP3, WAV, OGG, M4A)

## 🐛 Risoluzione Problemi

### L'audio non si sente
- Controlla il volume master (sidebar destra)
- Verifica che il formato audio sia supportato
- Ricarica la pagina

### Il trimmer non funziona
- Assicurati che il file audio sia valido
- Prova con un file più piccolo
- Usa formato MP3 o WAV

### I pad non si salvano
- Verifica che localStorage sia abilitato nel browser
- Controlla la dimensione totale dei dati (max ~5-10MB)
- Prova a svuotare alcuni pad

## 📝 Changelog

### v1.0.0 (2026-01-16)
- 🎉 Release iniziale
- ✂️ Audio trimmer integrato
- 🌍 Supporto multilingua (IT/EN)
- 🎭 Effetti fade in/out
- 💾 Salvataggio locale

## 📄 Licenza

Questo progetto è distribuito sotto licenza MIT.

## 👤 Autore

**Chazy**

## 🤝 Contribuire

I contributi sono benvenuti! Sentiti libero di aprire issue o pull request.

## ⭐ Supporto

Se ti piace questo progetto, lascia una stella su GitHub!

---

Made with ❤️ for the audio community
