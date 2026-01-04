prvni bylo tcp to funguje ted v praxi a ta teoreticka cast je iso osi
tcp od arpanetu(praxi)
osi od international organization for standardization(referenční)

existence sítovich moodelu kvuli tomu ze vime jaka vrstva co dela 
diky tomu máme 
jednodušší návrh síte
hledání chyb

aplikační 7
komunikace s uzivatelem
protkoly:
http/https prenos webovek
FTP přenos souboru
SMTP prenos emailu
POP3 stahovani emailu
IMAP aby jsme mohli z vice zarizeni na email
DNS preklad ip na domenu 
DHCP pridavani ip adress

prezentační 6
jak ty data vidíme
šifrování(SSH),komprese(zmenšení),kodovani(jak ty data jsou zapsana)
komprese = aaabbb = 3a3b
kodovani = a = 7 = 111
sifrovani = tls/ssh

relační 5
navazuje relaci a udržuje
řízení dialogu

transportní 4
cisluje porty 
ridi prenos data 
tcp =pomaly ale spolehlivy -segment
udp = rychly ale nespolehlivy-datagram

sitova 3
logicke adresy IP
smerovani paketu
ip = nespolehlivý
ipsec da se radit i k transportní = aby byl prenos safe
icpm = dava nam hlasku pri ping ze neni dostupny 
router

spojova/linkova 2
dela ramec
pouziva se tu mac adresy 
pridava se crc/fcs a preamble
ethernet = kouka na crc/fcs taky urcuje rychlost jakou bude se posilat
arp = získava mac adresy zavisi na ip adresach
switch L2

fyzicka 
uz prenos dat
elektricke radiove opticke signaly
je tady vse fyzicke kabely konektory napeti frekvence

tcp         iso
aplikacni   -aplikacni 
                prezentacni
                relacni
transportni - transportni
internet    - sitova
                linkova spojova
sitove rozhrani-fyzicka

