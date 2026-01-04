1.Klasifikace sítí, topologie sítí

Podle geografického rozsahu
Pan(Personal)
-velmi malý rozsah
-propojení osobních zařízení
-prenos medium Bluetooth 2.4
-příklad:(sluchatka mobil)

Lan(local)
-místní síť (domáconst,škola,firma)
-vysoké rychlosti nízká latence
-drát i bez drát
-příklad:školní sÍť

Man(metropoli)
-pokrýva město
-spojuje Lany
-optika drát
-příklad:síť poskytovatelů

Wan(wide) - největší
-velké vzdálenosti - státy kontinenty
-vyšší latence, nižší rychlost než Lan
-příklad:Internet

Podle způsobu řízení

Peer-to-Peer
-není žádný server žádný client
-každý může být server či client
-jednoduchy ale méně bezpečné než client server
-příklad:malá domácí síť(pc chce od pc neco takže to pc co něco chce je client a ten co odesíla(poskytuje službu) je server)

Client-Server
-určeny servery a od nich si clienti žádají služby
-předem vše určeno
-lepší správa,bezpečnost
-příklad:školní síť,firemní síť(počítač(client) chce něco vytisknout požádá tiskarnu(server) o tisk) 

Podle přenos media

Drát
-kroucena dvojlinka(utp-stp-ftp...)
-optické vlákno(single mod,multi mod)
-koaxilní kabel(historie)

Bezdrát
-wifi(2.4.,5.0,6.0 GHz)
-Bluetooth,Zigbee(2.4)
-mobilní síť(LTE,5G)

Topologie

Bus(sběrnice)
coax 
pouziva ji se Tcka na propojení a terminatory s 50odporem aby nebyla kolize
jen jeden posíla

Star(Hvězda)
coax ale spíše kroucena
central bod nejlépe switch L2 nebo L3 a nebo hub ale s hubem nepujde fullduplex
muze více posila ale podle kabelu a sttredu jestli hub nebo switch

Ring(Kruhová)
posíla se jen jednim smerem data i token kdo token ten posila data
spise historicke

tree(strom)
vice hvezd propojeno pres ten stred bod
ale neda se vice nez 7 switchu protoze pak je problem s casovanim dat

Mesh
kazdy s kazdym 
hodne draha nejvice spolehliva




