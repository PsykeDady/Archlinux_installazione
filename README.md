# Archlinux_installazione
Guida installazione di archlinux personalizzata

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

## note FIX/ADD/DEL/EDIT -> 1.3
* [add] in pacstrap aggiunti linux e linux-firmware (! **importante**)
* [edit/del/add] modificata sezione aur-helper, tolto pakku e aggiunto yay ( più guida generale)
* [add] nel comandone son stati aggiunti hyphen, mythes e hunspell per la sillabazione italiana su libreoffice
* [add] aggiunta una sezione per la personalizzazione GRUB
* [add] aggiunto gruppo telegram di ArchlinuxItalia
* [edit] grazie a **MattiaCosmy** per avermi mandato molte correzioni :) 
* [edit] salvato il file in formato fodt, formato non compresso di libreoffice che preserva un po' meglio la formattazione del documento

## TODO -> verso la 1.4
* se avete telegram e vi intendete di licenze, contattatemi (contatti nelle ultime pagine del pdf), perchè il primo punto che vorrei sistemare è l'introduzione di una licenza e vorrei chiacchierare con qualcuno con cui confrontarmi su LGPL, CC e WTFPL(1/2)
* creare stile apposito per percorsi di sistema come è stato fatto per codici inline e non
* inserire rfkill unblock/block nella sezione del net per recupero linea (unblock all/list all)
* rendere il documento più "impersonale"
* aggiungere plugin zsh
* sostituire mountpoint /boot/efi con le specifiche più recenti per /efi
* powerlevel10k invece ( o accanto a) di powerlevel9k


## TODO -> verso la 2.0
* guida dedicata per macbook
* guida lvm
* copertina documento da rifare, non è mia.

