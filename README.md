# CP Method — Context Pack Method

> **A structured methodology for building and maintaining portable AI context.**  
> **Una metodologia strutturata per costruire e mantenere contesto AI portabile.**

---

## 🇮🇹 Italiano

### Cos'è il CP Method

Il **Context Pack (CP) Method** è una proposta metodologica strutturata per la progettazione, la strutturazione e l'aggiornamento incrementale del contesto fornito ai modelli AI generativi. Non è un tool, non è un software: è un metodo di lavoro.

Il metodo definisce:
- una struttura standard a **14 sezioni** per organizzare il contesto
- un **ciclo di aggiornamento incrementale** per mantenere il contesto coerente nel tempo
- una logica di **prompt ottimizzati** per trasferire il contesto tra sessioni e piattaforme

### A chi è rivolto

Chiunque lavori con strumenti AI generativi in modo ricorrente e strutturato: formatori, consulenti, professionisti, team aziendali. Il metodo è applicabile a qualsiasi dominio — dalla gestione della posta elettronica allo sviluppo personale, dalla consulenza alla formazione.

### Vantaggio chiave: persistenza locale e indipendenza dalla piattaforma

I modelli AI generativi non hanno memoria tra una sessione e l'altra. Le soluzioni cloud che promettono di risolvere questo problema introducono dipendenza tecnologica, costi e rischi per la privacy.

Il CP Method risolve il problema della persistenza **senza nessuno di questi svantaggi**:

- il contesto vive in un **file locale** sotto il controllo dell'utente
- è **human-readable** e modificabile con qualsiasi editor
- è **portabile tra i principali modelli AI generativi** (ChatGPT, Claude, Gemini, Copilot)
- conserva **localmente la conversazione** e lo stato del lavoro nel tempo
- funziona **offline**, senza API, senza abbonamenti aggiuntivi

Poiché il metodo è local-first e non richiede servizi terzi per la conservazione del contesto, può favorire strategie di minimizzazione del dato e maggiore controllo da parte dell'utente. La conformità GDPR dipende tuttavia dal contenuto trattato, dal contesto d'uso e dall'eventuale piattaforma AI coinvolta.

### Contributi originali

Una ricerca strutturata in 4 fasi (Perplexity, Claude, Gemini, verifica manuale su arXiv/Scholar/GitHub — marzo 2026) ha identificato i seguenti contributi non documentati nella letteratura esistente:

| Contributo | Descrizione |
|---|---|
| **Prompt di reidratazione embedded** | Il documento contiene i propri prompt di riutilizzo — nessuna istruzione esterna necessaria |
| **Ciclo di aggiornamento autonomo** | Il modello AI segnala quando il CP va rigenerato, basandosi sulla deriva semantica |
| **Design platform-agnostic** | Progettato esplicitamente per workflow multi-AI in parallelo da utenti non tecnici |
| **Struttura canonica a 14 sezioni** | Formato standardizzato che include snapshot, decisioni motivate, output gold, informazioni mancanti |
| **Versionamento semantico del contesto** | v0.1 → v0.2 → v1.0 applicato all'evoluzione conversazionale, non al software |
| **Varianti di reasoning per piattaforma** | Strategie di esecuzione platform-specific embedded nello stesso documento |
| **Compatibilità Microsoft Loop** | Il formato `.docx` nativo abilita l'uso collaborativo in ambienti Teams/M365 |

### Posizionamento rispetto alla letteratura

I precedenti più vicini identificati sono:

| Riferimento | Similitudine | Cosa manca rispetto al CP |
|---|---|---|
| Session Handoff Protocol (Blake Link, 2025) | Trasferimento contesto strutturato | Singola piattaforma, nessun prompt embedded, nessun auto-refresh |
| AI Context Kit (MSiccDev, gen 2026) | Istruzioni portabili cross-platform | Orientato agli sviluppatori, nessun prompt embedded, nessun auto-refresh |
| Agentic Context Engineering / ACE (Zhang et al., arXiv 2026) | Contesto come playbook evolutivo | Per sistemi agentici automatizzati, non per utenti umani su piattaforme eterogenee |
| MemGPT, Mem0, framework RAG | Memoria esterna per LLM | In-system e automatizzata, non portabile né human-editable |

### Stato del progetto

| Componente | Stato |
|---|---|
| Struttura a 14 sezioni | ✅ Completa |
| Ricerca originalità (4 fasi) | ✅ Completata — marzo 2026 |
| Zenodo DOI | ✅ Registrato |
| GitHub repository | ✅ Attivo |
| Prompt base | ✅ Pronto (non pubblicato) |
| Variante Copilot | ✅ Pronta (non pubblicata) |
| Variante Gemini / ChatGPT | 🔄 Da validare |
| Post LinkedIn annuncio | 🔄 Da pubblicare |
| White paper | 🔄 In lavorazione |
| Corso / Workshop | 🔄 In strutturazione |

### Citazione

> Conte, L. (2026). *CP Method — Context Pack Method: una metodologia strutturata per costruire e mantenere contesto AI portabile*. Zenodo. https://doi.org/10.5281/zenodo.19006805

### Autore

**Luca Conte** · [Oltresoftware](https://oltresoftware.com)  
Microsoft Certified Trainer (MCT)

---

## 🇬🇧 English

### What is the CP Method

The **Context Pack (CP) Method** is a structured methodological proposal for the design, structuring, and incremental updating of context provided to generative AI models. It is not a tool or a piece of software — it is a working method.

The method defines:
- a standard **14-section structure** for organizing context
- an **incremental update cycle** to keep context coherent over time
- a logic of **optimized prompts** for transferring context across sessions and platforms

### Who it's for

Anyone working with generative AI tools in a recurring and structured way: trainers, consultants, professionals, business teams. The method applies to any domain — from email management to personal development, from consulting to education.

### Key advantage: local persistence and platform independence

Generative AI models have no memory between sessions. Cloud-based solutions that promise to solve this problem introduce technological dependency, costs, and privacy risks.

The CP Method solves the persistence problem **without any of these drawbacks**:

- context lives in a **local file** under the user's full control
- it is **human-readable** and editable with any text editor
- it is **portable across the major generative AI models** (ChatGPT, Claude, Gemini, Copilot)
- it **preserves conversations and work state** locally over time
- it works **offline**, with no APIs, no additional subscriptions

Since the method is local-first and does not require third-party services for context storage, it can support data minimisation strategies and greater user control. GDPR compliance depends, however, on the content processed, the context of use, and the AI platform involved.

### Original contributions

A structured 4-phase research process (Perplexity, Claude, Gemini, manual verification on arXiv/Scholar/GitHub — March 2026) identified the following contributions not documented in existing literature:

| Contribution | Description |
|---|---|
| **Embedded rehydration prompts** | The document contains its own prompts for reuse — no external instructions needed |
| **Autonomous refresh cycle** | The AI model signals when the CP needs regeneration, based on semantic drift |
| **Platform-agnostic design** | Explicitly designed for parallel multi-AI workflows by non-technical users |
| **Canonical 14-section structure** | Standardized format including context snapshot, motivated decisions, gold outputs, missing information |
| **Semantic versioning for conversations** | v0.1 → v0.2 → v1.0 applied to context evolution, not software versioning |
| **Reasoning mode variants** | Platform-specific execution strategies embedded in the same document |
| **Microsoft Loop compatibility** | Native `.docx` format enables collaborative use in Teams/M365 environments |

### Positioning in the landscape

The closest prior references identified are:

| Reference | Similarity | What it lacks vs CP |
|---|---|---|
| Session Handoff Protocol (Blake Link, 2025) | Structured context transfer | Single platform, no embedded prompts, no auto-refresh |
| AI Context Kit (MSiccDev, Jan 2026) | Cross-platform portable instructions | Developer-oriented, no embedded prompts, no auto-refresh |
| Agentic Context Engineering / ACE (Zhang et al., arXiv 2026) | Context as evolving playbook | For automated agentic systems, not human-mediated multi-platform workflows |
| MemGPT, Mem0, RAG frameworks | External memory for LLMs | In-system and automated, not portable or human-editable |

### Project status

| Component | Status |
|---|---|
| 14-section structure | ✅ Complete |
| Originality research (4 phases) | ✅ Completed — March 2026 |
| Zenodo DOI | ✅ Registered |
| GitHub repository | ✅ Active |
| Base prompt | ✅ Ready (not yet published) |
| Copilot variant | ✅ Ready (not yet published) |
| Gemini / ChatGPT variant | 🔄 To be validated |
| LinkedIn announcement post | 🔄 To be published |
| White paper | 🔄 In progress |
| Course / Workshop | 🔄 Being structured |

### Citation

> Conte, L. (2026). *CP Method — Context Pack Method: a structured methodology for building and maintaining portable AI context*. Zenodo. https://doi.org/10.5281/zenodo.19006805

### Author

**Luca Conte** · [Oltresoftware](https://oltresoftware.com)  
Microsoft Certified Trainer (MCT)

---

## License / Licenza

The conceptual framework and methodology described in this repository are released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the content with attribution to the author. No part of the operational prompts or implementation details may be reproduced or distributed without explicit written permission.

Il framework concettuale e la metodologia descritti in questo repository sono rilasciati sotto licenza [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Sei libero di condividere e adattare il contenuto con attribuzione all'autore. Nessuna parte dei prompt operativi o dei dettagli implementativi può essere riprodotta o distribuita senza esplicita autorizzazione scritta.

© 2026 Luca Conte · Oltresoftware
