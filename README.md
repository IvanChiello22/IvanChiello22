# Ciao, sono Ivan Chiello! 👋

🎓 **Computer Science Student** | 💻 **Software Engineering & Tech Enthusiast**

Benvenuto sul mio profilo GitHub! Qui raccolgo i progetti accademici e personali.

---

### 🚀 Progetti in Evidenza

### 🔬 Progetto di Tesi / Research Highlight

#### 🌱 [Tesi Triennale - Identificazione e Refactoring di pratiche sostenibili automatici con LLM](https://github.com/IvanChiello22/IdentificazionePraticheSostenibiliThesis)
> **Empirical Research on Green AI Tactics, LLM-based Identification & Refactoring Benchmarks.**
* *Ruolo:* Autore / Ricerca & Sviluppo Tesi di Laurea
* **Descrizione:** Progetto di ricerca sperimentale incentrato sull'identificazione automatica e sul refactoring di pratiche di sostenibilità energetica nel codice (Green AI) tramite modelli di linguaggio avanzati (LLM come GPT-4o mini e GPT-5 mini).
* **Focus sulle Tattiche di Sostenibilità:**
  * **T11:** Utilizzo di funzioni built-in ottimizzate nelle librerie anziché implementazioni ad alto consumo computazionale.
  * **T15:** Energy-aware pruning e compressione dei modelli.
  * **T19:** Adozione di checkpointing strategico durante l'addestramento per prevenire sprechi energetici dovuti a interruzioni.
* **Architettura & Contributo Tecnico:**
  * Costruzione del dataset etichettato (`corpo/SnippetTot.json`) strutturato per categorie e combinazioni di tattiche.
  * Sviluppo della pipeline di valutazione (`llm_eval_green_tactics_identification.py`) con supporto multi-provider (OpenAI, Anthropic) e modalità deterministica offline/dummy.
  * Pipeline automatizzata di batch refactoring (`refactor_runner.py`) con generazione di manifest e tracciamento dei metadati di esecuzione.
  * Strumenti di analisi comparativa a 2 e 3 vie (`compare_refactor_outputs.py`, `tri_compare_refactor.py`) per generare metriche sintetiche, report in Markdown, tabelle CSV e diff visivi HTML side-by-side.
* **Tecnologie:** `Python 3.10+` `LLM Prompt Engineering` `OpenAI API` `Green Computing` `Empirical Software Engineering` `Data Mining`
* 
---

#### 🌿 [Green-SE4AI](https://github.com/LuigiAuriemma/Green-SE4AI)
> **Framework per la profilazione energetica ibrida e l'ottimizzazione dell'impatto ambientale nella generazione automatica di unit test con LLM/SLM.**
* **Descrizione:** Piattaforma di benchmarking per valutare e ridurre l'impronta carbonica (CO2) e il consumo energetico (kWh) durante la generazione di suite di test con modelli di intelligenza artificiale sul dataset `HumanEval+`.
* **Punti chiave**
  * **Ottimizzazione Sintattica AST (GreenTransformer):** Pre-processing del codice sorgente via Abstract Syntax Tree per abbattere il consumo di token (rimozione docstring, type hints e token minification) preservando l'integrità logica.
  * **Profilazione Energetica Ibrida:** Tracciamento simultaneo di CPU/RAM locale con **CodeCarbon** e **psutil**, unito alla stima di impatto cloud d'inferenza e latenza via **EcoLogits**.
  * **Valutazione della Qualità del Codice:** Pipeline automatica con **pytest**, parsing XML avanzato, analisi di **Code Coverage** (line/branch) e calcolo del **Mutation Score** per certificare la reale capacità di rilevamento bug dei test generati.
  * **Data Analysis & Visualization:** Elaborazione statistica comparativa (approccio *Raw* vs *Green*, architetture *LLM* vs *SLM*) con plotting automatico Seaborn/Matplotlib.
* **Tecnologie:** `Python` `AST Parsing` `CodeCarbon` `EcoLogits` `Pytest` `Mutation Testing` `Hugging Face` `Seaborn/Matplotlib`

---

#### 🛡️ [AC-Gainz Dependability](https://github.com/LuigiAuriemma/AC-Gainz-Dependabiity)
> **Piattaforma e-commerce Full-Stack containerizzata: focus su affidabilità (Dependability), robustezza architetturale e microbenchmarking.**
* **Descrizione:** Progetto collaborativo di estensione e validazione di un e-commerce enterprise per il fitness basato su architettura **MVC**. L'obiettivo primario è stato garantire l'affidabilità del sistema, l'isolamento degli ambienti e l'ottimizzazione delle risorse critiche sotto carico.
* **Punti chiave:**
  * Containerizzazione completa e riproducibile dell'applicazione e del DBMS relazionale tramite **Docker** e **Docker Compose**.
  * Validazione della robustezza con suite di unit/integration test in **JUnit**.
  * Analisi metodica dei colli di bottiglia e scaling con **JMH (Java Microbenchmark Harness)** per misurare al nanosecondo query batch, filtraggio dati e lifecycle degli ordini.
* **Tecnologie:** `Java EE` `Docker` `Docker Compose` `JMH` `JUnit` `SQL` `Maven` `JavaScript ES6`

---

#### 🍃 [AC-Gainz Sustainable](https://github.com/IvanChiello22/AC-Gainz-Sustainable)
> **Estensione, containerizzazione ed efficientamento di un e-commerce enterprise con focus su sostenibilità del software e performance engineering.**
* **Descrizione:** Progetto nato dall'integrazione e dal perfezionamento di una piattaforma e-commerce full-stack preesistente (sviluppata precedentemente da colleghi studenti per l'esame di Tecnologie Software per il Web - TSW). Il nostro intervento si è focalizzato sulla componente **Sustainable**: ottimizzazione computazionale, riduzione degli sprechi di risorse, containerizzazione, suite di stress test e analisi delle licenze.
* **Intervento & Architettura:**
  * Analisi e refactoring dell'architettura enterprise legacy in **Java EE / MVC** (Servlets, JSP, DAO, Connection Pooling su database SQL).
  * Containerizzazione dell'intero stack tramite **Docker** e **Docker Compose** per garantire replicabilità d'ambiente e gestione efficiente delle risorse computazionali.
* **Performance Tuning, Benchmarking & Testing:**
  * **JMH (Java Microbenchmark Harness):** Implementazione di benchmark metodici al nanosecondo per misurare e ottimizzare operazioni critiche (query batch, elaborazione ordini e filtri JSON).
  * **Apache JMeter:** Definizione ed esecuzione di scenari di stress/load testing per verificare la scalabilità e la resilienza del sistema sotto carichi massivi (sessioni anonime, autenticate e lifecycle del carrello/checkout).
* **Studio e Conformità delle Licenze:** Analisi approfondita dei vincoli legali e della compatibilità di licenze open source delle librerie di terze parti, formalizzata nel file `LICENSE`.
* **Tecnologie:** `Java EE` `Servlets` `Docker` `Docker Compose` `Apache JMeter` `JMH` `SQL` `Maven` `JSP` `JavaScript`

---

#### 🎾 [Artificial Tennis Predictor](https://github.com/IvanChiello22/ArtificialTennisPredictor)
> **Modello di Machine Learning supervisionato per la predizione degli esiti dei match del circuito ATP.**

* **Descrizione:** Sistema di analisi statistica e predittiva che stima le probabilità di vittoria nelle sfide tennistiche d'élite elaborando dati storici ufficiali.
* **Punti chiave:**
  * Data pre-processing, data cleaning e gestione di dataset complessi di serie storiche ATP.
  * Feature engineering avanzata: rating Elo/ranking, rendimento su specifica superficie, stato di forma recente e confronti Head-to-Head.
  * Addestramento, validazione e confronto empirico di modelli di classificazione.
* **Tecnologie:** `Python` `Scikit-learn` `Pandas` `NumPy` `Data Science` `Machine Learning`

---

#### 🏋️ [BodyLife-n.11](https://github.com/IvanChiello22/BodyLife-n.11)
> **Progetto di frontend e UX per fitness management progettato secondo le regole di Human-Computer Interaction (HCI).**

* **Descrizione:** Progettazione e sviluppo dell'interfaccia utente per un centro benessere/fitness, strutturata interamente per soddisfare le euristiche di usabilità e le linee guida scientifiche di HCI.
* **Punti chiave:**
  * Approccio User-Centered Design (UCD) per abbattere il carico cognitivo dell'utente.
  * Applicazione rigorosa di usabilità, coerenza visiva, accessibilità e prevenzione proattiva degli errori operativi.
  * Progettazione dell'architettura dell'informazione e dei percorsi di fruizione per schede di allenamento e orari corsi.
* **Aree di competenza:** `Human-Computer Interaction (HCI)` `UI/UX Design` `Usability Heuristics` `Frontend Prototyping`

---

### 🛠️ Competenze Tecniche

- **Linguaggi di Programmazione:** Python, Java (Enterprise/J2EE), C, JavaScript (ES6+), SQL
- **Ingegneria del Software & Metodologie:** Metodologie Agili (Scrum/Kanban), Design Patterns (MVC, DAO, Factory), Object-Oriented Design (OOD), Clean Code, Refactoring architetturale, Human-Computer Interaction (HCI)
- **DevOps, CI/CD & Infrastruttura:** CI/CD Pipelines (GitHub Actions), Docker, Docker Compose, Containerization, Environment Isolation, Dependency Management (Maven)
- **Testing, Affidabilità & Performance:** Unit & Integration Testing (JUnit, Pytest), Test-Driven Development (TDD), Mutation Testing, Load & Stress Testing (Apache JMeter), Microbenchmarking ad alta precisione (JMH)
- **AI, MLOps & Green Computing:** MLOps lifecycle (dataset versioning, experiment tracking, model evaluation), Prompt Engineering con LLM/SLM, Green AI & AST Code Optimization, EcoLogits, CodeCarbon, Scikit-learn, Pandas, NumPy
- **Strumenti & Version Control:** Git, GitHub, VS Code, Linux/Bash

---

### 📬 Contatti

- **LinkedIn:** [Ivan Chiello](https://www.linkedin.com/in/ivan-chiello-649876372)
- **Email:** [ivanchiello03@gmail.com](mailto:ivanchiello03@gmail.com)
