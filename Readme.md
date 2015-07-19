Diese Vorlage ist für die Community Kiel angepasst, aber Ihr könnt sie gerne für eure Zwecke benutzen.

# Anpassen an deine Community
Um den Sticker anzupassen einfach dieses Git Repository klonen und die Schriften anpassen. 

Die Quell-Datei ist `freifunk-sticker.sla`, für die Bearbeitung ist **Scribus 1.5** nötig (hier benutze Version: 1.5.1), dies ist unter Debian in dem paket `scribus-trunk` erhältlich, das man sich aus einem ppa installieren muss, siehe http://askubuntu.com/questions/639070

Alle Quellen für den Sticker sind im Repository enthalten, also könnt ihr auch einfach weitere Änderungen einbauen.

# Drucken

## als PDF exportieren
Beim Exportieren darauf achten:
* PDF-Version 1.5 auswählen
* Etwaige Fehler wegen leeren Textrahmen ignorieren
* Allgemein -> Höchste Auflösung ankreuzen und 600dpi Auflösung wählen (standard in Scribus ist 300dpi)
* Schriftarten -> "Outline all fonts" **sonst fehlen bei Flyer Alarm die Bindestriche!!!**

## Flyer-Alarm
Noch nicht getestet

# Fonts installieren
Die benötigten Fonts sind im Ordner `/fonts`, in Linux kann man fonts installieren, z.b. mit:

	sudo mkdir -p ~/.fonts/truetype/minionpro
	sudo cp fonts/MinionPro-Regular.otf ~/.fonts/truetype/minionpro/

# Danksagungen
Dieser Sticker ist angelehnt an entsprechende das Faltblatt:

 * https://github.com/rubo77/freifunk-faltblatt-6-seiten/
 
Vielen Dank an anĺle Beteiligten.
 
