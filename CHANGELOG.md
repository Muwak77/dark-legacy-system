# Changelog

Alle wichtigen Änderungen an Dark Legacy werden in diesem Dokument festgehalten.

## 0.3.32

- Neues SL-Werkzeug „Charakterübersicht“ mit den aktuellen Hauptcharakteren der Spieler, ihren Zuständen und verlinkten Standorten.
- Standortwerkzeug heißt nun kurz „Standorte“.
- Tabellenlinks, insbesondere in der Übersicht Dunkler Erbschaften, sind nun kontrastreich und nicht mehr unterstrichen.

## 0.3.31

- Reisen von Spielern werden nun immer als persistente SL-Aufträge ausgeführt. Offene Ziele werden automatisch von der ersten aktiven Spielleitung abgearbeitet; genehmigungspflichtige Reisen warten auf deren Bestätigung. Dadurch werden auch Fahrzeuge und Insassen ausschließlich mit den nötigen SL-Rechten bewegt.

## 0.3.30

- Standortwerkzeug: Fahrzeuge werden vor Personen gezeigt; kompakte Schaltflächen wählen Fahrzeuge, Personen oder alles gemeinsam aus beziehungsweise ab. Der Dialog heißt nun „Standorte“.
- Standorte besitzen die Erreichbarkeit „Offen“, „Genehmigen“ oder „Geschlossen“.
- Über den Pfeil neben dem Standort in der Statusanzeige können Charaktere reisen. Genehmigungspflichtige Ziele senden eine private Anfrage an die Spielleitung; Fahrzeug und Insassen können gemeinsam mitreisen. Erfolgreiche Reisen werden im Chat protokolliert.

## 0.3.29

- Anwesenheitskacheln in Standortbögen sind für Spieler nun echte Links statt deaktivierter Formular-Schaltflächen.
- Der Charakterbogen kann für Nutzer mit Limited-Berechtigung in seiner eingeschränkten Ansicht geöffnet werden.

## 0.3.28

- Standortlinks öffnen Akteure auch bei Klick auf Portrait oder Namen zuverlässig und prüfen Limited-Rechte über Foundrys Berechtigungslogik.

## 0.3.27

- Akteure in der Anwesenheitsliste eines Standorts können bereits mit Limited-Berechtigung geöffnet werden.
- Spielleiter können Dunkle Erbschaften im Erbebogen nach Bestätigung löschen.

## 0.3.26

- Die Anwesenheitsliste eines Standorts ist dreispaltig und vertikal scrollbar.
- Ein Rechtsklick auf das Kopf-Icon eines Itembogens öffnet die Bildvorschau in einem eigenen Foundry-Fenster.

## 0.3.25

- Spielleiter können das Icon eines Standorts direkt im Standortbogen per Bildauswahl ändern.
- Das Beschreibungsfeld von Standorten ist doppelt so hoch; der Standortbogen wurde entsprechend vergrößert.

## 0.3.24

- Charakter und Standort in der Statusanzeige öffnen bei vorhandener Berechtigung direkt den jeweiligen Bogen.
- Neu über das Standortwerkzeug erstellte Standorte erhalten ausdrücklich Beobachterrechte für alle Spieler.

## 0.3.23

- Standortbögen zeigen Anwesende in zwei Reihen mit horizontaler Navigation; berechtigte Nutzer können einen Akteur direkt über seine Kachel öffnen.
- Neue Statusanzeige oben mittig: Spieldatum, eigener Charakter und Standort. Die Spielleitung stellt Datum und Uhrzeit direkt dort ein und kann sie um Stunden oder Tage verschieben.

## 0.3.22

- Die Kacheln der Anwesenheitsliste in Standortbögen sind höher; Portraits sitzen linksbündig und vollständig sichtbar.

## 0.3.21

- Die Anwesenheitsliste in Standortbögen ist dreispaltig und füllt sich spaltenweise von oben nach unten.
- Behälter-, Fahrzeug- und Immobilienbögen zeigen den Standort im Ansichtsmodus nur als Text; die Auswahl bleibt dem SL-Bearbeitungsmodus vorbehalten.

## 0.3.20

- Neu: Standorte sind eigene Sidebar-Items mit öffentlicher Beschreibung, SL-Information, Standardicon, eigenem Hintergrund und einer dynamischen Anwesenheitsliste.
- Die Spielleitung kann SC und zugeordnete Fahrzeuge über das neue Standortwerkzeug gemeinsam bewegen; Fahrzeugpassagiere ziehen automatisch mit.
- Im ortsgebundenen Modus sind normale Inventartransfers nur am selben Standort möglich. Akteure ohne Standort sind nicht erreichbar; die SL bleibt uneingeschränkt.
- Standortnamen sind eindeutig. Beim Löschen eines Standort-Items wird der Standort bei allen betroffenen Akteuren entfernt.
- Vorhandene Standortdaten werden beim nächsten Start automatisch zu Standort-Items migriert.

## 0.3.19

- Die SL-Übersicht für Dunkle Erbschaften zeigt eine verlinkte Tabelle mit Erbe, Charakter sowie den Zuständen „Verwendet“ und „Abgeschlossen“.
- Standardmäßig werden verwendete, noch nicht abgeschlossene Erbschaften gezeigt. Filter am oberen Rand können unverwendete und abgeschlossene Erbschaften einblenden.

## 0.3.18

- Der Antrag für ein Dunkles Erbe ist klarer gestaltet: Pergamenthintergrund, Felder unter ihren Beschriftungen und ein erklärender Regeltext.
- Der Dunkles-Erbe-Gegenstandsbogen wurde am Stil der Fertigkeitenbögen ausgerichtet, mit einem eigenen okkulten Pergamenthintergrund, kompakten Textflächen und gut lesbaren Beschriftungen.
- Der Freigabe-Button einer Erbe-Anfrage wird ausschließlich der Spielleitung im Chat angezeigt.
- Spielleitungen können Erbschaften direkt vom Charakterbogen aus öffnen und die Zustände „Verwendet“ sowie „Abgeschlossen“ jederzeit aktivieren oder zurücksetzen.

## 0.3.17

- Neu: „Dunkles Erbe“ als eigener, nicht-inventarisierter Gegenstandstyp mit Spielerantrag, SL-Freigabe, SL-Informationen sowie den Zuständen „Verwendet“ und „Abgeschlossen“.
- Der neue Charakterbogen-Reiter erlaubt das einmalige Heilen einer Wunde oder eines Wahnsinnspunkts; die Verwendung wird im Chat protokolliert.
- Die Szenen-Steuerleiste der Spielleitung enthält eine Übersicht aller noch aktiven Dunklen Erbschaften, nach Charakter sortiert.
- Dunkle Erbschaften haben ein eigenes Icon und einen thematisch gestalteten Bogen. Die Bearbeitung ist auf die Spielleitung beschränkt.
- Housekeeping prüft weiterhin Bildkonvertierungen, zeigt jedoch keine Vorschläge für auffällige Dateinamen mehr.
- Housekeeping-Schaltflächen werden im Dialog zweispaltig dargestellt; Tabellenüberschriften sind auf dunklem Hintergrund lesbar.

## 0.3.16

- Die Spielleiterfunktionen erscheinen jetzt Foundry-konform als eigene Werkzeuge in der Szenen-Steuerleiste.
- Housekeeping kann referenzierte PNG- und JPEG-Bilder nach WebP konvertieren, die Verweise aktualisieren und die Originaldateien behalten.

## 0.3.15

- Überschriften in Richtextfeldern werden auf den hellen Inhaltsflächen dunkel und gut lesbar dargestellt.
- Housekeeping entfernt erfolgreich korrigierte Bildpfad-Treffer sofort aus der offenen Ergebnisliste und aktualisiert die Anzahl.

## 0.3.14

- Housekeeping erkennt Systempfade nun korrekt und verwechselt deren `assets/`-Anteil nicht mehr mit Weltpfaden.
- Korrigierte Systembildpfade werden absolut gespeichert, damit sie sich in Journalen nicht mehrfach relativ auflösen.

## 0.3.13

- Der globale Bildpfad-Fix prüft nun den ausgewählten Ersatzpfad, speichert Änderungen nacheinander und verifiziert anschließend, dass keine alten Verweise übrig sind.
- Erfolgs- und Fehlermeldungen des globalen Fixes enthalten detailliertere Diagnosen für die Browser-Konsole.

## 0.3.12

- Housekeeping prüft Bildpfade nun über den Foundry-Dateibrowser und protokolliert ausführliche Diagnoseinformationen in der Konsole.
- Die Auswahl eines Ersatzbilds startet im Weltordner, auch wenn der alte Bildordner nicht mehr existiert.
- Nach dem Ausführen eines Spielleiterwerkzeugs öffnet sich das Dark-Legacy-Menü erneut.

## 0.3.11

- Housekeeping kann einen defekten Bildpfad jetzt mit einem ausgewählten vorhandenen Bildpfad ersetzen und aktualisiert dabei alle identischen Verweise in der Welt auf einmal.

## 0.3.10

- Housekeeping zeigt bei defekten Bildverweisen jetzt das genaue betroffene Datenfeld und kann ein Ersatzbild hochladen sowie den Verweis direkt aktualisieren.
- Für nicht verwendete Weltdateien erzeugt Housekeeping ein Linux-Shell-Skript, das die aufgelisteten Dateien nach `unused/` verschiebt und die Ordnerstruktur beibehält.
- Die Suche nach ungenutzten Dateien berücksichtigt nun auch Audio-, Video- und PDF-Dateien.

## 0.3.9

- Die Spielleiterwerkzeuge enthalten jetzt „Housekeeping“: Es findet defekte Bildverweise und öffnet die betroffenen Entitäten direkt; Journale werden dabei im Bearbeitungsmodus geöffnet.
- Housekeeping listet außerdem nicht verwendete Medien-Dateien aus dem Ordner der aktuellen Welt mit ihrem vollständigen Pfad.

## 0.3.8

- Die Systeminformation verlinkt auf das öffentliche Release-Repository.

## 0.3.7

- Charakterbögen haben den Reiter „Fahrzeuge/Immobilien“, über den SL Fahrzeuge, Behälter oder Immobilien zuordnen und wieder lösen können.
- Zugeordnete Objekte zeigen ihren Besitzer an und aktualisieren sich bei allen geöffneten Charakterbögen sofort.
- Fahrzeuge, Behälter und Immobilien teilen sich einen einheitlichen Bogen mit passendem Bild-Fallback und einer kompakten Kartenansicht.
- Immobilien ergänzen Behälter um Adress-, Flächen- und Telefonangaben, Besitzer, Infotext sowie eine anklickbare Übersichtskarte.
- Limited-Berechtigungen blenden Behälterinventare aus und verhindern Einlagern, Entnehmen sowie das Öffnen enthaltener Gegenstände.

## 0.3.6

- Fahrzeug- und Behälterbilder werden im Kopfbereich oben ausgerichtet.
- Fahrzeugbögen zeigen im Ansichtsmodus einen kompakten Kopfbereich mit festem Sitzplan, Name, Volumen und Fahrzeugwerten.
- Sitzfelder passen sich innerhalb einer festen Planfläche an die gewählte Rastergröße an.
- Der Bearbeitungsmodus hat kompaktere Fahrzeugfelder, ein beschriftetes Namensfeld und ein größeres Beschreibungsfeld.
- Die Kopfaktionen sind gleich große, rechtsbündige Icon-Schaltflächen.

## 0.3.5

- Behälter und Fahrzeuge erhalten ein passendes Standardbild, wenn kein eigenes Bild gesetzt ist.
- Mit Umschalt + Rechtsklick auf ein Charakterportrait lässt sich die normale Bildauswahl öffnen, ohne Tokenizer zu verwenden.
- Bilder auf Behälter- und Fahrzeugbögen werden am oberen Bildrand ausgerichtet.

## 0.3.4

- Veröffentlichung für Foundry VTT 14.
