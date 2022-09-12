# Installazione Archlinux - note aggiuntive per Macbook

**Il seguente documento è ancora in fase di scrittura.**

> **<u>ATTENZIONE</u>**:
>
> ==La guida &egrave; pensata specificatamente per il mio Macbook, modello Late 2012 (retina)==

## pacstrap

Aggiunte da fare a pacstrap: 

- dkms
- broadcom-wl-dkms
- linux-headers

## ventola

installare pacchetto aur 

**mbpfan-git** 



attivare servizio con :
` systemctl enable mbpfan.service`

# Template e legenda

Seguono i template utilizzati per il file Markdown:

`codice inline o singola linea di codice`

```bash
# codice bash 
a blocchi o con sintassi da evidenziare
```

Nei blocchi di codice l'introduzione di un cancelletto (#) è da intendersi come commento.

Tra parentesi angolate (&lt;&gt;) trovate il nome dei valori che dovreste sostituire voi (ad esempio `<nomeutente>` se il vostro nome è *Mario*, è da sostituire con **Mario**, eliminando le parentesi)

Tutti i comandi dati con sudo è da sottintendere che necessitino dei permessi di amministratore, perciò se li operate da account root può essere evitato il sudo.

> <u>NOTE</u>:
>
> note 

> **<u>ATTENZIONE</u>**:
>
> ==Un avvertimento.
> Il tratto appena spiegato non è stato testato oppure potrebbe fallire in determinati casi, perciò ne è sconsigliato l'utilizzo se non si sa esattamente quello che si fa. L’autore declina ogni responsabilità per danni che si possano verificare sul proprio sistema o dispositivo==

> *<u>SUGGERIMENTO</u>*:
> Un suggerimento orientato soprattutto ai meno esperti
