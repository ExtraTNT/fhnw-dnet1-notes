[[IP]] to [[Mac]], [[IPv4]]

broadcast ip to ff:ff:ff:ff:ff:ff

Host A kennt IP von Host B, aber nicht MAC

Host A erstellt ARP Request Package (IP, MAC von A, IP von B, Broadcast MAC)

Kommt es zu einem Switch werden die Infos über source MAC gespeichert 
Das Paket wird an alle Mitglieder im Layer 2 weitergeleitet (Broadcast alle Ports)

Kommt es beim Host mit der Destination IP an, erstellt dieser eine ARP response welche er dann an die MAC des Senders zurück sendet

Switches dazwischen leiten den Unicast Response gemäss eigener MAC Tabelle weiter.

ACHTUNG: L2 Switches erstellen keine ARP Table – sie leiten nur weiter gemäss ihrer MAC Address Table

![[Pasted image 20250225093218.png]]

Gratuitous ARP Message
ARP Message (grundsätzlich an Broadcast) welche nicht auf einen Request Antwortet und nicht nach einer Adresse Sucht

z.B Announcement (NIC up, new ip)
Probe (NIC test, if someone already uses an ip)