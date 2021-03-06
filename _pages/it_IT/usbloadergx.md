---
title: "USB Loader GX"
---

{% include toc title="Table of Contents" %}

Se ti serve aiuto riguardo questa guida, entra nel [server Discord di RiiConnect24](https://discord.gg/b4Y7jfD) (consigliato, solo in inglese) o [mandaci una e-mail a support@riiconnect24.net](mailto:support@riiconnect24.net).
{: .notice--info}

Questa guida è una presentazione a USB Loader GX, un USB Loader molto famoso, utilizzato per giocare ai giochi tramite un dispositivo USB.

![USB Loader GX](/images/usbloadergx.png)

#### Cosa ti servirà

* Una Wii
* Un dispositivo USB
* [USB Loader GX](https://sourceforge.net/projects/usbloadergx/files/latest/download)

Assicurati di aver installato i [cIOS](/cios) prima di continuare!
{: .notice--info}

Consigliamo di copiare i giochi tramite [Wii Backup Manager](/wiibackupmanager) su Windows (WitGui per Mac).
{: .notice--info}

Se programmi di tenere molti giochi, consigliamo un hard drive esterno USB, al quale ci riferiremo come "dispositivo USB" per il resto della guida. La maggior parte di essi disponibili sul mercato dovrebbe funzionare senza problemi se hanno compatibilità USB 2.0 backwars. I dispositivi con 1TB o più di spazio disponibile saranno più che sufficienti. Una flash drive USB funzionerà senza problemi, ma per via della capacità di memoria inferiore non potranno reggere molti giochi.
{: .notice--info}

Assicurati che il tuo dispositivo USB sia formattato in FAT32 o NTFS. Non formattarlo in exFAT o WBFS, l'ultimo citato è un vecchio metodo di tenere giochi Wii.
{: .notice--info}

#### Istruzioni

##### Download

1. Estrai USB Loader GX nella cartella `apps` nella root della tua scheda SD o USB.
1. Inserisci il tuo dispositivo USB e la tua scheda SD (se ne usi una) e avvia USB Loader GX dal canale Homebrew Channel.

##### Iniziamo

Non c'è nessuna "guida" sul come usare USB Loader GX. La nostra vuole solo insegnarti ad usarlo dandoti una piccola introduzione ad esso. Imparerai ad utilizzare tutte le fantastiche funzioni di USB Loader GX utilizzandolo da solo.
{: .notice--info}

* Se USB Loader GX dice "Waiting for HDD..." con un countdown di 20 secondi, è altamente probabile che non riesce a localizzare il tuo dispositivo USB. Prova a uscire dall'app e aprila nuovamente dopo aver connesso il tuo dispositivo USB ad un'atra porta USB della Wii.
* Puoi premere il pulsante 1 sul telecomando Wii per scaricare le cover e banner dei giochi da [GameTDB](https://gametdb.com/). La durata del download dipenderà da quanti giochi possiedi.
* Ci sono WADs che possono aprire USB Loader GX se aperti dal Menù Wii. Essi si chiamano forwarder WAD.
* I giochi GameCube o i giochi Wii "custom" potrebbero non avere una cover/banner da usare con USB Loader GX. Per aggirare il problema, scrivi `CustomBannersURL = http://banner.rc24.xyz/` nel file config/GXGlobal.cfg sul tuo dispositivo USB. Potrai successivamente scaricare i Banner "Custom" premendo 1 sul tuo telecomando Wii.

##### Interfaccia

Ci sono molti pulsanti nell'interfaccia di USB Loader GX.

###### Menù Principale

Ecco le funzioni che puoi trovare nel Mnù Principale in alt (da sinistra a destra):

* Stella - Mostra i giochi ai quali hai assegnato una o più stelle, segnandoli come "preferiti".
* Cerca - Ti permette di cercare i giochi per nome.
* Ordina - Ti permette di scegliere in che ordine posizionare i giochi.
* Piattaforma - Ti permette di ordinare i giochi per piattaforma.
* Categoria - Ti permette di ordinare i giochi per categoria.
* Lista - Mostra i giochi in lista.
* Vista Multi-Cover - Mostra i giochi in una lista Multi-Cover.
* Vista Cover a giostra - Mostra i giochi in uno stile "Cover a giostra".
* Vista Wii Menù - Mostra i giochi come se fossero canali del Menù Wii.
* Parental Control - Restringe USB Loader GX.
* Disco - Carica un gioco via disco.

Premere su un qualunque gioco ti permetterà di giocarlo premendo "Gioca".

There are also other buttons:

* Icona + - "Installa" un gioco, effettuando un backup del gioco inserito nella console Wii (via DVD).
* Rotelle - Impostazioni di USB Loader GX.
* Scheda SD - Rimonta la scheda SD.
* Homebrew - Carica app Homebrew.
* Wii - Apre il Menù HOME (che puoi aprire anche premendo il pulsante HOME sul telecomando Wii).
* Pulsante POWER - Spegne la tua Wii.

In basso al centro puoi vedere quanto spazio disponibile hai sul tuo dispositivo USB e quanti giochi possiedi.

##### Ora che hai finito

[Naviga il sito](site-navigation)<br>
Abbiamo molte altre guide che apprezzerai.
{: .notice--info}
