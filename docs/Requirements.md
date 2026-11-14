# Anforderungen an C.Plan

## Fachlichkeit

Die Applikation ist eine Plattform, die dabei hilft, in Bauprojekten Pläne und Dokumente über einen definierten Freigabeprozess freizugeben. Dabei werden die Pläne und Dokumente von internen und externen Projektmitgliedern begutachtet. Fällt die Begutachtung positiv aus, wird der Plan bzw. das Dokument freigegeben. An wen die Freigabe geht, hängt von der Projektphase ab: je nach Phase an die Behörde (Einreichung) oder an die Baustelle.

Ein Bauprojekt hat verschiedene Phasen. In jeder Phase werden Pläne und Dokumente erzeugt, die anschließend begutachtet werden. In einem Projekt existieren Rollen, die bestimmte Aufgaben und Rechte haben. In einem Projekt arbeiten mehrere Planer.

Die Stammdaten werden global für alle Projekte definiert. Dazu gehören die Projektphasen, die Dokumenttypen, die Rollen und die Freigabeprozesse.

Ein Bauprojekt besteht aus mehreren Objekten, und jedes Objekt besteht aus einem oder mehreren Gewerken. Zu jedem Objekt bzw. Gewerk gehören mehrere Pläne und Dokumente. Diese werden geprüft und freigegeben. Das fertige Artefakt wird für das Projekt freigegeben und ist damit bindend.

Zu diesem Zweck erstellen der Projektleiter und die Planer eine Plan- und Dokumentenliste. In ihr wird eingetragen, wer welchen Plan bzw. welches Dokument bis wann zu liefern hat und welcher Freigabeprozess dafür verwendet wird.

Negative Begutachtung

Bereits eine einzelne negative Begutachtung löst eine Zweitbegutachtung durch eine speziell befugte Person aus. Diese Person kann die negative Begutachtung überstimmen:

Zweitbegutachtung positiv: Die negative Begutachtung ist überstimmt, und der Prozess läuft weiter.
Zweitbegutachtung negativ: Der Plan bzw. das Dokument geht zur Überarbeitung zurück an den Planer. Die überarbeitete Fassung erhält eine neue Versionsnummer und setzt den Prozess an der Stelle fort, an der negativ beurteilt wurde. Bereits positiv durchlaufene Schritte werden nicht wiederholt.
Überführung ins Zweitsystem

C.Plan soll diesen Prozess unterstützen. Freigegebene Pläne und Dokumente werden bei der Freigabe mittels einer Message bereitgestellt und so für die weitere interne Verwendung in ein Zweitsystem überführt.

Bestandsplanung und Archivierung

Zum Projektende wird eine sogenannte Bestandsplanung durchgeführt. Als Basis dient die Ausführungsplanung. Bei der Überführung der Ausführungsplanung in die Bestandsplanung werden etwaige Änderungen, die sich während des Bauprozesses ergeben haben, eingearbeitet und erneut einem Begutachtungsprozess unterzogen.

Anschließend archiviert der Projektleiter das Projekt als ZIP-Datei. Dabei werden entweder alle oder nur die freigegebenen Pläne zusammen mit dem Prüfprotokoll im HTML-Format komprimiert. Nach der Archivierung ist das Projekt nur noch für Administratoren sichtbar. Diese Sperre ist endgültig: Auch ein Administrator kann das Projekt für andere Benutzer nicht wieder sichtbar machen.

## Was soll besser werden gegenüber C.DES

## Umfang

## Ablöse

## Technische Vorgaben

## Entwicklerteam