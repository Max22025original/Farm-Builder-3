FarmBuilder 3.0 - Paper-Plugin
==============================
/farm          -> Menue: 10 Kategorien, 100 Farmen, 4 Groessen (Klein 15, Mittel 31, Mega 51, Riesig 75)
/farm cancel   -> Vorschau abbrechen
Vorschau: Partikel-Rahmen; Rechtsklick = platzieren (ohne Materialien), Linksklick = abbrechen.
Nur OPs bzw. Permission farmbuilder.use.

Arten von Farmen (steht im Menue in der Beschreibung):
* Echt: Spawner-Falle (20): Spawner im dunklen Raum, Wasser spuelt Mobs/Items zum Loch, Wasserschacht,
  Trichter, Kiste unten am Turm. Das Plugin toetet die gespawnten Mobs nach 1,5 s. Laeuft, wenn ein
  Spieler innerhalb von 48 Bloecken ist. Mega/Riesig = mehrere Tuerme.
* Knochenmehl-Farm: Skelett-Falle + Crafter + Trichter-Uhr + Komparator + Redstone (experimentell).
* Echt: Villager-Hallen (10): Villager mit Beruf + Arbeitsblock, Handel durch Eisengitter.
* Weizen-Farm mit Villager: Felder + echte Bauern + Produktionskisten.
* Plugin-gesteuert (rest): Bauwerk mit Kisten, die das Plugin automatisch fuellt.

config.yml: cycle-seconds, speed-multiplier, max-villagers, max-animals; entries/traps = gespeicherte Farmen.
