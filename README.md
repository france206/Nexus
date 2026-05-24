# Nexus
# NEXUS: Modern Age (Geopolitical AI Simulator)

NEXUS: Modern Age è un simulatore geopolitico e macroeconomico open-source di nuova generazione per Android, progettato per superare i limiti dei classici giochi di strategia basati su script rigidi. Il progetto introduce un framework ad agenti multi-AI eseguiti interamente in locale sul dispositivo dell'utente, combinando un motore economico a circuito chiuso con un'interfaccia utente iper-fluida.

## 🚀 Visione del Progetto
Attualmente, i simulatori politici su mobile soffrono di eccessiva semplificazione o di interfacce utente macchinose. NEXUS risolve questo problema introducendo due pilastri fondamentali:
1. **Comodità Conversazionale:** Gestione totale dello Stato attraverso un dialogo in linguaggio naturale con il proprio Gabinetto dei Ministri potenziato da Intelligenza Artificiale.
2. **Sovranità dei Dati e Privacy-First:** Tutta l'elaborazione dei modelli linguistici avviene offline sul dispositivo (Edge AI), senza alcuna dipendenza da server cloud di terze parti o tracciamento dei dati sensibili.

## 🛠️ Stack Tecnologico
Il progetto adotta un'architettura modulare progettata per massimizzare le prestazioni hardware riducendo drasticamente l'impatto sulla batteria:

*   **Core Simulator Engine:** Scritto in **Rust**, responsabile dei calcoli matematici ad alta frequenza per le variabili macroeconomiche dello Stato.
*   **Edge AI Client:** Runtime ottimizzato basato su **ONNX / Llama.cpp** per l'esecuzione locale di modelli linguistici quantizzati ed estremamente efficienti (es. Gemma 3 1b).
*   **Android Application:** Sviluppata nativamente in **Kotlin** utilizzando **Jetpack Compose** per un'interfaccia grafica moderna, reattiva e priva di attriti visivi.

## 📊 Modello Macroeconomico
Il motore economico non utilizza valori arbitrari, ma simula un circuito macroeconomico chiuso regolato dalle equazioni di stato standard.

Il PIL (Y) viene ricalcolato dinamicamente ad ogni turno:
Y = C + I + G + (X - M)

La sostenibilità del Debito Pubblico (D) risponde alla variazione dei tassi di interesse (r) in base alla stabilità geopolitica ed al consenso interno:
Delta_D = G - T + r * D_previous

## 🤖 Sistema ad Agenti Multi-AI Local-First
Ogni nazione estera e ogni ministero interno è gestito da un agente intelligente autonomo. Attraverso l'ottimizzazione dei pesi del modello locale, l'applicazione simula:
* **Ministro dell'Economia:** Monitoraggio contabile, gestione della partita doppia dello Stato, previsioni inflazionistiche e suggerimenti di manovre finanziarie.
* **Geopolitica Dinamica:** Le nazioni rivali reagiscono ai trattati commerciali e alle sanzioni analizzando l'impatto reale sulle proprie catene di approvvigionamento (Semiconduttori, Terre Rare, Energia).

## 📄 Licenza
Questo progetto è rilasciato sotto licenza **Apache License 2.0**. È possibile utilizzare, modificare e distribuire il software anche per scopi commerciali, a condizione di mantenere intatta la licenza open-source della spina dorsale tecnologica.
