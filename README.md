# 🚀 MediaFlow Proxy per HuggingFace

> **Utilizza questo Dockerfile per installare facilmente qualsiasi MediaFlow Proxy su HuggingFace Spaces**

## 📋 Descrizione

Questo progetto fornisce un Dockerfile ottimizzato per deployare MediaFlow Proxy su HuggingFace Spaces, combinando le funzionalità di due repository principali:

- 🎯 **[mhdzumair/mediaflow-proxy](https://github.com/mhdzumair/mediaflow-proxy)** - Proxy server ad alte prestazioni per streaming media
- 🔧 **[nzo66/HF-MFP](https://github.com/nzo66/HF-MFP)** - Configurazioni specifiche per HuggingFace

## ✨ Caratteristiche

- 📦 **Setup automatico** - Clone e merge automatico di entrambi i repository
- 🐳 **Docker ottimizzato** - Immagine leggera basata su Python 3.10
- ⚡ **Performance elevate** - Configurato con Uvicorn e 4 workers
- 🔒 **Sicuro** - Supporto per DRM e proxy avanzati
- 🌐 **HuggingFace Ready** - Preconfigurato per Spaces

## 🛠️ Installazione

### Opzione 1: HuggingFace Spaces
1. Crea un nuovo Space su HuggingFace
2. Carica questo Dockerfile
3. (OPZIONALE) Modifica il link per mediaflow-proxy se ne vuoi usare uno custom
4. Il deployment avverrà automaticamente

