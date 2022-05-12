# Raspberry-PiCursus-Project
## Beschrijving
Lamp doen branden met een relais, later eventueel sturing aan/ uit van Jacuzzi en verwarming met zonneboilerpanelen.
Het te bekomen einddoel werd opgedeeld in diverse deelprojecten. 
Ik moest eerst zien overeen te komen met de Raspberry Pi, het betrof een nieuwe omgeving inzake besturingssysteem en een stuk electronica bij het besturen van de diverse GPIO-pinnen. Ook het programmeren met python was een (moeilijke) aanpassing. 
De eerste projecten waren het aansluiten van een LED, drukknop en een weerstand. Verschillende obstakels kwamen naar voor, waarom een weerstand plaatsen, waarom plaats je de weerstand niet voor de LED (->stroomrichting), welke weerstand moet ik gebruiken, ... Dit werd gaandeweg duidelijk. De toepassing lukte en de LED kon gestuurd worden. 
Het volgende was het plaatsen van een temperatuursonde, die de temperatuur doorstuurt naar de RAspberry Pi. De temperatuursonde las ik uit via code in python. Ik stelde dan een voorwaarde in die bij het bereiken van een bepaalde temperatuur een actie deed -> bedoeling is een relais te sturen die in het thuisnetwerk is geplaatst. 
De volgende kennismaking is deze met de werking van een relais. Ik gebruikte 2 soorten relais, een relais op dezelfde spanning als de RaspberryPi en een relais op 220V. 
De relais op dezelfde spanning als de RaspberryPi werkte op dezelfde manier als de LED. 
Ik gebruikte daarna een relais van het merk Sonoff die in het 220V netwerk wordt geplaatst. 
De sturing van de Sonoff gebeurde via een app op de smartphone. Teneinde deze via eigen code te benaderen werd deze geflasht, de originele firmware werd overschreven via de toepassing Tasmotizer. Via een USB-kabeltje werd deze aangesloten op de PC en via een webtoepassing werd een BIN-file geflasht op de Sonoff. Via commando's kon deze aan- en uitgezet worden.  
Het volgende is al deze deelprojecten samenvoegen en zo alles te sturen vanuit één programma. 
## Bronnen
huidige sturing uitbreiden
## Hardware
temperatuursensoren, relais -> sturing klep glycol
## Software
*****
Eigen scripts en programma's
