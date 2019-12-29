# Archlinux_installazione
Guida installazione di archlinux personalizzata

## Se vuoi modificare la guida
font e stili attualmente utilizzati per la guida:
* Ubuntu (corpo del testo, pt 12)
* Fira Code (stile codice inline e codici )
* Liberation Sans (titolo 1, senza capolettera)
* Liberation Serif (capolettera titolo 1) 

## note rilascio 1.0
È uscita la versione 1.0 Talete, la prima versione di questa guida che mi sento dichiarare "matura".
__La primissima e importante novità è che ho abbandonato il file latex a vantaggio di un normalissimo odt__, modificabile con molte tipologie di suite per l'ufficio. Questa scelta sono sicuro che farà stizzire tantissimi utenti, ma latex non mi consentiva modifiche veloci al file da qualunque postazione, inoltre molti utenti lamentavano del fatto che con il copia e incolla alcuni caratteri sformattavano malissimo, quindi ho riscritto tutto. 
Il file latex è ancora nella cartella latex_old, chiunque volesse mantenerlo è libero di farlo. 
Prego a chiunque voglia suggerirmi modifiche, di non toccare la formattazione del file, si può discutere comunque su accostamenti colori/forme dei box, ma la decisione finale vorrei mi spettasse.

qui un riassunto di ciò che è stato introdotto/corretto:

* [add] aggiunta sezione per swap e ibernazione
* [fix] sistemata sezione pakku
* [fix] invertiti comandi per aggiornamento grub
* [add] aggiunta sezione lsd
* Comandone 
* * [fix] sostituito aurman con pakku
* * [fix] suddivise zone per tipologia di programmi
* * [add] aggiunto chrome
* * [fix] eliminato rar, in conflitto con unrar
* * [edit] sostituita la jdk proprietaria con quella open
* [fix] eliminato kde l10n it
* [add] aggiunto a neofetch il pacchetto pacman-contrib
* [add] aggiunta sezione per orario in dual boot con windows
* [add] aggiunte ( su richiesta di utenti) istruzioni per fdisk nella sezione dei dischi dell'installazione
* [fix/add/edit] altre piccole modifiche

## note FIX/ADD/DEL/EDIT -> 1.5
* [edit] PACSTRAP= separato su pacstrap nano da altri pacchetti 
* [add] POST-INSTALLAZIONE= aggiunta installazione man e man-pages
* [fix] LOCALE= sistemate virgolette su sezione locale
* [edit] LOCALE= specificato come sbloccare altre lingue
* [edit] DE=specificato che per altri DE è meglio consultare la guida
* [fix] COMANDONE= era rimasto un riferimento a pakku
* [fix] SWAPFILE= aggiunto mkswap e sistemato mkconfig di grub
* [edit/add] FSTAB= separate sezioni virtualbox da aggiunta nuovo volume su fstab
* [add] DUALBOOT= aggiunta installazione ntfs-3g
* [add] LICENZA=aggiunta licenza in prefazione + ultimo capitolo per intera (licenza FDL)

## TODO -> verso la 1.5.1
* [add] Aggiungere cartelle e readme per creare una docs con mirko

## TODO -> verso la 1.6
* creare stile apposito per percorsi di sistema come è stato fatto per codici inline e non
* inserire rfkill unblock/block nella sezione del net per recupero linea (unblock all/list all)
* rendere il documento più "impersonale"
* aggiungere plugin zsh
* powerlevel10k invece ( o accanto a) di powerlevel9k
* aggiustare dipendenze neofetch, guardare da github

## TODO -> verso la 2.0
* guida dedicata per macbook
* guida lvm
* copertina documento da rifare, non è mia.

