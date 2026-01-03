# 🛒 Dispensa Smart PWA - La Tua Cucina Organizzata

## 📱 Cos'è?

**Dispensa Smart** è una Progressive Web App (PWA) per gestire il tuo inventario di casa e la lista della spesa. Funziona come un'app nativa e può essere installata sul tuo telefono!

---

## ✨ Funzionalità

### 🏠 Inventario Casa
- Gestisci tutti i prodotti che hai in casa
- Quantità e unità di misura personalizzabili
- Note personalizzate per ogni prodotto

### 📝 Lista della Spesa
- Crea e gestisci la tua lista della spesa
- Spunta gli articoli mentre fai la spesa
- Sposta facilmente gli articoli tra inventario e lista

### 🔍 Autocomplete Intelligente
- **70+ alimenti** pre-configurati
- Ricerca predittiva: scrivi "pat" → suggerisce "Patata"
- Unità di misura automatiche (Latte → L, Patate → kg)

### 📊 Statistiche
- Grafico a torta della distribuzione per categoria
- Percentuali dettagliate
- 9 categorie colorate

### 📏 Unità di Misura
- **pz** (pezzi), **kg**, **g**, **L**, **ml**
- **confezione**, **scatola**, **vasetto**, **bottiglia**, **pacco**
- Unità predefinite intelligenti per ogni alimento

### 💾 Progressive Web App
- ✅ Installabile come app nativa
- ✅ Funziona offline
- ✅ Velocissima
- ✅ Nessun app store necessario

---

## 🚀 Installazione Rapida

### Passo 1: Metti Online l'App

Scegli una di queste opzioni **GRATUITE**:

#### Opzione A: GitHub Pages (Consigliato)
1. Crea un account su https://github.com
2. Crea un nuovo repository pubblico
3. Carica tutti i file (dispensa-smart-pwa.html, manifest.json, service-worker.js, icon-192.png, icon-512.png)
4. Vai su Settings → Pages → Source: main branch → Save
5. Il tuo URL sarà: `https://tuo-username.github.io/nome-repo/dispensa-smart-pwa.html`

#### Opzione B: Netlify (Più Veloce)
1. Vai su https://app.netlify.com/drop
2. Trascina tutti i 5 file
3. Ottieni il tuo URL: `https://nome-casuale.netlify.app`

### Passo 2: Installa sul Telefono

**Android:**
1. Apri l'URL in Chrome
2. Clicca sul banner "📲 Installa App"
3. Oppure: Menu → "Installa app"

**iPhone:**
1. Apri l'URL in Safari
2. Tocca "Condividi" → "Aggiungi a Home"

---

## 📦 File Inclusi

```
📁 Dispensa Smart PWA
├── 📄 dispensa-smart-pwa.html    ← App principale (apri questo!)
├── 📄 manifest.json              ← Configurazione PWA
├── 📄 service-worker.js          ← Funzionamento offline
├── 🖼️ icon-192.png               ← Icona piccola
├── 🖼️ icon-512.png               ← Icona grande
├── 📖 GUIDA-INSTALLAZIONE-PWA.md ← Guida dettagliata
└── 📖 README.md                  ← Questo file
```

---

## 🎯 Categorie Alimenti

L'app include **70+ alimenti** organizzati in 9 categorie:

- 🍎 **Frutta** (14 alimenti) - Rosa
- 🥕 **Verdura** (14 alimenti) - Verde
- 🫘 **Legumi** (5 alimenti) - Marrone
- 🥛 **Latticini** (7 alimenti) - Azzurro
- 🥩 **Carne** (6 alimenti) - Rosso
- 🐟 **Pesce** (6 alimenti) - Cyan
- 🍝 **Cereali** (6 alimenti) - Arancione
- 🫒 **Condimenti** (6 alimenti) - Viola
- 💧 **Bevande** (6 alimenti) - Blu

---

## 💡 Come Usare

### Aggiungere un Alimento
1. Scrivi il nome (es. "lat" per Latte)
2. Seleziona dal menu o continua a scrivere
3. Scegli quantità (es. "2")
4. L'unità si imposta automaticamente (Latte → L)
5. (Opzionale) Aggiungi note personali
6. Clicca "+"

### Gestire gli Articoli
- **📝** = Modifica note
- **🛒/🏠** = Sposta tra inventario e lista
- **○/✓** = Spunta nella lista spesa (solo lista)
- **🗑️** = Elimina

### Vedere le Statistiche
1. Vai alla tab "Statistiche"
2. Visualizza il grafico a torta
3. Controlla le percentuali per categoria

---

## 🌟 Caratteristiche PWA

### Offline First
L'app funziona anche **senza connessione internet** dopo la prima apertura!

### Installabile
Appare nella home screen come un'app nativa, nessun app store necessario.

### Veloce
Caricamento istantaneo grazie alla cache del Service Worker.

### Aggiornamenti Automatici
Quando carichi nuove versioni, l'app si aggiorna automaticamente.

---

## 🔧 Personalizzazione

### Cambiare le Icone
1. Crea due PNG: 192x192px e 512x512px
2. Sostituisci `icon-192.png` e `icon-512.png`
3. Ricarica sul server

### Cambiare Nome o Colori
1. Modifica `manifest.json`:
   - `name`: Nome completo
   - `short_name`: Nome abbreviato
   - `theme_color`: Colore principale
   - `background_color`: Sfondo
2. Ricarica il file

---

## 📊 Tecnologie Usate

- **HTML5** - Struttura
- **CSS3** - Stile moderno e gradients
- **JavaScript Vanilla** - Logica e interattività
- **Canvas API** - Grafico a torta
- **Service Worker** - Funzionamento offline
- **Web App Manifest** - Installabilità PWA
- **LocalStorage** - Salvataggio dati

---

## 🎨 Design

- Gradiente moderno blu-viola
- 9 colori distintivi per le categorie
- Interfaccia mobile-first
- Animazioni fluide
- Emoji native per le icone degli alimenti

---

## 📱 Compatibilità

### ✅ Supporto Completo
- Chrome Android 90+
- Safari iOS 15+
- Edge 90+
- Samsung Internet 14+

### ⚠️ Supporto Parziale
- Firefox Android (no installazione automatica)
- Safari iOS 14 (alcune limitazioni PWA)

---

## 🐛 Risoluzione Problemi

**L'app non si installa?**
- Verifica di essere su HTTPS
- Cancella cache del browser
- Riavvia il browser

**Non funziona offline?**
- Apri l'app almeno una volta online
- Controlla che il Service Worker sia registrato (F12 → Application → Service Workers)

**Icone non appaiono?**
- Verifica che i file PNG siano nella stessa cartella
- Cancella cache e ricarica

---

## 🚀 Prossimi Sviluppi (Idee)

- [ ] Sincronizzazione cloud tra dispositivi
- [ ] Scanner codici a barre
- [ ] Ricette basate sugli ingredienti disponibili
- [ ] Notifiche scadenze
- [ ] Export/Import dati
- [ ] Condivisione liste con familiari
- [ ] Integrazione supermercati online

---

## 📄 Licenza

Progetto dimostrativo - Libero da usare e modificare

---

## 🙏 Credits

Creato con ❤️ per rendere la gestione della cucina più semplice e organizzata!

---

## 📞 Supporto

Hai domande o problemi? Consulta la **GUIDA-INSTALLAZIONE-PWA.md** per istruzioni dettagliate!

**Buona organizzazione! 🛒✨**
