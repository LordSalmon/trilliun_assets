# Trilliun Anleitung

1. [Abrechnungsübersicht](#abrechnungsübersicht)
2. [Abrechnungseinstellungen](#abrechnungseinstellungen)
   1. [Person hinzufügen](#person-hinzufügen)
3. [Rechnung erstellen](#rechnung-erstellen)
   1. [Spezialfälle bei der Rechnungserstellung](#spezialfälle-bei-der-rechnungserstellung)
4. [Status der Abrechnungsperiode](#status-der-abrechnungsperiode)
   1. [Wofür dient der Status?](#wofür-dient-der-status)
   2. [Ist der Status repräsentativ für eine gut geführte Abrechnungsperiode?](#ist-der-status-repräsentativ-für-eine-gut-geführte-abrechnungsperiode)
5. [Export](#export)

<br />
<br />

## Abrechnungsübersicht

<br />
<br />

![Abrechnungsübersicht](https://raw.githubusercontent.com/LordSalmon/trilliun_assets/main/user-manual/images/settlement-overview.png)

<br />
<br />

Das ist die Übersicht einer Abrechnung. Hier sind die wichtigsten Informationen und Navigationsmöglichkeiten zu sehen, die für die Abrechnung relevant sind.

- Saldo: Der Saldo zeigt den aktuellen Stand der Abrechnung an. Er wird automatisch berechnet und aktualisiert.

- Schüler:innen im Minus: Zeigt die Anzahl der Schüler:innen, deren Saldo unter 0 liegt.

- Status: Der Status ist ein Indikator für die Qualität der Rechnugnsführung. Weiteres wird in [Status der Abrechnungsperiode](#status-der-abrechnungsperiode) erläutert.

<br />
<br />

## Abrechnungseinstellungen

<br />
<br />

![Abrechnungseinstellungen](https://raw.githubusercontent.com/LordSalmon/trilliun_assets/main/user-manual/images/settlement-settings.png)

<br />
<br />

In den Abrechnungseinstellungen können Sie die Abrechnung anpassen. Sie können die Abrechnungsperiode ändern, den Namen oder Klassennamen anpassen und die Benutzer:innen, die von der Abrechnung betroffen sind anpassen. Um Personen zur Abrechnungsperiode hinzuzufügen, klicken Sie auf das `+` oben rechts über der Liste. Um Personen zu entfernen, klicken Sie auf das Mülleimer-Symbol rechts neben dem Namen der Person.

<br />
<br />

### Person hinzufügen

<br />
<br />

![Person hinzufügen](https://raw.githubusercontent.com/LordSalmon/trilliun_assets/main/user-manual/images/settlement-add-user.png)

<br />
<br />

Um eine Person hinzuzufügen, geben Sie den Namen der Person ein und klicken Sie auf die Kachel der Person. Die linke Liste steht für Personen die sie auswählen können, rechts wird die Liste der bereits ausgewählten Personen angezeigt. Dabei können Sie auswählen was für eine Rolle die Person in der Abrechnungsperiode spielt und mit welchem Saldo die Person startet. Dies wird gebraucht wenn ein:e Schüler:in bspw. eine Klasse wechselt, oder eine neue Abrechnungsperiode einer bereits existierenden Klasse erstellt wird. Die Liste der auswählbaren Personen ist filterbar durch den Namen, die Tags in denen der Klassenname steht und die Rollen der Personen. Um nach den Rollen zu filtern (um bspw. nur Schüler:innen anzeigen) klicken Sie auf das Rollen-Symbol rechts von den Tags bei einer Person.

<br />
<br />

![Nach Rolle filtern](https://raw.githubusercontent.com/LordSalmon/trilliun_assets/main/user-manual/images/filter-by-role.png)

<br />
<br />

## Rechnung erstellen

Die Hauptaufgabe der Kassiers / Kassiererinnen ist es, Rechnungen zu erstellen. Dazu klicken Sie auf den Button `Rechnung erstellen`. Es öffnet sich ein neues Fenster, in dem Sie die Rechnung erstellen können. Sie können die Rechnung auch manuell erstellen, indem Sie die Daten in die entsprechenden Felder eingeben. Klicken Sie auf `Speichern`, um die Rechnung zu speichern.

1. Titel

- Geben Sie einen aussagekräftigen Namen für die Rechnung ein. Dieser Name dient zur Identifizierung und kann optional spezifische Informationen wie den Namen der Schüler:innen enthalten.

2. Titel für Schüler:innen

- Kann als zusätzliche Bemerkung benutzt werden, die mehr Aufschluss über die Rechnung gibt. Ungeändert wird automatisch der Rechnungstitel übernommen. Dieses Feld wird nur intern in der Rechnungsübersicht angezeigt.

3. Empfänger:in

- Geben Sie den Namen der Firma oder Institution ein, an die die Zahlung erfolgte. Dies könnte zum Beispiel der Name eines Buchladens sein.

4. Rechnungstyp

- Hierbei wird angegeben, ob es sich bei der Bewegung um eine Einnahme oder eine Ausgabe handelt.

5. Betrag

- Geben Sie den Betrag der Rechnung ein. Dieser Betrag wird automatisch auf die Schüler:innen aufgeteilt, die in der Rechnung enthalten sind (sofern nicht anders angegeben). **Wichtig:** Dieser Betrag ist immer derselbe wie der Betrag der Kontobewegungen im E-Banking. Bei einer internen Verschiebung (beispielsweise von einem Schüler zu einem anderen) muss der Betrag 0.00 CHF betragen, da keine wirkliche Transaktion erfolg ist.

6. Überweisungsdatum

- Geben Sie das Datum ein, an dem die Zahlung erfolgte. **Wichtig:** Damit ist nicht das Datum gemeint, an dem die Rechnung in Trilliun erfasst wurde, sondern das Datum, an dem die Kontobewegung stattgefunden hat.

7. Hinzufügen von Schüler:innen

- Um Schüler:innen hinzuzufügen, klicken Sie auf die Boxen mit den entsprechenden Namen der Schüler:innen im Reiter `Beteiligte`.

8. Aufteilung des Rechnungsbetrags

- Standardmäßig wird der Rechnungsbetrag automatisch auf alle hinzugefügten Schüler:innen gleichmäßig aufgeteilt. Falls jedoch ein Schüler oder eine Schülerin einen speziellen Betrag hat, können Sie diesen individuell festlegen.

9. Spezielle Beträge festlegen

- Um einen individuellen Betrag für eine Person festzulegen, klicken Sie auf das Vorhängeschloss-Symbol neben dem Namen der Person und geben Sie den entsprechenden Betrag ein.

10. Kontoausgleich

- Es kann sein, dass die Aufteilung des Rechnungsbetrags auf die einzelnen Schüler:innen (gerundet auf 5 Rappen) nicht exakt aufgeht und eine Diskrepanz mit dem Gesamtbetrag besteht. In diesem Fall können Sie den Kontoausgleich verwenden, um den Betrag auszugleichen. Dieser wird automatisch berechnet, meistens ist also keine manuelle Anpassung notwendig. Falls doch, wird im nächsten Reiter erklärt, wie dies gemacht wird.

11. Hinzufügen von Notizen

- Falls erforderlich, können Sie zusätzliche Informationen oder Erläuterungen zur Rechnung in das Notizfeld eingeben. Dies könnte beispielsweise Details darüber enthalten, wie bestimmte Beträge zustande gekommen sind.

12. Verwendung von Tags

- Verwenden Sie Tags, um Rechnungen später einfach zu filtern.

13. Hinzufügen von Medien

- Es wird **dringend** empfohlen, einen Rechnungsscan oder einen Zahlungsbeleg als in der Kategorie _Belege_ hinzuzufügen, insbesondere bei Zahlungen an Dritte.

<br />
<br />

### Spezialfälle bei der Rechnungserstellung

Es kann passieren, dass der Kontoausgleich einen speziellen Betrag erfordert. Dies kann bei einer komplexeren Rechnung passieren oder auch wenn das **virtuelle** Saldo des Kontoausgleichs aufgefüllt werden soll. Bei zweiterem kann wie folgt vorgegangen werden:

- Geben sie im Eingabefeld `Betrag` den Betrag ein, der aufgefüllt werden soll.
- Fügen Sie alle Schüler:innen der Klasse hinzu, die beim Auffüllen des virtuellen Saldos beteiligt sind. Normalerweise sind dies alle Schüler:innen der Klasse.
- Nun wird der Betrag für jede:n Schüler:in gleichmässig aufgeteilt. Fixieren sie die Beträge der Schüler mit dem Vorhängeschloss.
- Ersetzen Sie den ursprünglichen Rechnungsbetrag durch 0.00 CHF.
- Nun sollte der Kontoausgleich der Summe aller Beträge der Schüler:innen entsprechen.

<br />
<br />

## Status der Abrechnungsperiode

Der Status der Abrechnungsperiode kann über die Übersicht angesehen werden.

![Person hinzufügen](https://raw.githubusercontent.com/LordSalmon/trilliun_assets/main/user-manual/images/settlement-overview-status-highlight.png)

<br />
<br />

### Wofür dient der Status?

Der Status beschreibt die **messbare** _Gesundheit_ der Abrechnungsperiode. Dabei wird folgendes kontrolliert:

- Die hinzugefügten Benutzer:innen sind alle im System aktiviert (Schüler:innen sind in Klassen und im Schulwesen aktiv)
- Für Rechnungen wurden Belege oder Anhänge hinzugefügt. Dies dient zur besseren Nachverfolgung.
- Rechnungen haben eine:n Begünstigte:n (Bspw. Bücherversand AG)
- Der Abrechnungebetrag ist positiv
- Der Kontoausgleichsbetrag ist auf 0.00 CHF oder darüber.

All diese Faktoren werden anhand ihrer Wichtigkeit summiert und ein Score ergibt sich. Dieser Score ist ein Indikator dafür, wie gut die Abrechnungsperiode geführt wird und wo Fehler sein könnten oder verbesserungen vorgenommen werden könnten.

<br />
<br />

### Ist der Status repräsentativ für eine gut geführte Abrechnungsperiode?

Ein hoher Status kann ein Indikator für eine gut geführte Abrechnungsperiode sein, ist allerdings nicht als absolutes Mass zu verstehen. Er kontrolliert nicht den Inhalt der Rechnungsbelege oder ob die Gründe und Beträge in einer erfassten Rechnung sinnvoll oder nachvollziehbar sind. Für die absolute Gewissheit, ob eine Abrechnungsperiode den Anforderungen entsprechend geführt wird, müssen weiterhin die Rechnungen und Saldi der Teilnehmer:innen kontrolliert werden.

<br />
<br />

## Export

Der Export-Bereich fasst alle Transaktionen der Abrechnungsperiode zusammen und generiert daraus ein PDF-Dokument. Dabei kann gewählt werden, ob die gesamte Abrechnungsperiode exportiert werden soll, oder das Dokument für die einzelnen Teilnehmer:innen. Diese können bei Bedarf postalisch oder per E-Mail an die Eltern der Teilnehmer:innen gesendet werden.
