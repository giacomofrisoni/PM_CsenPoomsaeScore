# Piano di qualità  <!-- omit in toc -->

## INDICE <!-- omit in toc -->

- [1 QUADRO RIEPILOGATIVO DEGLI INDICATORI DI QUALITÀ](#1-quadro-riepilogativo-degli-indicatori-di-qualit%c3%80)
  
- [1 QUADRO RIEPILOGATIVO DEGLI INDICATORI DI QUALITÀ](#1-quadro-riepilogativo-degli-indicatori-di-qualit%c3%80)
- [2 INDICATORI DI QUALITÀ DI OBIETTIVO](#2-indicatori-di-qualit%c3%80-di-obiettivo)
  - [2.1 Indicatori di qualità applicabili a tutti gli obiettivi](#21-indicatori-di-qualit%c3%a0-applicabili-a-tutti-gli-obiettivi)
    - [2.1.1 IQ01 - Slittamento nell'esecuzione dell'obiettivo](#211-iq01---slittamento-nellesecuzione-dellobiettivo)
    - [2.1.2 IQ02 - Slittamento della consegna di un incremento dell'obiettivo](#212-iq02---slittamento-della-consegna-di-un-incremento-dellobiettivo)
    - [2.1.3 IQ03 - Rilievi sull'obiettivo](#213-iq03---rilievi-sullobiettivo)
    - [2.1.4 IQ04 - Mancato raggiungimento del Business Value previsto](#214-iq04---mancato-raggiungimento-del-business-value-previsto)
  - [2.2 Indicatori di qualità applicabili agli obiettivi di sviluppo, mev e mad](#22-indicatori-di-qualit%c3%a0-applicabili-agli-obiettivi-di-sviluppo-mev-e-mad)
    - [2.2.1 IQ05 - Test negativi in collaudo](#221-iq05---test-negativi-in-collaudo)
    - [2.2.2 IQ06 - Difettosità in collaudo](#222-iq06---difettosit%c3%a0-in-collaudo)
    - [2.2.3 IQ07 - Giorni di sospensione del collaudo](#223-iq07---giorni-di-sospensione-del-collaudo)
    - [2.2.4 IQ08 - Slittamento della risoluzione dei malfunzionamenti del collaudo](#224-iq08---slittamento-della-risoluzione-dei-malfunzionamenti-del-collaudo)
    - [2.2.5 IQ09 - Difettosità in esercizio (per applicazione)](#225-iq09---difettosit%c3%a0-in-esercizio-per-applicazione)
  - [2.3 Indicatori di qualità applicabili agli obiettivi di sviluppo, mev](#23-indicatori-di-qualit%c3%a0-applicabili-agli-obiettivi-di-sviluppo-mev)
    - [2.3.1 IQ10 - Densità dei commenti del software sviluppato](#231-iq10---densit%c3%a0-dei-commenti-del-software-sviluppato)
    - [2.3.2 IQ11 - Linee di codice inerte](#232-iq11---linee-di-codice-inerte)
    - [2.3.3 IQ12 - Copertura dei test](#233-iq12---copertura-dei-test)
    - [2.3.4 IQ13 - Qualità della documentazione](#234-iq13---qualit%c3%a0-della-documentazione)
    - [2.3.5 IQ14 - Qualità e utilità meeting](#235-iq14---qualit%c3%a0-e-utilit%c3%a0-meeting)
    - [2.3.6 IQ15 - Qualità UX](#236-iq15---qualit%c3%a0-ux)
  - [2.4 Indicatori di qualità specifici degli obiettivi sviluppati in modalità object oriented](#24-indicatori-di-qualit%c3%a0-specifici-degli-obiettivi-sviluppati-in-modalit%c3%a0-object-oriented)
    - [2.4.1 IQ16 - Violazioni dell’Incapsulamento da parte di una Classe](#241-iq16---violazioni-dellincapsulamento-da-parte-di-una-classe)
    - [2.4.2 IQ17 - Metodi implementati in una Classe](#242-iq17---metodi-implementati-in-una-classe)
    - [2.4.3 IQ18 - Grado di coesione dei Metodi di una Classe](#243-iq18---grado-di-coesione-dei-metodi-di-una-classe)
- [3 INDICATORI DI QUALITÀ DEL SERVIZIO DI MANUTENZIONE CORRETTIVA](#3-indicatori-di-qualit%c3%80-del-servizio-di-manutenzione-correttiva)
    - [3.1 IQ19 - Casi recidivi (per area applicativa)](#31-iq19---casi-recidivi-per-area-applicativa)
- [4 INDICATORI DI QUALITÀ DEL SERVIZIO DI GESTIONE APPLICATIVA](#4-indicatori-di-qualit%c3%80-del-servizio-di-gestione-applicativa)
    - [4.1 IQ20 - Tempo medio di risposta al cliente](#41-iq20---tempo-medio-di-risposta-al-cliente)
- [5 INDICATORI DI QUALITÀ APPLICABILI A TUTTI I SERVIZI DELLA FORNITURA](#5-indicatori-di-qualit%c3%80-applicabili-a-tutti-i-servizi-della-fornitura)
    - [5.1 IQ21 - Soddisfazione del committente](#51-iq21---soddisfazione-del-committente)
  
- [3 INDICATORI DI QUALITÀ DEL SERVIZIO DI MANUTENZIONE CORRETTIVA](#3-indicatori-di-qualit%c3%80-del-servizio-di-manutenzione-correttiva)
    - [3.1 IQ19 - Casi recidivi (per area applicativa)](#31-iq19---casi-recidivi-per-area-applicativa)
  
- [4 INDICATORI DI QUALITÀ DEL SERVIZIO DI GESTIONE APPLICATIVA](#4-indicatori-di-qualit%c3%80-del-servizio-di-gestione-applicativa)
    - [4.1 IQ20 - Tempo medio di risposta al cliente](#41-iq20---tempo-medio-di-risposta-al-cliente)
  
- [5 INDICATORI DI QUALITÀ APPLICABILI A TUTTI I SERVIZI DELLA FORNITURA](#5-indicatori-di-qualit%c3%80-applicabili-a-tutti-i-servizi-della-fornitura)
    - [5.1 IQ21 - Soddisfazione del committente](#51-iq21---soddisfazione-del-committente)

## 1 QUADRO RIEPILOGATIVO DEGLI INDICATORI DI QUALITÀ

Di seguito si trova una matrice di corrispondenza tra gli indicatori di qualità e le azioni contrattuali previste nel caso di non rispetto dei valori di soglia.

<table>
  <tr>
    <th rowspan="2" align="center">Indicatori di Qualità</th>
    <th colspan="2" align="center">Azione Contrattuale</th>
  </tr>
  <tr>
    <th align="center">Rilievo</th>
    <th align="center">Penale</th>
  </tr>
  <tr>
    <td>IQ01 - Slittamento nell'esecuzione dell'obiettivo</td>
    <td align="center"></td>
    <td align="center">X</td>
  </tr>
  <tr>
    <td>IQ02 - Slittamento della consegna di un protocollo dell'obiettivo</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ03 - Rilievi sull'obiettivo</td>
    <td align="center"></td>
    <td align="center">X</td>
  </tr>
  <tr>
    <td>IQ04 - Mancato raggiungimento del Business Value previsto</td>
    <td align="center"></td>
    <td align="center">X</td>
  </tr>
  <tr>
    <td>IQ05 - Test negativi in collaudo</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ06 - Difettosità in collaudo</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ07 - Giorni di sospensione del collaudo</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ08 - Slittamento della risoluzione dei malfunzionamenti in collaudo</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ09 - Difettosità in esercizio (per applicazione)</td>
    <td align="center"></td>
    <td align="center">X</td>
  </tr>
  <tr>
    <td>IQ10 - Densità dei commenti del software sviluppato</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ11 - Linee di codice inerte</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ12 - Copertura dei test</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ13 - Qualità della documentazione</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ14 - Qualità e utilità meeting</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ15 - Qualità UX</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ16 - Violazioni dell’Incapsulamento da parte di una Classe</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ17 - Metodi implementati in una Classe</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ18 - Grado di coesione dei Metodi di una Classe</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ19 - Casi recidivi (per area applicativa)</td>
    <td align="center"></td>
    <td align="center">X</td>
  </tr>
  <tr>
    <td>IQ20 - Tempo medio di risposta al cliente</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
  <tr>
    <td>IQ21 - Soddisfazione del committente</td>
    <td align="center">X</td>
    <td align="center"></td>
  </tr>
</table>

<br/>
<br/>

## 2 INDICATORI DI QUALITÀ DI OBIETTIVO

### 2.1 Indicatori di qualità applicabili a tutti gli obiettivi

#### 2.1.1 IQ01 - Slittamento nell'esecuzione dell'obiettivo

L'indicatore vuole valutare se la durata effettiva dell'obiettivo è maggiore rispetto a quella concordata nell'ultima pianificazione approvata da CSEN, considerando la data di attivazione come la data di partenza (comune alle due durate) per il calcolo della metrica.  
Si valuta quindi lo slittamento della data di accettazione effettiva rispetto a quella di fine obiettivo riportata nell'ultima pianificazione.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza temporale</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Slittamento della fine effettiva dell'obiettivo (data di accettazione) rispetto a quella concordata nell'ultima pianificazione, partendo dalla data di attivazione, per cause imputabili al fornitore</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Giorni lavorativi</th>
    <th align="left">Fonte dati</th>
    <td align="left">Piano di lavoro<br/>Lettera di accettazione</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Dopo il termine dell'obiettivo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Data di accettazione (<i>Data_accett</i>)</li>
            <li>Data di accettazione prevista dall'ultimo Piano di lavoro approvato (<i>Data_pian_accett</i>)</li>
            <li>Data di attivazione dell'obiettivo (<i>Data_attiv</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ01 = (Data_accett - Data_attiv) - (Data_pian - Data_attiv)</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ01 <= 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Penale <i>"Slittamento nell'esecuzione dell'obiettivo"</i> qualora non sia rispettato il valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.1.2 IQ02 - Slittamento della consegna di un incremento dell'obiettivo

L'indicatore si applica ad ogni macro incremento previsto per l'obiettivo.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza temporale</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Puntualità nella consegna di un macro incremento dell'obiettivo rispetto alla data prevista nel Piano di lavoro</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Giorni lavorativi</th>
    <th align="left">Fonte dati</th>
    <td align="left">Piano di lavoro<br/>Lettera di accettazione</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Ad ogni consegna di incremento</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Data prevista di consegna di un incremento (<i>Data_prev</i>)</li>
            <li>Data effettiva di consegna di un incremento (<i>Data_eff</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerate tutte le consegne di incremento eseguite nel periodo di riferimento</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ02 = Data_eff - Data_prev</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ02 <= 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo per ogni ritardo di 5 giorni lavorativi o frazione rispetto al valore di soglia (<i>es. un ritardo rispetto al piano di 11 gg lavorativi comporterà 3 rilievi sull'obiettivo</i>)</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.1.3 IQ03 - Rilievi sull'obiettivo

I rilievi conteggiati nella metrica sono quelli notificati al fornitore tramite comunicazione formale emessa da CSEN. Si precisa che ciascuna comunicazione potrà contenere più rilievi.  
Il numero di rilievi tollerati dall'obiettivo è in relazione alla [classe](project_docs/csen_poomsae_score/project_classification/project_classification.md) del progetto.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficacia</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficacia</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Numero di rilievi emessi sull'obiettivo</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Rilievo</th>
    <th align="left">Fonte dati</th>
    <td align="left">Rilievo</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine dell'obiettivo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di rilievi emessi sull'obiettivo (<i>Nrilievi_obiettivo</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i rilievi emessi nel periodo di riferimento sull'obiettivo</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ03 = Nrilievi_obiettivo</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">
        IQ03 <= 4&emsp;Classe = A<br/>
        <b>IQ03 <= 3&emsp;Classe = B</b><br/>
        IQ03 <= 2&emsp;Classe = C o Classe = D<br/>
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Penale <i>"Eccesso di rilievi tollerati per obiettivo"</i> qualora non sia rispettato il valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

#### 2.1.4 IQ04 - Mancato raggiungimento del Business Value previsto

Con questo indicatore si vuole individuare il mancato raggiungimento dei Business Value riportati all'interno del POS.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficacia</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficacia</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Numero di Business Value non raggiunti</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Business Value</th>
    <th align="left">Fonte dati</th>
    <td align="left">Report temporali sul progetto finale</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine dell'obiettivo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Business Value non raggiunti (<i>Nbusiness_value</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i Business Value</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ04 = Nbusiness_value</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">
        IQ04 <= 0
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Penale <i>"Business Value non raggiunte"</i> qualora non sia rispettato il valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

----------

### 2.2 Indicatori di qualità applicabili agli obiettivi di sviluppo, mev e mad

#### 2.2.1 IQ05 - Test negativi in collaudo

Con questo indicatore si vogliono individuare i casi di test eseguiti (sia in modalità manuale che automatica) dal fornitore con successo prima del rilascio e che, se rieseguiti durante il collaudo, danno esito negativo.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Affidabilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Maturità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Casi di test eseguiti con esito negativo in collaudo</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Casi di test eseguiti in collaudo con esito negativo</th>
    <th align="left">Fonte dati</th>
    <td align="left">Piano di Test<br/>Verbale di collaudo</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di collaudo dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine del collaudo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di casi di test dichiarati come eseguiti con successo dal fornitore e che in collaudo hanno dato esito negativo (<i>Ntest_notok</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ05 = Ntest_notok</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ05 = 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo per ogni caso di test eseguito in collaudo con esito negativo</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.2.2 IQ06 - Difettosità in collaudo

Per "*Difetto*" si intende un errore presente nel software da collaudare, latente finchè non rilevato.  
Per "*Difettosità in collaudo*" si intende la media pesata del numero di difetti emersi, con peso in funzione della loro categoria (assegnata dal fornitore sulla base di una stima delle risorse che occorreranno per la correzione).

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Affidabilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Maturità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Difettosità in collaudo</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Numero Difetti / Peso Categoria Difetto</th>
    <th align="left">Fonte dati</th>
    <td align="left">-</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">La fase di collaudo dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine del collaudo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero totale di elementi difettosi emersi durante il collaudo, suddivisi in tre categorie, in base alla grandezza del problema
              <ul>
                <li><b>A</b> - per difetti correggibili entro 2 giorni (<i>N_difetti_A</i>).</li>
                <li><b>B</b> - per difetti correggibili entro 3 giorni (<i>N_difetti_B</i>).</li>
                <li><b>C</b> - per difetti correggibili entro 5 giorni (<i>N_difetti_C</i>).</li>
              </ul>
            </li>
            <br/>
            <li>Peso assegnato ad ogni categoria:
              <ul>
                <li><b>0,15</b> - per la categoria A.</li>
                <li><b>0,25</b> - per la categoria B</li>
                <li><b>0,6</b> - per la categoria C.</li>
              </ul>
            </li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti gli elementi difettosi rilevati durante il collaudo</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <i>IQ06 = (0,15 x N_difetti_A) + (0,25 x N_difetti_B) + (0,6 x N_difetti_C)</i>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,05<br/>
      - per eccesso se la prima cifra decimale è > 0,05
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ06 < 0,6</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di mancato rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.2.3 IQ07 - Giorni di sospensione del collaudo

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Affidabilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Maturità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Numero complessivo di giorni in cui è stato sospeso il collaudo di un obiettivo per cause imputabili al fornitore</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Giorni lavorativi</th>
    <th align="left">Fonte dati</th>
    <td align="left">Comunicazione formale di sospensione del collaudo<br/>Comunicazione formale di ripresa del collaudo</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">La fase di collaudo dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine del collaudo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Data e ora di sospensione del collaudo (<i>Data_sospensione<sub>j</sub></i>)</li>
            <li>Data e ora di ripresa del collaudo (<i>Data_ripresa<sub>j</sub></i>)</li>
            <li>Numero di giorni non lavorativi tra la sospensione e la ripresa del collaudo (<i>Ngiorni_nolav<sub>j</sub></i>)</li>
            <li>Numero di sospensioni del collaudo (<i>Nsosp_collaudo</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Si applica a tutte le sospensioni di collaudo (<i>sia la prima che, qualora capiti, le successive</i>)</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ07&space;=&space;\sum_{j=1}^{Nsosp\_collaudo}(Data\_ripresa_j&space;-&space;Data\_sospensione_j&space;-&space;Ngiorni\_nolav_j)" title="IQ07 = \sum_{j=1}^{Nsosp\_collaudo}(Data\_ripresa_j - Data\_sospensione_j - Ngiorni\_nolav_j)" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ07 = 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di mancato rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.2.4 IQ08 - Slittamento della risoluzione dei malfunzionamenti del collaudo

Durante il collaudo di ogni obiettivo gli interventi effettuati a fronte di malfunzionamenti del software applicativo avranno un livello di ripristino della piena operatività in funzione della categoria di malfunzionamento, così definito:

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza temporale</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Tempestività di ripristino in collaudo a seguito di malfunzionamenti, valutata in base alla durata stimata della correzione</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Giorni lavorativi</th>
    <th align="left">Fonte dati</th>
    <td align="left">Stato avanzamento lavori</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Fase di collaudo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al termine del collaudo</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Avvio del processo di risoluzione del malfunzionamento: data, ora e minuti comunicati dal fornitore <i>(inizio<sub>i</sub>)</i></li>
            <li>Termine della risoluzione del malfunzionamento: data, ora e minuti <i>(fine<sub>i</sub>)</i></li>
            <li>Tempo di sospensione della risoluzione del malfunzionamento (<i>sospensione</i>) a causa dell'indisponibilità dell'ambiente di correzione, o per ragioni non imputabili al fornitore (<i>TRO<sub>i</sub></i>)</li>
            <li>Numero totale di segnalazioni chiuse a fronte di malfunzionamenti rilevati in collaudo (<i>Ntotale_malf_coll</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ08&space;=&space;\sum_{i=1}^{Ntotale\_malf\_coll}ritardo\_risol_i" title="IQ08 = \sum_{i=1}^{Ntotale\_malf\_coll}ritardo\_risol_i" />
      <br/>
      Dove:
      <br/>
      <ul>
        <li><i>durata_risol<sub>i</sub> = termine<sub>i</sub> - inizio<sub>i</sub> - TRO<sub>i</sub></i></li>
        <li>
          <i>valore_limite = </i>
          <table>
            <tr>
              <td align="center"><i>categoria A</i></td>
              <td align="center"><i>categoria B</i></td>
              <td align="center"><i>categoria C</i></td>
            </tr>
            <tr>
              <td align="center"><i>2 giorni lavorativi</i></td>
              <td align="center"><i>3 giorni lavorativi</i></td>
              <td align="center"><i>5 giorni lavorativi</i></td>
            </tr>
          </table>
        </li>
        <li>
          <i>ritardo_risol<sub>i</sub> = </i>
          <table>
            <tr>
              <td align="center"><i>0</i></td>
              <td align="center"><i>durata_risol<sub>i</sub> - valore_limite</i></td>
            </tr>
            <tr>
              <td align="center"><i>(se durata_risol<sub>i</sub> <= valore_limite)</i></td>
              <td align="center"><i>(se durata_risol<sub>i</sub> > valore_limite)</i></td>
            </tr>
          </table>
        </li>
      </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ08 = 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Il mancato rispetto del valore di soglia comporterà un rilievo sull'obiettivo per ogni giorno lavorativo o frazione eccedente la soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.2.5 IQ09 - Difettosità in esercizio (per applicazione)

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Affidabilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Maturità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Difettosità in esercizio di un'applicazione</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Numero Difetti / Peso Categoria Difetto</th>
    <th align="left">Fonte dati</th>
    <td align="left">Verbale di rilevazione</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Tremestre precedente la rilevazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Trimestrale</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
      <ul>
            <li>Numero totale di elementi difettosi emersi, suddivisi in tre categorie, in base alla grandezza del problema
              <ul>
                <li><b>A</b> - per difetti correggibili entro 3 giorni (<i>N_difetti_A</i>).</li>
                <li><b>B</b> - per difetti correggibili entro 4 giorni (<i>N_difetti_B</i>).</li>
                <li><b>C</b> - per difetti correggibili entro 6 giorni (<i>N_difetti_C</i>).</li>
              </ul>
            </li>
            <br/>
            <li>Peso assegnato ad ogni categoria:
              <ul>
                <li><b>0,15</b> - per la categoria A.</li>
                <li><b>0,25</b> - per la categoria B</li>
                <li><b>0,6</b> - per la categoria C.</li>
              </ul>
            </li>
        </ul>
    </td>
  </tr>
    <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti gli elementi difettosi rilevati</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <i>IQ09 = (0,15 x N_difetti_A) + (0,25 x N_difetti_B) + (0,6 x N_difetti_C)</i>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,05<br/>
      - per eccesso se la prima cifra decimale è > 0,05
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td align="left" colspan="3">IQ09 < 0,6</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di mancato rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

### 2.3 Indicatori di qualità applicabili agli obiettivi di sviluppo, mev

#### 2.3.1 IQ10 - Densità dei commenti del software sviluppato

Si applica ai soli obiettivi che generano software nuovo. Qualora l'obiettivo includa l'uso di più linguaggi, l'indicatore va applicato separatamente al codice sviluppato in ogni singolo linguaggio.  
I commenti dovranno essere facilmente separabili dalle istruzioni.  
Si precisa che non sono considerati commenti le linee blank e le eventuali righe con contenuto non significativo (tratteggi, caratteri di spaziatura, ecc.).

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Densità dei commenti del software sviluppato in linguaggio di programmazione C#, Java e con linguaggio di markup XAML</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Punto percentuale</th>
    <th align="left">Fonte dati</th>
    <td align="left">Codice sorgente<br/>Tool automatici</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Una volta<br/><i>(al termine del periodo di riferimento)</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di moduli nuovi (<i>Nmoduli</i>)</li>
            <li>Numero di linee di codice del singolo modulo nuovo (<i>Nloc</i>)</li>
            <li>Numero di linee di commento del singolo modulo nuovo (<i>Ncomm</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i moduli software nuovi scritti in linguaggio C# / Java / XAML</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ10&space;=&space;\frac{\sum_{i=1}^{Nmoduli}{Ncomm_i}}{\sum_{i=1}^{Nmoduli}{NLoc_i}}\times&space;100" title="IQ10 = \frac{\sum_{i=1}^{Nmoduli}{Ncomm_i}}{\sum_{i=1}^{Nmoduli}{NLoc_i}}\times 100" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,5<br/>
      - per eccesso se la prima cifra decimale è > 0,5
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">
      <table>
        <tr>
          <td align="left">
            IQ10 >= 20%<br/>
            <i>(per i linguaggi C# / Java)</i>
          </td>
        </tr>
        <tr>
          <td align="left">
            IQ10 >= 10%<br/>
            <i>(per il linguaggio XAML)</i>
          </td>
        </tr>
      </table>
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.3.2 IQ11 - Linee di codice inerte

L'indicatore si applica sia al software nuovo che al software modificato. Per software modificato si intende il software modificato nell'ambito della fornitura anche se realizzato in forniture precedenti.  
Qualora l'obiettivo includa l'uso di più linguaggi, l'indicatore si utilizza su ogni singolo linguaggio.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Codice inerte del software nuovo o modificato, sviluppato in linguaggio C# / Java</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Numero di linee di codice inerte</th>
    <th align="left">Fonte dati</th>
    <td align="left">Codice sorgente<br/>Tool automatici</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Una volta<br/><i>(al termine del periodo di riferimento)</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di linee di codice sorgente modificato e di nuova realizzazione mai percorso in fase di esecuzione (<i>Nlin_inerte</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerate tutte le linee di codice dei moduli software nuovi o modificati dall'obiettivo scritti in linguaggio C# / Java</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ11 = Nlin_inerte</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ11 = 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

#### 2.3.3 IQ12 - Copertura dei test

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Copertura dei test sul codice complessivo</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Valore percentuale</th>
    <th align="left">Fonte dati</th>
    <td align="left">Risultati dei tool di coverage</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Al completamento di ogni task</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Copertura percentuale dei test (<i>TestCoverage</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i moduli software nuovi scritti in linguaggio C# / Java</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;IQ12&space;=&space;TestCoverage" title="IQ12 = TestCoverage" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,05<br/>
      - per eccesso se la prima cifra decimale è > 0,05
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">
      IQ12 >= 70%
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

#### 2.3.4 IQ13 - Qualità della documentazione

Grazie all'uso della Gamification si possono ottenere feedback sulla documentazione svolta dai dipendenti.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Valutazione della documentazione da parte dei dipendenti</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Valutazione con numero intero (da 1 a 5)</th>
    <th align="left">Fonte dati</th>
    <td align="left">Feedback dei dipendenti</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Almeno una volta al mese (libera sulla base della disponibilità dei dipendenti)</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di documenti valutati (<i>Ndoc</i>)</li>
            <li>Valutazione espressa per la documentazione di un file da parte di un dipendente (<i>Val_doc<sub>i</sub></i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i documenti per cui è stata rilasciata una valutazione</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;IQ13&space;=&space;\frac{\sum_{i=1}^{Ndoc}{Val\_doc_i}}{Ndoc}" title="IQ13 = \frac{\sum_{i=1}^{Ndoc}{Val\_doc_i}}{Ndoc}" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,05<br/>
      - per eccesso se la prima cifra decimale è > 0,05
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">
      IQ13 >= 3.7
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

#### 2.3.5 IQ14 - Qualità e utilità meeting

L'indicatore ha l'obiettivo di valutare la qualità e l'utilità dei meeting organizzati, basandosi sulle autovalutazioni prodotte dai partecipanti al termine di ogni incontro. Nel far ciò si considerano le domande booleane (YES/NO) nei questionari conclusivi (in numero potenzialmente diverso sulla base della tipologia di meeting), ricordando come le risposte "YES" siano sempre associate a caratteristiche positive del meeting in esame.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Qualità e utilità dei meeting</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Punto percentuale</th>
    <th align="left">Fonte dati</th>
    <td align="left">Documentazione dei meeting</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Mensile (solo se in presenza di meeting)</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di meeting svolti (<i>Nmeeting</i>)</li>
            <li>Numero di partecipanti di un meeting (<i>Npartecipanti<sub>i</sub></i>)</li>
            <li>Risposte "YES" di un partecipante nel documento di un meeting (<i>Nyes<sub>ij</sub></i>)</li>
            <li>Numero totale di domande presenti nel documento di un meeting (<i>Ndom<sub>i</sub></i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerati tutti i documenti per cui è stata rilasciata una valutazione</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ14&space;=&space;\left&space;(&space;\frac{\sum_{i=1}^{Nmeeting}{\sum_{j=1}^{Npartecipanti_i}{\frac{Nyes_ij}{Ndomi}}}}{Nmeeting}&space;\right&space;)&space;\times&space;100" title="IQ14 = \left ( \frac{\sum_{i=1}^{Nmeeting}{\sum_{j=1}^{Npartecipanti_i}{\frac{Nyes_ij}{Ndomi}}}}{Nmeeting} \right ) \times 100" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,5<br/>
      - per eccesso se la prima cifra decimale è > 0,5
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">
      IQ14 >= 70%
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

#### 2.3.6 IQ15 - Qualità UX

L'indicatore ha l'obiettivo di valutare la qualità dell'UX, basandosi sulle valutazioni rilasciate per mezzo degli specifici questionari rivolti agli utenti delle varie applicazioni. Nel far ciò si considerano solo i dati della soluzione finale e non quelli legati a soluzioni passate, pesando ogni punteggio espresso con un peso legato all'importanza del caso d'uso cui si riferisce.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Qualità UX</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Punteggio (1 - 10)</th>
    <th align="left">Fonte dati</th>
    <td align="left">Questionari UX</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Alla consegna delle micro e delle macro release (eventualmente in più sessioni)</i></th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di questionari svolti (<i>Nquestionari</i>)</li>
            <li>Numero di valutazioni di ultima sessione di un questionario (<i>Nvalutazioni<sub>i</sub></i>)</li>
            <li>
            Peso d'importanza di una valutazione (<i>Peso<sub>ij</sub></i>)
              <table>
                <tr>
                  <th>Importanza</th>
                  <td align="center"><i>Alta</i></td>
                  <td align="center"><i>Medio</i></td>
                  <td align="center"><i>Bassa</i></td>
                </tr>
                <tr>
                  <th>Peso</th>
                  <td align="center"><i>3</i></td>
                  <td align="center"><i>2</i></td>
                  <td align="center"><i>1</i></td>
                </tr>
              </table>
            </li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nel caso di più sessioni di rilevazione, nel calcolo vanno considerati soltanto i punteggi più recenti (di ultima sessione) per il questionario in esame</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;IQ15&space;=&space;\left&space;(&space;\frac{&space;\sum_{i=1}^{Nquestionari}{&space;\frac{\sum_{j=1}^{Nvalutazioni_i}{valutazione_ij&space;\times&space;peso_ij}}{\sum_{k=1}^{Nvalutazioni_i}{peso_ik}}}&space;}&space;{Nquestionari}&space;\right&space;)&space;\times&space;10" title="IQ15 = \left ( \frac{ \sum_{i=1}^{Nquestionari}{ \frac{\sum_{j=1}^{Nvalutazioni_i}{valutazione_ij \times peso_ij}}{\sum_{k=1}^{Nvalutazioni_i}{peso_ik}}} } {Nquestionari} \right ) \times 10" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - per difetto se la prima cifra decimale è <= 0,05<br/>
      - per eccesso se la prima cifra decimale è > 0,05
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">
      IQ15 >= 75%
    </td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

### 2.4 Indicatori di qualità specifici degli obiettivi sviluppati in modalità object oriented

Gli indicatori di seguito elencati, relativi ai soli obiettivi sviluppati in modalità object oriented, si applicano in aggiunta ai precedenti di cui ai paragrafi da 3.1 a 3.3.

#### 2.4.1 IQ16 - Violazioni dell’Incapsulamento da parte di una Classe

La metrica, applicata in maniera analitica ad ogni Classe dell’obiettivo contrattuale, consente di stabilire se è rispettato il paradigma Object  Oriented dell’incapsulamento poiché rileva il numero dei metodi che accedono a dati definiti in un’altra Classe che sono una violazione di questo paradigma. La violazione dell’incapsulamento peggiora la manutenibilità del codice stesso, in quanto una modifica della definizione di uno dei suddetti dati, comporta un impatto su tutte le Classi che accedono a quel dato.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Rispetto del paradigma OO dell'incapsulamento da parte della Classe per software sviluppato in linguaggi C# / Java</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Numero di violazioni dell'incapsulamento</th>
    <th align="left">Fonte dati</th>
    <td align="left">Codice sorgente<br/>Tool automatici</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione dell'obiettivo</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">A fine sviluppo o a fine realizzazione</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di Metodi di una Classe che accedono ai dati Pubblici o Protetti, generando una violazione al principio di incapsulamento (<i>Pub_data</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Si applica a tutti i metodi della classe</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ16 = Pub_data</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ16 = 0</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.4.2 IQ17 - Metodi implementati in una Classe

Questa metrica va applicata ad ogni Classe dell'obiettivo contrattuale ed effettua il conteggio dei metodi che è una prima misura della complessità di una Classe. Troppi metodi rendono la Classe di difficile comprensione e incrementano il rischio di errori a fronte di una modifica. Inoltre un numero elevato di metodi incoraggia il "coupling" tra le Classi, diminuendo la manutenibilità del software.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Numero dei Metodi implementati in una Classe per software sviluppato in linguaggi C# / Java</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Numero dei Metodi implementati in una Classe</th>
    <th align="left">Fonte dati</th>
    <td align="left">Codice sorgente<br/>Tool automatici</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">A fine sviluppo o a fine realizzazione</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero dei Metodi della Classe (<i>NMC</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ17 = NMC</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ17 <= 16</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">
    Una coppia di metodi Getter e Setter è considerata con valore unitario ai fini del conteggio.
    </td>
  </tr>
</table>

<br/>

------------

<br/>

#### 2.4.3 IQ18 - Grado di coesione dei Metodi di una Classe

Questa metrica va applicata ad ogni Classe dell’obiettivo contrattuale e quantifica la Coesione dei Metodi di una Classe. Valori elevati indicano un migliore disegno delle Classi, mentre, valori bassi indicano un incremento della complessità sino a risultare procedurale e non di tipo OO. La metrica deve essere usata per aiutare a determinare se la numerosità delle funzioni esplicate dalla Classe è giustificata, in relazione alla complessità della Classe stessa.

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Manutenibilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Modificabilità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Coesione dei Metodi di una Classe per software sviluppato nei linguaggi C# / Java</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Unità percentuale</th>
    <th align="left">Fonte dati</th>
    <td align="left">Codice sorgente<br/>Tool automatici</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Durata della fase di realizzazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">A fine sviluppo o a fine realizzazione</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero dei Metodi della Classe (<i>M</i>)</li>
            <li>Numero di Variabili (Attributi) di una Classe (<i>A</i>)</li>
            <li>Numero di Metodi che accedono ad una Variabile (Attributo) (<i>m<sub>j</sub></i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Si applica a tutti i metodi di una Classe</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ18&space;=&space;\left&space;(&space;1&space;-&space;\frac{\sum_{j=1}^{A}{m_j}}{M&space;\times&space;A}&space;\right&space;)&space;\times&space;100" title="IQ18 = \left ( 1 - \frac{\sum_{j=1}^{A}{m_j}}{M \times A} \right ) \times 100" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
      Il risultato della misura va arrotondato:<br/>
      - all'intero per difetto se la prima cifra decimale è <= 5<br/>
      - all'intero per eccesso se la prima cifra decimale è > 5
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ18 >= 75%</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sull'obiettivo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">
    Sono escluse dal rispetto del valore di soglia le classi che non hanno dati propri
    </td>
  </tr>
</table>

<br/>

------------

<br/>

## 3 INDICATORI DI QUALITÀ DEL SERVIZIO DI MANUTENZIONE CORRETTIVA

#### 3.1 IQ19 - Casi recidivi (per area applicativa)

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Affidabilità</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Maturità</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Numero di interventi correttivi riguardanti uno stesso malfunzionamento (riciclo correttivo)</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Casi recidivi</th>
    <th align="left">Fonte dati</th>
    <td align="left">Verbale della rilevazione</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Trimestre precedente la rilevazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Trimestrale</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero di interventi di manutenzione correttiva recidivi per lo stesso malfunzionamento (<i>Ncasi_recidivi</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3"><i>IQ19 = Ncasi_recidivi</i></td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ19 = 2</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Il mancato rispetto del valore di soglia durante il periodo di garanzia comporterà Penale "Casi recidivi in garanzia"</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

## 4 INDICATORI DI QUALITÀ DEL SERVIZIO DI GESTIONE APPLICATIVA

#### 4.1 IQ20 - Tempo medio di risposta al cliente

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Efficienza</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Efficienza temporale</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">Tempo medio di risposta al cliente</td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Ore lavorative</th>
    <th align="left">Fonte dati</th>
    <td align="left">E-mail</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Mese precedente la rilevazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Mensile</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Data e Ora (hh/mm) di ricezione della richiesta (<i>Data_ricezione</i>)</li>
            <li>Data e Ora (hh/mm) della effettiva risposta all’utente / della prima diagnosi (<i>Data_risposta</i>)</li>
            <li>Numero totale richieste riguardanti una singola area applicativa pervenute nel periodo di riferimento (<i>Ntotale_richieste</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Vanno considerate tutte le richieste che riguardano una singola area applicativa pervenute nel periodo di riferimento</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ20&space;=&space;\frac{\sum_{j=1}^{Ntotale\_richieste}{(Data\_risposta_j&space;-&space;Data\_ricezione_j)}}{Ntotale\_richieste}" title="IQ20 = \frac{\sum_{j=1}^{Ntotale\_richieste}{(Data\_risposta_j - Data\_ricezione_j)}}{Ntotale\_richieste}" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
    Il risultato della misura va arrotondato al decimo di punto:<br/>
    - per difetto se la prima cifra decimale è <= 5 <br/>
    - per eccesso se la prima cifra decimale è > 5
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ20 <= 3h</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo sulla fornitura per ogni ora o frazione superiore al valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>

<br/>

------------

<br/>

## 5 INDICATORI DI QUALITÀ APPLICABILI A TUTTI I SERVIZI DELLA FORNITURA

#### 5.1 IQ21 - Soddisfazione del committente

<table>
  <tr>
    <th align="left">Caratteristica</th>
    <td align="left">Soddisfazione</th>
    <th align="left">Sottocaratteristica</th>
    <td align="left">Soddisfazione del cliente</th>
  </tr>
  <tr>
    <th align="left">Aspetto da valutare</th>
    <td align="left" colspan="3">
      La soddisfazione del committente (CSEN) è misurata rilevando dai questionari delle interviste le risposte fornite alle specifiche domande sulla soddisfazione dell'intervento rispetto alla rilevazione.
      <br/>
      Per le risposte vanno utilizzati numeri positivi su scala da 1 a 10 dove:
      <ul>
        <li>1 corrisponde a "non soddisfatto";</li>
        <li>6 corrisponde a "appena soddisfatto";</li>
        <li>7 corrisponde a "soddisfatto";</li>
        <li>10 corrisponde a "pienamente soddisfatto".</li>
      </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Unità di misura</th>
    <td align="left">Punto percentuale</th>
    <th align="left">Fonte dati</th>
    <td align="left">Questionari</th>
  </tr>
  <tr>
    <th align="left">Periodo di riferimento</th>
    <td align="left">Periodo antecedente la rilevazione</th>
    <th align="left">Frequenza di misurazione</th>
    <td align="left">Ad ogni macro release e a un mese dal completamento dell'intero progetto</th>
  </tr>
  <tr>
    <th align="left">Dati da rilevare</th>
    <td align="left" colspan="3">
        <ul>
            <li>Numero risposte positive (<i>risposte con valore >= 7</i>) (<i>Nrispsote_pos</i>)</li>
            <li>Numero di domande del questionario (<i>Ndomande</i>)</li>
            <li>Numero totale di questionari compilati (<i>Nquestionari</i>)</li>
        </ul>
    </td>
  </tr>
  <tr>
    <th align="left">Regole di campionamento</th>
    <td align="left" colspan="3">Va scelto un campione significativo degli utenti dei servizi della fornitura da intervistare da concordare con CSEN</td>
  </tr>
  <tr>
    <th align="left">Formula</th>
    <td align="left" colspan="3">
      <img src="https://latex.codecogs.com/gif.latex?\inline&space;\dpi{150}&space;IQ21&space;=&space;\sum_{i&space;=&space;1}^{Nquestionari}{\frac{Nrisposte\_pos_i}{Ndomande_i}}\times&space;100" title="IQ21 = \sum_{i = 1}^{Nquestionari}{\frac{Nrisposte\_pos_i}{Ndomande_i}}\times 100" />
    </td>
  </tr>
  <tr>
    <th align="left">Regole di arrotondamento</th>
    <td align="left" colspan="3">
    Il risultato della misura va arrotondato al decimo di punto:<br/>
    - per difetto se la prima cifra decimale è <= 5 <br/>
    - per eccesso se la prima cifra decimale è > 5
    </td>
  </tr>
  <tr>
    <th align="left">Valore di soglia</th>
    <td colspan="3">IQ21 >= 70%</td>
  </tr>
  <tr>
    <th align="left">Azioni contrattuali</th>
    <td align="left" colspan="3">Rilievo nel caso di non rispetto del valore di soglia</td>
  </tr>
  <tr>
    <th align="left">Eccezioni</th>
    <td align="left" colspan="3">Nessuna</td>
  </tr>
</table>