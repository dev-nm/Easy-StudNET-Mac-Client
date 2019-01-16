## Entwicklung wird nicht weiter geführt.
Da ich nicht länger an der Universität Leipzig bin, habe ich die Entwicklung abgebrochen.
Mit dem Code könnt ihr anstellen, was ihr wollt :)

## Development is cancelled
As I'm not longer a student of the University of Leipzig, I cancelled the Development of this script.
Feel free to do what ou want with the Code :)

# Easy-StudNET-Mac-Client (Deutsch)
Ein einfach ein zu richtender und zu nutzender StudNet Client für Mac.

Und so funktioniert es:
- Verbinde dich per LAN oder WLAN mit dem StudNET und schließe alle Terminal Fenster (Du musst den gesammten Prozess beenden)
- Öffne das Programm.
- Beim ersten mal wirst du nach deinen Accountinformationen gefragt (Mieternummer, Password). Keine Sorge, alle Informationen werden sicher im Apple Schlüsselbund gespeichert
- Wenn du die App schon einmal verwendet hast wirst du gefragt ob du deinen Account verwenden oder einen neuen erstellen möchtest.
- Du bist nun verbunden!

Im Hintergrund läuft ein Prozess welcher überwacht ob du noch mit dem Internet verbunden bist und dich falls die Verbindung abbricht automatisch neu Verbindet. Dieser Verbraucht beim durchgängigen laufen 24 Stunden am Tag, 30 Tage im Monat in dieser Zeit in etwa 16MB. Das Programm aber nicht läuft wenn du schläfst oder deinen Mac nicht benutzt dürfte sich der verbrauch auf höchstens 10MB belaufen. Das sind in etwa 0.01% deines Monatlichen Datenvolumens (80GB). Wenn dir das dennoch zu viel ist kannst du einfach das Terminal Fenster in dem die Google Ping Statistics aufgelistet werden beenden.

# Easy-StudNET-Mac-Client (English)
An easy to set up and easy to use StudNet Mac client.

How To Use it:
- Connect with StudNET via LAN or WLAN and close all Terminal Windows (Shutdown it's whole process)
- Open the Application.
- First time you open it it will ask you for your account informations (tenant Number, Password). Dont worry, it will be all saved via secure Apple Keychain.
- If you used the app before, it will ask you if it schould use your account or you want to change it.
- You're now connected!

There is a process running in the background, getting sure you're still connected and if you're not reconnect you. Tis process will use up to 16MB of Internet if it is running 24h a Day, 30 Days a Month. Caluculating with Sleep and Time you're not on your Mac it will use under 10MB. That's arround 0.01% of your Monthly available Data (80GB) If this is still to much for you, just quit the Process that is running Google Ping Statistics.
Developed by Nicolas Mierbach - 06.10.2016
University Leipzig

# Changelog

0.94 (16.10.2016): Es läuft nun ein Prozess welcher überwacht ob die Internetverbindung noch besteht und diese wieder herstellt falls sie zusammenbricht. Zudem wurden einige Bugs behoben 

0.92 (10.10.2016): Es müssen nun nicht mehr alle Terminal Fenster geschlossen werden um das Programm aus führen zu dürfen. Die Sicherheit des Passwortes ist auch so sichergestellt. Simultanes arbeiten im Terminal und neuverbinden mit dem StudNET ist so möglich.

0.91 (09.10.2016): Bug bei dem das Password als Klartext ausgegeben wurde falls der Server mit dem sich verbunden werden sollte kein StudiNET Server war wurde gefixt.

0.90 (06.10.2016): Grundfunktionalität ist hergestellt

# To Do

- Ungenutzte Terminal Fenster automatisch schließen.
- Prüfen ob ein Fenster für Einstellungen mit reinen AppleScript Mitteln möglich ist.
Schickt mir gern noch weiter Verbesserungsvorschläge!
