# 📝 INI Editor

[![Python](https://img.shields.io/badge/Python-3.6%2B-blue)](https://www.python.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey)](https://github.com/yourusername/ini-editor)

Un editor di file INI moderno con interfaccia grafica che ti permette di visualizzare e modificare i file di configurazione INI in modo semplice e intuitivo, mantenendo i commenti inline e offrendo un'esperienza utente elegante.

## ✨ Caratteristiche

- 🖥️ **Interfaccia grafica intuitiva** con layout a doppio pannello
- 📊 **Visualizzazione strutturata** di sezioni e proprietà
- 📝 **Supporto completo per commenti inline** (mantiene i commenti accanto ai valori)
- 🔄 **Modifica diretta** tramite doppio click
- 📂 **Gestione file completa** (nuovo, apri, salva, salva con nome)
- ⌨️ **Scorciatoie da tastiera** per operazioni comuni
- 🔍 **Supporto multi-piattaforma** (Windows, macOS, Linux)

## 🚀 Installazione

```bash
# Clona il repository
git clone https://github.com/yourusername/ini-editor.git

# Naviga nella directory
cd ini-editor

# Esegui l'applicazione
python main.py
```

## 🛠️ Requisiti

- Python 3.6 o superiore
- Tkinter (incluso nella maggior parte delle installazioni Python standard)

## 📖 Come utilizzare

### Operazioni base

- **Creare un nuovo file**: Menu → File → Nuovo
- **Aprire un file esistente**: Menu → File → Apri
- **Salvare le modifiche**: Menu → File → Salva (o `Ctrl+S`)
- **Salvare con nome**: Menu → File → Salva con nome

### Lavorare con le sezioni

- **Aggiungere una sezione**: Clicca sul pulsante "Aggiungi" nel pannello delle sezioni
- **Rimuovere una sezione**: Seleziona una sezione e clicca su "Rimuovi"

### Lavorare con le proprietà

- **Aggiungere una proprietà**: Seleziona una sezione e clicca sul pulsante "Aggiungi" nel pannello delle proprietà
- **Modificare una proprietà**: Doppio click sulla proprietà nella tabella
- **Rimuovere una proprietà**: Seleziona una proprietà e clicca su "Rimuovi"

## 🧰 Architettura

Il progetto è composto da due classi principali:

1. **CustomConfigParser**: Un parser personalizzato che gestisce i file INI preservando i commenti inline.
2. **IniEditorApp**: L'interfaccia grafica che utilizza Tkinter per fornire un'esperienza utente intuitiva.

## 🔍 Caratteristiche tecniche

Il parser personalizzato offre diverse funzionalità avanzate:

- Mantenimento dei commenti inline accanto ai valori
- Supporto per diversi prefissi di commento (`#`, `;`)
- API simile a ConfigParser standard di Python
- Gestione robusta delle sezioni e delle proprietà

## 🤝 Contribuire

I contributi sono benvenuti! Se desideri contribuire a questo progetto:

1. Fai un fork del repository
2. Crea un branch per la tua feature (`git checkout -b feature/NuovaFeature`)
3. Committa le tue modifiche (`git commit -m 'Aggiunta nuova feature'`)
4. Effettua il push al branch (`git push origin feature/NuovaFeature`)
5. Apri una Pull Request

## ⚠️ Note sulla compatibilità

L'applicazione è stata progettata per funzionare su tutte le principali piattaforme, ma potrebbe richiedere piccole modifiche per adattarsi al meglio a ciascun sistema operativo.

## 📄 Licenza

Questo progetto è distribuito con licenza MIT. Vedi il file `LICENSE` per maggiori dettagli.
