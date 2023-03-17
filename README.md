# Filius-Router

A cosa serve il server DHCP?
Un server DHCP ci permette di assegnare automaticamente ai dispositivi che si collegano alla rete un indirizzo IP, una subnet mask, il gateway e il DNS server eliminando così la necessità per l’utente di configurare manualmente queste informazioni. Può anche gestire gli IP dinamici.


Perchè inizialmente i PC delle due reti non si raggiungevano con ping?
Nel progetto riscontriamo più di un problema. Nella rete con IP 192.168.0.0 ci accorgiamo subito che il DHCP server non ha impostato il gateway della rete e quindi i ping non riescono ad uscire da questa rete, per risolvere ci basterà assegnare l’IP del gateway, in questo caso il router, dentro al DHCP server setup.

Mentre nella rete con IP 192.168.1.0 ci basterà dentro il nostro notebook cliccare sulla casella “Use DHCP for configuration” data che in questo caso il DHCP è configurato bene.

Quale protocollo viene utilizzato dal comando ping?
Il comando ping utilizza un protocollo per verificare la connessione tra due dispositivi, esso utilizza il protocollo ICMP (Internet Control Message Protocol) che viene utilizzato per inviare messaggi di controllo su una rete. Quando eseguiamo il ping, il dispositivo invia un “echo request”  all’altro dispositivo e attende un “echo reply”, se questa risposta viene ricevuta significa che la connessione funziona in modo corretto.



