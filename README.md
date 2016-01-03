# wlan_switcher
Speedport W724V WLAN_Switcher

              WLAN_SWITCHER für SPEEDPORT W724V

 Der Speedport W724V deaktiviert die WLAN-Module nach eingestelltem
 Intervall nur wenn zum Schaltzeitpunkt kein Device eingebucht ist.
 Dieses Problem wird in den Telekom-Support Foren schon lange
 angeprangert, es erfolgt aber leider keine Reaktion:

 https://telekomhilft.telekom.de/t5/Telefonie-Internet/Speedport-W-724V-Zeitschaltung-funktioniert-nicht/td-p/339560/page/10

 Dieses Skript stellt hierfür eine mögliche Lösung dar!
 Ausgeführt in einem cron-job auf zB einem Raspberry-PI kann es
 zuverlässig die einzelnen WLAN-Module des W724V aktivieren und
 deaktivieren!
 Es könnte möglich sein, dass der wlan_switcher auch für andere
 Speedport-Modelle funktioniert! Bitte unbedingt um Rückmeldungen!

 Bitte unbedingt die IP-Adresse und das Router-Passwort in
 der zugehörigen wlan_switcher.conf an die eigenen Werte an-
 passen!
 Falls die wlan_switcher.conf nicht im Verzeichns exisitiert, wird
 sie beim erstmaligen Start des WLAN_Switcher angelegt!

 Dieses Skript benötigt python3 und die requests library.
 Bitte bei Bedarf nachinstallieren mit:

 pip install requests
