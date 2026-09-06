# Executive Analytics & Logistics Intelligence (Tableau)

### Descrizione del Progetto

Sviluppo di una soluzione interattiva di Business Intelligence in Tableau per il monitoraggio end-to-end delle performance economico-logistiche della catena *Superstore* nel mercato europeo. 
Il progetto sostituisce le metodologie di reportistica statica con un ecosistema di due dashboard executive ad alta densità informativa e una **Tableau Story** orientata al decision-making strategico. L'analisi guida la riallocazione efficiente del budget marketing e l'ottimizzazione operativa attraverso l'isolamento dei colli di bottiglia logistici e delle inefficienze di margine.

### Workflow Tecnico e Metodologia

Il workflow visuale e analitico si articola su tre direttrici principali:

1. **Financial & Geographic Mapping (Dashboard Economics)**:
   * **Dual-Level Spatial Analysis**: integrazione di mappe per identificare i Paesi in utile vs in perdita e mappe a bolle per la granularità delle vendite a livello cittadino.
   * **Margin & Volume Divergence**: confronto combinato tra profitti generati e quantità vendute per categoria, per individuare i prodotti ad alta movimentazione ma a bassa marginalità.
   * **Sales Trend Analysis**: monitoraggio storico trimestrale del fatturato (2.94M € totali) per intercettare la stagionalità e i picchi di domanda.
2. **Logistics & Operational Efficiency (Dashboard Spedizioni)**:
   * **Delivery Mode Segmentation**: analisi volumetrica della distribuzione degli ordini per classe di spedizione (*Standard*, *Second*, *First Class*, *Same Day*).
   * **Dynamic Return Threshold Modeling**: implementazione di un parametro interattivo (*Selettore % Resi*) per consentire allo stakeholder di impostare una soglia critica e identificare visivamente le categorie trasgressive e il loro impatto sui profitti.
   * **Lead Time Tracking**: analisi temporale del tempo medio di spedizione (target 4.0 giorni) con fasce di riferimento (Min, Media, Max).
3. **Strategic Marketing Storytelling (Tableau Story)**:
   * Applicazione della **regola delle 3C** (Contesto, Conflitto, Conclusione) per la definizione della strategia d'attacco promozionale: allocazione budget su prodotti ad alto margine inespressi, riduzione su mercati saturi ed eliminazione dal catalogo degli articoli in perdita strutturale.

### Tech Stack

* **BI Tool**: Tableau Desktop / Tableau Public
* **Funzionalità Avanzate**: Campi Calcolati (Calculated Fields), Parametri dinamici di soglia (User Parameters), Dashboard Actions (Cross-filtering e Navigazione a schede), Dual-Axis Charts, Time Series Analysis.

### Valore Strategico

* **Marketing ROI Optimization**: allocazione scientifica del budget promozionale basata sul potenziale di margine anziché sui soli volumi di vendita.
* **Logistics & Margin Protection**: identificazione tempestiva dell'erosione dei margini dovuta all'alto tasso di reso su specifiche categorie di prodotto.
* **Geographic Expansion**: individuazione immediata dei mercati nazionali e delle città chiave per pianificare campagne di penetrazione o ridimensionamento.

### Struttura del Repository

* [EU Superstore Analysis](https://public.tableau.com/views/EUSuperstoreanalysis/SupestoreEconomics?:language=en-GB&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link): dashboard interattive e Tableau Story pubblicate su Tableau Community.
* `superstore.xlsx`: file excel utilizzato per l'analisi.
