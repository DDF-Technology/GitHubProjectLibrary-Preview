# Note di versione

## 0.2.0-preview1 — Demo Read-Only pubblica

- Interfaccia derivata dalla versione Full, con dashboard, catalogo, dettagli, README e statistiche reali.
- Collegamento GitHub tramite PAT con permessi di sola lettura e credenziale DPAPI separata dalla Full.
- Clone, fetch, pull, scansione locale, launcher, ricerca eseguibili e generazione prompt disabilitati.
- Assembly Infrastructure, Git e App della Full esclusi automaticamente dal pacchetto.
- Preview distribuita senza firma Authenticode, con checksum SHA-256 pubblico e avvertenza esplicita.

## 0.1.0-rc4 — candidato pre-release

- Interfaccia riallineata visivamente alla versione Full.
- Stesse dimensioni della finestra, header, sidebar, titoli, contatori, card e tabella.
- Avvertenza Demo spostata nella barra di stato inferiore per conservare la gerarchia visiva della Full.
- Screenshot pubblici rigenerati dopo il confronto diretto delle due applicazioni.

## 0.1.0-rc1 — candidato pre-release

- Prima Demo offline autonoma di GitHub Project Library.
- Dashboard, catalogo sintetico, confronto delle edizioni e informazioni.
- Nessun accesso a rete, GitHub, token, repository locali, database o strumenti Git.
- Badge Demo e avvertenza pre-release sempre visibili.
- Self-test e controlli automatici di separazione dalla versione Full.

La preview 0.2.0 può essere distribuita senza firma Authenticode con approvazione del proprietario.
La firma resta un requisito previsto per le future release stabili o quasi definitive.
