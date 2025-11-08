# Capstone Olist E-commerce Analysis
## Project Overview
Olist è una piattaforma di e-commerce brasiliana che connette venditori e clienti in tutto il Paese.
Questo progetto analizza i Trend degli ordini, degli incassile e la soddisfazione dei clienti utilizzando dati reali e anonimizzati forniti da Olist.

Il lavoro è stato pensato per essere facilmente consultabile anche da un contesto aziendale, con particolare attenzione alla user experience, ai filtri dinamici e alla chiarezza dei KPI principali.

## Data Preparation
La prima fase del progetto ha previsto un’attività di **pulizia e unificazione dei dati utilizzando Python e Power Query**, al fine di:
- Uniformare i formati data e i tipi di variabile
- Gestire i valori mancanti
- Unire i vari dataset forniti da Olist (ordini, clienti, prodotti, pagamenti e recensioni)
- Creare nuove colonne derivate per l’analisi temporale e la modellazione in Power BI

## Data Model
- Il modello dati è strutturato secondo uno **Star Schema**
- È stata creata una **dimensione calendario** per la gestione delle analisi temporali e dei confronti anno su anno
- Le relazioni sono state impostate in modo da consentire filtri e drill-through coerenti in tutto il report.

## Power BI Report
Il report “Olist E-commerce Analysis” è composto da **9 pagine principali** e **3 pagine tooltip**:

### Pagine principali
1. **Overview** – Sintesi generale con i KPI principali del business  
2. **Orders Trend** – Andamento mensile degli ordini con confronto anno su anno e per status  
3. **Revenue Trend** – Analisi dei ricavi totali e variazioni percentuali mensili  
4. **Revenue Map** – Ricavi e ordini aggregati per stato geografico raggiungibile tramite drill-through 
5. **Review Trend** – Distribuzione dei rating e andamento della soddisfazione clienti  
6. **Payment Details** – Analisi dei metodi di pagamento più utilizzati e dei ricavi associati  
7. **Products Trend** – Performance delle categorie di prodotto e confronto di vendita  
8. **Order Details** – Tabella dettagliata degli ordini
10. **Revenue Details** – Approfondimento sui ricavi e confronto con l’anno precedente

### Tooltips
- **TT Order Status (Orders)** – Mostra dettagli sull’andamento per status ordine  
- **TT Order Status (Revenue)** – Approfondimento dei ricavi per status  
- **TT Revenue Map** – Approfondimento geografico dei ricavi

## UX e Design
Il report è stato progettato con particolare attenzione alla user experience:
- Layout coerente e navigazione tramite **bottoni interattivi**  
- **Drill-through** per l’esplorazione di livelli di dettaglio aggiuntivi  
- **Tooltip personalizzati** per fornire insight contestuali  
- Palette cromatica coerente con la brand identity di Olist

## Tools & Technologies
- **Python** → per la preparazione e pulizia dei dati  
- **Power BI Desktop** → per modellazione, DAX e visualizzazione interattiva

## 👤 Author
**Niccolò Giacomin**  
📍 Capstone Project – Epicode Data Analyst  
📅 Novembre 2025  
