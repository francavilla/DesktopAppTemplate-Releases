# DesktopAppTemplate

Modello di solution per applicazioni desktop **.NET Framework** con architettura a slice e interfaccia a scelta
**WPF** o **Windows Forms** (`--ui wpf|winforms`), con configurazione unificata (App.config + riga di comando),
accesso ai dati ADO.NET (SQL Server o SQLite) e logging su file e/o database.

Questo repository contiene **solo le versioni pronte da scaricare**.

## Download

➡ **[Ultima versione](https://github.com/francavilla/DesktopAppTemplate-Releases/releases/latest)** —
oppure l'elenco completo in [Releases](https://github.com/francavilla/DesktopAppTemplate-Releases/releases).

Nella pagina della release, sezione **Assets**, scaricare `DesktopAppTemplate-vX.Y.Z.zip`
(gli archivi "Source code" generati da GitHub non servono).

## Requisiti

- Windows 10 o 11 con **.NET Framework 4.6.2** o successivo.
- Per il database predefinito: **SQL Server** sull'istanza locale (`Server=.;Database=ClaudeDB`, creato se manca).
  Senza SQL Server avviare con `--storage sqlite`.

## Primo avvio

1. Clic destro sullo zip → **Estrai tutto…** in una cartella (serve tutto il contenuto, non solo l'`.exe`).
2. Avviare **`DesktopAppTemplate.exe`**; `--help` elenca le opzioni.
3. Se Windows mostra *"Windows ha protetto il PC"* (l'eseguibile non è firmato digitalmente):
   **Ulteriori informazioni → Esegui comunque**. Succede solo la prima volta.

Le novità di ogni versione sono descritte nelle note della relativa release.
