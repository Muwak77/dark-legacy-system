# Changelog

Alle wichtigen Änderungen an Dark Legacy werden in diesem Dokument festgehalten.

## 0.3.73

- Spieler können Nachrichten gezielt an andere Spieler oder die Spielleitung senden; Benachrichtigungstöne werden zuverlässig lokal abgespielt.
- Waffenschaden wird für Spieler sicher über die aktive Spielleitung angewendet. Veraltete, nicht zuordenbare Standardmunition wird beim Update entladen.
- Standorte bieten erweiterte Reiseabläufe mit einstellbarer Reisedauer, Ankunftshinweis und automatischer Dokumentation manueller Standortwechsel.
- Das Housekeeping enthält ein Werkzeug, um Token-Einstellungen eines Charakters auf ausgewählte Charaktere oder ganze Gruppen zu übertragen.
- Charakter-, Inventar- und Standortbögen sowie Handouts wurden weiter verbessert und lokalisiert.

## 0.3.69

- Studien in Büchern zeigen beschriftete Felder für Fertigkeit, Zeitdauer, Stabilitätsverlust und Poolpunkte.

## 0.3.68

- Bücher besitzen keine Aktionspunkte mehr und können nur außerhalb eines laufenden Kampfes benutzt werden.

## 0.3.67

- Buch-Fertigkeiten werden über die gleiche, nach Fertigkeitsschlüssel bereinigte Auswahl wie Waffen gewählt.
- Der Sichtbarkeitswechsel und das Löschen funktionieren auch für Text-Handouts in allen Galerien.
- Offene Ermittlungsarchive aktualisieren sich sofort, wenn die SL einen Eintrag entfernt.

## 0.3.66

- Schmuck verwendet nun einen eigenen, reduzierten und nicht stapelbaren Gegenstandsbogen mit eigenem Standardicon und Hintergrund; er enthält nur Name, Bild, Beschreibung und die Anlegefunktion. Schmuck und Rüstung verwenden einheitliche, zustandsabhängige Symbole und eindeutige Anlegen-/Ablegen-Beschriftungen.
- Taschen besitzen keine pauschalen Aktionspunktkosten und keinen allgemeinen Benutzen-Button mehr; Kapazität und Inventartransfers bleiben davon unberührt.
- Kleidung und Rüstung können nur noch angelegt oder abgelegt werden. Das Gewichtsfeld wurde aus allen Gegenständen entfernt; das Inventarsystem verwendet ausschließlich Volumen.
- Die englische Lokalisierung wurde mit der deutschen Fassung vollständig abgeglichen und weitere fest eingebaute Oberflächentexte wurden lokalisiert.
- Veraltete, nicht registrierte Regel- und Fertigkeitskompendien wurden entfernt; `skills-de` und `skills-en` bleiben als aktuelle Fertigkeitskompendien erhalten.
- Dark-Legacy-Konsolenausgaben werden vollständig vom Debug-Schalter in den Systemeinstellungen gesteuert.
- Buch-, Dokument- und Standortgalerien unterstützen jetzt auch Text-Handouts mit dem integrierten Foundry-Editor.
- Sichtbare Handouts können allen gezeigt werden. Sie erscheinen sofort im bisherigen Handoutfenster und werden im gemeinsamen Ermittlungsarchiv gespeichert, das über die Statusleiste erreichbar ist.
- Die SL kann versehentlich veröffentlichte Archiv-Einträge entfernen. Zeigt sie einen verborgenen Galerieeintrag, wird dieser zugleich für Spieler freigegeben und die SL erhält einen Hinweis.
- Buch- und Dokumentbögen lassen sich in ihrer Größe verändern.
- Gegenstände verwenden statt Dollarpreisen Wertstufen mit Münzanzeige. Finanzkraft berücksichtigt die gebundenen Wertstufen von Fahrzeugen und Immobilien.
- Immobilien werden im Besitz-Reiter wie Fahrzeuge und Behälter mit Charakteren verknüpft.
- Versorgungskisten können gestapelt, weitergegeben und über eine Spielleiteranfrage gegen passende Gegenstände eingelöst werden.
- Bücher können pro Fertigkeit einmalig Poolpunkte gewähren; Autor, Erscheinungsjahr, Sprache und bisherige Leser werden auf dem Buchbogen verwaltet.
- Munition kann passende Waffen aus sichtbaren Akteursinventaren, der Welt-Itemliste und Kompendien anzeigen.
- Kleidung und Rüstung verwenden Tragezonen. Mehrere Kleidungsstücke können übereinander getragen werden, während pro Zone nur ein schützendes oder belastendes Teil aktiv sein darf.
- Beim Stapeln von Gegenständen werden nur noch Einträge mit gleichem Bild zusammengeführt.

## 0.3.59

- Eine laufende langfristige Aktion wird abgebrochen, sobald der Teilnehmer erfolgreich eine andere Handlung ausführt. Blockierte Handlungsversuche lassen den Fortschritt bestehen; gezieltes Fortsetzen erhält die Aktion ebenfalls.
- Bewegungskosten, Nervenstärke-SG, Stabilitätsverlust und eigene Trefferzonen von Monstern befinden sich nun im neuen Reiter „Regeln“.
- Die Kampf-Comfortbar zeigt für einen angelegten Wurfgegenstand nun ein Bombensymbol anstelle des Fadenkreuzes.
- Monster können im Reiter „Regeln“ für jede Schadensart Resistenz, Immunität oder Empfindlichkeit festlegen; gemischter Schaden wird komponentenweise angepasst, bevor Rüstung abgezogen wird.
- Sämtliche Schadenspfade einschließlich Zaubern und manueller Schadenseingabe ziehen Rüstung nun einheitlich als letzten Rechenschritt ab; das Regelbuch beschreibt die Reihenfolge und Monsterreaktionen vollständig.
- Das System enthält ein leeres Szenenkompendium für später hinzugefügte Szenen.
- Der Regelreiter auf Monsterbögen ist zur besseren Abgrenzung halbtransparent beige hinterlegt.
- Monster besitzen keine Wunden; beim Übergang auf 0 Gesundheit erhalten sie den Foundry-Status „Tot“ und für alle erscheint die Meldung, dass sie ausgeschaltet wurden.

## 0.3.58

- Die Kampf-Comfortbar zeigt die nächsten fünf Teilnehmer mit Charakterportraits, AP-Anzeige und SL-Steuerung; fehlende Initiative lässt sich direkt über ein Würfelsymbol nachholen.
- Fremde Tokens lassen sich per Klick als Ziel wählen. Im Kampf werden Angriffe ohne eindeutiges Ziel oder außerhalb der Waffenreichweite verhindert.
- Monsterbögen verwenden einen eigenen hochformatigen, flächendeckenden Hintergrund und blenden unpassende Personen-, Fahrzeug- und Behälterfelder aus.
- Waffen aus dem Gegenstandskompendium verwenden nach Gewichtsklasse 4, 5 oder 6 AP. Das neue Housekeeping-Werkzeug „Items migrieren“ gleicht Welt- und Inventaritems anhand ihres Namens mit dem Kompendium ab, ohne Menge oder aktuelle Munition zu verändern.
- Automatische Laufzeitmigrationen der Gegenstandsmodelle wurden entfernt, damit Teilaktualisierungen keine vorhandenen Werte mehr durch Standardwerte ersetzen.
- An- und Ablegen von Rüstung sind strikt getrennte Aktionen. Bei fehlenden AP werden sie langfristig ausgeführt und ändern den Ausrüstungszustand erst nach Abschluss.
- Artefakte zeigen keine Herkunft, Aktivierung oder Ladungsfelder mehr.
- Die manuellen Integrationsprüfungen wurden aus dem Regelwerk in eine eigene Checkliste verschoben.
- Kampfaktionen prüfen Berechtigungen auch in der Ausführungsschicht; nur die SL kann langfristige Aktionen abbrechen.

## 0.3.57

- Charakterbilder im Charaktergenerator sind optional; ohne Upload-Berechtigung wird die Bildauswahl ausgeblendet.
- Wetter-Tooltips erscheinen auch über Symbol und Temperatur. Region, Jahreszeit und Temperatur werden kompakt angezeigt; die Ereigniszeile erscheint nur bei aktivem Wetter.
- Die ausgeschriebene Mondphase und der Beleuchtungsgrad erscheinen im Tooltip des Datums.
- Die SL-Standortanzeige und ihre Dropdown-Einträge öffnen den jeweiligen Schauplatz. Das Dropdown zeigt jeden einem Spieler zugewiesenen SC einzeln, unabhängig vom Online-Status, mit fett hervorgehobenem Namen und linksbündiger Darstellung.
- Starkregen und Orkan ergänzen die Wetterereignisse; Hitzewelle und Kälteeinbruch entfallen. Starkregen verwendet standardmäßig den Karteneffekt heavyrain; Nebel hat keinen Standard-Sound.
- Wettersounds laufen bei allen Spielern in Endlosschleife und stoppen beim Ende des Ereignisses. Später beitretende Spieler hören das aktuelle Wetter ebenfalls.
- Housekeeping ist über die Spieleinstellungen erreichbar. Die zusätzliche Anzeige in der Sidebar ist über eine standardmäßig deaktivierte Checkbox einschaltbar.
- Neue Sounddateien für Wetter und Benachrichtigungen sind im Paket enthalten.

## 0.3.52

- Galerien von Standorten, Büchern und Dokumenten verwalten Bilder und PDFs nun zuverlässig, ohne neue Einträge mit zuvor verwendeten Bildern zu befüllen oder bestehende Einträge unbeabsichtigt zu überschreiben.
- Die Spielleitung kann Inventargegenstände per Drag-and-drop direkt zwischen Charakter- und Behälterbögen sowie in die Sidebar verschieben beziehungsweise kopieren. Für Spieler ist Drag-and-drop deaktiviert; die normale Transferfunktion bleibt für die Spielleitung erhalten.
- Neues SL-Werkzeug „Skills aktualisieren“: Skilldaten lassen sich anhand des eindeutigen Schlüssels aus einem Skillset aktualisieren und ergänzen, während vorhandene Werte erhalten bleiben. Einzelne Skills können systemweit von allen Akteuren entfernt werden.
- Das deutsche Fertigkeitskompendium wurde aktualisiert.
- Charakterbögen sind frei skalierbar; bei NSCs und Monstern wird der Reiter „Dunkles Erbe“ ausgeblendet.
- Beantragte Dunkle Erbschaften werden als nur für die Spielleitung sichtbarer Entwurf angelegt. Die Spielleitung kann sie vor der Freigabe ansehen, veröffentlichen, wieder verbergen oder ablehnen.
- Bei Standortwechseln werden Zugriffsrechte nun vor dem Öffnen des Zielorts gesetzt, sodass keine irreführende Berechtigungsfehlermeldung mehr erscheint.
- Datumsanzeigen zeigen die astronomisch berechnete Mondphase einschließlich Beleuchtungsgrad an.

## 0.3.51

- Standortgalerien erscheinen im Bearbeitungsmodus nur noch einmal; in der Spieleransicht bleiben freigegebene Bilder und PDFs klickbar.

## 0.3.50

- Standorte besitzen jetzt eine Bildergalerie mit Bildern und PDFs. Die Spielleitung kann Einträge hinzufügen, ersetzen, löschen und individuell für Spieler freigeben.
- Die Spielleitung kann Standortbögen zwischen Bearbeitungs- und Spieleransicht umschalten.

## 0.3.49

- Der aktuell eingestellte Elternstandort bleibt in der Standortauswahl sichtbar und ausgewählt, sodass er beim Ändern anderer Standortdaten nicht mehr entfernt wird.

## 0.3.48

- Elternstandorte bleiben beim Ändern allgemeiner Standortdaten erhalten, auch bei älteren Standortdaten mit `parentId`-Referenz.

## 0.3.47

- Das Seitenverhältnis der Karte im Standortdialog bleibt beim Skalieren erhalten.

## 0.3.46

- Standort-Itemdialoge können nun vom Benutzer in ihrer Größe verändert werden.

## 0.3.45

- Charaktere dürfen ihr persönliches Volumenlimit überschreiten, können dann jedoch keine Skilleinsätze mehr nutzen und nicht reisen. Fahrzeuge und Behälter behalten ihre harte Kapazitätsgrenze.

## 0.3.44

- Fahrzeuge besitzen nun eine frei konfigurierbare Zusatzkapazität pro freiem Sitz. Bestehende Fahrzeuge übernehmen beim ersten Start ihren bisherigen Wert von 75 % des Basisvolumens.

## 0.3.43

- Freie Fahrzeugsitze erhöhen die verfügbare Lagerkapazität um jeweils 75 % des Basisvolumens. Bei großer Ladung werden benötigte Sitze ausgegraut und können nicht belegt werden.

## 0.3.42

- Erreichbarkeit gilt beim Reisen nun sowohl für den Start- als auch für den Zielstandort: Geschlossene Standorte können nicht verlassen werden; genehmigungspflichtige Abreisen benötigen eine SL-Freigabe.

## 0.3.41

- Standorte können optionale Angaben zu Adresse, Fläche und Telefonnummer anzeigen. Der Bereich bleibt ohne eingetragene Werte unsichtbar.
- Der Behältermodus „Immobilie“ wurde entfernt; bestehende Immobilien werden beim nächsten Start der Spielleitung automatisch zu Behältern migriert.
- Der Charakterreiter heißt nun „Fahrzeuge/Behälter“.
- Fehlende englische Übersetzungen der Standortansicht wurden ergänzt; Standortangaben sind in der Spieleransicht besser lesbar.

## 0.3.40

- Das SL-Standorttool zeigt hinter jedem Akteur dessen aktuellen Standort als anklickbaren Link.
- Standortbögen ohne Kartenbild öffnen standardmäßig den Reiter „Allgemein“; die Parentangabe im Kartenreiter heißt nun „Lage“.
- Buchbögen sind scrollbar und bieten deutlich größere Bereiche zum Lesen und Bearbeiten längerer Texte.

## 0.3.39

- Standortbögen besitzen einen großen, standardmäßig geöffneten Kartenreiter mit eigenem Kartenbild, Parent-Hierarchie und persistent verschiebbaren Markern.
- Kartenmarker berücksichtigen Spielerberechtigungen, markieren den eigenen aktuellen Standort live und bieten direkt Aktionen zum Ansehen und Reisen an. Karten und Standortlisten reagieren auf externe Änderungen und Standortwechsel.
- Standorte ohne Kartenbild zeigen ihre sichtbaren untergeordneten Standorte als Liste. Parentstandorte können angesehen oder als Reiseziel gewählt werden.
- Das SL-Standorttool kann beim spontanen Anlegen einen Parent setzen. Ein konfigurierbarer Item-Ordner bestimmt, wo neue Standorte angelegt werden; beim erstmaligen Betreten erhalten Spieler Beobachterrechte.
- Reisen zeigen Spielern nur berechtigte Ziele. Besitzer eines bewegten Charakters erhalten den neuen Standortbogen automatisch geöffnet.
- Einsteigen in Fahrzeuge setzt denselben Standort voraus. Fahrzeuge können nur vom Fahrersitz aus mitgenommen werden; zurückbleibende Insassen werden nach Bestätigung automatisch aus dem Fahrzeug entfernt.

## 0.3.38

- In schreibgeschützten Standortbögen bleiben die Anwesenheits-Schaltflächen aktiv. Spieler können dadurch berechtigte Actor-Bögen wieder öffnen; Standortfelder selbst bleiben gesperrt.

## 0.3.37

- Standortbögen überlassen beim Öffnen anwesender Akteure die Zugriffsprüfung wieder Foundry, sodass Spieler ihren eigenen Charakter zuverlässig öffnen können.

## 0.3.36

- Die Anwesenheits-Schaltflächen in Standortbögen rufen ihren Öffnungs-Handler wieder korrekt auf.

## 0.3.35

- Akteure in der Anwesenheitsliste eines Standorts sind nun Schaltflächen statt Links und öffnen bei ausreichenden Rechten direkt ihren Actor-Bogen.

## 0.3.34

- Charakterübersicht: verlinkte Namen und Standorte verwenden nun die gleiche kontrastreiche Schriftfarbe wie die Tabelle der Dunklen Erbschaften.
- Standortbögen sind bei kleinen Bildschirmen scrollbar, sodass untere Inhalte nicht mehr abgeschnitten werden.

## 0.3.33

- Die Charakterübersicht aktualisiert Zustände und Standort live. Wunden und Wahnsinn erscheinen als kompakte Zustands-Icons.
- Die Charakterübersicht hat einen eigenen Charakterakten-Hintergrund im Stil der Dunklen Erbschaften; die Einleitungsbox entfällt.
- Der Standortdialog zeigt die Transfer-Schaltfläche auch auf niedrigen Bildschirmen zuverlässig. Die Einstellung für den freien Transfermodus bleibt beim Schließen erhalten.

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
