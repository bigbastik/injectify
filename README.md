# 🚀 Injectify
### HTML Injector + Code Analyzer + Auto‑Fixer (Windows EXE)

Injectify è un’applicazione avanzata per Windows che permette di modificare automaticamente file HTML, HTM e PHP, inserendo codice in punti specifici della pagina.  
Include un analizzatore intelligente per HTML, CSS e JavaScript con patch automatiche.

Questo repository contiene **solo la versione compilata (.exe)** dell’applicazione, pronta all’uso.

---

## ✨ Funzionalità principali

### 🔧 Injection Engine
- Inserimento codice in:
  - Dentro `<head>`
  - Prima di `</head>`
  - Subito dopo `<body>`
  - Prima di `</body>`
  - Dentro `<footer>`
  - Prima di `</footer>`
  - Inizio file
  - Fine file
- Anti‑duplicazione tramite hash SHA‑256
- Backup automatico dei file modificati
- Supporto per cartelle e multi‑file

---

## 🧠 Code Analyzer Ultra
Analisi avanzata del codice con:

- Parsing HTML (BeautifulSoup + lxml)
- Parsing CSS (cssutils)
- Parsing JavaScript (esprima)
- Rilevamento:
  - tag non chiusi
  - attributi mancanti (`alt`, `href`, ecc.)
  - errori CSS
  - errori JS
- Patch automatiche sicure con un click

---

## 🖥 Interfaccia moderna
- Tema Dark/Light
- Editor codice integrato
- Anteprima live del file modificato
- Report dettagliato delle anomalie
- Pulsante “Analizza + Patcha”

---

## 📦 Download
Scarica l’ultima versione da:

👉 **Releases** → `Injectify.exe`

Non richiede installazione.  
Basta avviare l’eseguibile.



