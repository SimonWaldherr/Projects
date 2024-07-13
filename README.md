# Projekte

Eine chronologische Übersicht einiger meiner Software-Projekte an denen ich über die Zeit gearbeitet habe:

## DynDrink

mein erstes Programmier-Projekt das über "Hello World", kleinere Tests und Experimente hinaus ging.
DynDrink war eine Datenbank aus Cocktailrezepten. Neue Rezepte konnten hinzugefügt werden, bestehende sortiert und gefiltert werden. Der Haupteinsatzzweck der Software war das Auflisten von Cocktails, die sich mit noch vorhandenen Zutaten (Resten) mixen lassen.

## algopia

Fasziniert von "Sozialen Netzwerken" der 2000er Jahre und Social Bookmarking wollte ich meine eigene Plattform bauen.
Mit algopia können die Nutzer Internetseiten bewerten und mit Stichwörtern versehen (taggen). Ähnlich wie bei Digg, Delicious oder anderen Social Bookmarking Diensten, werden diese Daten mit den Daten anderer Nutzer kombiniert und daraus eine Gesamtbewertung der Internetseiten berechnet. Leider hatte das Projekt wenig erfolg.
algopia wurde mittlerweile eingestellt.

## 301log

Ein weiterer Versuch, eine eigene große Plattform zu bauen.
301log ist ein Kurz-URL-Dienst wie z.B. tinyurl oder bit.ly, jedoch mit Zusatzfunktionen, die damals keiner der Dienste hatte. Es wurde automatisch zu jeder generierten Kurz-URL ein Semacode (2D-Barcode) generiert. Zu der Zeit, in der ich 301log entwickelt habe, war der Kampf der 2D-Barcodes noch nicht entschieden, deshalb verwendete ich anstatt QR-Codes (die heute "dank" Corona jeder kennt) eine andere Art 2D-Barcodes, die Semacodes. Zusätzlich zur Kurz-URL- und Barcode-Funktion, können URLs per Passwort oder CAPTCHA geschützt werden.

## RelaKey

Ein großer Nachteil der meisten On-Screen Tastaturen ist, dass man aufgrund der fehlenden Haptik beim bedienen ständig auf das Gerät blicken muss. RelaKey ermöglicht es, auf größeren Touchscreen Geräten, wie z.B. dem iPad blind Texte zu schreiben.
RelaKey errechnet aus relativen Abstand und Winkel der Berührungen des Touchscreens, welches Wort geschrieben werden sollte. Für die Erkennung der Wörter, muss dafür ein Wörterbuch in die Software integriert werden.

## iSection

iSection ist/war eine Kombination aus Hardware und Software welche die Steuerung von (ISOBUS-kompatiblen) Landwirtschaftlichen Maschinen per Smartphone oder Tablet ermöglicht. Auf iOS Geräten kann eine spezielle App verwendet werden, alle anderen Smartphones können den Adapter per Webinterface nutzen.
Grundsätzlich können alle per ISOBUS steuerbaren Geräte gesteuert werden, jedoch beschränkte ich die Software auf Sicherheitsunkritische Systeme.

## scancod.es

Lange Zeit nach meinem ersten 2D-Barcode Dienst wollte ich mit scancod.es einen weiteren Versuch wagen. ScanCod.es ist ein einfaches, übersichtliches und kostenfreies Tool um QR-Codes zu generieren. Große Bekanntschaft hat es leider trotzdem nicht erreicht.

http://scancod.es  


## DE102012014829A1

Als großer Fan und Beführworter der Open Source, Free Software und Open Content Bewegung bin ich Patenten eher abgeneigt.
Natürlich sind Patente in gewisser Weiße auch wichtig und richtig. Ich wollte mich mit dem Thema beschäftigen und habe einfach selbst eins angemeldet.

https://patents.google.com/patent/DE102012014829A1/en  

## passkit.php

Eine PHP Funktion um Pässe für Apple Passbook (inzwischen Wallet) zu erstellen

https://github.com/SimonWaldherr/passkit.php  

## imgResize.js

Bilder verkleinern, aber wichtige Teile des Bildes dabei beibehalten. Schwer zu erklären, einfach mal anschauen.

https://github.com/SimonWaldherr/imgResize.js  

## micromarkdown

Begonnen hat es mit dem Markdown zu HTML Converter micromarkdown.js, danach folgten dann auch Varianten in PHP und Golang.

https://github.com/SimonWaldherr/micromarkdown.php  
https://github.com/SimonWaldherr/micromarkdownGo  
https://github.com/SimonWaldherr/micromarkdown.js  

## parseTime und disTime

Zwei sehr faszinierende Projekte. ParseTime erkennt Zeitangaben innerhalb von Texten und kann diese für Berechnungen vorbereiten.
DisTime ermöglicht die Umwandlung in die andere Richtung. Unix-Timestamps können zu Texten wie "vor zwei Tagen" umgewandelt werden.
Besonders bemerkenswert ist, dass beide Tools inzwischen in sehr viele Sprachen übersetzt wurden (parseTime 9 und disTime 19).

https://github.com/SimonWaldherr/parseTime.js  
https://github.com/SimonWaldherr/disTime.js  

## selfCSS

Ein kleines Onlinetool um CSS zu lernen, quasi ein CSS WYSIWYG-Editor.

https://github.com/SimonWaldherr/selfCSS  
http://selfcss.org/  

## shownot.es

Eines der bekanntesten Projekte in dieser Auflistung. Die Domain shownot.es war ursprünglich als Webdienst für Podcaster geplant, aus Zeitmangels kam ich jedoch nicht dazu. Ende September 2012 entschied ich mich mein ursprüngliches Projekt aufzugeben und mich dem DieShownotes Team anzuschließen. Seit dem arbeitete das Shownotes Team an verschiedenen Tools für Podcaster und schreibt für diverse Podcasts Shownotes. Shownotes, auch als "Sendungsnotizen" oder "Mitschriften" bekannt, sind ergänzende und zusammenfassende Notizen und Texte, die vor allem bei Podcasts eingesetzt werden. Sie bieten eine schnelle Übersicht über den Inhalt von Podcast-Episoden und enthalten oft Links zu erwähnten Themen, Produkten oder Webseiten.

https://shownotesarchive.github.io/about-us/  


## Podlove Web Player

Neben dem Shownot.es Projekt habe ich mich auch in anderer Weiße in die deutschsprachige Podcast-Szene eingebracht.
Der geniale Tim Pritlove gründete das Podlove Projekt, welches viele Tools für Podcaster:innen und Hörer:innen hervorgebracht hat.
Ich habe mich dem Podlove-Team angeschlossen, um bei der (Weiter-)Entwicklung des Podlove Web Players zu helfen.

https://podlove.org/podlove-web-player/  
https://wordpress.org/plugins/podlove-web-player/  
https://github.com/podlove/podlove-ui  

## ToTo

Ein closed Source Software-Tool bei dem ich mitentwickelt habe.
Ziel und Einsatzzweck des Tools war die Unterstützung bei der Migration (physisch und datentechnisch) von einem Lager und einem in Cobol entwickelten Lagerverwaltungssystem in ein neues Lager und SAP EWM. Das Tool konnte Bestände und Artikelstammdaten aus dem alten LVM auslesen, bei der Erfassung zusätzlicher Daten wie bspw. Gewicht- und Volumendaten helfen, Etiketten drucken und bei der Einlagerung am neuen Ziellagerplatz unterstützen.

## RGB-LED-Matrix

Eine 128x128 Pixel-RGB-LED-Matrix bestehend aus 8 HUB75 Panels mit je 32x64 RGB-LEDs, welche mit einem Raspberry Pi angesteuert werden.

https://github.com/SimonWaldherr/RGB-LED-Matrix  

## UPS (Codename: NicerWatch)

Das Uncommon Printing System ist ein Etiketten-Druckserver der Daten/Druckaufträge von anderen Systemen (SAP, CI_LOG, ...) entgegen nimmt und anhand von vordefinierten ZPL-Templates an die vorgegebenen Drucker (Zebra) überträgt. Zusätzlich zum befüllen von Templates und drucken kann das System auch Drucker-Konfigurationen verteilen und invalide XML-Dateien korrigieren.

https://github.com/SimonWaldherr/ups  

## ZPLGFA

Neben UPS ein weiteres Tool das hilfreich ist, wenn man mit Zebra-Druckern arbeitet.
ZPLGFA kann Bilddateien (JPG, PNG, ...) in ZPL-Grafiken umwandeln, welche dann vom Drucker gedruckt werden können.

https://github.com/SimonWaldherr/zplgfa  

## ZNDZ

Ein weiteres closed Source Tool für den Einsatz in der Logistik. Der ZNDZ ist eine Anwendung die verschiedene Funktionen in einem praktischen Tool kombiniert.
Eine dieser Funktionen war der Zugriff auf ein Dokumenten-Archiv über ein einfaches Web-Frontend, die zweite Funktion war der Ausdruck von diversen Dokumenten zur richtigen Zeit am richtigen Ort, bspw. ein Lieferschein in der Verpackung oder ein Versandlabel am Ende des Förderbands. 
Eine weitere Funktion war der Versand von eMails bei bestimmten Trigger-Aktionen, bspw. wenn eine Lieferung WA-gebucht wird, ein Produkt eingelagert wird oder ein Versandlabel gedruckt wird. Damit kann man sich über bestimmte Kunden, Aufträge, Lieferungen, Versanddienstleister, Produkte, ... und Aktionen informieren lassen.

## fsagent

Ein Tool das FileSystem-Events trackt und bei neuen Dateien bestimmte Aktionen ausführt (per Mail verschicken, per HTTP hochladen, verschieben, kopieren, löschen, ...).

https://github.com/SimonWaldherr/fsagent  

## Div. weitere Tools für SAP

Um von anderen Anwendungen heraus auf SAP-Daten und -Funktionen zuzugreifen habe ich einige Tools entwickelt. Öffentlich zugänglich ist der Code von se16jsonify.

https://github.com/SimonWaldherr/se16jsonify  

## Zhuchengtyrannus 

SAP enthält eine Suchmaschine namens TREX welche nichts mit dem Dinosaurier zu tun hat, sondern eine Abkürzung für "Text Retrieval and information EXtraction" ist.
Da Eigenentwicklungen in SAP immer mit einem Z beginnen und TREX trotzdem an eine bekannte Dino-Gattung erinnert habe ich eine eigene, minimalistische Suchmaschine für SAP-Daten wie Produktinformationen mit dem Namen Zhuchengtyrannus programmiert. Der Zhuchengtyrannus ist eine Gattung theropoder Dinosaurier aus der Familie der Tyrannosauridae, der Gattungsname leitet sich von Zhucheng ab, dem Fundort der fossilen Überreste in China.

## Diverse Beispiel-Sammlungen

Meine bekannteste Beispiel-Sammlung ist "golang-examples", eine Sammlung vieler verschiedener Beispiele für die Programmiersprache Golang.
Aber auch für SQL (SQLite), Zig, SCAD und MicroPython (für den RP2040) habe ich entsprechende Beispiele erstellt.

https://github.com/SimonWaldherr/rp2040-examples  
https://github.com/SimonWaldherr/golang-examples  
https://github.com/SimonWaldherr/openscad-examples  
https://github.com/SimonWaldherr/zig-examples  
https://github.com/SimonWaldherr/rpi-examples  
https://github.com/SimonWaldherr/sql-examples  

## CocktailTDI

Per Zufall habe ich kurz vor einer Party sehr günstig Ventile kaufen können, damit war klar, dass ich daraus was bauen muss. Da ich schon länger mit der Idee gerungen habe, eine Cocktail-Misch-Maschine zu bauen, war das dann somit mein Plan. Rechtzeitig zur Party wurde dann die erste Version der Cocktail TDI genannten Maschine fertig. Einiges bedurfte aber noch einiger Nacharbeit, da der 36c3 kurz bevor stand war damit das nächste Ziel klar – Eine vorführbare Version musste bis zum Congress fertig werden.
Im Zusammenhang mit dem Projekt sind diverse weitere Repos entstanden, wie bspw. einen "Treiber" um NAU7802 und HX711 Wiegezellen abzufragen und weitere Codes für PCA9685, PCF8574, WS2812, RC522, ...

https://github.com/SimonWaldherr/CocktailTDI  

## HARP

HARP (HTTP Autoregister Reverse Proxy) ist ein invertierender Reverse-Proxy-Server, der es Backend-Anwendungen ermöglicht, sich selbst zu registrieren und eingehende Anfragen aus dem Internet anzunehmen, ohne direkt exponiert zu sein. Die Backend-Anwendungen geben die Domäne und die Ziel-URL an, und der Proxy-Server leitet eingehende Anfragen basierend auf der Domäne in der Anfrage an das entsprechende Backend weiter.

https://github.com/SimonWaldherr/HARP  

## WorkingTimeMeasurementSystem

Dieses Projekt zeigt, wie man mit Golang und SQLite ein einfaches Zeiterfassungssystem erstellt. Die Anwendung ermöglicht es Benutzern, sich ein- und auszustempeln, Arbeitszeiten zu verfolgen und ihren aktuellen Status anzuzeigen. Die Daten sind nach Abteilungen, Benutzern und Aktivitäten organisiert.
Neben dem Web-Frontend kann auch via RFID-Tag und einem Lesegerät ein- und ausgestempelt werden.

https://github.com/SimonWaldherr/WorkingTimeMeasurementSystem  

## liveCalc

Ein einfaches Webtool mit dem man Berechnungen durchführen und die Ergebnisse praktisch via URL teilen kann.

https://github.com/SimonWaldherr/liveCalc  

## check-deadlines-action

Eine GitHub Action welche in CI/CD Prozesse integriert werden kann um provisorische Korrekturen nicht zu vergessen. 
Soll dem Spruch "Nichts hält länger als ein Provisorium" ein Ende setzen.

https://github.com/SimonWaldherr/check-deadlines-action  

## DatabaseExtractor

Eigentlich sollte überall auf Entwicklungssystemen oder Lokal entwickelt/programmiert werden, dann die Änderungen via CI getestet und dann über CD (nein, nicht die Runde Scheibe, sondern Continuous Delivery) auf die Produktivsysteme übertragen werden. Oder zumindest über das "Dreigestirn" aus Entwicklungs-, Test- und Produktivsystem eine gewissen Qualität sichergestellt werden.
Oftmals gibt es aber leider nur ein System, somit ist das Produktivsystem gleichzeitig das Probiersystem (um Änderungen zu probieren, also zu testen).
Für den Fall des es sich hierbei um eine Datenbank handelt, kann der DatabaseExtractor behilflich sein. Es extrahiert View-, SP- und Tabellen-Definitionen (ohne Inhalte) um diese mittels VCS wie Git versionieren zu können.

https://github.com/SimonWaldherr/DatabaseExtractor  
