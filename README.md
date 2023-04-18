# WPFThreads

## Introduzione:
### Abbiamo seguito questo compito pari passo col prof e ciò aveva lo scopo di farci capire come funzionassero i thread e di come poter creare dei thread attraverso delle righe di codice presenti nel file allegato a questa repository.
## Obbiettivo del compito:
### In questo compito abbiamo creato 3 contatori che contavano insieme e 1 contatore totale,dove abbiamo creato un thread per ognuno di essi .


## Step 1:
### Inanzitutto un thread è una parte del processo che viene eseguita in maniera concorrente ed indipendente internamente allo stato generale del processo stesso.
### Quindi come prima cosa abbiamo creato ed istanziato i nostri thread:
### ![creazione thread](/immagini_WPFThreads/wpf1.png)

## Step 2:
### In seguito abbiamo creato un altro thread con all'interno una funzione di WAIT che ci serve a sospendere il thread e subito dopo  abbiamo usato un Dispatcher.Invoke che serve a eseguire in modo sincrono nell'ordine in cui sono posizionate le istruzioni che seguono dopo la funzione lambda che ci aiuta a creare una funzione
### ![creazione thread](/immagini_WPFThreads/wpf3.png)
### Una volta finita l'esecuzione dei comandi all'interno del Dispatcher.Invoke il pulsante sarà di nuovo disponibile per l'utilizzo

### ![creazione thread](/immagini_WPFThreads/wpf4.png)

## Step 3:
### Proseguendo abbiamo inserito i comandi da eseguire all'interno del dispatcher che ci servivano ad incrementare il contatore:
### ![creazione thread](/immagini_WPFThreads/wpf5.png)
### e la progressbar:
### ![creazione thread](/immagini_WPFThreads/wpf6.png)


