Diese Vorlage ist für die Community Kiel angepasst, aber Ihr könnt sie gerne für eure Zwecke benutzen.

# Anpassen an deine Community
Um den Sticker anzupassen einfach dieses Git Repository klonen und die Schriften anpassen. 

Die Quell-Datei ist `freifunk-sticker.sla`, für die Bearbeitung ist mindestens **Scribus 1.5** nötig (hier benutze Version: 1.5.1), dies ist unter Debian in dem paket `scribus` erhältlich.

Alle Quellen für den Sticker sind im Repository enthalten, also könnt ihr auch einfach weitere Änderungen einbauen.

# Drucken

## als PDF exportieren
Beim Exportieren darauf achten:
* PDF-Version 1.5 auswählen
* Etwaige Fehler wegen leeren Textrahmen ignorieren
* Allgemein -> Höchste Auflösung ankreuzen und 600dpi Auflösung wählen (standard in Scribus ist 300dpi)
* Schriftarten -> "Outline all fonts" **sonst fehlen bei Flyer Alarm die Bindestriche!!!**

## Flyer-Alarm
Der Sticker `freifunk-sticker_85x55mm.sla` wurde so als PDF-Export `freifunk-sticker_85x55mm.pdf` exportiert und 1000x erfolgreich gedruckt bei [Flyer-Alarm](https://www.flyeralarm.com/de/shop/configurator/index/id/34/outdoor-aufkleber.html#159=586&160=609&161=615&162=585) (90 µm Haftfolie weiß ohne geschlitzte Rückseite)

# Fonts installieren
Die benötigten Fonts sind im Ordner `/fonts`, in Linux kann man fonts installieren, z.b. mit:

	sudo mkdir -p ~/.fonts/truetype/minionpro
	sudo cp fonts/MinionPro-Regular.otf ~/.fonts/truetype/minionpro/

# Weitere Sticker in diesem Repository

* `freifunk-sticker_85x55mm.sla` Haupt-Projekt (erfolgreich bei Flyer Alarm gedruckt)
* `freifunk-sticker_85x35mm.sla` (falsches Format für Flyer Alarm)
* `freifunk-sticker_Router_Skyline_Kiel_85x55mm.sla` Aufkleber für Router mit Kiel Skyline und URL (noch nicht drucken lassen)
 * `exports/freifunk-sticker_Router_Skyline_Kiel__no_URL_85x55mm.pdf` enthält noch die alte Version ohne http://kiel.freifunk.net/
* `freifunk-sticker_252x87,4mm.sla` Din A4 groß zum selbstausdrucken
* `freifunk-sticker_plain_85x55mm.sla` wie `freifunk-sticker_85x55mm.sla` nur ohne Himmel und Gras (noch nicht drucken lassen)
* `freifunk-sticker_Router_85x55mm.sla` Aufkleber für Router mit Standard freifunk.net Logo (noch nicht drucken lassen)

# Danksagungen
Dieser Sticker ist angelehnt an entsprechende das Faltblatt:

 * https://github.com/rubo77/freifunk-faltblatt-6-seiten/
 
Vielen Dank an an alle Beteiligten.
 
Lizenz
------
Die Inhalte sind in der Regel unter CC-BY-SA veröffentlicht. In Ausnahmen ist dies explizit angegeben!

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
