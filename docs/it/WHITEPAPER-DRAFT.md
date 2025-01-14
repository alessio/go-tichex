# Tichex Blockchain

Tichex é una blockchain DPoS basata su Tendermint e Cosmos SDK.

Tichex nasce per risolvere il problema delle stable coin centralizzate. Inoltre risolve il rpoblema della liquidità, sia Crypto/crypto Che Crypto/fiat. Sulla blockchain di Tichex sarà possibile creare 3 tipologie differenti di token.

## Blockchain
La blockchain si basa sull'algoritmo di consenso Bizantine Fault Tolerance (consenso 2/3 della rete), con algoritmo di Stacking DPoS.

## Tipologie di Token
* Token pegged to Fiat
* Liquidity Token pegged to TCX (our native coin)
* Standard Token (no pegged)

## Attori partecipanti
Per far si che la blockchain funzioni, devono esserci 4 tipologie di utenti.

* Fiat Providers
* Validators
* Aziende
* Utenti

I *Fiat Providers*, sono istituti bancari autorizzati e regolamentati. Il loro compito è di fare da bridge tra la nostra blockchain ed il loro circuito bancario. Loro sono gli unici autorizzati ad emettere (mint) parte di un Token Fiat. Dico parte, perché nella blockchain di Tickex i token pegged to fiat iniziano per T, esempio TEUR, TUSD, TGBP, TKRW.
Un Fiat Provider può quindi eseguire un mint dei seguenti token. Facciamo un esempio...

*Em@ney plc* essendo un istituto autorizzato, fa richiesta a Tichex per essere un Fiat Provider. Per fare richiesta Emoney aprirà un proposal sulla blockchain di Tichex, successivamente la proposta avrà un periodo di voting di 30 giorni (o più). I Validator e qualsiasi altro utente abbia messo in Stacking TCX ha diritto ad esprimere un parere e quindi votare la proposta. Il voto dell'utente avrà il valore uguale al suo valore nella rete (es se ci sono 100 milioni di TCX in Stacking e l'utente ne ha messo 1000, il suo voto avrà un voting power del 0.0001%)
Durante il periodo di voting, chiunque può eseguire e/o richiedere documentazionr attestante la solidità del Fiat Provider. Una volta terminato il periodo di voting, il Fiat Provider sarà autorizzato ad emettere Fiat Token sulla nostra blockchain. Un altro esempio è SisalPay che decide di emettere un proprio token legato all'Euro e lo può fare pegged a TKEUR semplicemente selezionando una casella. In quel caso qualsiasi transazione sisal pay girerebbe sulla Blockchain di Tickex.
Al fine di evitare truffe o provider non solidi, il Fiat Provider, oltre a passare il processo di voting, dovrà anche depositare il controvalore di 1.000.000 € in TCX presso gli altri Fiat Providers. In questi giorni abbiamo assistito allo scandalo Tether, Dover risulterebbe un ammanco di 850 milioni di dollari dalle casse di bitfinex. Episodi del genere fanno perdere credibilità ad un settore con un grosso potenziale di crescita. Con questo sistema, il rischio viene ridotto ai minimi termini in quanto non sarà più solo un ente ad emettere TEUR, ma sarà un insieme di enti ad emettere un'unico token legato all'Euro. Stesso identico discorso vale per ogni altro Token Fiat.
Ricapitolando, i Fiat Provider saranno i Miner di TEUR e degli altri token stabili e devono rispettare requisiti legislativi e di community.

## I Validators
Loro hanno un ruolo importantissimo, sono i responsabili della nostra blockchain. Al fine di essere più decentralizzato possibile, Tichex in una fase iniziale avrà 100 validators, successivamente il numero sarà esteso a 500. I Validator Hanno il ruolo di proporre i blocchi con le transazioni, vengono scelti in base al loro voting power (ovvero il numero di TCX in Stacking / il totale dei TCX in Stacking). Il tempo di creazione di un blocco sarà di circa 5 secondi, ad ogni nuovo blocco creato verranno emessi [X] TCX, questo reward verrà inviato ogni 12 blocchi (circa un minuto) e sarà suddiviso a tutti i Validator in base al loro voting power.
I Validator inoltre guadagneranno anche dalla fee delle transazioni (anche esse decise tramite proposal). Ogni 250,000 blocchi (circa 2 settimane) verrà diminuito il numero di TCX emessi, i blocchi termineranno di emettere TCX non appena sarà raggiunto il supply di 10.000.000.000 TCX (da decidere). Le fee se pur microscopiche, saranno applicate per i trasferimenti, creazione di token, scelta del ticker....

## Aziende
Come aziende s'intende il motore del business, ovvero qualsiasi cosa che effettui transazioni. Immaginiamo un e-commerce, sulla nostra blockchain può emettere un token e deciderlo se farlo Fiat pegged, liquidity pegged (ovvero pegged ad altri token liquidty all'interno di Tichex, incluso quello nativo). Oppure un token standard ovvero no pegged. Successivamente tramite apposito plugin, può accettare pagamenti nel suo sito tramite il suo token oppure tramite altri token interni a Tichex ed avere liquidità Crypto o Fiat in maniera immediata. 
In molti casi anche i Fiat Provider possono iniziare a proporre questo nuovi servizi ai loro clienti business.

Gli utenti invece, possono effettuare transazioni, creare token, scambiarlo sul nostro Exchange nativo, fare IEO in maniera decentralizzato e anche loro avere liquidità immediata.

Un altro esempio è, un altro istituto che entra a fare parte del circuito ed estende il servizio ai propri clienti, quindi l'utente genererà token dal suo c/c.

I token Liquidity, avendo liquidità immediata, possono essere scambiati immediatamente senza necessità di dover immettere l'ordine in Exchange.

## ICO? No, grazie!
Tichex non ha intenzione di effettuare alcuna ICO. Il motore verrà azionato già dal primo blocco.

Nel blocco genesi, *TCX* avrà un supply iniziale di 0 e verrà emessa già come primo blocco reward. TKEUR invece, sarà emessa da Emoney e sarà acquistata dai Validator per lo staking iniziale. (Si potrebbe anche proporre un'asta iniziale per i primi 16, in questo caso a 100 Validator ci arriveremo nel tempo).
Una volta nato il blocco 12, i Validator hanno già i primi reward, e possono quindi andarli a vendere in TKEUR determinandone il valore di mercato. TKEUR/TCX sarà la prima coppia disponibile.

Le tecnologie utilizzate sono le stesse di Binance, BitSong, MINTEr, Cosmos, Iris Network. Tutte blockchain avanzate ed interconnesse tra di loro grazie a Cosmos.

Il progetto attirerebbe immediatamente numerosissimi investitori (oltre che Validator, ultimamente fanno a pugni per tutto quello che è Cosmos) e butterebbe giù la prima vera blockchain decentralizzata con valute stabili, Fiat Provider e token liquidi.
