# Grey Hack - Traduzione Italiana 🇮🇹

<div align="center">
  <img alt="Grey Hack Logo" src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/605230/header.jpg?t=1713885604" width="600px">
  <br><br>

  <!-- Badge informativi, di stato e download tracker -->
  <a href="https://store.steampowered.com/app/605230/Grey_Hack/"><img src="https://img.shields.io/badge/Gioco-Grey%20Hack-blue?style=for-the-badge&logo=steam" alt="Grey Hack Game"></a>
  <a href="https://github.com/GLWine/Grey-Hack-Traduzione-Italiana/releases/latest"><img src="https://img.shields.io/github/v/release/GLWine/Grey-Hack-Traduzione-Italiana?style=for-the-badge&color=success" alt="Latest Release"></a>
  <img src="https://img.shields.io/badge/Versione%20Gioco-V0.9.7195a-orange?style=for-the-badge" alt="Game Version">
  <a href="https://github.com/GLWine/Grey-Hack-Traduzione-Italiana/releases"><img src="https://img.shields.io/github/downloads/GLWine/Grey-Hack-Traduzione-Italiana/total?style=for-the-badge&color=blue" alt="Total Downloads"></a>
  <a href="https://github.com/GLWine/Grey-Hack-Traduzione-Italiana/blob/main/LICENSE"><img src="https://img.shields.io/github/license/GLWine/Grey-Hack-Traduzione-Italiana?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/GLWine/Grey-Hack-Traduzione-Italiana/actions"><img src="https://img.shields.io/github/actions/workflow/status/GLWine/Grey-Hack-Traduzione-Italiana/create-folders-on-release.yml?style=for-the-badge&label=Build" alt="Build Status"></a>
</div>

---

## 📖 Informazioni sul Progetto

Benvenuto nel repository ufficiale della **traduzione in italiano di Grey Hack**. 

Questo progetto nasce per offrire un'esperienza di gioco localizzata ed estesa. La traduzione copre la maggioranza dei testi presenti all'interno del gioco, inclusi:

* 🖥️ **Interfaccia di sistema** e menu di configurazione.
* 📜 **Documentazione tecnica** per le API di GreyScript (`computer`, `shell`, `metalib`, `router`, ecc.).
* 💬 **Missioni, dialoghi ed email** degli NPC.
* 📚 **Tutorial e guide** per i nuovi giocatori.

> ⚠️ *Nota:* La traduzione non è al 100% integrale, ma copre la quasi totalità dei contenuti principali e giocabili.

---

## 🚀 Come Installare la Traduzione

1. Scarica l'ultimo file `custom_lang.json` rilasciato nella sezione [Releases](https://github.com/GLWine/Grey-Hack-Traduzione-Italiana/releases).
2. Copia il file nel seguente percorso sul tuo computer:
   ```text
   %USERPROFILE%/AppData/LocalLow/Loading Home/Grey Hack/Translation/
   ```
3. Avvia **Grey Hack** e seleziona la lingua custom dalle impostazioni di gioco.

---

## 🛠️ Struttura del Repository

```text
.
├── .github/
│   └── workflows/
│       ├── create-folders-on-release.yml  # Genera la struttura cartelle al release
│       └── validate-json.yml             # Valida la sintassi JSON del file traduzione
├── custom_lang.json                       # File principale della localizzazione
├── version                                # Versione corrente del gioco supportata
├── LICENSE                                # Licenza open-source MIT
└── README.md                              # Documentazione del repository
```

---

## 🤝 Contribuire

Se trovi errori di traduzione, rifusi o vuoi estendere i testi mancanti:

1. Fai un **Fork** di questo repository.
2. Apporta le modifiche al file `custom_lang.json`.
3. Assicurati di **aggiornare anche il file `version`** allineandolo con la versione corrente del gioco che stai traducendo.
4. Verifica che la sintassi JSON sia corretta (il workflow eseguirà un controllo automatico).
5. Apri una **Pull Request**.

---

## 📜 Licenza

Questo progetto è distribuito sotto la licenza **MIT**. Consulta il file [LICENSE](LICENSE) per ulteriori dettagli.
