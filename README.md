# Utilizzo del Nomogramma per la Previsione di Metastasi nel Tumore al Seno

## Descrizione
Questa repository contiene l'analisi statistica e il codice R sviluppati per il mio progetto di **Tesi di Laurea Triennale** in *Statistica per le Tecnologie e le Scienze* presso l'Università degli Studi di Padova (A.A. 2024/2025).

Il lavoro si concentra sulla costruzione delle fondamenta statistiche per un **nomogramma clinico**, uno strumento predittivo basato su modelli matematici. L'obiettivo è stimare la probabilità di riscontrare metastasi nei linfonodi non sentinella (non-SLN) in pazienti affette da carcinoma mammario, analizzando l'impatto di diverse caratteristiche clinico-patologiche e dello stato del linfonodo sentinella.

## Metodologia e Modelli
L'analisi è strutturata in due parti:
1. **Analisi Esplorativa (EDA):** Indagine univariata e bivariata delle relazioni tra variabili cliniche (es. correlazione tra dimensione della metastasi e linfonodi non-SLN positivi) mediante test non parametrici (Kruskal-Wallis, Mann-Whitney) e test del Chi-quadrato.
2. **Modellazione Statistica:** Implementazione di un **Modello Lineare Generalizzato (GLM)** con distribuzione Binomiale e funzione di legame *logit* (Regressione Logistica per dati raggruppati), selezionando le variabili predittive tramite procedura *forward*.

## Risultati e Validazione
Il modello finale, validato tramite curva ROC (AUC = 0.77), identifica i principali fattori di rischio associati alla positività dei linfonodi non sentinella. L'analisi fornisce indicazioni preziose per il supporto alle decisioni cliniche, pur evidenziando aree di miglioramento legate alla sovradispersione dei dati che potranno essere oggetto di sviluppi futuri.

## Contenuto della Repository
* `tesi.Rmd`: Script R Markdown completo per l'analisi: data cleaning, generazione dei grafici esplorativi, selezione delle variabili e diagnostica del modello binomiale.
* `Perin_Leonardo.pdf`: Il documento di tesi completo.
* `Presentazione_Perin_Leonardo.pdf`: Le slide utilizzate per la discussione della tesi.

## Autore
* **Leonardo Perin** - *Laureando in Statistica per le Tecnologie e le Scienze, Università degli Studi di Padova*
