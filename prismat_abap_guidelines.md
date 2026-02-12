









prismat GmbH   ·    Stockholmer Allee 30a-c   ·    D-44269 Dortmund
Tel: +49 231 44 66 5 – 0    ·    Fax: +49 231 44 66 5 – 111    ·    info@prismat.de    ·    www.prismat.de


© prismat GmbH Seite 1 von 76

## Entwicklungsrichtlinien
von prismat
## Version 1.8

## 02.11.2020
Marcel Seufert-Peterka










»Die Kleinigkeiten erzeugen Perfektion, aber Perfektion
ist keine Kleinigkeit.«
## – Henry Royce


© prismat GmbH Seite 2 von 76


## Inhalt
Änderungshistorie .................................................................................................................. 6
1 Einleitung ........................................................................................................................ 7
1.1 Weiterführende Dokumente ............................................................................................. 7
1.2 Kundeneigene Richtlinien ................................................................................................ 7
2 Dokumentation ................................................................................................................. 7
2.1 Dokumentationen im Programm (intern) ........................................................................... 8
2.1.1 Programmkopf............................................................................................................... 8
2.1.2 Kommentare ................................................................................................................. 9
2.1.2.1 Block-Kommentare ................................................................................................... 9
2.1.2.2 Inline-Kommentare ................................................................................................. 10
2.2 Änderungen (nach Projektphase) ................................................................................... 10
2.2.1 Dokumentation im Programmkopf .................................................................................. 11
2.2.2 Dokumentation im Quellcode ......................................................................................... 11
2.3 Quellcode ................................................................................................................... 12
2.3.1 Allgemein ................................................................................................................... 12
2.3.2 Datendeklarationen: ..................................................................................................... 13
2.4 ABAP-Editor-Einstellungen ............................................................................................. 14
2.5 Dateien ...................................................................................................................... 14
2.6 Einstellungen .............................................................................................................. 15
2.7 Optionen .................................................................................................................... 18
3 Namenskonventionen ...................................................................................................... 18
3.1 Transportaufträge ........................................................................................................ 19
3.2 Repository-Objekte ...................................................................................................... 20
3.3 ABAP Dictionary ........................................................................................................... 21
3.3.1 Pakete ....................................................................................................................... 21
3.3.2 Programme ................................................................................................................. 26
3.3.2.1 Funktionsbibliothek ................................................................................................. 26
3.3.2.2 Programmbibliothek ................................................................................................ 27
3.3.2.3 Unterprogramme .................................................................................................... 28
3.3.2.4 Klassenbibliothek .................................................................................................... 29
3.3.2.5 Interfaces .............................................................................................................. 29
3.3.2.6 Methoden .............................................................................................................. 30
3.3.2.7 Typkonvertierung ................................................................................................... 30
3.3.2.8 Boolsche Werte ...................................................................................................... 30
3.3.2.9 Ereignisse .............................................................................................................. 31
3.3.2.10 Ereignisbehandlung ............................................................................................... 31
3.3.3 Dynpros ..................................................................................................................... 32


© prismat GmbH Seite 3 von 76

3.3.4 BAdI's ........................................................................................................................ 32
3.3.5 Lagerverwaltungsmonitor .............................................................................................. 34
3.3.6 Break-Point-ID's .......................................................................................................... 35
3.3.7 Enhancement-Points..................................................................................................... 37
3.3.8 User Exits - Erweiterungen (CMOD und SMOD) ................................................................. 37
3.3.9 Feldexits zu den Datenelementen ................................................................................... 38
3.3.10 Screen Exits ............................................................................................................ 38
3.3.11 Data Dictionary ....................................................................................................... 38
3.4 Deklarationen .............................................................................................................. 40
3.4.1 Programminterne Deklarationen ..................................................................................... 40
3.4.2 Tabellarische Übersicht ................................................................................................. 41
3.5 Exceptions (Klasse) ...................................................................................................... 42
3.6 Konstanten ................................................................................................................. 44
4 Datenbank ..................................................................................................................... 45
4.1 Datenbankzugriffe........................................................................................................ 45
4.2 Verwaltung von eigenen Customizingtabellen ................................................................... 46
4.3 Verwaltung von eigenen Datenbanktabellen ..................................................................... 46
5 Applog .......................................................................................................................... 46
5.1 Applog instanziieren ..................................................................................................... 47
5.2 Programm-Informationen in das Applog aufnehmen .......................................................... 48
5.3 Nachrichten in das Applog aufnehmen............................................................................. 48
5.4 Applog speichern ......................................................................................................... 49
6 Radio-Frequency-Namenskonventionen .............................................................................. 50
6.1 Paket ......................................................................................................................... 50
6.2 Darstellungsprofil ......................................................................................................... 50
6.3 Prozessliste ................................................................................................................. 50
6.4 Logische Transaktion .................................................................................................... 52
6.5 Schritte ...................................................................................................................... 54
6.6 Stände ....................................................................................................................... 55
6.7 Funktionsgruppe .......................................................................................................... 55
6.8 Funktionsbaustein ........................................................................................................ 55
6.9 Klassen ...................................................................................................................... 55
6.10 Dynpro ....................................................................................................................... 56
6.11 Checkpointgruppe ........................................................................................................ 56
7 Post Processing Framework .............................................................................................. 57
7.1 Paket ......................................................................................................................... 57
7.2 Customizing ................................................................................................................ 57
7.2.1 Applikation ................................................................................................................. 57
7.2.2 Aktionsprofil ................................................................................................................ 57
7.2.3 Aktionsdefinition .......................................................................................................... 58


© prismat GmbH Seite 4 von 76

7.3 ABAP ......................................................................................................................... 58
7.3.1 BAdIs ......................................................................................................................... 58
7.3.1.1 Ausführung ............................................................................................................ 58
7.3.1.2 Einplanbedingung ................................................................................................... 59
7.3.1.3 Startbedingung ...................................................................................................... 59
7.3.1.4 Externe Kommunikation (Druck) ............................................................................... 60
7.3.1.5 Druckerfindung ...................................................................................................... 60
7.3.1.6 Vervollständigung von Verarbeitungen ....................................................................... 61
7.3.1.7 Kontexterweiterung ................................................................................................ 61
7.3.1.8 Container vor Bedingungsauswertung ergänzen .......................................................... 62
7.3.2 Weitere PPF-Klassen ..................................................................................................... 62
7.3.2.1 Applikationsklasse .................................................................................................. 62
7.3.2.2 Kontextklasse ........................................................................................................ 63
7.3.2.3 Triggerklasse ......................................................................................................... 63
7.3.2.4 Druckklasse (Smartforms) ....................................................................................... 63
8 Konditionstechnik ........................................................................................................... 65
8.1 Paket ......................................................................................................................... 65
8.2 Customizing ................................................................................................................ 65
8.2.1 Feldkatalog ................................................................................................................. 65
8.2.1.1 Suchfeld ................................................................................................................ 65
8.2.1.2 Verwendungsfeld .................................................................................................... 66
8.2.2 Konditionstabelle ......................................................................................................... 66
8.2.3 Zugriffsfolge ............................................................................................................... 66
8.2.4 Zugriff zur Zugriffsfolge ................................................................................................ 67
8.2.5 Konditionsart .............................................................................................................. 67
8.2.6 Findungsschema .......................................................................................................... 67
8.2.7 Konditionspflegegruppe ................................................................................................ 68
8.2.8 Applikation ................................................................................................................. 68
8.2.9 Verwendung ................................................................................................................ 69
8.2.10 Signatur zur Verwendung .......................................................................................... 69
8.3 ABAP ......................................................................................................................... 70
8.3.1 BAdIs ......................................................................................................................... 70
8.3.1.1 Suchfeld ................................................................................................................ 70
8.3.1.2 Verwendungsfeld .................................................................................................... 71
9 Druck ............................................................................................................................ 72
9.1 Allgemein ................................................................................................................... 72
9.1.1 Klassen ...................................................................................................................... 72
9.1.2 SAP Smartforms .......................................................................................................... 72
9.1.3 SAP Adobe Interactive Forms ......................................................................................... 72
9.2 Namenskonventionen ................................................................................................... 72
9.2.1 Klassen ...................................................................................................................... 72
9.2.2 SAP Smartforms .......................................................................................................... 73
9.2.2.1 Formulare .............................................................................................................. 73


© prismat GmbH Seite 5 von 76

9.2.2.2 Elemente ............................................................................................................... 73
9.2.2.3 Styles ................................................................................................................... 74
9.2.3 SAP Interactive Forms by Adobe .................................................................................... 74
9.2.3.1 Formulare .............................................................................................................. 74
9.2.3.2 Schnittstelle ........................................................................................................... 74
10 SAP Online Service System (OSS) ................................................................................... 75
11 Aktuelle Änderungen zur letzten Version ........................................................................... 75
11.1 Dokumentation ............................................................................................................ 75
11.2 Quellcode ................................................................................................................... 75
11.3 Transportaufträge ........................................................................................................ 75
11.4 Repository-Objekte ...................................................................................................... 75
11.5 ABAP Dictionary ........................................................................................................... 76
11.6 Namenskonventionen ................................................................................................... 76



© prismat GmbH Seite 6 von 76

## Änderungshistorie

Datum Version Änderung bearbeitet von
## 21.05.12 1.0 Dokumentenerstellung Beernink
## 04.06.12 1.1 Vorschläge
## Entwicklungsabteilung
## Beernink
02.03.13 1.2 Vorschläge aus 2012 Beernink
27.03.14 1.3 Vorschläge aus 2013 Beernink
09.07.15 1.4 Vorschläge aus 2014 Steinweg
29.02.16 1.5 Vorschläge aus 2015 Steinweg
31.07.19 1.6 Erweiterung ERP und
## Vorschläge 2019
Seufert-Peterka
27.10.20 1.7 Anpassung RF-Richtlinien Andernach
12.03.21 1.7 Ergänzung Namenskürzel ToCs Morgenstern
## 17.03.21 1.7 Ergänzung
Namenskonventionen PPF,
## Konditionstechnik
## Andernach
## 22.01.25 1.8 Anpassung Dokumentationen
Nutzung von Break-Point-ID‘s
## Beil




© prismat GmbH Seite 7 von 76

## 1 Einleitung
Dieses Dokument bietet eine verbindliche Richtlinie für alle Mitarbeiter der Firma
prismat GmbH. Insbesondere betrifft diese Ausarbeitung die Teams der
Entwicklungsabteilung und darüber hinaus alle Mitarbeiter mit einem
Entwicklerschlüssel. Die Konventionen gelten sowohl für alle Kundensysteme als
auch für die unternehmenseigenen SAP-Systeme. Die definierten technischen
Normen sind bei der Entwicklung unbedingt einzuhalten. Ein Abweichen von den
hier definierten Grundsätzen ist nur mit vorhergehender Absprache des
Teamleiters möglich. Tipps und Empfehlungen, die nicht zwingend bindend sind,
sind als solche gekennzeichnet. Folglich unterteilen sich die Richtlinien in
einzuhaltende Standards und Best Practice Tipps.
## 1.1 Weiterführende Dokumente
In den Kapiteln wird u. U. auf andere externe Dokumente mit zusätzlichen
Informationen oder spezifischen Anleitungen verwiesen.
## 1.2 Kundeneigene Richtlinien
Grundsätzlich werden die prismat Entwicklungsrichtlinien immer bevorzugt. Dabei
werden diese Richtlinien zu Beginn eines Projektes jedem Entwickler zugänglich
gemacht und in einem Projektmeeting besprochen. Sofern der Kunde die prismat
Entwicklungsrichtlinien ablehnt, müssen in dem Projektmeeting die kunden-
eigenen Entwicklungsrichtlinien vorgestellt werden. In diesem Projektmeeting wird
darüber hinaus festgelegt, ob und inwiefern prismat-Richtlinien ergänzend zu den
Kundeneigenen Richtlinien genutzt werden (siehe Dokument zum Projektablauf).
## 2 Dokumentation
Die Dokumentationen unterteilen sich nicht nur in der Art und Weise sondern auch
in den Zeitpunkten der Erstellung. Es wird grundsätzlich zwischen internen und
externen Dokumentationen und zwischen Dokumentationen während und nach
einer Projektphase unterschieden.



© prismat GmbH Seite 8 von 76

2.1 Dokumentationen im Programm (intern)
In den Programmen werden Programmköpfe zur allgemeinen Übersicht und
Kommentare zum besseren Verständnis angelegt. Die zur Verfügung stehenden
Kommentare unterscheiden sich dabei noch einmal voneinander. Sämtliche
Kommentare (Programmköpfe, Änderungsprotokolle) sind als Vorlage hinterlegt.
Sie können mittels Optionen ( ) am unteren rechten Bildrand über Code-Vorlagen
ausgewählt werden. Bei den Vorlagen kann das Tag %Autor% durch den
jeweiligen Entwickler ersetzt werden. Die Uhrzeit sollte nach der Benutzung der
Vorlagen wieder aus dem entsprechenden Feld entfernt werden, so dass nur das
Datum stehen bleibt.
## 2.1.1 Programmkopf
Zur Kennzeichnung des Verwendungszwecks und zur Identifikation des
Entwicklers sind folgende Elemente mit einem Kopf zu versehen. Die
Beschreibungen im Programmkopf sind in Abhängigkeit zu der Anmeldsprache zu
tätigen. Sofern diese nicht vorgegeben ist, ist es dem Entwickler selbst überlassen
eine Sprache zu wählen.
## • Report
## • Methode
## • Funktionsbaustein
- BAdI
## • Selektionsscreen
Dabei sind folgende Informationen anzugeben:
- Informationen zum Entwickler (Name, Firma, Datum)
- ID (PSE-/CR-/Meldungsnummer, Name des Beraters)
Hinweis: Variable Daten, wie bspw. die Paketzuordnung, Name des
Entwicklungsobjekts und die Zuordnung des Paketes werden bewusst
weggelassen, da sich diese durch Refactoring ändern können.
Der obere Abschnitt des Programmkopfes ist für die initiale Implementierung
vorgesehen. Hier werden die relevanten der der PSE oder des CR, Name des
Entwicklers und des Beraters sowie das Datum hinterlegt.


© prismat GmbH Seite 9 von 76

Im zweiten Abschnitt werden Änderungen dokumentiert, die im Rahmen einer
separaten PSE oder eines CR erfolgt. Dabei werden die entsprechenden Daten
(PSE- bzw. CR-Nummer, Name des Entwicklers und Datum) eingetragen. Für jede
weitere Änderung wird eine neue Zeile mit den gleichen Daten erfasst.
## Beispiel:
## " -------------------------------------------------------------------
" Author: prismat GmbH      | Name Entwickler:in
" Date  : YYY-MM-DD
" ID    : PSE/CR/BCS-ID     | Name Berater:in
## "--------------------------------------------------------------------
" Change-ID     |       Developer       |    Date    |  Description
" PSE/CR/BCS-ID |  Name Entwickler:in   | YYYY-MM-DD |
## " -------------------------------------------------------------------


## 2.1.2 Kommentare
Es werden Block-Kommentare und Inline-Kommentare unterschieden:
2.1.2.1 Block-Kommentare
Auf Block-Kommentare sollte, wenn möglich, verzichtet werden. Im besten Fall
wird ein Block durch eine separate Kapselung bspw. bei einer Klasse durch eine
Methode mit eindeutiger Beschreibung abgebildet.
Ist dies nicht möglich, und es müssen entsprechende Blöcke verwendet werden,
ist folgende Vorlage zu verwenden:
Hinweis: Ein einfaches Refactoring ist über die Nutzung von der eclipse IDE mit
den ABAP-Development-Tools (ADT) über einen sogenannten Quick-Fix und die
Option „extract Method“ möglich.
## " Beginn 1. Funktionsblock
## " < Beschreibung 1. Funktionsblock >
## " **********************************
## < Quellcode >
## " Beginn 2. Funktionsblock
## " < Beschreibung 2. Funktionsblock >
## " **********************************


© prismat GmbH Seite 10 von 76

## < Quellcode >
## " Ende 2. Funktionsblock
## " **********************
## < Quellcode>
## " Ende 1. Funktionsblock
## " **********************
2.1.2.2 Inline-Kommentare
Diese Kommentare dienen der besseren Übersicht. So können z.B. Festwerte als
Kommentar vermerkt werden. Selbstverständlich können beide Kommentar-
Methoden auch zusammen genutzt werden.
Die horizontale Einrückung soll automatisch über den Pretty-Printer erfolgen, so
dass diese Kommentare mit dem Anführungszeichen (") eingeleitet werden
müssen.

## Beispiele:
IF sy-subrc = 0.
## ...
ELSE. "Else: sy-subrc = 0
## ...
ENDIF. "End: sy-subrc = 0
## 2.2 Änderungen (nach Projektphase)
Dieser Punkt betrifft Änderungen an Programmen, die nach der
Entwicklungsphase in den Projekten durchgeführt werden (z.B. Fehlerbehebung
nach Go-Live, Change Requests, o.ä.). Bei allen Anpassungen muss der Bezug zur
entsprechenden Meldung oder zum CR hergestellt werden, indem entsprechend
kommentiert wird.



© prismat GmbH Seite 11 von 76

2.2.1 Dokumentation im Programmkopf
Alle Änderungen von Quellcode müssen dokumentiert werden. Grundsätzlich
werden alle Änderungen im Programmkopf (Änderer, Datum, ID, Autor) vermerkt.
Falls die entsprechende Zeile bereits gefüllt ist, wird eine neue vom Änderer
angelegt. Ggf. muss auch die Beschreibung des Programms angepasst werden,
sofern sich die Logik ändert.
## Beispiel:
" Change-ID     |       Developer       |    Date    |  Description
" PSE/CR/BCS-ID |  Name Entwickler:in   | YYYY-MM-DD |
## " -------------------------------------------------------------------


2.2.2 Dokumentation im Quellcode
Erläuterungen im Quellcode sind ausdrücklich erwünscht. Sie sollten zum
besseren Verständnis des Codes eingesetzt werden, als auch zur Einteilung der
logischen Ebenen. Die Kommentare sollen vor den kommentierten Anweisungen
platziert werden. Die horizontale Einrückung soll automatisch über den Pretty-
Printer erfolgen, so dass diese Kommentare mit dem Anführungszeichen (")
eingeleitet werden müssen.
Falls im bestehenden Quellcode Änderungen getätigt werden müssen, stehen
folgende Vorlagen zur Verfügung um die Änderungen kenntlich zu machen:
## Vorgang Vorlage
Einfügen " >>  insert begin: Change-ID Daniel Beernink
## " Kommentar
neu eingefügter Quellcode
" <<  insert end: Change-ID Daniel Beernink
Löschen " >>  delete begin: Change-ID Daniel Beernink
## " Kommentar
"  auskommentierter Quellcode
" <<  delete end: Change-ID Daniel Beernink


© prismat GmbH Seite 12 von 76

Ersetzen " >>  replace begin: Change-ID Daniel Beernink
## " Kommentar
"  auskommentierter Quellcode
## " Kommentar
neu eingefügter Quellcode
" <<  replace end: Change-ID Daniel Beernink

## 2.3 Quellcode
## 2.3.1 Allgemein
- Pretty Printer mindestens vor Transport ins Q-System anwenden
- Anweisungen über mehrere Zeilen sinnvoll einrücken
## Beispiele:
## SELECT *
FROM     <db_tab>
INTO  <Variable>]
WHERE  <Feld 1>     EQ <Bed. 1>
AND  <Feldname 2>  EQ <Bed. 2>
OR  <Feld 3>     EQ <Bed. 3>

CALL <Function> [IN BACKGROUND TASK]
## IMPORTING
<Para. 1>         = <Wert 1>
<Parameter 2>     = <Wert 2>
## EXPORTING
<Parameter 3>     = <Wert 3>
<Parametername 4> = <Wert 4>

## • Globale Variablen
Sollten möglichst vermieden werden. Sie machen das Coding unleserlich,
Tests und spätere Änderungen/Erweiterungen aufwendiger.
- Inline-Deklarationen
Dürfen nicht verwendet werden, wenn die deklarierte Variable innerhalb
des Programmablaufs mehrfach verwendet wird. Für die neuen ABAP 7.50
Sprachkonstrukte, wie bspw. LOOP AT mit der Anweisung GROUP BY wäre
der Einsatz der Inline-Deklarationen hingegen sinnvoll.
Hinweis: Inline-Deklarationen können über die eclipse IDE mit den ADT
durch den Quick-Fix „Declare XXX XXX explicit“ aufgelöst werden.


© prismat GmbH Seite 13 von 76

## • PAI/PBO
Keine Deklarationen in diesen Modulen, umfangreiche Programmlogik
vermeiden. Nach Möglichkeit sollten nur Unterprogramme und/oder
Methoden aufgerufen werden.
## • Programmstrukturierung
»Sinnvoll« kapseln: Die Anzahl von »Methoden« und
»Funktionsbausteinen« sollte so groß wie nötig und so klein wie möglich
gehalten werden. Das bedeutet, sobald Prozesse/Funktionen mehrmals
und/oder in verschiedenen Programmen aufgerufen werden oder eine
Prozess-/Funktionskapselung für die Übersichtlichkeit des Codings sorgt,
sollten diese möglichst atomar funktional gekapselt werden.
- Bei mehreren Prüfungen auf ein und dergleichen Variablen
statt IF/ELSE/ELSEIF/ENDIF immer CASE benutzen.








## 2.3.2 Datendeklarationen:
- Der Deklarationsteil ist übersichtlich zu gestalten, das bedeutet:
o Blöcke (Variablen, Strukturen, Tabellen, Feldsymbole, Referenzen,
Ranges, ...) bilden und durch Leerzeile trennen
▪ Optional können zusammengehörige Strukturen und Tabellen
einen eigenen Block bilden
o Typisierungen bündig einrücken



© prismat GmbH Seite 14 von 76

## Beispiel:

## DATA:
<Var. 1>   TYPE <Typ 1>,
<Variable 2>  TYPE <Typ 2>,
<Lange_Variable 3> TYPE <Typ 3> VALUE <Wert>,
<Lange_Variable 4> TYPE <sehr langer Typ 4>
VALUE <Wert>.

2.4 ABAP-Editor-Einstellungen
## 2.5 Dateien
Die beiden Dateien »abap_user.xml« & »settings.xml« in das Arbeitsverzeichnis
der SAP-GUI kopieren (vom Prismat-Fileserver, hierin befinden sich Code-
Vorlagen (Dokumentation, Selection-Screen, Korrekturen, ...),
Anzeigeneinstellungen (Zeilenlänge, Zeilenumbruch, ...), usw.



© prismat GmbH Seite 15 von 76

## 2.6 Einstellungen
Die Einstellungen sind über das Menü: »Hilfsmittel->Einstellungen« zu tätigen:




© prismat GmbH Seite 16 von 76





© prismat GmbH Seite 17 von 76





© prismat GmbH Seite 18 von 76

## 2.7 Optionen
Die Optionen sind über das Icon auf der rechten Seite (Optionen ( )) aufrufbar.
Folgende Einstellungen sind zu tätigen:

## 3 Namenskonventionen
Dieser Abschnitt legt fest, welche Vorgaben es bezüglich der Namenskonvention
gibt. Der Aufbau ist in drei Kapitel unterteilt, die jeweils aufeinander aufbauen.
Die Spezialisierung nimmt dabei zu.
Grundsätzlich werden alle Objekte englischsprachig angelegt. Das betrifft sowohl
die frei wählbaren Namen, als auch die Objekte im Data Dictionary. Diese sollen
möglichst an die Datentypen angelehnt werden.



© prismat GmbH Seite 19 von 76

## 3.1 Transportaufträge
Beim Erstellen eines Transportauftrags ist die Kurzbeschreibung in folgender Form
einzugeben:
1.) Art der Änderung:
- WB für Entwicklung
- CUS für Customizing
- TW für Transportkopie Entwicklung
- TC für Transportkopie Customizing
2.) Im Anschluss das Datum in der Form JJJJMMTT
3.) Die Initialen des Benutzers (Ausnahme Sammeltransporte).
4.) Anschließend folgt eine Kurzbeschreibung der Tätigkeit
## Beispiele:




© prismat GmbH Seite 20 von 76

3.2 Repository-Objekte
Die prismat GmbH verwendet grundsätzlich den Kundenamensraum »Z«.
Außerdem gibt es den produktbezogenen Namensraum /PRIS/ und den
Namensraum /PS4R/ für die prismat/RAKETE im S/4HANA.
## Kundennamensraum Bedeutung
Z Erster Buchstabe bei allen Repository-Objekten
/PRIS/ Produktbezogene Repository-Objekte
/PS4R/ Repository-Objekte der prismat/RAKETE für
## S/4HANA
Darauf schließt sich immer ein eindeutiger Projektidentifizierer an. Diese sind aus
der folgenden Tabelle zu entnehmen. Ist kein passender Eintrag vorhanden, ist
dieser vor der Implementierung mit dem Teamleiter abzustimmen.
## Projektidentifizierer Erläuterung
EWM Extended Warehouse Management
LE Logistics Execution
APO Advanced Planner & Optimizer
QM Qualitätsmanagement
## (MM, SD, PP usw.) Weitere ERP Logistik-Module....
ERP ERP modulübergreifend
MAIN ERP/EWM/TM übergreifend

Auf die Kombination Kundennamensraum und Projektidentifizierer folgt immer ein
## Unterstrich »_«.
Dies dient der Abgrenzung zu den nachfolgenden Präfixen.



© prismat GmbH Seite 21 von 76

3.3 ABAP Dictionary
Die Dictionary-Elemente werden als Kombination aus den oben angeführten
Konventionen für Repostitory-Objekten und den folgenden angelegt:
## 3.3.1 Pakete
Alle hier aufgeführten Pakete werden in einem übergeordneten Paket »ROOT«
integriert. Somit ist dieses Paket das einzige auf dieser Ebene.
Ist kein passender Eintrag vorhanden ist dieser vor der Implementierung mit dem
Teamleiter abzustimmen, so dass bei Bedarf ein zusätzliches Paket angelegt wird.
Der Entwickler kann grundsätzlich eigenverantwortlich entscheiden, in welches
Paket die Entwicklung passt.
Vor der Entwicklung muss analysiert werden, welche Programmbestandteile
prozessübergreifend eingesetzt werden können und somit im CORE-Paket
abgelegt werden müssen. Darüber hinaus sollen alle BAdIs, dessen
Erweiterungsspot »CORE« enthält (z.B. /SCWM/ES_CORE_PTS), dem CORE-Paket
zugeordnet werden. Implementierungen, die Schnittstellen betreffen, sollen ins
Paket »EXT« aufgenommen werden. Dies betrifft auch die Lieferschnittstelle und
die CIF-Schnittstelle (z.B. BAdI SMOD_APOCF005).
Die grobe Paketstruktur ist wie folgt definiert:
## • ROOT
o MAIN
o EWM
o ERP
o TM







© prismat GmbH Seite 22 von 76

Die Pakethierarchie sieht eine weitere Feingliederung in folgende Unterpakete vor:
## Paket Bedeutung
EWM Extended Warehouse Management
CORE Prozessübergreifende Objekte (cross-process
objects)
CONF Konfiguration (configuration)
EXT Externe Systeme (external systems)
GI Warenausgang  (goods issue)
GR Wareneingang  (goods receipt)
IP Lagerinterne Prozesse  (internal processes)
LM Arbeitsmanagement  (labor management)
MFS Materialflusssystem   (material flow system)
MON Monitorerweiterungen  (monitor options)
PACK Packtisch  (packing station)
RF Radio Frequency
PRNT Druck (printing)
WEB Webapplikationen / -services
YM Yardmanagement




© prismat GmbH Seite 23 von 76

## Paket Erläuterung
ERP Enterprise Resource Planning
## ERP Logistikmodul (Bsp.: MM, SD, LE, PP usw.)
CORE Prozessübergreifende Objekte (cross-process
objects)
CONF Konfiguration (configuration)
EXT Externe Systeme (external systems)
RF Radio Frequency
PRNT Druck (printing)
WEB Webapplikationen / -services

## Paket Erläuterung
MAIN ERP/EWM/TM übergreifend
CORE Prozessübergreifende Objekte (cross-process
objects)
CONF Konfiguration (configuration)
EXT Externe Systeme (external systems)
PRNT Druck (printing)
WEB Webapplikationen / -services




© prismat GmbH Seite 24 von 76

In einem Embedded Szenario sollten Entwicklungen, die sowohl vom ERP als auch
von EWM/TM genutzt werden in einem gemeinsamen Paket MAIN
zusammengefasst werden.
Beispiele zur Paket-Benennung:
<Kundennamensraum>< Projektidentifizierer>_<Paket>
## ZEWM_CORE
## ZERP_SD
## ZMAIN_CONF
## /PRIS/ROOT
## /PRIS/EWM
## /PRIS/EWM_WEB




© prismat GmbH Seite 25 von 76

Beispiele zur Paket-Zuordnung:
## Paket Objekttyp Objektname
ZEWM_CONF Tabelle ZEWM_PARAM
ZEWM_CONF Tabellentyp ZEWM_TT_PARAM
ZEWM_CONF Klasse ZEWM_CL_PARAM
ZEWM_CONF Funktionsgruppe für
## Pflegedialog
## ZEWM_PARAM
ZEWM_CORE Erweiterungsimplementierung ZEWM_EI_CORE_PTS
ZEWM_CORE Implementierende Klasse ZEWM_CB_CORE_PTS
ZEWM_CORE Klasse ZEWM_CL_HELP_GENERAL
ZEWM_EXT Erweiterungsimplementierung ZEWM_EI_ERP_MAPIN
ZEWM_IP Klasse ZEWM_CL_INVENTORY



© prismat GmbH Seite 26 von 76

## 3.3.2 Programme
## 3.3.2.1 Funktionsbibliothek
## Objekt Beschreibung
Funktionsgruppe <Kundennamensraum><Projektidentifizierer>_<Name
der Funktionsgruppe>
Funktionsbaustein <Kundennamensraum>_<Projektidentifizierer>_< Name
des Funktionsbaustein>

## Beispiel:
Funktionsgruppe ZEWM_CORE_CUST_SEL
Funktionsbaustein Z_EWM_PUT_SSEQ_READ_SINGLE











© prismat GmbH Seite 27 von 76

## 3.3.2.2 Programmbibliothek
## Objekt Beschreibung
## Report
(Programm)
<Kundennamensraum>
<Projektidentifizierer>_<Report>
Beachten: Der Report wird immer mit Top-Include angelegt
Include <Kundennamensraum><Projektidentifizierer>_<Report>_xxx
## TOP: _TOP
Klassendefinition _CDEF
Klassenimplementierung _C<Nummerierung>
Unterprogramm _F<Nummerierung>
PBO _O<Nummierung>
PAI _I<Nummierung>
Selektionsbild _SEL

Beachte: Nummerierung entsprechend den Dynpros







© prismat GmbH Seite 28 von 76

## Beispiel:
Report: ZEWM_Reportname
TOP-Include: ZEWM_Reportname_TOP
Include Klassendefinition ZEWM_Reportname_CDEF
## Include Klassenimplementierung
## 1
ZEWM_Reportname_C01
Include Unterprogramme 1 ZEWM_Reportname_F01
PBO ZEWM_Reportname_O01
PAI ZEWM_Reportname_I01
Selektionsbild ZEWM_Reportname_SEL
Report: ZEWM_Reportname
## 3.3.2.3 Unterprogramme
Bei der Namensvergabe von Unterprogrammen gelten dieselben Konventionen wie
bei der Benamung von Methoden (siehe Kapitel 3.3.3).



© prismat GmbH Seite 29 von 76

## 3.3.2.4 Klassenbibliothek
## Objekt Beschreibung
Klasse: <Kundennamensraum><Projektidentifizierer>_CL_<Klasse>
## Ausnahme-
## Klasse
<Kundennamensraum>CX_<Projektidentifizierer>_<Klasse>
BAdI-Klasse <Kundennamensraum><Projektidentifizierer>_CB_<Klasse>
PPF-Klasse <Kundennamensraum><Projektidentifizierer>_CP_<Klasse>
## Enhancement-
point-Klasse
<Kundennamensraum><Projektidentifizierer>_CE_<Klasse>
## Programmlokale
## Klasse
LCL_<Klasse>
Beachte: Die Ausnahme-Klassen können nur zwingend mit
»<Kundennamensraum>CX« angelegt werden.
## 3.3.2.5 Interfaces
## Objekt Beschreibung
## Klassen-
## Interface
<Kundennamensraum><Projektidentifizierer>_IF_<Interface>
## Programmlokales
## Interface
LIF_<Interface>





© prismat GmbH Seite 30 von 76

## 3.3.2.6 Methoden
Bei der Namensvergabe von Methoden wird angehalten, einen schlüssigen
englischsprachigen Namen zu verwenden. Bei Methoden welche Attributzugriffe
jedweder Art definieren/implementieren beginnen mit dem Präfix »GET_« beim
Lesen des Attributes und dem Präfix »SET_« beim Setzten des Attributes.
Allgemein sollte eine Methode mit einem englischen Verb beginnen.
## Beispiele:
GET_<Attribut> SET_<Attribut>
GET_<Attribut> SET_<Attribut>
Alternative zu Getter-Methoden:
Statt der Getter-Methoden wird empfohlen, eine Variable als Read-only-Variable
anzulegen (public). Dies bewirkt, dass das Attribut außerhalb der Klasse lesbar,
aber nicht bzw. nur durch die Setter-Methoden änderbar ist.
## 3.3.2.7 Typkonvertierung
Methoden die Typkonvertierungen durchführen beginnen mit dem Präfix »AS_«.
## Beispiele:
AS_<Typ>
## AS_STRING
## 3.3.2.8 Boolsche Werte
Methoden, die boolsche Werte zurückgeben beginnen mit dem Präfix »IS_«. Diese
Methoden dürfen keine Exception zurückgeben.



© prismat GmbH Seite 31 von 76

## Bespiel:
IS_<Prüfung>
## IS_ACTIVE
## 3.3.2.9 Ereignisse
Ereignisnamen beginnen mit dem Präfix »EVT_«.
- Erläuterung: »EVT« steht für den engl. Begriff Event (deutsch = Ereignis).
- Empfehlung: Ereignisnamen sollten weiter in der Form
<Substantiv>_<Verb in Partizipform> benannt werden.
## Beispiele:
EVT_<Substantiv>_<Verb in Partizipform>
## EVT_BUTTON_PUSHED
## 3.3.2.10 Ereignisbehandlung
Methoden, welche ein Ereignis (Event) behandeln, beginnen mit dem Präfix
»ON_EVT«. Anschließend wird der Namen des Ereignisses, dass Sie behandeln,
angegeben.
## Beispiele:
ON_EVT_<Ereignisname>
## ON_EVT_BUTTON_PUSHED



© prismat GmbH Seite 32 von 76

## 3.3.3 Dynpros
Es wird kein Quellcode direkt in die Module eingetragen. Stattdessen werden
entsprechende Unterprogramme oder Methoden mit dem Quellcode aufgerufen.
Die Includes werden dabei nach einzelnen Screens getrennt. (1, 2, 3).
Die Nummerierung ist wie folgt geregelt:
- eigen entwickelte Dynpro’s: 9000-9990
- Screens in 100er Schritten
- Subscreens in 110er-Schritten
Bei Selektionsbildern kann das Standardselektionsbild (Dynpronummer 1000)
verwendet werden.
## Beispiel:
9000 Anmeldescreen zur autom Warenausgangsbuchung
9100 Auswahl für autom. Warenausgangsbuchung
3.3.4 BAdI's
Für die Implementierung der BAdI's ist die entsprechende Anleitung zu
empfehlen. Im Folgenden ist der Name des entsprechenden Objektes mit »Teil
des ...« angegeben. Das bedeutet, dass nur ein bestimmter Teil des Namens der
Objekte aus den Hilfetexten entnommen werden darf. Dieser Teil kann aus den
nachfolgenden Beispielen oder ausführlich erläutert aus der Anleitung zur BAdI-
Benennung entnommen werden.
Es wird pro Erweiterungsspot eine Klasse angelegt. Darin werden alle BAdI's des
Erweiterungssports angelegt. Die Entwicklungen werden in einer eigenen Methode
implementiert (nicht in der Standardmethode).



© prismat GmbH Seite 33 von 76

## Objekt Beschreibung
## Erweiterungs-
implementierung
<Kundennamensraum><Projektidentifizierer>_EI_<Teil des
## Erweiterungsspot Namens>
BAdI-
## Implementierung
<Kundennamensraum><Projektidentifizierer>_BI_<Teil des
## Interface Namens>
Beschreibung Beachten: Falls mehrere BAdI’s mit Filter eingesetzt werden, wird
eine fortlaufende Nummer an den Namen angehängt. Der erste
implementierte BAdI bleibt davon unbetroffen, somit beginnt die
Nummerierung mit „02“.
## Implementierende
## Klasse
<Überschrift aus Dokumentation zur IMG-Aktivität zum BAdI>
## Beispiel:
## Erweiterungsimpl
ementierung
<Kundennamensraum><Projektiden
tifizierer>_EI_<Teil des
## Erweiterungsspot Namens>
## ZEWM_EI_CORE_PTS
BAdI-
## Implementierung
<Kundennamensraum><Projektiden
tifizierer>_BI_<Teil des Interface
## Namens>
## ZEWM_BI_CORE_PTS_
## NBIN_NRM
BAdI-
## Implementierung
<Kundennamensraum><Projektiden
tifizierer>_BI_<Teil des Interface
## Namens>
## ZEWM_BI_CORE_PTS_
## NBIN_NRM_02
## Implementierende
## Klasse
<Kundennamensraum><Projektiden
tifizierer>_CB_<Teil der Benennung
des Erweiterungsspots>
## ZEWM_CB_CORE_PTS



© prismat GmbH Seite 34 von 76

## 3.3.5 Lagerverwaltungsmonitor
Neu-Implementierungen im Lagerverwaltungsmonitor werden mithilfe der
prismat-Basisklasse für den LVM angelegt. Die Programmlogik muss daher je
Knoten in eine Logik-Klasse ausgelagert werden, die von der Basisklasse erbt. Der
Ablauf in den Funktionsbausteinen basiert auf den Vorlagen zu den verschiedenen
möglichen Knoten. Weitere Informationen können der entsprechenden Anleitung
entnommen werden.
Als Namenskonvention gilt:
## Objekt Benennung
Klassifizierung <Kundennamensraum><Klassifizierung>
Knoten <Kundennamensraum>N<Nummerierung>
Klassifizierungsknoten <Kundennamensraum>NC<Nummerierung>
Knotenprofil <Kundennamensraum>P<Nummerierung>
Objektklasse <Kundennamensraum>O<Nummerierung>
Objektklassenmethode <Kundennamensraum>M<Nummerierung>
## Beispiel:
Klassifizierung ZOUTB
Knoten ZN00000001
Klassifizierungsknoten ZNC0000001
Knotenprofil ZP000001
Objektklasse ZO0001
Objektklassenmethode ZM0001


© prismat GmbH Seite 35 von 76

3.3.6 Break-Point-ID's
Der Aufbau der ID's sieht eine Unterscheidung von mehreren Ebenen (speziell
nach allgemein) vor. Dabei gelten folgende Konventionen:
Break-Point-ID’s werden nur an öffentlichen (public) Methoden im
objektorientierten Umfeld verwendet.
Findet eine Implementierung außerhalb der Objektorientierten Programmierung
statt, sollten die Break-Point-ID’s nur an den Einstiegspunkten (bspw. zu Beginn
eines Funktionsbausteines) verwendet werden.
BREAK-POINT-ID Beschreibung Erklärung Verwendung
<Kundennamensraum>
<Projektidentifizierer>_
## MAIN
alle kunden-
spezifischen
## Entwicklungen
Break-Point ID für
## Entwicklungen Fa.
prismat GmbH
In allen
Entwicklungen der
Fa. prismat GmbH
<Kundennamensraum>
<Projektidentifizierer>_
## BADI
alle kunden-
spezifischen BAdIs
Break-Point ID für
alle
implementierten
BAdI's
In allen
implementierten
BAdI's
<Kundennamensraum>
<Projektidentifizierer>_
<Erweiterungs-spot>
<Beschreibung aus
## Erwei-terungsspot>
Break-Point ID auf
## Erwei-
terungsspotebene
In allen
implementierten
BAdI's des
## Erweiterungsports
<Kundennamensraum>
<Projektidentifizierer>_
<Interface Name>
<Beschreibung aus
## Interface>
Break-Point ID für
## Interface
In allen BAdI's des
## Interfaces
<Kundennamensraum>
<Projektidentifizierer>_
RF_<Prozess>
alle kunden-
spezifischen RF-
## Prozesse
Break-Point ID für
## Funktionsbaustein
In allen Funktions-
bausteinen im RF-
## Umfeld
<Kundennamensraum>
<Projektidentifizierer>_
<Paketname>
<Beschreibung des
## Pakets>
Break-Point ID auf
## Paketebene
In allen
## Entwicklungen
des Pakets
<Kundennamensraum>
<Projektidentifizierer>_
## EP
alle kunden-
spezifischen
## Enhancementpoints
Break-Point-ID für
## Enhancementpoints
In allen
## Enhancementpoints
<Kundennamensraum>
<Projektidentifizierer>_
EP_<Prozess>
<Beschreibung des
entsprechenden
Break-Point ID für
EP-Programm
In allen
## Enhancementpoints


© prismat GmbH Seite 36 von 76

## Enhancement
## Points>




© prismat GmbH Seite 37 von 76

## Beispiel:
ZEWM_ES_CORE_PTS <Kundennamensraum><Projektidentifizierer>_
<Erweiterungsspot>
ZEWM_EX_CORE_PTS_NBIN_NRM <Kundennamensraum><Projektidentifizierer>_
<Interface Name>
3.3.7 Enhancement-Points
Es wird kein Quellcode direkt in die Enhancementpoints eingetragen. Stattdessen
wird eine entsprechende Methode der Enhancementpoint-Klasse mit dem
Quellcode aufgerufen.
## Namenskonvention:
<Kundennamensraum><Projektidentifizierer>_EP_<Funktionsname/Bezug>
3.3.8 User Exits - Erweiterungen (CMOD und SMOD)
Transaktion CMOD – Projektverwaltung von SAP-Erweiterungen
Z<Projektname_des_Kunden_Repository>
Falls kein Projekt angelegt werden soll, dann gilt:
Z<Bereich>








© prismat GmbH Seite 38 von 76

## Beispiele (max. 8-stellig):
ZMM, ZSD, ZPP etc. Modulabhängig
ZPRNT Druck
ZWEB Web
ZEXT Externe Systeme
ZERP Modulübergreifend / nicht eindeutig zuzuordnen
3.3.9 Feldexits zu den Datenelementen
Der generierte Funktionsbaustein ist wie folgt zu benennen:
## ZFIELD_EXIT_<FELDNAME>
## 3.3.10 Screen Exits
Die gewählte Dynpronummer ist nach Möglichkeit im 9000er Bereich zu wählen.
## 3.3.11 Data Dictionary
Die folgende Tabelle beschreibt die Konventionen der Dictionary-Objekte. Dabei
ist der vorgegebene Namensraum (Z) bereits eingefügt. Das doppelte »X« steht
hier für den Projektidentifizierer, der entsprechend gewählt werden muss. Die
Begriffe in den spitzen Klammern sind frei wählbar, sollten aber sinnvoll gewählt
werden.




© prismat GmbH Seite 39 von 76

## Objekt Beschreibung
Datenbanktabelle Zxx_<Tabelle>
Struktur Zxx_S_<Struktur>
Tabellentyp Zxx_TT_<Tabellentyp>
View Zxx_<View>V
Domäne Zxx_DO_<Domäne>
Datenelement Zxx_DE_<Datenelement>
Typgruppe Zxx_TG_<Typgruppe>
Sperrobjekt EZ_<Tabellenname>
Beachte: Wenn sich das Sperrobjekt auf eine Struktur bezieht, soll
ein Teil des Strukturnamens verwendet werden.
Tabellenfeld (Z-
## Tabelle)
<Feldname>
Beachte: möglichst den Namen aus dem Datenelement verwenden
Tabellenfeld (SAP-
## Tabelle)
ZZ_<Feldname>
Beachte: möglichst den Namen aus dem Datenelement verwenden
zusätzliche Felder in einem Append zusammenfassen und in einem
Include an die SAP-Tabelle anhängen
Strukturfeld <Feldname>
Beachte: möglichst den Namen aus dem Datenelement verwenden
Append Zxx_A_<Teil des Tabellen-/Struktur-Namens>
Include-Struktur Zxx_I_<Teil des Tabellen-/Struktur-Namens>
Festwert-Append Zxx_DA_<Teil des Domänennamens>
Viewcluster Zxx_VC_<Viewcluter>
Tabellenindizes Z<Tabellenindex>
Suchhilfe Zxx_SH_<Suchhilfe>
Tabellenpflegedialog <Tabellenname>
Beachte: Pro Tabelle immer eine eigene Funktionsgruppe



© prismat GmbH Seite 40 von 76

## Beispiel:
<Kundennamensraum>< Projektidentifizierer><Tabelle>
## ZEWM_APPLOG

## 3.4 Deklarationen
## 3.4.1 Programminterne Deklarationen
Bei Datendeklarationen sind folgende Präfixe in allen Programmarten, also auch
Methoden zu beachten. Klassenattribute sind gesondert im folgenden Kapitel
aufgeführt. Auch für Feldsymbole sind diese Regeln einzuhalten und um spitze
Klammern zu ergänzen (z.B. <ls_*>)
## Präfix Sichtbarkeit Bedeutung
P_ Global Selektionsparameter auf einem Selektionsbild
PC_ Global Selektionsparameter als Checkbox auf einem
## Selektionsbild
PR_ Global Selektionsparameter als Radiobutton auf einem
## Selektionsbild
S_ Global Selektionsoption auf einem Selektionsbild
GTY_S_ Global Strukturtyp
GTY_T_ Global Tabellentyp




© prismat GmbH Seite 41 von 76

## 3.4.2 Tabellarische Übersicht
## 1. Stelle
## (scope)
- Stelle (DataType)
## V
## (field)
## T
## (table)
## S
## (structure)
## RS
## (structure
range)
## RT
## (table
range)
## C
## (constants)
## O
## (object)
## X
## (exception)
## D
## (data
reference)
I (importing) iv_ it_ is_ irs_ irt_ - io_ ix_ id_
## E
## (exporting)
ev_ et_ es_ ers_ ert_ - eo_ ex_ ed_
C (changing) cv_ ct_ cs_ crs_ crt_ - co_ cx_ cd_
## R
## (returning)
rv_ rt_ rs_ rrs_ rrt_ - ro_ rx_ rd_
## L
## (local)
lv_ lt_ ls_ lrs_ lrt_ lc_ lo_ lx_ ld_
## G
## (global)
gv_ gt_ gs_ grs_ grt_ gc_ go_ gx_ gd_
## S
## (static)
sv_ st_ ss_ srs_ srt_ sc_ so_ sx_
sd_
## M
## (member)
mv_ mt_ ms_ mrs_ mrt_ - mo_ mx_
## -



© prismat GmbH Seite 42 von 76

3.5 Exceptions (Klasse)
Im Folgenden sind sinnvolle Exception-Beispiele für Klassen gelistet. Die Punkte
»...« stehen dabei als Platzhalter für eine sinnvolle Ergänzung einer
entsprechenden Ausnahme.
## Exception Bedeutung
ACTION_NOT_SUPPORTED Die angeforderte Aktion bzw. der angeforderte
OK-Code wird nicht unterstützt.
CANCELLED Sollte in einer Methode anhand eines Dialoges
erst ermittelt werden, was zu tun ist (Beispiel:
Auswahlliste) und der Benutzer wählt.
EXISTING Ein neu anzulegendes Objekt existiert auf der
Datenbank schon.
FAILED Die Methode konnte ihre Aufgabe aufgrund der
aktuellen Umfeldsituation nicht ausführen. Diese
Exception ist insbesondere für solche Fälle
gedacht, in welchen sich das Umfeld temporär in
einer Konstellation befindet, die das Ausführen
der Methodenaufgabe unmöglich macht.
..._FAILED Eine Teilfunktion der Methode konnte aufgrund
der aktuellen Umfeldsituation nicht ausgeführt
werden. (OPEN_FAILED, CLOSE_FAILED,
## SELECTION_FAILED, AUTHORIZATION_FAILED)
FOREIGN_LOCK Daten sind durch anderen Benutzer gesperrt.
INCONSISTENT Objektdaten auf der Datenbank sind inkonsistent.
..._INCONSISTENT Die Teilobjektdaten ... eines Objektes auf der
Datenbank sind inkonsistent.
INVALID Die eingegebenen Objektdaten sind nicht korrekt.
(z.B. Buchungskreis nicht vorhanden) (im
Gegensatz zu NOT_QUALIFIED)


© prismat GmbH Seite 43 von 76

..._INVALID Die eingegebenen Teilobjektdaten eines Objektes
sind nicht korrekt. (im Gegensatz zu
## NOT_QUALIFIED)
INTERNAL_ERROR Der letzte Ausweg. Wenn der Fehler nicht weiter
eingegrenzt werden kann, dann erst soll diese
EXCEPTION verwendet werden.
NOT_AUTHORIZED Der Benutzer ist nicht zur Aktion berechtigt.
NOT_CUSTOMIZED Das angeforderte Objekt ist nicht korrekt
gecustomized.
..._NOT_CUSTOMIZED Das Teilobjekt ... des angeforderten Objektes ist
nicht korrekt gecustomized.
NOT_FOUND Das verlangte Objekt ist nicht gefunden worden.
..._NOT_FOUND Das Teilobjekt ... des verlangten Objektes ist
nicht gefunden worden.
NOT_QUALIFIED Die Kombination der Eingabeparameter reicht
nicht aus, um die Funktion der Methode
auszuführen. (im Gegensatz zu INVALID)
..._NOT_QUALIFIED Ein bestimmter Parameter der Methode ist nicht
qualifiziert.
NUMBER_ERROR Fehler bei der Nummernvergabe.
SYSTEM_ERROR Sollte aus dem Basissystem ein Fehlercode gemeldet
werden, der nicht erwartet wird, dann kann diese
EXCEPTION gesetzt werden.
## Beispiel:
## ..._ NOT_FOUND
## DATE_NOT_FOUND


© prismat GmbH Seite 44 von 76

## 3.6 Konstanten
Falls in den Entwicklungen feste Werte verwendet werden müssen, werden diese
nicht hart codiert in den Quellcode eingefügt. Je nach benötigter Reichweite der
Werte werden diese in Konstanten gespeichert. Werden die Werte nur
programmintern benötige, sollten diese als globale Konstante gespeichert werden
(z.B. Klassenattribut). Andernfalls bieten sich Interfaces an. Hier können
Konstante programmübergreifend gesammelt werden. Die maximale Ebene ist
hier das Paket. Das bedeutet, dass keine paketübergreifende Konstante in einem
Interface gesammelt werden dürfen.
Beachte: Die Begrenzung auf Paketebene hat den Grund, dass alle von dem
Interface partizipierenden Programme neu kompiliert werden müssen, sobald ein
Wert der Konstanten geändert wird. Je mehr unterschiedliche Programme
betroffen sind, desto mehr Bereiche müssen bei Änderungen im P-System die
Arbeit unterbrechen.


© prismat GmbH Seite 45 von 76

## 4 Datenbank
## 4.1 Datenbankzugriffe
Lesende Zugriffe auf kundeneigene Datenbanktabellen werden über
entsprechende, speziell entwickelte Klassen, zentral getätigt. Der Vorteil liegt in
der Pufferung der bereits von anderer Stelle zuvor selektierten Datensätze. Der
Schlüssel der gepufferten Tabelle sollte möglichst allgemein gehalten werden.
Sind die nun selektierten Datensätze in der internen Tabelle vorhanden wird der
Zugriff auf die Datenbank/den Puffer gespart. Auf Bewegungsdaten darf nicht
gepuffert zugegriffen werden. Nach Möglichkeit sollten die Zugriffe Programm-
und Entwicklerübergreifend abgestimmt werden.
## Name Methode Beschreibung
READ_SINGLE Einzelzugriff
READ_MULT Massenzugriff
Schreibende Zugriffe auf kundeneigene Datenbanktabellen werden über eigens
angelegte Verbuchungsbausteine vorgenommen.
Die Zugriffe auf SAP-eigene Datenbanktabellen werden über entsprechende SAP-
Funktionsbausteine realisiert. Sind keine passenden Funktionsbausteine
verfügbar, bleibt es dem Entwickler überlassen, die Zugriffe zu managen. Dabei
sollten natürlich Techniken wie Kapselung und Exceptionhandling beachtet
werden.
Bei Datenbankzugriffen mit Hilfe von Range-Tabellen oder über den Zusatz »FOR
ALL ENTRIES« muss sichergestellt werden, dass die entsprechenden Tabellen
nicht leer sind, da ansonsten keinerlei Einschränkung stattfindet.


© prismat GmbH Seite 46 von 76

4.2 Verwaltung von eigenen Customizingtabellen
Die Verwaltung der Customizingtabellen sollen dem Berater/Kunden so einfach
wie möglich gemacht werden. Dafür werden diese Tabellen zentral über das
Customizing in einem eigenen Knoten gepflegt. Dazu werden die Tabellen einem
Viewcluster zugeordnet. Hierfür wird die entsprechende Anleitung zur Erstellung
des Clusters und der Einbindung ins Customizing empfohlen.
4.3 Verwaltung von eigenen Datenbanktabellen
Zur Pflege von Stammdaten in Datenbanktabellen werden grundsätzlich immer
Pflegedialoge nach der entsprechenden Anleitung angelegt. Nur in
Ausnahmefällen, unter Absprache mit dem Teamleiter, sollte auf den Pflegedialog
verzichtet werden. Nach der Generierung des Pflegedialogs ist die Tabelle im
Dynpro möglichst so breit zu ziehen, dass die Tabelle ohne Scrollen angezeigt
wird. Ist dies nicht möglich, wird die Tabelle so breit gemacht wie möglich. Die
Datenelemente der Datenbanktabelle sollten dokumentiert sein. Die Eingabehilfe
soll wenn möglich über passende Fremdschlüsselbeziehungen oder hinterlegte
Suchhilfen realisiert werden.
## 5 Applog
Um in den Eigenentwicklungen eventuell auftretende Probleme/Fehler bestmöglich
dokumentieren und auswerten zu können wird in jedem Programm das Applog
eingebunden. Dabei ist unbedingt darauf zu achten, dass, unabhängig von Art und
Auftreten eines Fehlers, die entsprechenden Einträge in das Applog geschrieben
und gespeichert werden.
Für die Nutzung des Applog (sowohl die Einbindung in die Programme als auch für
die Auswertung) stehen umfangreiche Schulungsunterlagen und Dokumente zu
## Verfügung.


© prismat GmbH Seite 47 von 76

5.1 Applog instanziieren
Wenn die Instanziierung des Applogs fehlschlägt (z.B. aufgrund von
Konfigurationsfehlern), muss die entsprechende Ausnahme abgefangen werden
und der Fehlertext in Form einer Nachricht vom Typ „X“ ausgegeben werden. Bei
der Instanziierung muss eine sinnvolle externe ID mitgegeben werden, um die
Suche nach relevanten Applog-Einträgen zu beschleunigen. Über diese externe ID
sollte nach Möglichkeit auch der jeweilige Prozess identifizierbar sein, indem z. B.
eine entsprechende Beschreibung oder ein Klassenname hinzugefügt wird.
## Beispiel:
## DATA:
lv_msg              TYPE bapi_msg,                      "#EC NEEDED
lv_extnumber        TYPE balnrext,
lo_log              TYPE REF TO /pris/ewm_cl_applog,
lx_log_wrong_config TYPE REF TO /pris/cx_ewm_log_wrong_config.

CONCATENATE sc_classname
iv_lgnum
iv_huident
INTO lv_extnumber
SEPARATED BY space.

## TRY.

CREATE OBJECT lo_log
## EXPORTING
iv_lgnum     = lv_lgnum
-       iv_object    = SC_BALOBJ
iv_subobject = sc_subobject
iv_extnumber = lv_extnumber.

CATCH /pris/cx_ewm_log_wrong_config INTO lx_log_wrong_config.

lv_msg = lx_log_wrong_config->get_text( ).
MESSAGE lv_msg TYPE 'X'.

## ENDTRY.


© prismat GmbH Seite 48 von 76

5.2 Programm-Informationen in das Applog aufnehmen
Wenn das /PRIS/-Applog eingesetzt wird, ist darüber hinaus die Methode
»ADD_PROGRAM_INFO« zu Beginn und Ende von komplexeren Methoden,
Unterprogrammen, Funktionsbausteinen etc. aufzurufen.
## Beispiel:
lo_log->add_program_info( ).

## * - Ablauflogik -

lo_log->add_program_info( iv_end = abap_true ).
5.3 Nachrichten in das Applog aufnehmen
Die Nachrichten sollen mit Hilfe des MESSAGE-Befehls in eine Textvariable
geschrieben werden, so dass das Applog auf die Systemfelder (z. B. »sy-msgty«)
zurückgreifen kann. Ein Vorteil dieser Vorgehensweise ist, dass der
Verwendungsnachweis auf die Nachrichten korrekt funktioniert. Die
Nachrichtenklasse sollte nach Möglichkeit global (z.B. in den Eigenschaften einer
Klasse) angegeben werden. Der Nachrichtentext selbst muss als Kommentar über
dem MESSAGE-Befehl angegeben werden. Wenn es vorkommen kann, dass die
Platzhalter mit leeren Werten gefüllt werden, müssen diese erkennbar gemacht
werden, z.B. indem die Platzhalter von spitzen Klammern umschlossen werden.
Textsymbole sollen vermieden werden.
## Beispiel:
- HU <&1> wird überprüft
MESSAGE i001
WITH iv_huident
INTO lv_msg.

lo_log->add_message( ).
Wenn eine bapiret-Tabelle benötigt wird (z.B. in einem BAdI), so muss die
bapiret-Tabelle über das Applog gefüllt werden. Somit ist ein einheitlicher Aufbau
inkl. funktionierendem Verwendungsnachweis möglich. Darüber hinaus können


© prismat GmbH Seite 49 von 76

Zusatzfunktionen, wie das Hinzufügen der Programminformationen, verwendet
werden. Die Bapiret-Tabelle kann anschließend über die Methode »get_prot«
ermittelt werden.
## Beispiel:
et_bapiret = lo_log->get_prot( ).
5.4 Applog speichern
Beim Speichern des Applogs muss berücksichtigt werden, dass die entsprechende
Methode keinen COMMIT ausführt. Dies führt auch dazu, dass ein ggf.
notwendiger ROLLBACK WORK vor dem Speichern des Applogs durchgeführt
werden muss. Sollten beim Speichern des Applogs Ausnahmen auftreten, so soll
der weitere Programmablauf dadurch nicht beeinflusst werden (im Gegensatz zur
Behandlung der Ausnahmen beim Instanziieren).


© prismat GmbH Seite 50 von 76

6 Radio-Frequency-Namenskonventionen
Folgende Namenskonventionen sollen eingehalten werden.
## 6.1 Paket
<Kundennamensraum><Projektidentifizierer>_RF
Beispiel: ZEWM_RF
## 6.2 Darstellungsprofil
Sämtliches RF-Customizing aus Standard-Transaktionen zum Darstellungsprofil
**** darf in jedem Fall nie geändert werden.
Für kundenspezifische Anpassungen in Standard-Transaktionen erfolgt die Pflege
immer im kundenspezifischen Darstellungsprofil.
Komplett neue kundenspezifische RF-Transaktionen können jedoch zum
Darstellungsprofil **** definiert werden.
## 6.3 Prozessliste
In der nachfolgenden Tabelle sind alle vorgegebenen Prozessnummern definiert.
Diese orientieren sich am Aufbau der RF-Standard-Funktionsgruppen.
Jede neu zu erstellende logische Transaktion ist einer sinnvollen Prozessnummer
zuzuordnen.
## Prozessnummer Prozessbeschreibung
General, Internal Processes (Allgemein, Interne Prozesse)
## 00 General
(Allgemein)
## 01 Ressource Management
(Ressourcenmanagement)


© prismat GmbH Seite 51 von 76

## 02 Adhoc
## 03 Inquiry
(Abfrage)
## 04 Packing
(Verpacken)
## 05 Inventory
(Inventur)
## 06 Replenishment
(Nachschub)
07 Quality management
(Qualitätsmanagement)
08 Labor management
(Arbeitsmanagement)
## 09 Spreading
(Dekonsolidierung)
Goods issue processes (Warenausgangsprozesse)
## 10 Picking
(Kommissionierung)
## 11 Loading
(Verladen)
Good receipt processes (Wareneingangsprozesse)
12 Receiving HUs / Good receipt
(Empfang HUs / Wareneingang)
## 13 Putaway
(Einlagerung)
## 14 Unloading
(Entladen)
Manufacturing processes (Produktionsprozesse)


© prismat GmbH Seite 52 von 76

## 15 Manufacturing Consumption / Consumption Reversal
## Produktionsverbauch + Stornierung
## 16 Manufacturing Receive Goods / Reversal
Empfang von Produktionsgütern + Stornierung
Transit warehouse processes (Transit-Lager Prozesse)
17 Transit warehousing: Floorcheck
(Transitlagerung: Flächenprüfung)
18 Transit warehousing: Loading TU
(Transitlagerung: TU verladen)
19 Transit warehousing: Maintain HU
(Transitlagerung: HU ändern)
20 Transit warehousing: Packing
(Transitlagerung: Verpacken)
21 Transit warehousing: Receiving and Unloading
(Transitlagerung: Empfang und Entladen)
## Others
22 Distribution Device/ Equipment (Transportgeräte)
## 6.4 Logische Transaktion
Die Definition der Logischen Transaktionen sollen nach einem fest definierten
Schema vorgenommen werden, um Konflikte im Zielsystem zu vermeiden.
Stellen der logischen Transaktion Schema
## 1 Namensraum – Z
2 und 3 Prozessnummer gemäß Kapitel 6.1
4 und 5 Fortlaufende Nummerierung der
Lösungen von 01 bis 99



© prismat GmbH Seite 53 von 76

## 01 – 50
(Kundenlösungen im Zielsystem)
## 51 – 99
(Raketenlösungen)
6 Reserviert für Definition der Schritte
Z<Prozessnummer><Fortlaufende Nummerierung der Lösungen von 01 bis 99>
Die fortlaufende Nummerierung beginnt immer innerhalb einer Prozessnummer
mit 01 (Kundenlösung) oder 51 (Raketenlösung) und es wird die nächste freie
verwendbare Nummer genommen.
## Beispiele:
10 = Picking/Kommissionierung
51/52 = Nummerierung der Lösungen
Z1051 RPI – Picking
Z1052 RCP – Combined Picking
## 04 = Packing/ Verpacken
51 = Nummerierung der Lösung
Z0451 RRP: Repacking
Definition Beschreibung logische Transaktion
Die technische Beschreibung bei der Definition der logischen Transaktion soll
immer nach dem nachfolgenden Schema benannt werden.
Das Lösungskürzel bezieht sich nur auf Raketenlösungen und fällt bei
Kundenlösungen weg.
<Beschreibung zu Prozessnummer> - <Lösungskürzel>: Beschreibung der Lösung
## Beispiel:
Packing – RRP: Repacking Transaction
Picking – RPI: Picking
Picking – RCP: Combined Picking


© prismat GmbH Seite 54 von 76


## Darstellungstexte
Der Darstellungstext für die logische Transaktion im Menü soll immer mit dem
Lösungskürzel (sofern Raketenlösung), gefolgt von der Beschreibung der
Transaktion starten:
Beschreibung: <Lösungskürzel> - <Beschreibung der Lösung>

## 6.5 Schritte
Die Definition der Schritte einer logischen Transaktion knüpfen an der
Namenskonvention für die Transaktionen aus Kapitel 6.4 an.
Die Nummerierung der Schritte erfolgt alphanumerisch.
## Schema:
Z<Prozessnummer><Fortlaufende Nummerierung der Lösungen>
<Alphanumerische fortlaufende Nummerierung der Schritte von A bis Z>
## Beispiele:
Z0401A Selection by Location
Z0401B Process repacking by HU/material
Z0401C Create Destination-HU
## ...
bis Z0401Z


© prismat GmbH Seite 55 von 76

## 6.6 Stände
Die Definition der Stände orientiert sich analog an dem Schema der Schritte und
erfolgt alphanumerisch.
## 6.7 Funktionsgruppe
Der Prozess sollte eine möglichst sprechende Bezeichnung auf Englisch sein, pro
logische Transaktion im Customizing wird eine neue Gruppe angelegt. So können
die Gruppen gleichen Prozessen zugeordnet sein, sind aber trotzdem noch durch
die logische Transaktion unterscheidbar.
<Kundennamensraum><Projektidentifizierer>_RF_<Prozess>_<log. Trans.>
Beispiel: ZEWM_RF_PACKING_Z0451
## 6.8 Funktionsbaustein
Die Bezeichnung PBO/PAI kann wegfallen; da der PBO immer den Funktionscode
‚INIT‘ haben wird kann davon ausgegangen werden, dass alle Funktionsbausteine
ohne ‚INIT‘ im klassischen Sinne zum PAI gehören.
Durch die Nutzung eines Funktionsbausteins pro Funktionscode wird eine bessere
Übersicht gewährleistet.
Das Kürzel „RF“ entfällt bei der Definition der Funktionsbausteine.
<Kundennamensraum>_<Projektidentifizierer>_<log.Trans.>_<Step>_<FCode>
Beispiel: Z_EWM_Z0451_Z0451A_INIT, Z_EWM_Z0451_Z0451A_ENTER
## 6.9 Klassen
Die Klassen werden genau wie die Funktionsgruppen nur mit zusätzlichem _CL_
benannt, den vorangegangenen Beispielen folgend also:
<Kundennamensraum><Projektidentifizierer>_ CL_RF_<Prozess>_<log. Trans.>
Beispiel: ZEWM_ CL_RF_PACKING_Z0451


© prismat GmbH Seite 56 von 76

## 6.10 Dynpro
Die Nummerierung der Dynpros muss unterschiedlich sein, je nach der
Screengröße. Im Breitbild sollte innerhalb der Funktionsgruppe mit 9000
angefangen, und dann in 1er Schritten weitergegangen werden (also 9001, 9002,
## 9003,...).
Im Schmalbildformat wird mit 9100 angefangen und dann ebenfalls in 1er
Schritten weitergegangen (also 9101, 9102, 9103,...).
Die Beschreibung des Dynpros sollte nach dem folgenden Schema aufgebaut
werden:
<Anzeigeprofil> - <Schritt> - Beschreibung des Schritts/Dynpros
Beispiel: SB – Z0101A – Eingabe der HU
BB – Z0101A – Eingabe der HU
## 6.11 Checkpointgruppe
Für jede Funktionsgruppe sollte eine Checkpointgruppe angelegt werden.
<Kundennamensraum><Projektidentifizierer>_RF_<log. Trans.>
Beispiel: ZEWM_RF_ZPKHU


© prismat GmbH Seite 57 von 76

## 7 Post Processing Framework
## 7.1 Paket
<Kundennamensraum><Projektidentifizierer>_PPF
Beispiel: ZEWM_PPF
## 7.2 Customizing
Dieses Kapitel beinhaltet die Namenskonventionen für Customizing-Objekte des
## Post Processing Frameworks.
Transaktion: SPPFCADM
## 7.2.1 Applikation
## Maximale Länge: 30 Stellen
## Namenskonvention:
<Kundennamensraum><Modul>_<Objektbezeichnung>
## Beispiele:
## ZEWM_HU
## ZEWM_WT
## 7.2.2 Aktionsprofil
## Maximale Länge: 30 Stellen
## Namenskonvention:
<Applikation>_<Aufrufer>_<Prozess>_<Fortlaufende Nummerierung>
## Beispiele:
## ZEWM_HU_CLOSE_HU_GI_01


© prismat GmbH Seite 58 von 76

## 7.2.3 Aktionsdefinition
## Maximale Länge: 30 Stellen
## Namenskonvention:
<Aktionsprofil>_<Aktionsbeschreibung>
## Beispiele:
## ZEWM_HU_CLOSE_HU_GI_01_CREATE_OD
## ZEWM_HU_CLOSE_HU_GI_01_PRINT_OD
## 7.3 ABAP
Dieses Kapitel beinhaltet die Namenskonventionen für PPF ABAP-Objekte.
7.3.1 BAdIs
Dieses Kapitel beinhaltet die Namenskonventionen für PPF-BAdIs.
Grundsätzlich gilt:
- Eine BAdI-Implementierung je Aktionsprofil
- Ein Filterwert je Aktionsdefinition
## 7.3.1.1 Ausführung
BAdI-Definition: EXEC_METHODCALL_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_EX
## Beispiel:
## ZEWM_CLS_HU_GI_01_EX
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_EX
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_EX


© prismat GmbH Seite 59 von 76

## 7.3.1.2 Einplanbedingung
BAdI-Definition: EVAL_SCHEDCOND_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_SC
## Beispiel:
## ZEWM_CLS_HU_GI_01_SC
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_SC
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_SC
## 7.3.1.3 Startbedingung
BAdI-Definition: EVAL_STARTCOND_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_ST
## Beispiel:
## ZEWM_CLS_HU_GI_01_ST
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ST
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_ST


© prismat GmbH Seite 60 von 76

7.3.1.4 Externe Kommunikation (Druck)
Diese Technologie arbeitet über BAdI-Definitionen und bietet zu implementierende
Methoden sowohl für Smart Forms als auch für Adobe Forms an.
BAdI-Definition: DOC_PERSONALIZE_BCS
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_EC
## Beispiel:
## ZEWM_CLS_HU_GI_01_EC
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ EC
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_EC
## 7.3.1.5 Druckerfindung
BAdI-Definition: PRINTER_DETERM_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_PR
## Beispiel:
## ZEWM_CLS_HU_GI_01_PR
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ PR
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_PR


© prismat GmbH Seite 61 von 76

7.3.1.6 Vervollständigung von Verarbeitungen
BAdI-Definition: COMPLETE_PROC_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_CP
## Beispiel:
## ZEWM_CLS_HU_GI_01_CP
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ CP
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_CP
## 7.3.1.7 Kontexterweiterung
BAdI-Definition: CONTEXT_EXTEND_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_CX
## Beispiel:
## ZEWM_CLS_HU_GI_01_CX
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ CX
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_CX


© prismat GmbH Seite 62 von 76

7.3.1.8 Container vor Bedingungsauswertung ergänzen
BAdI-Definition: CONTAINER_PPF
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_<Aktionsprofil, ggf. gekürzt>_CN
## Beispiel:
## ZEWM_CLS_HU_GI_01_CN
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_<Aktionsprofil, ggf. gekürzt>_ CN
## Beispiel:
## ZEWM_CB_CLS_HU_GI_01_CN
7.3.2 Weitere PPF-Klassen
## 7.3.2.1 Applikationsklasse
Oberklasse prismat/RAKETE: /PRIS/CL_EWM_PPF_APPL
Oberklasse Standard:  keine
Schnittstellen:   IF_OS_STATE, IF_LOCK_PPF
## Namenskonvention:
<Kundennamensraum>CL_<Modul>_PPF_APPL_<Objektname>
## Beispiel:
## /PRIS/CL_EWM_PPF_APPL_HU


© prismat GmbH Seite 63 von 76

## 7.3.2.2 Kontextklasse
Oberklasse prismat/RAKETE: /PRIS/CL_EWM_PPF_CTX
Oberklasse Standard:  CL_CONTEXT_PPF
Schnittstellen:   keine
## Namenskonvention:
<Kundennamensraum>CL_<Modul>_PPF_CTX_<Objektname>
## Beispiel:
## /PRIS/CL_EWM_PPF_CTX_HU
## 7.3.2.3 Triggerklasse
Oberklasse prismat/RAKETE:  /PRIS/CL_EWM_PPF_TRG
Oberklasse Standard:  keine
Schnittstellen:   keine
## Namenskonvention:
<Kundennamensraum>CL_<Modul>_PPF_TRG_<Objektname>
## Beispiel:
## /PRIS/CL_EWM_PPF_TRG_HU
7.3.2.4 Druckklasse (Smartforms)
Der Einsatz einer Druckklasse für Smart Forms (Verarbeitungsart Smart Forms
Druck) im Post Processing Framework wird nicht mehr empfohlen.
Stattdessen sollte der Druck mit der Verarbeitungsart Externe Kommunikation
umgesetzt werden (siehe Kapitel 7.3.1.4).
Oberklasse prismat/RAKETE:  /PRIS/CL_EWM_PPF_PROC_PRINT_SF
Oberklasse Standard:  keine
Schnittstellen:   keine
## Namenskonvention:
<Kundennamensraum>CL_<Modul>_<Aktionsprofil, ggf. gekürzt>_PR_SF


© prismat GmbH Seite 64 von 76

## Beispiel:
## ZCL_EWM_WT_C_CONF_01_PR_SF
Definition einer statischen Druck-Methode je Aktionsdefinition
- diese Druck-Methode wird dann von der Methode EXEC_SMART_FORMS
dynamisch aufgerufen
- Erforderliche Schnittstelle (aufgrund des statischen Aufrufs durch
Standard-PPF nicht mit Hilfe von Interfaces abbildbar)



© prismat GmbH Seite 65 von 76

## 8 Konditionstechnik
## 8.1 Paket
<Kundennamensraum><Projektidentifizierer>_COND
Beispiel: ZEWM_COND
## 8.2 Customizing
Dieses Kapitel beinhaltet die Namenskonventionen für Customizing-Objekte der
## Konditionstechnik.
Transaktion:  SPRO
Pfad: SCM Extended Warehouse Management -> Extended Warehouse
## Management -> Prozessübergreifende Einstellungen -> Konditionstechnik
## 8.2.1 Feldkatalog
## 8.2.1.1 Suchfeld
## Namenskonvention:
<Applikation>_<Feldname>
## Beispiele:
## ZWT_LGNUM
## ZHU_LGNUM
Hinweis prismat/RAKETE: Bei der Definition von Suchfeldern ist es enorm wichtig,
dass  die  definierte  Namenskonvention  eingehalten  wird,  damit  dynamisch  zur
Laufzeit  aus  den  Kontext-/Applikationsdaten  die  zugehörigen  Werte  ermittelt
werden können.


© prismat GmbH Seite 66 von 76

## 8.2.1.2 Verwendungsfeld
## Namenskonvention:
<Verwendung>_<Feldname>
## Beispiele:
## Z1_LGNUM
## Z2_LGNUM
Hinweis prismat/RAKETE: Bei der Definition von Verwendungsfeldern ist es enorm
wichtig, dass die definierte Namenskonvention eingehalten wird, damit dynamisch
zur Laufzeit aus den Kontext-/Applikationsdaten die zugehörigen Werte ermittelt
werden können.
## 8.2.2 Konditionstabelle
## Maximale Länge: 8 Stellen
## Namenskonvention:
CUS<Applikation><Fortlaufende Nummerierung, 2 stellig>
## Beispiel:
## CUSZWT01
## CUSZHU01
## 8.2.3 Zugriffsfolge
## Maximale Länge: 4 Stellen
## Namenskonvention:
Z<Fortlaufende Nummerierung, 3 stellig>
## Beispiel:
## Z001


© prismat GmbH Seite 67 von 76

8.2.4 Zugriff zur Zugriffsfolge
## Maximale Länge: 3 Stellen
## Namenskonvention:
<Fortlaufende Nummerierung>
## Beispiele:
## 1
## 2
## 3
## 8.2.5 Konditionsart
## Maximale Länge: 4 Stellen
## Namenskonvention:
Z<Fortlaufende Nummerierung, 3 stellig>
## Beispiel:
## Z001
## 8.2.6 Findungsschema
## Maximale Länge: 6 Stellen
## Namenskonvention:
Z<Applikation><Fortlaufende Nummerierung, 3 stellig>
## Beispiel:
## ZWT001
## ZHU001


© prismat GmbH Seite 68 von 76

## 8.2.7 Konditionspflegegruppe
## Maximale Länge: 10 Stellen
## Namenskonvention Druck:
<Applikation>PRNT<Fortlaufende Nummerierung, 3 stellig>
## Beispiel:
## ZWTPRNT001
## ZHUPRNT001

## Namenskonvention Prozess:
<Applikation>PROC<Fortlaufende Nummerierung, 3 stellig>
## Beispiel:
## ZWTPROC001
## ZHUPROC00
## 8.2.8 Applikation
Transaktion: SM30
View:  /SAPCND/V_APPLIC
## Maximale Länge: 3 Stellen
## Namenskonvention:
Z<Objektbezeichnung, 2-stellig>
## Beispiele:
## ZHU
## ZWT


© prismat GmbH Seite 69 von 76

## 8.2.9 Verwendung
Transaktion:  SM34
Viewcluster: /SAPCND/VC_FC_US (Verwendung)
## Maximale Länge: 2 Stellen
## Namenskonvention:
Z<Fortlaufende Nummerierung, 1 stellig>
Rakete:   Z<0-9> – Z<A-P>
Projektgeschäft: Z<Q-Z>
## Beispiele:
## Z1
## Z2
8.2.10 Signatur zur Verwendung
Gleichnamige Benennung zur Verwendung
Transaktion: SM30
View:  /SAPCND/V_TASK




© prismat GmbH Seite 70 von 76

## 8.3 ABAP
Dieses Kapitel beinhaltet die Namenskonventionen für Konditionstechnik ABAP-
## Objekte.
8.3.1 BAdIs
## 8.3.1.1 Suchfeld
BAdI-Definition: /SAPCND/EX_ROLLNAME
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_CON_<Feldname>
## Beispiel:
## ZEWM_CON_LGNUM
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_CON_<Feldname>
Beispiel: ZEWM_CB_CON_LGNUM
prismat/RAKETE:
Oberklasse: /PRIS/EWM_CL_CON_ROLLNAME
Namenskonvention implementierende Enhancement-Klasse:
<Kundennamensraum><Modul>_CL_CON_<Feldname>_ENH
## Beispiel:
## /PRIS/EWM_CL_CON_LGNUM_ENH


© prismat GmbH Seite 71 von 76

## 8.3.1.2 Verwendungsfeld
BAdI-Definition: /SAPCND/EX_MNT_USG_ROLL
Namenskonvention BAdI-Implementierung:
<Kundennamensraum><Modul>_CON_<Feldname>
## Beispiel:
## ZEWM_CON_PRINTER
Namenskonvention implementierende BAdI-Klasse:
<Kundennamensraum><Modul>_CB_CON_<Feldname>
Beispiel: ZEWM_CB_CON_PRINTER
prismat/RAKETE:
Oberklasse: /PRIS/EWM_CL_CON_ROLLNAME
Namenskonvention implementierende Enhancement-Klasse:
<Kundennamensraum><Modul>_CL_CON_<Feldname>_ENH
## Beispiel:
## /PRIS/EWM_CL_CON_PRINTER_ENH


© prismat GmbH Seite 72 von 76

## 9 Druck
## 9.1 Allgemein
Für das Vorgehen beim Erstellen eines neuen Formulars gibt es eine eigene
Anleitung. Die wichtigsten Namenskonventionen werden jedoch auch hier
aufgeführt. Dabei wird zwischen SAP Smartforms und SAP Interactive Forms by
Adobe unterschieden.
## 9.1.1 Klassen
Es wird für jede Formulargruppe (HU-Etiketten, Material-Etiketten, Lieferscheine,
...) eine eigene Klasse angelegt.
9.1.2 SAP Smartforms
Für jedes SAP Smartforms wird ein eigener Style angelegt. Der Name des Styles
beinhaltet dann den Namen des SAP Smartforms (siehe Namenskonvention).
9.1.3 SAP Adobe Interactive Forms
Für jedes SAP Interactive Forms wird eine eigene Schnittstelle angelegt. Der
Name der Schnittstelle beinhaltet dann den Namen des SAP Interactive Forms
## (siehe Namenskonvention).
## 9.2 Namenskonventionen
## 9.2.1 Klassen
<Kundennamensraum><Projektidentifizierer>_PRNT_<Formulargruppe>
Beispiel: ZEWM_PRNT_HU_LABEL
## Methode Typ Sichtbarkeit Beschreibung


© prismat GmbH Seite 73 von 76

PRINT Obligatorisch/Optional
(in PPF,
## Konditionstechnik)
PUBLIC Methode für
externen Aufruf
des Drucks aus
dem Prozess
heraus
GET_DATA Obligatorisch PUBLIC Methode zum
Beschaffen der
## Druckdaten
PREPARE_DATA Obligatorisch PRIVATE Methode zum
Aufbereiten der
## Druckdaten
CALL_FORM Obligatorisch/Optional
(in PPF,
## Konditionstechnik)
PRIVATE Methode für den
Aufruf des zu
druckenden
## Formulars
GET_PRINTER Optional PRIVATE Methode für die
## Druckerermittlung
9.2.2 SAP Smartforms
## 9.2.2.1 Formulare
<Kundennamensraum><Projektidentifizierer>_SF_<Formularname>
Beispiel: ZEWM_SF_HU_CONTENT
## 9.2.2.2 Elemente
## Element Benennung Beispiel
Seite PAGE_<Zähler> PAGE_1
Fenster WIN_<Name> WIN_MAIN;
## WIN_HEADER
Grafik GRAPH_<Name> GRAPH_LOGO


© prismat GmbH Seite 74 von 76

Adressfeld ADR_<Name> ADR_SEND
Textfeld TXT_<Name> TXT_MATNR
VAL_<Name> VAL_MATNR
Tabelle TAB_<Name> TAB_DLV_HDR
Schablone/Template TMP_<Name> TMP_DLV_HDR
Alternative ALT_<Name> ALT_SHOW_MATNR
Schleife LOOP_<Name> LOOP_DLV_HDR
Programmzeile PROG_<Name> PROG_CONV_MATID
Kommando COMM_<Name> COMM_PAGE_SWITCH
## 9.2.2.3 Styles
<Kundennamensraum><Projektidentifizierer>_SFST_<Name des Formulares>
Beispiel: ZEWM_SFST_HU_CONTENT
9.2.3 SAP Interactive Forms by Adobe
## 9.2.3.1 Formulare
<Kundennamensraum><Projektidentifizierer>_IFA_<Name>
Beispiel: ZEWM_IFA_HU_CONTENT
## 9.2.3.2 Schnittstelle
<Kundennamensraum><Projektidentifizierer>_IF_<Name des Formulars>
Beispiel: ZEWM_IF_HU_CONTENT


© prismat GmbH Seite 75 von 76

10 SAP Online Service System (OSS)
Jeder Mitarbeiter der Firma prismat GmbH hat einen eigenen Zugang zum OSS.
Somit ist jeder Mitarbeiter angehalten eigenständig nach eventuell vorhandenen
Lösungen für entsprechende Probleme zu suchen.
Dagegen erfolgt eine Eröffnung einer Meldung ausschließlich nach Absprache mit
dem Teamleiter.
11 Aktuelle Änderungen zur letzten Version
## 11.1 Dokumentation
Die notwendigen Kommentare bzw. die Dokumentation bei Programmköpfen
wurde überarbeitet. (Kapitel 2.1.1)
Änderungen (nach Projektphasen) (Kapitel 2.2) Das permanente Sichern der
Sourcen in die Projektordner vor einer Änderung entfällt, da auch durch
Versionsverwaltung die Änderungen nachgehalten werden können.

## 11.2 Quellcode
Die Vorgaben zu Inline-Deklarationen und Programmstruktur wurden aktualisiert.
(Kapitel 2.3.1)
## 11.3 Transportaufträge
Es wurde ein neues Kapitel zur Anlage von Transportaufträgen eingefügt, welches
die Definition und Benennung von Transportaufträgen thematisiert. (Kapitel 3.1)
11.4 Repository-Objekte
Es wurden neue Namensräume für Entwicklungen im Produktbereich und für die
prismat S/4 Rakete definiert. Zusätzlich wurden neue Projektidentifizierer für den
Bereich ERP und EWM/ERP/TM übergreifend festgelegt. (Kapitel 3.2)


© prismat GmbH Seite 76 von 76

11.5 ABAP Dictionary
Die Paketdefinitionen, -strukturen und –hierarchien wurden ganzheitlich
überarbeitet um sowohl einem ERP System (ggf. S/4 HANA) im dezentralen
Szenario als auch einem Embedded Szenario mit EWM/ERP und TM
übergreifenden Entwicklungen gerecht zu werden (Kapitel 3.3.1)
Ein neues Kapitel zur Definition und Handhabung der ERP User Exits
(CMOD/SMOD Erweiterungen) wurde hinzugefügt (Kapitel 3.3.8)
Neue Kapitel zum Umgang mit Feldexits (Kapitel 3.3.9) und Screen Exits (Kapitel
3.3.10) im ERP wurden hinzugefügt.
Anpassungen zur Namenskonvention von Suchhilfen und Views wurden
durchgeführt (Kapitel 3.3.11).
## 11.6 Namenskonventionen
In der tabellarischen Übersicht der Deklarationen (Kapitel 3.4.2) wurde für die
2.Stelle der Präfix d für Datenreferenzen aufgenommen.