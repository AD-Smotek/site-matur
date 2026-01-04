aplikacní vrstva je nejvissi vrstva modelu osi  i tcp ip
zajistuje komikaci mezi uzivatelem a aplikacemi a siti
aplikacní vrstva neni samostatna aplikace ale souhrn protokolu a sluzeb ktery aplikace pouzivaji
zajistuje:
-prenos souboru
-prenos emailu
-webouvou komunikaci
-preklad nazvu jako treba dns
-overeni uzivatelu
-vzdalenou spravu

aplikacni vrstva v tcp je jedna ale v osi je rozdelena na 3
aplikacni - komunikace mezi programem a siti
prezentacni- sifrovani kodovani a komprese
relacni - navazuje a drzi relaci

http/s
port:80
port:443 safe
prenos webovy stranky
pouziva tls - sifrovana komikace

smtp
odesila email
port:25,587,465

pop3
stahovani emailu
pak se maže s serveru
port:110

imap 
stahuje email
zustava na serveru
synchro vice zarizeni
port:143

ftp
prenos souboru
not safe
port:21
ftps/sftp
safe sifrovany

dns 
prevadi domenu na ip
port:53

telnet
vzdaleny pristup
not safe
nepouziva
port:23

ssh
vzdaleny pristup
sprava zarizeni
safe
port:22

dhcp
automaticky dava ip,maska,branu,
port:67,68

snmp
sprava monitoring siti
sledovani zarizeni
port:161/162

