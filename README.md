# kEtape

**Bessere Fahrdaten für deinen Karoo.**

Ein kurzer Blick aufs Display reicht, um zu sehen, was gerade zählt. Mit **Stacked Fields** kombinierst du den aktuellen Messwert mit den wichtigsten Zahlen deiner Fahrt. Mit **Palmarès** siehst du schon unterwegs, wie sich dein bester Sprint, dein längstes Intervall oder dein Anstieg gegen frühere Bestwerte schlägt.

[**kEtape für den Hammerhead Karoo herunterladen**](https://github.com/jlojkasek/ketape-releases/releases/latest) · [Installation](#installation-auf-dem-karoo) · [Alle Einstellungen](#einstellungen)

## Stacked Fields

Wähle die Felder, die zu deiner Fahrt passen. Der Hauptwert steht groß oben, die Fahrtwerte darunter.

| Datenfeld | Hauptwert | Zusatzwerte |
| --- | --- | --- |
| **Leistung** | Watt | Fahrt-Ø und Normalized Power (NP) |
| **Herzfrequenz** | Puls in bpm | Fahrt-Ø und höchster Puls |
| **Geschwindigkeit** | Tempo in km/h | Fahrt-Ø und Höchstgeschwindigkeit |
| **Strecke** | Gefahrene Kilometer | Höhenmeter bergauf und bergab |
| **Trittfrequenz** | Umdrehungen pro Minute | Fahrt-Ø und Maximum oder Links-rechts-Leistungsbalance |

Bei Leistungs- und Herzfrequenzfeldern kannst du die Zone direkt an der Farbe erkennen. Die Grenzen stammen aus deinem Karoo-Profil. Für weniger springende Zahlen lässt sich der Hauptwert von Leistung, Herzfrequenz, Tempo und Trittfrequenz pro Messart glätten.

## Palmarès

Deine persönliche Bestenliste fährt mit. **Palmarès** stellt den besten Wert deiner aktuellen Fahrt je Dauer neben deine Referenz aus Intervals.icu. Du siehst zum Beispiel, wie dein stärkstes Fünf-Minuten-Intervall heute im Vergleich zur Saison liegt.

| Datenfeld | So erscheint der Vergleich |
| --- | --- |
| **Palmarès** | Kompaktes Feld für deine normale Fahrseite. Oben steht der Fahrtbestwert mit einem Dauerkürzel wie **5S** oder **20M**. Darunter stehen die ausgewählten Referenzen. Das Feld wechselt automatisch zwischen den gewählten Leistungsdauern. |
| **Palmarès Tabelle** | Mehrere Dauern auf einen Blick mit Spalten für **Fahrt**, **Saison** und **42 Tage**, je nach Vergleichsauswahl. Ideal für eine eigene Datenseite. Wenn mehr Zeilen ausgewählt sind, als auf das Feld passen, blättert die Tabelle automatisch weiter. |

**Vergleichszeiträume** sind die aktuelle Saison, die letzten 42 Tage oder beide. Im kompakten Feld steht **S** für Saison und **42** für die letzten 42 Tage.

**Leistungsdauern** sind 1, 5, 10, 15 und 30 Sekunden sowie 1, 2, 3, 5, 10, 15, 20, 30, 45 und 60 Minuten. Standardmäßig sind 1 s, 5 s, 1 min, 5 min und 20 min ausgewählt. Die Auswahl gilt für beide Palmarès-Felder.

**Bestwertmeldungen** blenden einen übertroffenen Referenzwert etwa zehn Sekunden lang im Leistungsfeld ein. Auf Wunsch kommt ein Signalton dazu. Neue Puls-Höchstwerte erscheinen im Herzfrequenz-Feld, wenn du diese Option aktivierst.

## Einstellungen

Öffne **kEtape** auf dem Karoo. Unter **Anzeige** und **Palmarès** findest du diese Optionen.

| Tab | Einstellung | Auswahl und Wirkung |
| --- | --- | --- |
| **Anzeige** | Farbschema | Systemeinstellung, Hell oder Dunkel |
| **Anzeige** | Zonenfarben | Farbiger Hintergrund, farbige Zonenmarkierung oder Aus |
| **Anzeige** | Glättung des Hauptwerts | Live, 3 s, 5 s oder 10 s für Leistung, Herzfrequenz, Geschwindigkeit und Trittfrequenz. Die Auswahl gilt für alle Platzierungen der jeweiligen Messart. |
| **Anzeige** | Links-rechts-Balance | Zeigt die Leistungsanteile der beiden Beine im Trittfrequenzfeld. Dafür brauchst du einen Leistungsmesser, der Balance-Daten liefert. |
| **Anzeige** | Balance-Warnschwelle | Aus oder 2, 3, 4, 5, 6, 8 oder 10 Prozentpunkte Abweichung von 50/50. Bei einer Schwelle von 5 wird 44/56 rot, 45/55 bleibt im normalen Farbschema. |
| **Anzeige** | Herzfrequenz-Höchstwerte | Schaltet die Meldung neuer Puls-Höchstwerte im Herzfrequenz-Feld ein oder aus. |
| **Palmarès** | Intervals.icu | Verbinden, manuell synchronisieren oder trennen. Nach dem Abgleich siehst du die gespeicherten Referenzwerte und den Zeitpunkt der Synchronisierung. |
| **Palmarès** | Vergleichszeitraum | Aktuelle Saison, letzte 42 Tage oder beide |
| **Palmarès** | Leistungsdauern | Wähle die Dauern, die das kompakte Feld und die Tabelle anzeigen sollen. |
| **Palmarès** | Signalton | Ton bei neuen Bestwerten ein- oder ausschalten |
| **Info** | Einrichtung und Version | Hinweise zu Datenseiten und Updates sowie die installierte Version |

Die App zeigt deutsche Texte bei deutscher Systemsprache. Für andere Systeme dient Englisch als Standardsprache.

## Installation auf dem Karoo

1. Öffne den [aktuellen Release](https://github.com/jlojkasek/ketape-releases/releases/latest) auf deinem Smartphone und lade die Datei **ketape-…apk** herunter.
2. Teile die APK oder ihren direkten Downloadlink mit der **Hammerhead Companion App**. Folge der Installationsanfrage auf deinem verbundenen Karoo. [Hammerhead-Anleitung zur Installation externer Apps](https://support.hammerhead.io/hc/en-us/articles/31576497036827-Companion-App-Sideloading)
3. Bearbeite eine Datenseite in deinem Karoo-Fahrprofil und wähle unter **kEtape** die gewünschten Felder. Im Editor siehst du Beispieldaten.
4. Öffne **kEtape**, passe die Felder unter **Anzeige** an und verbinde für historische Bestwerte bei Bedarf Intervals.icu.

**Wechsel von Stacked Fields 0.x:** Installiere kEtape einmalig als neue App, füge die gewünschten Felder erneut zu deinen Datenseiten hinzu und verbinde Intervals.icu neu. Danach kannst du die alte Erweiterung entfernen. Updates für kEtape findest du anschließend in der App-Verwaltung auf dem Karoo.

## Intervals.icu verbinden

1. Kopiere deinen persönlichen API-Schlüssel aus den **Entwicklereinstellungen** von [Intervals.icu](https://intervals.icu/settings).
2. Öffne auf dem Karoo **kEtape → Palmarès → Intervals.icu verbinden** und gib den Schlüssel ein. Mit **API-Schlüssel anzeigen** kannst du die Eingabe kontrollieren.
3. Wähle den Vergleichszeitraum und prüfe unter **Synchronisierte Bestwerte**, welche Referenzen geladen wurden. Mit **Jetzt synchronisieren** startest du den Abgleich manuell.

Der Schlüssel wird verschlüsselt auf dem Karoo gespeichert. Nach dem Abgleich kann kEtape beim Fahren auch ohne Internet mit den zuletzt gespeicherten Referenzen vergleichen. Beim Trennen entfernt die App den Schlüssel und die gespeicherten Referenzen vom Gerät. Für verfügbare historische Werte zählt die Radfahrthistorie, die Intervals.icu über seine API bereitstellt.

## Downloads und Feedback

Die APK, das Update-Manifest und die SHA-256-Prüfsummen findest du beim [aktuellen Release](https://github.com/jlojkasek/ketape-releases/releases/latest). Wenn dir beim Einsatz etwas auffällt, helfen bei einer Meldung im [Issue-Bereich](https://github.com/jlojkasek/ketape-releases/issues) die kEtape-Version, dein Karoo-Modell und die Größe des betroffenen Felds.


## Réserve ab kEtape 1.1.0

Réserve zeigt dir während der Fahrt deine modellierte W′-Reserve. **Balance** zeigt Verbrauch und Erholung, **Available Power** schätzt die verfügbare Dauerleistung und **Insights** fasst die Beanspruchung der Reserve über die Fahrt zusammen. Die Parameter lassen sich aus Intervals.icu übernehmen oder manuell eingeben.
