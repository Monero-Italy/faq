# FAQ
Domande frequenti per Monero project. Queste faq non sono tecniche ma un aiuto per i primi utenti, pertanto se ne sconsiglia l'uso nel caso in cui cerchiate un informazione strettamente tecnica. 

## D: Che cosa è Monero?
Monero è una criptomoneta basata sul protocollo p2p e su una blockchain pubblica in cui vengono tracciate tutte le transazioni. A differenza di altre criptomonete come bitcoin o ethereum, Monero è l'unica ad avere un algoritmo sicuro e privato utilizzato di default per nascondere la tracciabilità delle transazioni. In poche parole nessuno può vedere quanti Monero hai o quanti ne hai spesi per quella transazione.

## D: Consiglio per un buon wallet?

Per sistemi come Windows, Mac OS e Linux, esiste solo un wallet di cui potete fidarvi: quello originale e ufficiale, scaricabile su https://getmonero.org

Per sistemi come Android, alcuni membri della community hanno sviluppato un wallet per Monero 
https://play.google.com/store/apps/details?id=com.m2049r.xmrwallet

Diffidate di progetti esterni che non sono garantiti dalla community di Monero, basta infatti una semplice ricerca sul web per capire se un progetto è una truffa (anche chiamato progetto scam).

Se invece non si vuole installare alcun wallet, esiste il web wallet per eccellenza, sviluppato da uno degli sviluppatori principali fluffypony: http://mymonero.com


## D: Blockchain? Devo scaricarla tutta? 

Sarebbe meglio scaricarla tutta avviando il programma monerod.exe (win) o ./monerod (linux, mac), altrimenti c'è l'opzione Remote node, ovvero connettersi a un remote node che ha già scaricato la blockchain. 

Semplicemente su Settings (Impostazioni) > Daemon address, mettete l'indirizzo del nodo remoto node.moneroworld.com e come porta 18089. Online ce ne sono vari di daemon, per una lista completa visitare https://moneroworld.com

Prima di connettersi ad un remote node, assicurarsi di aver chiuso il daemon (si può vedere ciò dal pulsante "Stop daemon" disabilitato).

![Daemon remoto](https://getmonero.org/resources/user-guides/png/remote_node/remote-node-screenshot.png)

Usando un remote node, il tempo medio di download è circa 5/10 minuti. Il tempo può variare in base alle caratteristiche tecniche del proprio computer e della rete a cui si è connessi.

## D: Monero è una truffa: ho appena trasferito un po' di Monero sul mio nuovo address ma non compare nulla!11! I miei soldi son spariti

Prima di dire che Monero sia una truffa, assicurarsi di aver eseguito tutti i passaggi elencati qua sotto:

* L'address a cui si è inviato Monero è valido ed è giusto
* La sincronizzazione della blockchain è finita (remoto o no non cambia)
* Il computer è acceso ed è connesso stabilmente ad internet
* L'eventuale exchange con cui si sta operando non è un exchange scam (Attenzione: durante i periodi di pump o dump, a causa dell'alto volume degli utenti, gli exchange faticano a star dietro a tutti le transazioni. Se per qualche ragione pensate di aver perso i soldi, contattate immediatamente il supporto dell'exchange).

