+--------------------------------------------------------------------------------------+
| Änderungshistorie                                                                    |
+====================+====================+====================+=======================+
| **Datum**          | **Version**        | **Änderung**       | **bearbeitet von**    |
+--------------------+--------------------+--------------------+-----------------------+
| 12.02.2025         | M23                | Erstellung         | Tim Andernach\        |
|                    |                    |                    | Pierre-René Michel\   |
|                    |                    |                    | Kilian Bertram        |
+--------------------+--------------------+--------------------+-----------------------+
| 22.12.2025         | M23_2              | Aktualisierung     | Tim Andernach         |
|                    |                    | Rahmenbedingungen  |                       |
+--------------------+--------------------+--------------------+-----------------------+
| 08.01.2026         | M23_2              | Kapitel zur Lösung | Pierre-René Michel    |
|                    |                    | BEF hinzugefügt    |                       |
+--------------------+--------------------+--------------------+-----------------------+
| 12.01.2026         | M23_2              | Kapitel zur Lösung | Pierre-René Michel    |
|                    |                    | GTB System         |                       |
|                    |                    | hinzugefügt        |                       |
+--------------------+--------------------+--------------------+-----------------------+
| 19.01.2026         | M23_2              | Kapitel zu „GTB -  | Pierre-René Michel    |
|                    |                    | Kleine Werkzeuge"  |                       |
|                    |                    | hinzugefügt        |                       |
+--------------------+--------------------+--------------------+-----------------------+
| 22.01.2026         | M23_2              | Kapitel zu Easy    | Pierre-René Michel    |
|                    |                    | Mapper und RFC     |                       |
|                    |                    | Hilfsklasse        |                       |
|                    |                    | ergänzt            |                       |
+--------------------+--------------------+--------------------+-----------------------+

# Inhalt

[Inhalt [2](#inhalt)](#inhalt)

[1 Vorwort [16](#vorwort)](#vorwort)

[2 Rahmenbedingungen [17](#rahmenbedingungen)](#rahmenbedingungen)

[3 Definition [18](#definition)](#definition)

[3.1 Key Values - Schlüsselwerte
[18](#key-values---schlüsselwerte)](#key-values---schlüsselwerte)

[3.1.1 Kontext [18](#kontext)](#kontext)

[3.1.2 Prozessbeschreibung
[18](#prozessbeschreibung)](#prozessbeschreibung)

[3.1.3 Ablaufbeschreibung
[18](#ablaufbeschreibung)](#ablaufbeschreibung)

[3.1.4 Konfiguration [20](#konfiguration)](#konfiguration)

[3.1.4.1 Schlüsselarten [20](#schlüsselarten)](#schlüsselarten)

[3.1.4.2 Schlüsselwerte einstellen
[21](#schlüsselwerte-einstellen)](#schlüsselwerte-einstellen)

[3.1.4.3 Zugriff auf Schlüsselwerte
[22](#zugriff-auf-schlüsselwerte)](#zugriff-auf-schlüsselwerte)

[3.2 CFG -- Konfigurations-Framework
[23](#cfg-konfigurations-framework)](#cfg-konfigurations-framework)

[3.2.1 Kontext [23](#kontext-1)](#kontext-1)

[3.2.2 Prozessbeschreibung
[23](#prozessbeschreibung-1)](#prozessbeschreibung-1)

[3.2.3 Ablaufbeschreibung
[24](#ablaufbeschreibung-1)](#ablaufbeschreibung-1)

[3.2.4 Konfiguration [25](#konfiguration-1)](#konfiguration-1)

[3.2.4.1 Grundlegende Einstellungen
[25](#grundlegende-einstellungen)](#grundlegende-einstellungen)

[3.2.4.2 Daten pflegen [25](#daten-pflegen)](#daten-pflegen)

[3.3 SWT -- Schalter-Framework
[34](#swt-schalter-framework)](#swt-schalter-framework)

[3.3.1 Kontext [34](#kontext-2)](#kontext-2)

[3.3.2 Prozessbeschreibung
[34](#prozessbeschreibung-2)](#prozessbeschreibung-2)

[3.3.3 Ablaufbeschreibung
[35](#ablaufbeschreibung-2)](#ablaufbeschreibung-2)

[3.3.4 Konfiguration [37](#konfiguration-2)](#konfiguration-2)

[3.3.4.1 Grundlegende Einstellungen
[37](#grundlegende-einstellungen-1)](#grundlegende-einstellungen-1)

[3.3.4.2 Daten pflegen [38](#daten-pflegen-1)](#daten-pflegen-1)

[3.4 SDT Adjustment Report
[43](#sdt-adjustment-report)](#sdt-adjustment-report)

[3.4.1 Kontext [43](#kontext-3)](#kontext-3)

[3.4.2 Prozessbeschreibung
[43](#prozessbeschreibung-3)](#prozessbeschreibung-3)

[3.4.3 Ablaufbeschreibung
[44](#ablaufbeschreibung-3)](#ablaufbeschreibung-3)

[3.4.4 Konfiguration [46](#konfiguration-3)](#konfiguration-3)

[3.5 Wizard [47](#wizard)](#wizard)

[3.5.1 Kontext [47](#kontext-4)](#kontext-4)

[3.5.2 Prozessbeschreibung
[47](#prozessbeschreibung-4)](#prozessbeschreibung-4)

[3.5.3 Ablaufbeschreibung
[48](#ablaufbeschreibung-4)](#ablaufbeschreibung-4)

[3.5.4 Konfiguration [49](#konfiguration-4)](#konfiguration-4)

[3.6 Generische Tabellenleseklasse
[50](#generische-tabellenleseklasse)](#generische-tabellenleseklasse)

[3.6.1 Kontext [50](#kontext-5)](#kontext-5)

[3.6.2 Prozessbeschreibung
[50](#prozessbeschreibung-5)](#prozessbeschreibung-5)

[3.6.3 Ablaufbeschreibung
[51](#ablaufbeschreibung-5)](#ablaufbeschreibung-5)

[3.6.4 Konfiguration [51](#konfiguration-5)](#konfiguration-5)

[3.7 Transport Order Tool
[52](#transport-order-tool)](#transport-order-tool)

[3.7.1 Kontext [52](#kontext-6)](#kontext-6)

[3.7.2 Prozessbeschreibung
[52](#prozessbeschreibung-6)](#prozessbeschreibung-6)

[3.7.3 Ablaufbeschreibung
[53](#ablaufbeschreibung-6)](#ablaufbeschreibung-6)

[3.7.3.1 Klasse /PRIS/MAIN_CL_TOT
[53](#klasse-prismain_cl_tot)](#klasse-prismain_cl_tot)

[3.7.3.2 Report /PRIS/MAIN_TOT_ADD_LANG
[58](#report-prismain_tot_add_lang)](#report-prismain_tot_add_lang)

[3.7.4 Konfiguration [59](#konfiguration-6)](#konfiguration-6)

[3.8 Generische Suchhilfe
[60](#generische-suchhilfe)](#generische-suchhilfe)

[3.8.1 Kontext [60](#kontext-7)](#kontext-7)

[3.8.2 Prozessbeschreibung
[60](#prozessbeschreibung-7)](#prozessbeschreibung-7)

[3.8.3 Ablaufbeschreibung
[61](#ablaufbeschreibung-7)](#ablaufbeschreibung-7)

[3.8.4 Konfiguration [61](#konfiguration-7)](#konfiguration-7)

[3.9 CSV-Handling [62](#csv-handling)](#csv-handling)

[3.9.1 Kontext [62](#kontext-8)](#kontext-8)

[3.9.2 Prozessbeschreibung
[62](#prozessbeschreibung-8)](#prozessbeschreibung-8)

[3.9.3 Ablaufbeschreibung
[63](#ablaufbeschreibung-8)](#ablaufbeschreibung-8)

[3.9.4 Konfiguration [65](#konfiguration-8)](#konfiguration-8)

[3.10 Access Control Definition - Zugriffsfolgen
[66](#access-control-definition---zugriffsfolgen)](#access-control-definition---zugriffsfolgen)

[3.10.1 Kontext [66](#kontext-9)](#kontext-9)

[3.10.2 Prozessbeschreibung
[66](#prozessbeschreibung-9)](#prozessbeschreibung-9)

[3.10.3 Ablaufbeschreibung
[66](#ablaufbeschreibung-9)](#ablaufbeschreibung-9)

[3.10.3.1 Lagernummer unabhängige Logik
[66](#lagernummer-unabhängige-logik)](#lagernummer-unabhängige-logik)

[3.10.3.2 Filter [66](#filter)](#filter)

[3.10.3.3 Logging [66](#logging)](#logging)

[3.10.3.4 Prüfung der Suchfolgen
[67](#prüfung-der-suchfolgen)](#prüfung-der-suchfolgen)

[3.10.3.5 Ermittlungsmöglichkeiten erweitern
[67](#ermittlungsmöglichkeiten-erweitern)](#ermittlungsmöglichkeiten-erweitern)

[3.10.3.6 Wildcard [67](#wildcard)](#wildcard)

[3.10.3.7 Statischer Speicher
[67](#statischer-speicher)](#statischer-speicher)

[3.10.4 Konfiguration [68](#konfiguration-9)](#konfiguration-9)

[3.10.4.1 Protokollierung [68](#protokollierung)](#protokollierung)

[3.10.4.2 Tabellenpflege [68](#tabellenpflege)](#tabellenpflege)

[3.11 Generischer Löschreport
[71](#generischer-löschreport)](#generischer-löschreport)

[3.11.1 Kontext [71](#kontext-10)](#kontext-10)

[3.11.2 Prozessbeschreibung
[71](#prozessbeschreibung-10)](#prozessbeschreibung-10)

[3.11.3 Ablaufbeschreibung
[72](#ablaufbeschreibung-10)](#ablaufbeschreibung-10)

[3.11.4 Konfiguration [73](#konfiguration-10)](#konfiguration-10)

[3.11.4.1 Tabellenpflege [73](#tabellenpflege-1)](#tabellenpflege-1)

[3.12 GTB HTTP-Request [75](#gtb-http-request)](#gtb-http-request)

[3.12.1 Kontext [75](#kontext-11)](#kontext-11)

[3.12.2 Prozessbeschreibung
[75](#prozessbeschreibung-11)](#prozessbeschreibung-11)

[3.12.3 Ablaufbeschreibung
[76](#ablaufbeschreibung-11)](#ablaufbeschreibung-11)

[3.12.4 Konfiguration [77](#konfiguration-11)](#konfiguration-11)

[3.13 GTB Timer [78](#gtb-timer)](#gtb-timer)

[3.13.1 Kontext [78](#kontext-12)](#kontext-12)

[3.13.2 Prozessbeschreibung
[78](#prozessbeschreibung-12)](#prozessbeschreibung-12)

[3.13.3 Ablaufbeschreibung
[78](#ablaufbeschreibung-12)](#ablaufbeschreibung-12)

[3.13.4 Konfiguration [78](#konfiguration-12)](#konfiguration-12)

[3.14 Generische Berechtigungsprüfung
[79](#generische-berechtigungsprüfung)](#generische-berechtigungsprüfung)

[3.14.1 Kontext [79](#kontext-13)](#kontext-13)

[3.14.2 Prozessbeschreibung
[79](#prozessbeschreibung-13)](#prozessbeschreibung-13)

[3.14.3 Ablaufbeschreibung
[80](#ablaufbeschreibung-13)](#ablaufbeschreibung-13)

[3.14.4 Konfiguration [80](#konfiguration-13)](#konfiguration-13)

[3.15 BAdI and Enhancement Framework
[81](#badi-and-enhancement-framework)](#badi-and-enhancement-framework)

[3.15.1 Kontext [81](#kontext-14)](#kontext-14)

[3.15.2 Prozessbeschreibung
[82](#prozessbeschreibung-14)](#prozessbeschreibung-14)

[3.15.3 Ablaufbeschreibung
[84](#ablaufbeschreibung-14)](#ablaufbeschreibung-14)

[3.15.4 Konfiguration [88](#konfiguration-14)](#konfiguration-14)

[3.15.4.1 Konstanten- und Parameterwerte
[88](#konstanten--und-parameterwerte)](#konstanten--und-parameterwerte)

[3.15.4.2 Schaltereinstellungen
[88](#schaltereinstellungen)](#schaltereinstellungen)

[3.15.4.3 Protokollierung [88](#protokollierung-1)](#protokollierung-1)

[3.15.4.4 Checkpoint-Gruppen
[88](#checkpoint-gruppen)](#checkpoint-gruppen)

[3.15.4.5 Tabellenpflege [88](#tabellenpflege-2)](#tabellenpflege-2)

[3.16 GTB System [89](#gtb-system)](#gtb-system)

[3.16.1 Kontext [89](#kontext-15)](#kontext-15)

[3.16.2 Prozessbeschreibung
[90](#prozessbeschreibung-15)](#prozessbeschreibung-15)

[3.16.3 Ablaufbeschreibung
[92](#ablaufbeschreibung-15)](#ablaufbeschreibung-15)

[3.16.3.1 CHECK_DEVELOPMENT
[92](#check_development)](#check_development)

[3.16.3.2 CHECK_OPEN [92](#check_open)](#check_open)

[3.16.3.3 CHECK_PACKAGE_NOT_LOCAL
[93](#check_package_not_local)](#check_package_not_local)

[3.16.3.4 IS_CUSTOMIZING [93](#is_customizing)](#is_customizing)

[3.16.3.5 IS_DEMO [94](#is_demo)](#is_demo)

[3.16.3.6 IS_DEVELOPMENT [94](#is_development)](#is_development)

[3.16.3.7 IS_OPEN [95](#is_open)](#is_open)

[3.16.3.8 IS_PACKAGE_LOCAL [95](#is_package_local)](#is_package_local)

[3.16.3.9 IS_PRODUCTIVE [96](#is_productive)](#is_productive)

[3.16.3.10 IS_SAP_REFERENCE [96](#is_sap_reference)](#is_sap_reference)

[3.16.3.11 IS_TEST [97](#is_test)](#is_test)

[3.16.3.12 IS_TRAINING [97](#is_training)](#is_training)

[3.16.4 Konfiguration [97](#konfiguration-15)](#konfiguration-15)

[3.17 GTB - Kleine Werkzeuge
[98](#gtb---kleine-werkzeuge)](#gtb---kleine-werkzeuge)

[3.17.1 Kontext [98](#kontext-16)](#kontext-16)

[3.17.2 Prozessbeschreibung
[99](#prozessbeschreibung-16)](#prozessbeschreibung-16)

[3.17.3 Ablaufbeschreibung
[100](#ablaufbeschreibung-16)](#ablaufbeschreibung-16)

[3.17.3.1 /PRIS/MAIN_CL_GTB_CLASS_DET
[100](#prismain_cl_gtb_class_det)](#prismain_cl_gtb_class_det)

[3.17.3.2 /PRIS/MAIN_CL_GTB_DATA
[101](#prismain_cl_gtb_data)](#prismain_cl_gtb_data)

[3.17.3.3 /PRIS/MAIN_CL_GTB_ENQUEUE
[102](#prismain_cl_gtb_enqueue)](#prismain_cl_gtb_enqueue)

[3.17.3.4 /PRIS/MAIN_CL_GTB_SALV
[102](#prismain_cl_gtb_salv)](#prismain_cl_gtb_salv)

[3.17.3.5 /PRIS/MAIN_CL_GTB_SALV
[103](#prismain_cl_gtb_salv-1)](#prismain_cl_gtb_salv-1)

[3.18 Easy Mapper [104](#easy-mapper)](#easy-mapper)

[3.18.1 Kontext [104](#kontext-17)](#kontext-17)

[3.18.2 Prozessbeschreibung
[104](#prozessbeschreibung-17)](#prozessbeschreibung-17)

[3.18.3 Ablaufbeschreibung
[105](#ablaufbeschreibung-17)](#ablaufbeschreibung-17)

[3.18.4 Konfiguration [106](#konfiguration-16)](#konfiguration-16)

[3.18.4.1 Protokollierung [106](#protokollierung-2)](#protokollierung-2)

[3.18.4.2 Checkpoint-Gruppen
[106](#checkpoint-gruppen-1)](#checkpoint-gruppen-1)

[3.19 RFC Hilfsklasse [107](#rfc-hilfsklasse)](#rfc-hilfsklasse)

[3.19.1 Kontext [107](#kontext-18)](#kontext-18)

[3.19.2 Prozessbeschreibung
[107](#prozessbeschreibung-18)](#prozessbeschreibung-18)

[3.19.3 Ablaufbeschreibung
[107](#ablaufbeschreibung-18)](#ablaufbeschreibung-18)

[3.19.4 Konfiguration [108](#konfiguration-17)](#konfiguration-17)

[3.19.4.1 Protokollierung [108](#protokollierung-3)](#protokollierung-3)

[3.19.4.2 Checkpoint-Gruppen
[108](#checkpoint-gruppen-2)](#checkpoint-gruppen-2)

[[4]{.mark} [Implementierung]{.mark}
[109](#implementierung)](#implementierung)

[4.1 Key Values - Schlüsselwerte
[109](#key-values---schlüsselwerte-1)](#key-values---schlüsselwerte-1)

[4.1.1 Ablaufbeschreibung
[109](#ablaufbeschreibung-19)](#ablaufbeschreibung-19)

[4.2 CFG -- Konfigurations-Framework
[110](#cfg-konfigurations-framework-1)](#cfg-konfigurations-framework-1)

[4.2.1 Ablaufbeschreibung
[110](#ablaufbeschreibung-20)](#ablaufbeschreibung-20)

[4.3 SWT -- Schalter-Framework
[112](#swt-schalter-framework-1)](#swt-schalter-framework-1)

[4.3.1 Ablaufbeschreibung
[112](#ablaufbeschreibung-21)](#ablaufbeschreibung-21)

[4.4 SDT Adjustment Report
[114](#sdt-adjustment-report-1)](#sdt-adjustment-report-1)

[4.4.1 Ablaufbeschreibung
[114](#ablaufbeschreibung-22)](#ablaufbeschreibung-22)

[4.5 Wizard [117](#wizard-1)](#wizard-1)

[4.5.1 Ablaufbeschreibung
[117](#ablaufbeschreibung-23)](#ablaufbeschreibung-23)

[4.6 Generische Tabellenleseklasse
[118](#generische-tabellenleseklasse-1)](#generische-tabellenleseklasse-1)

[4.6.1 Ablaufbeschreibung
[118](#ablaufbeschreibung-24)](#ablaufbeschreibung-24)

[4.7 Transport Order Tool
[122](#transport-order-tool-1)](#transport-order-tool-1)

[4.7.1 Ablaufbeschreibung
[122](#ablaufbeschreibung-25)](#ablaufbeschreibung-25)

[4.7.1.1 Instanziierung [122](#instanziierung)](#instanziierung)

[4.7.1.2 Kopfdaten der Transporte einlesen
[122](#kopfdaten-der-transporte-einlesen)](#kopfdaten-der-transporte-einlesen)

[4.7.1.3 Übersetzungsobjekte einlesen
[124](#übersetzungsobjekte-einlesen)](#übersetzungsobjekte-einlesen)

[4.7.1.4 Objekte und Einträge einlesen
[125](#objekte-und-einträge-einlesen)](#objekte-und-einträge-einlesen)

[4.7.1.5 Dialog zur Transportauswahl einblenden
[127](#dialog-zur-transportauswahl-einblenden)](#dialog-zur-transportauswahl-einblenden)

[4.7.1.6 Objekte und Einträge in einem Transport einfügen
[129](#objekte-und-einträge-in-einem-transport-einfügen)](#objekte-und-einträge-in-einem-transport-einfügen)

[4.8 Generische Suchhilfe
[130](#generische-suchhilfe-1)](#generische-suchhilfe-1)

[4.8.1 Ablaufbeschreibung
[130](#ablaufbeschreibung-26)](#ablaufbeschreibung-26)

[4.9 CSV-Handling [134](#csv-handling-1)](#csv-handling-1)

[4.9.1 Ablaufbeschreibung
[134](#ablaufbeschreibung-27)](#ablaufbeschreibung-27)

[4.10 Access Control Definition - Zugriffsfolgen
[137](#access-control-definition---zugriffsfolgen-1)](#access-control-definition---zugriffsfolgen-1)

[4.10.1 Ablaufbeschreibung
[137](#ablaufbeschreibung-28)](#ablaufbeschreibung-28)

[4.11 Generischer Löschreport
[138](#generischer-löschreport-1)](#generischer-löschreport-1)

[4.11.1 Ablaufbeschreibung
[138](#ablaufbeschreibung-29)](#ablaufbeschreibung-29)

[4.12 GTB HTTP-Request [140](#gtb-http-request-1)](#gtb-http-request-1)

[4.12.1 Ablaufbeschreibung
[140](#ablaufbeschreibung-30)](#ablaufbeschreibung-30)

[4.12.1.1 Instanziierung [140](#instanziierung-1)](#instanziierung-1)

[4.12.1.2 Anfrage senden [140](#anfrage-senden)](#anfrage-senden)

[4.13 GTB Timer [142](#gtb-timer-1)](#gtb-timer-1)

[4.13.1 Ablaufbeschreibung
[142](#ablaufbeschreibung-31)](#ablaufbeschreibung-31)

[4.13.2 Ablaufdiagramm [143](#ablaufdiagramm)](#ablaufdiagramm)

[4.14 Generische Berechtigungsprüfung
[144](#generische-berechtigungsprüfung-1)](#generische-berechtigungsprüfung-1)

[4.14.1 Ablaufbeschreibung
[144](#ablaufbeschreibung-32)](#ablaufbeschreibung-32)

[4.14.1.1 Instanziierung [144](#instanziierung-2)](#instanziierung-2)

[4.14.1.2 Prüfung der Berechtigung
[144](#prüfung-der-berechtigung)](#prüfung-der-berechtigung)

[4.15 BAdI and Enhancement Framework
[146](#badi-and-enhancement-framework-1)](#badi-and-enhancement-framework-1)

[4.15.1 Ablaufbeschreibung
[146](#ablaufbeschreibung-33)](#ablaufbeschreibung-33)

[4.15.1.1 Konfiguration [146](#konfiguration-18)](#konfiguration-18)

[4.15.1.2 Erweiterung definieren
[148](#erweiterung-definieren)](#erweiterung-definieren)

[4.15.1.3 Erweiterung konfigurieren
[150](#erweiterung-konfigurieren)](#erweiterung-konfigurieren)

[4.15.1.4 Übersicht [153](#übersicht)](#übersicht)

[4.15.2 Aufruf des Frameworks in einer Erweiterungsimplementierung
[156](#aufruf-des-frameworks-in-einer-erweiterungsimplementierung)](#aufruf-des-frameworks-in-einer-erweiterungsimplementierung)

[4.15.3 Technische Implementierung einer Erweiterung
[161](#technische-implementierung-einer-erweiterung)](#technische-implementierung-einer-erweiterung)

[4.15.4 Erzeugen einer Implementierung über die Transaktion
/PRIS/BEF_CFG
[163](#erzeugen-einer-implementierung-über-die-transaktion-prisbef_cfg)](#erzeugen-einer-implementierung-über-die-transaktion-prisbef_cfg)

[4.15.4.1 Button zur Anlage einer neuen Implementierung
[163](#button-zur-anlage-einer-neuen-implementierung)](#button-zur-anlage-einer-neuen-implementierung)

[4.15.4.2 Art und Namen der Erweiterung definieren
[163](#art-und-namen-der-erweiterung-definieren)](#art-und-namen-der-erweiterung-definieren)

[4.15.4.3 Erfassen zusätzlicher Daten...
[164](#erfassen-zusätzlicher-daten)](#erfassen-zusätzlicher-daten)

[4.15.4.4 Anlage der Logikklasse
[168](#anlage-der-logikklasse)](#anlage-der-logikklasse)

[4.15.4.5 Angabe des Workbench-Transportauftrags
[168](#angabe-des-workbench-transportauftrags)](#angabe-des-workbench-transportauftrags)

[4.15.4.6 Auswahl fehlender Daten
[169](#auswahl-fehlender-daten)](#auswahl-fehlender-daten)

[4.15.5 Erzeugen einer Logikklasse über die Transaktion /PRIS/BEF_CFG
[170](#erzeugen-einer-logikklasse-über-die-transaktion-prisbef_cfg)](#erzeugen-einer-logikklasse-über-die-transaktion-prisbef_cfg)

[4.15.5.1 Button zur Anlage einer neuen Logikklasse
[170](#button-zur-anlage-einer-neuen-logikklasse)](#button-zur-anlage-einer-neuen-logikklasse)

[4.16 GTB System [172](#gtb-system-1)](#gtb-system-1)

[4.17 GTB - Kleine Werkzeuge
[173](#gtb---kleine-werkzeuge-1)](#gtb---kleine-werkzeuge-1)

[4.18 Easy Mapper [174](#easy-mapper-1)](#easy-mapper-1)

[4.18.1 Ablaufbeschreibung
[174](#ablaufbeschreibung-34)](#ablaufbeschreibung-34)

[4.19 RFC Hilfsklasse [175](#rfc-hilfsklasse-1)](#rfc-hilfsklasse-1)

[[5]{.mark} [Technische Dokumentation]{.mark}
[176](#technische-dokumentation)](#technische-dokumentation)

[5.1 Key Values - Schlüsselwerte
[176](#key-values---schlüsselwerte-2)](#key-values---schlüsselwerte-2)

[5.1.1 Dictionary Objekte
[176](#dictionary-objekte)](#dictionary-objekte)

[5.1.1.1 Domänen [176](#domänen)](#domänen)

[5.1.1.2 Datenelemente [176](#datenelemente)](#datenelemente)

[5.1.1.3 Datenbanktabellen
[176](#datenbanktabellen)](#datenbanktabellen)

[5.1.1.4 Tabellentypen [177](#tabellentypen)](#tabellentypen)

[5.1.1.5 Pflege-Views [177](#pflege-views)](#pflege-views)

[5.1.2 Klassenbibliotheken
[177](#klassenbibliotheken)](#klassenbibliotheken)

[5.1.3 Funktionsgruppen [177](#funktionsgruppen)](#funktionsgruppen)

[5.2 CFG -- Konfigurations-Framework
[178](#cfg-konfigurations-framework-2)](#cfg-konfigurations-framework-2)

[5.2.1 Dictionary Objekte
[178](#dictionary-objekte-1)](#dictionary-objekte-1)

[5.2.1.1 Domänen [178](#domänen-1)](#domänen-1)

[5.2.1.2 Datenelemente [179](#datenelemente-1)](#datenelemente-1)

[5.2.1.3 Strukturen [179](#strukturen)](#strukturen)

[5.2.1.4 Datenbank-Tabellen
[180](#datenbank-tabellen)](#datenbank-tabellen)

[5.2.1.5 Tabellentypen [180](#tabellentypen-1)](#tabellentypen-1)

[5.2.1.6 Pflege-Views [181](#pflege-views-1)](#pflege-views-1)

[5.2.1.7 Suchhilfen [181](#suchhilfen)](#suchhilfen)

[5.2.2 Klassen [182](#klassen)](#klassen)

[5.2.3 Klassen (falls Lösung im EWM)
[182](#klassen-falls-lösung-im-ewm)](#klassen-falls-lösung-im-ewm)

[5.2.4 Nachrichtenklassen
[182](#nachrichtenklassen)](#nachrichtenklassen)

[5.2.5 Funktionsgruppen [183](#funktionsgruppen-1)](#funktionsgruppen-1)

[5.2.6 Programme [183](#programme)](#programme)

[5.2.7 Transaktionscodes [183](#transaktionscodes)](#transaktionscodes)

[5.3 SWT -- Schalter-Framework
[184](#swt-schalter-framework-2)](#swt-schalter-framework-2)

[5.3.1 Dictionary Objekte
[184](#dictionary-objekte-2)](#dictionary-objekte-2)

[5.3.1.1 Datenelemente [184](#datenelemente-2)](#datenelemente-2)

[5.3.1.2 Datenbank-Tabellen
[184](#datenbank-tabellen-1)](#datenbank-tabellen-1)

[5.3.1.3 Pflege-Views [185](#pflege-views-2)](#pflege-views-2)

[5.3.1.4 Tabellentypen [185](#tabellentypen-2)](#tabellentypen-2)

[5.3.2 Klassen [186](#klassen-1)](#klassen-1)

[5.3.3 Klassen (falls Lösung im EWM)
[186](#klassen-falls-lösung-im-ewm-1)](#klassen-falls-lösung-im-ewm-1)

[5.3.4 Funktionsgruppen [186](#funktionsgruppen-2)](#funktionsgruppen-2)

[5.3.5 Nachrichtenklassen
[187](#nachrichtenklassen-1)](#nachrichtenklassen-1)

[5.3.6 Viewcluster [187](#viewcluster)](#viewcluster)

[5.3.7 Transaktionscodes
[187](#transaktionscodes-1)](#transaktionscodes-1)

[5.4 SDT Adjustment Report
[188](#sdt-adjustment-report-2)](#sdt-adjustment-report-2)

[5.4.1 Klassen [188](#klassen-2)](#klassen-2)

[5.4.2 Programme [188](#programme-1)](#programme-1)

[5.5 Wizard [189](#wizard-2)](#wizard-2)

[5.5.1 Dictionary Objekte
[189](#dictionary-objekte-3)](#dictionary-objekte-3)

[5.5.1.1 Strukturen [189](#strukturen-1)](#strukturen-1)

[5.5.1.2 Tabellentypen [189](#tabellentypen-3)](#tabellentypen-3)

[5.5.2 Klassenbibliotheken
[190](#klassenbibliotheken-1)](#klassenbibliotheken-1)

[5.5.3 Transaktionscode [190](#transaktionscode)](#transaktionscode)

[5.5.4 Nachrichtenklassen
[190](#nachrichtenklassen-2)](#nachrichtenklassen-2)

[5.6 Generische Tabellenleseklasse
[191](#generische-tabellenleseklasse-2)](#generische-tabellenleseklasse-2)

[5.6.1 Dictionary Objekte
[191](#dictionary-objekte-4)](#dictionary-objekte-4)

[5.6.1.1 Datenelemente [191](#datenelemente-3)](#datenelemente-3)

[5.6.1.2 Strukturen [191](#strukturen-2)](#strukturen-2)

[5.6.1.3 Tabellentypen [191](#tabellentypen-4)](#tabellentypen-4)

[5.6.2 Klassen [192](#klassen-3)](#klassen-3)

[5.6.3 Nachrichtenklassen
[192](#nachrichtenklassen-3)](#nachrichtenklassen-3)

[5.7 Transport Order Tool
[193](#transport-order-tool-2)](#transport-order-tool-2)

[5.7.1 Klassen [193](#klassen-4)](#klassen-4)

[5.7.2 Reports [193](#reports)](#reports)

[5.8 Generische Suchhilfe
[194](#generische-suchhilfe-2)](#generische-suchhilfe-2)

[5.8.1 Dictionary Objekte
[194](#dictionary-objekte-5)](#dictionary-objekte-5)

[5.8.1.1 Suchhilfe [194](#suchhilfe)](#suchhilfe)

[5.8.2 Interfaces [194](#interfaces)](#interfaces)

[5.8.3 Klassen [194](#klassen-5)](#klassen-5)

[5.8.4 Funktionsgruppen [195](#funktionsgruppen-3)](#funktionsgruppen-3)

[5.8.5 Funktionsbausteine
[195](#funktionsbausteine)](#funktionsbausteine)

[5.8.6 Nachrichtenklassen
[195](#nachrichtenklassen-4)](#nachrichtenklassen-4)

[5.9 CSV-Handling [196](#csv-handling-2)](#csv-handling-2)

[5.9.1 Dictionary Objekte
[196](#dictionary-objekte-6)](#dictionary-objekte-6)

[5.9.1.1 Strukturen [196](#strukturen-3)](#strukturen-3)

[5.9.1.2 Tabellentypen [196](#tabellentypen-5)](#tabellentypen-5)

[5.9.1.3 Suchhilfen [196](#suchhilfen-1)](#suchhilfen-1)

[5.9.2 Klassenbibliothek [197](#klassenbibliothek)](#klassenbibliothek)

[5.9.3 Programme [198](#programme-2)](#programme-2)

[5.9.4 Funktionsgruppe [198](#funktionsgruppe)](#funktionsgruppe)

[5.9.5 Nachrichtenklassen
[198](#nachrichtenklassen-5)](#nachrichtenklassen-5)

[5.10 Access Control Definition - Zugriffsfolge
[199](#access-control-definition---zugriffsfolge)](#access-control-definition---zugriffsfolge)

[5.10.1 Dictionary Objekte
[199](#dictionary-objekte-7)](#dictionary-objekte-7)

[5.10.1.1 Domänen [199](#domänen-2)](#domänen-2)

[5.10.1.2 Datenelemente [199](#datenelemente-4)](#datenelemente-4)

[5.10.1.3 Strukturen [199](#strukturen-4)](#strukturen-4)

[5.10.1.4 Tabellentypen [199](#tabellentypen-6)](#tabellentypen-6)

[5.10.2 Klassenbibliothek
[200](#klassenbibliothek-1)](#klassenbibliothek-1)

[5.10.3 Nachrichtenklassen
[200](#nachrichtenklassen-6)](#nachrichtenklassen-6)

[5.11 Generischer Löschreport
[201](#generischer-löschreport-2)](#generischer-löschreport-2)

[5.11.1 Dictionary Objekte
[201](#dictionary-objekte-8)](#dictionary-objekte-8)

[5.11.1.1 Datenbanktabellen
[201](#datenbanktabellen-1)](#datenbanktabellen-1)

[5.11.1.2 Tabellentypen [201](#tabellentypen-7)](#tabellentypen-7)

[5.11.2 Klassenbibliothek
[201](#klassenbibliothek-2)](#klassenbibliothek-2)

[5.11.3 Interfaces [202](#interfaces-1)](#interfaces-1)

[5.11.4 Funktionsgruppe [202](#funktionsgruppe-1)](#funktionsgruppe-1)

[5.11.5 Nachrichtenklassen
[202](#nachrichtenklassen-7)](#nachrichtenklassen-7)

[5.12 GTB HTTP-Request [203](#gtb-http-request-2)](#gtb-http-request-2)

[5.12.1 Klassenbibliothek
[203](#klassenbibliothek-3)](#klassenbibliothek-3)

[5.12.2 Nachrichtenklassen
[203](#nachrichtenklassen-8)](#nachrichtenklassen-8)

[5.13 GTB Timer [204](#gtb-timer-2)](#gtb-timer-2)

[5.13.1 Klassenbibliothek
[204](#klassenbibliothek-4)](#klassenbibliothek-4)

[5.14 Generische Berechtigungsprüfung
[205](#generische-berechtigungsprüfung-2)](#generische-berechtigungsprüfung-2)

[5.14.1 Dictionary Objekte
[205](#dictionary-objekte-9)](#dictionary-objekte-9)

[5.14.1.1 Domänen [205](#domänen-3)](#domänen-3)

[5.14.1.2 Datenelemente [205](#datenelemente-5)](#datenelemente-5)

[5.14.2 Klassenbibliothek
[205](#klassenbibliothek-5)](#klassenbibliothek-5)

[5.14.3 Nachrichtenklassen
[206](#nachrichtenklassen-9)](#nachrichtenklassen-9)

[5.14.4 Berechtigungsobjekt
[206](#berechtigungsobjekt)](#berechtigungsobjekt)

[5.15 BAdI and Enhancement Framework
[207](#badi-and-enhancement-framework-2)](#badi-and-enhancement-framework-2)

[5.15.1 Dictionary Objekte
[207](#dictionary-objekte-10)](#dictionary-objekte-10)

[5.15.1.1 Datenbanktabellen
[207](#datenbanktabellen-2)](#datenbanktabellen-2)

[5.15.1.2 Strukturen [207](#strukturen-5)](#strukturen-5)

[5.15.1.3 Tabellentypen [208](#tabellentypen-8)](#tabellentypen-8)

[5.15.1.4 Suchhilfen [209](#suchhilfen-2)](#suchhilfen-2)

[5.15.2 Klassenbibliothek
[209](#klassenbibliothek-6)](#klassenbibliothek-6)

[5.15.3 Funktionsgruppen
[209](#funktionsgruppen-4)](#funktionsgruppen-4)

[5.15.4 Reports [210](#reports-1)](#reports-1)

[5.15.5 Transaktionscodes
[210](#transaktionscodes-2)](#transaktionscodes-2)

[5.15.6 Nachrichtenklassen
[210](#nachrichtenklassen-10)](#nachrichtenklassen-10)

[5.16 GTB System [211](#gtb-system-2)](#gtb-system-2)

[5.16.1 Klassenbibliothek
[211](#klassenbibliothek-7)](#klassenbibliothek-7)

[5.16.2 Nachrichtenklassen
[211](#nachrichtenklassen-11)](#nachrichtenklassen-11)

[5.17 GTB - Kleine Werkzeuge
[212](#gtb---kleine-werkzeuge-2)](#gtb---kleine-werkzeuge-2)

[5.17.1 Datenelemente [212](#datenelemente-6)](#datenelemente-6)

[5.17.2 Strukturen [212](#strukturen-6)](#strukturen-6)

[5.17.3 Tabellentypen [212](#tabellentypen-9)](#tabellentypen-9)

[5.17.4 Klassenbibliothek
[213](#klassenbibliothek-8)](#klassenbibliothek-8)

[5.17.5 Nachrichtenklassen
[213](#nachrichtenklassen-12)](#nachrichtenklassen-12)

[5.18 Easy Mapper [214](#easy-mapper-2)](#easy-mapper-2)

[5.18.1 Dictionary Objekte
[214](#dictionary-objekte-11)](#dictionary-objekte-11)

[5.18.1.1 Tabellentypen [214](#tabellentypen-10)](#tabellentypen-10)

[5.18.2 Klassenbibliothek
[214](#klassenbibliothek-9)](#klassenbibliothek-9)

[5.18.3 Nachrichtenklassen
[215](#nachrichtenklassen-13)](#nachrichtenklassen-13)

[5.19 RFC Hilfsklasse [216](#rfc-hilfsklasse-2)](#rfc-hilfsklasse-2)

[5.19.1 Klassenbibliothek
[216](#klassenbibliothek-10)](#klassenbibliothek-10)

[5.19.2 Nachrichtenklassen
[216](#nachrichtenklassen-14)](#nachrichtenklassen-14)

[[6]{.mark} [Kundeneigene Anpassungen]{.mark}
[217](#kundeneigene-anpassungen)](#kundeneigene-anpassungen)

[6.1 Key Values -- Schlüsselwerte
[217](#key-values-schlüsselwerte)](#key-values-schlüsselwerte)

[6.2 CFG -- Konfigurations-Framework
[218](#cfg-konfigurations-framework-3)](#cfg-konfigurations-framework-3)

[6.3 SWT -- Schalter-Framework
[219](#swt-schalter-framework-3)](#swt-schalter-framework-3)

[6.4 SDT Adjustment Report
[220](#sdt-adjustment-report-3)](#sdt-adjustment-report-3)

[6.5 Wizard [221](#wizard-3)](#wizard-3)

[6.5.1 Interface-Implementierung
[221](#interface-implementierung)](#interface-implementierung)

[6.6 Generische Tabellenleseklasse
[226](#generische-tabellenleseklasse-3)](#generische-tabellenleseklasse-3)

[6.7 Transport Order Tool
[227](#transport-order-tool-3)](#transport-order-tool-3)

[6.7.1 Klassen ableiten [227](#klassen-ableiten)](#klassen-ableiten)

[6.8 Generische Suchhilfe
[228](#generische-suchhilfe-3)](#generische-suchhilfe-3)

[6.9 CSV-Handling [229](#csv-handling-3)](#csv-handling-3)

[6.9.1 Klassen ableiten [229](#klassen-ableiten-1)](#klassen-ableiten-1)

[6.9.2 Interface-Implementierungen
[229](#interface-implementierungen)](#interface-implementierungen)

[6.9.3 Konfigurationsmöglichkeiten
[229](#konfigurationsmöglichkeiten)](#konfigurationsmöglichkeiten)

[6.10 Access Control Definition -- Zugriffsfolgen
[230](#access-control-definition-zugriffsfolgen)](#access-control-definition-zugriffsfolgen)

[6.11 Generischer Löschreport
[231](#generischer-löschreport-3)](#generischer-löschreport-3)

[6.11.1 Spezielle Felder hinzufügen
[231](#spezielle-felder-hinzufügen)](#spezielle-felder-hinzufügen)

[6.11.2 Klassen ableiten
[231](#klassen-ableiten-2)](#klassen-ableiten-2)

[6.11.3 Interface-Implementierung
[231](#interface-implementierung-1)](#interface-implementierung-1)

[6.11.4 Konfigurationsmöglichkeiten
[233](#konfigurationsmöglichkeiten-1)](#konfigurationsmöglichkeiten-1)

[6.12 GTB HTTP-Request [235](#gtb-http-request-3)](#gtb-http-request-3)

[6.13 GTB Timer [236](#gtb-timer-3)](#gtb-timer-3)

[6.13.1 Klasse ableiten [236](#klasse-ableiten)](#klasse-ableiten)

[6.14 Generische Berechtigungsprüfung
[237](#generische-berechtigungsprüfung-3)](#generische-berechtigungsprüfung-3)

[6.14.1 Klassen ableiten
[237](#klassen-ableiten-3)](#klassen-ableiten-3)

[6.15 BAdI and Enhancement Framework
[238](#badi-and-enhancement-framework-3)](#badi-and-enhancement-framework-3)

[6.15.1 Felder hinzufügen [238](#felder-hinzufügen)](#felder-hinzufügen)

[6.15.2 Klassen ableiten
[238](#klassen-ableiten-4)](#klassen-ableiten-4)

[6.15.3 Interfaces [240](#interfaces-2)](#interfaces-2)

[6.15.4 Konfigurationsmöglichkeiten
[240](#konfigurationsmöglichkeiten-2)](#konfigurationsmöglichkeiten-2)

[6.16 GTB System [241](#gtb-system-3)](#gtb-system-3)

[6.16.1 Klassen ableiten
[241](#klassen-ableiten-5)](#klassen-ableiten-5)

[6.17 GTB - Kleine Werkzeuge
[242](#gtb---kleine-werkzeuge-3)](#gtb---kleine-werkzeuge-3)

[6.17.1 Klassen ableiten
[242](#klassen-ableiten-6)](#klassen-ableiten-6)

[6.18 Easy Mapper [243](#easy-mapper-3)](#easy-mapper-3)

[6.19 RFC Hilfsklasse [244](#rfc-hilfsklasse-3)](#rfc-hilfsklasse-3)

[[7]{.mark} [Einrichtung im Zielsystem]{.mark}
[245](#einrichtung-im-zielsystem)](#einrichtung-im-zielsystem)

[7.1 Key Values -- Schlüsselwerte
[245](#key-values-schlüsselwerte-1)](#key-values-schlüsselwerte-1)

[7.2 CFG -- Konfigurations-Framework
[246](#cfg-konfigurations-framework-4)](#cfg-konfigurations-framework-4)

[7.3 SWT -- Schalter-Framework
[247](#swt-schalter-framework-4)](#swt-schalter-framework-4)

[7.4 SDT Adjustment Report
[248](#sdt-adjustment-report-4)](#sdt-adjustment-report-4)

[7.5 Wizard [249](#wizard-4)](#wizard-4)

[7.6 Generische Tabellenleseklasse
[250](#generische-tabellenleseklasse-4)](#generische-tabellenleseklasse-4)

[7.7 Transport Order Tool
[251](#transport-order-tool-4)](#transport-order-tool-4)

[7.8 Generische Suchhilfe
[252](#generische-suchhilfe-4)](#generische-suchhilfe-4)

[7.9 CSV-Handling [253](#csv-handling-4)](#csv-handling-4)

[7.10 Access Control Definition -- Zugriffsfolgen
[254](#access-control-definition-zugriffsfolgen-1)](#access-control-definition-zugriffsfolgen-1)

[7.11 Generischer Löschreport
[255](#generischer-löschreport-4)](#generischer-löschreport-4)

[7.12 GTB HTTP-Request [256](#gtb-http-request-4)](#gtb-http-request-4)

[7.13 GTB Timer [257](#gtb-timer-4)](#gtb-timer-4)

[7.14 Generische Berechtigungsprüfung
[258](#generische-berechtigungsprüfung-4)](#generische-berechtigungsprüfung-4)

[7.15 BAdI and Enhancement Framework
[259](#badi-and-enhancement-framework-4)](#badi-and-enhancement-framework-4)

[7.16 GTB System [260](#gtb-system-4)](#gtb-system-4)

[7.17 GTB - Kleine Werkzeuge
[261](#gtb---kleine-werkzeuge-4)](#gtb---kleine-werkzeuge-4)

[7.18 Easy Mapper [262](#easy-mapper-4)](#easy-mapper-4)

[7.19 RFC Hilfsklasse [263](#rfc-hilfsklasse-4)](#rfc-hilfsklasse-4)

[[8]{.mark} [Sonstiges]{.mark} [264](#sonstiges)](#sonstiges)

[8.1 Key Values -- Schlüsselwerte
[264](#key-values-schlüsselwerte-2)](#key-values-schlüsselwerte-2)

[8.2 CFG -- Konfigurations-Framework
[265](#cfg-konfigurations-framework-5)](#cfg-konfigurations-framework-5)

[8.2.1 Pflegereport [265](#pflegereport)](#pflegereport)

[8.2.2 Zugriff auf Konstanten- und Parameterwerte
[267](#zugriff-auf-konstanten--und-parameterwerte)](#zugriff-auf-konstanten--und-parameterwerte)

[8.2.2.1 Instanz der Klasse /PRIS/MAIN_CL_CFG erzeugen
[267](#instanz-der-klasse-prismain_cl_cfg-erzeugen)](#instanz-der-klasse-prismain_cl_cfg-erzeugen)

[8.2.2.2 Instanz initialisieren
[271](#instanz-initialisieren)](#instanz-initialisieren)

[8.2.2.3 Einzelwert holen [273](#einzelwert-holen)](#einzelwert-holen)

[8.2.2.4 Wertegruppe holen
[274](#wertegruppe-holen)](#wertegruppe-holen)

[8.2.2.5 Alle Werte holen [275](#alle-werte-holen)](#alle-werte-holen)

[8.3 SWT -- Schalter-Framework
[276](#swt-schalter-framework-5)](#swt-schalter-framework-5)

[8.3.1 Zugriff auf die Erweiterungskonfiguration
[276](#zugriff-auf-die-erweiterungskonfiguration)](#zugriff-auf-die-erweiterungskonfiguration)

[8.3.1.1 Instanz der Klasse /PRIS/MAIN_CL_SWT erzeugen
[276](#instanz-der-klasse-prismain_cl_swt-erzeugen)](#instanz-der-klasse-prismain_cl_swt-erzeugen)

[8.3.1.2 Erweiterung prüfen
[278](#erweiterung-prüfen)](#erweiterung-prüfen)

[8.3.1.3 Beispiel-Coding [281](#beispiel-coding)](#beispiel-coding)

[8.4 SDT Adjustment Report
[283](#sdt-adjustment-report-5)](#sdt-adjustment-report-5)

[8.5 Wizard [284](#wizard-5)](#wizard-5)

[8.6 Generische Tabellenleseklasse
[285](#generische-tabellenleseklasse-5)](#generische-tabellenleseklasse-5)

[8.6.1 Kopiervorlage zum Lesen mehrerer Datensätze
[285](#kopiervorlage-zum-lesen-mehrerer-datensätze)](#kopiervorlage-zum-lesen-mehrerer-datensätze)

[8.6.2 Kopiervorlage zum Lesen einzelner Zeilen
[286](#kopiervorlage-zum-lesen-einzelner-zeilen)](#kopiervorlage-zum-lesen-einzelner-zeilen)

[8.7 Transport Order Tool
[287](#transport-order-tool-5)](#transport-order-tool-5)

[8.8 Generische Suchhilfe
[288](#generische-suchhilfe-5)](#generische-suchhilfe-5)

[8.9 CSV-Handling [289](#csv-handling-5)](#csv-handling-5)

[8.10 Access Control Definition -- Zugriffsfolge
[290](#access-control-definition-zugriffsfolge)](#access-control-definition-zugriffsfolge)

[8.10.1 Instanziierung [290](#instanziierung-3)](#instanziierung-3)

[8.10.2 Datenermittlung [291](#datenermittlung)](#datenermittlung)

[8.11 Generischer Löschreport
[292](#generischer-löschreport-5)](#generischer-löschreport-5)

[8.12 GTB HTTP-Request [293](#gtb-http-request-5)](#gtb-http-request-5)

[8.13 GTB Timer [294](#gtb-timer-5)](#gtb-timer-5)

[8.14 Generische Berechtigungsprüfung
[295](#generische-berechtigungsprüfung-5)](#generische-berechtigungsprüfung-5)

[8.15 BAdI and Enhancement Framework
[296](#badi-and-enhancement-framework-5)](#badi-and-enhancement-framework-5)

[8.16 GTB System [297](#gtb-system-5)](#gtb-system-5)

[8.17 Kleine Werkzeuge [298](#kleine-werkzeuge)](#kleine-werkzeuge)

[8.18 Easy Mapper [299](#easy-mapper-5)](#easy-mapper-5)

[8.19 RFC Hilfsklasse [300](#rfc-hilfsklasse-5)](#rfc-hilfsklasse-5)

# Vorwort

Die prismat-Rakete umfasst Basis-Lösungen und Plus-Lösungen.

Basis-Lösungen können als Grundlage für kundenspezifische Entwicklungen
und Plus-Lösungen der Rakete dienen und fungieren oft als
Projektbeschleuniger.

Bei den Basis-Lösungen wird zwischen technischen und prozessualen
Lösungen unterschieden.

Die prozessualen Basis-Lösungen dienen in der Regel als Grundlage für
Business Prozesse.

Die technischen Basis-Lösungen sind dabei das Fundament, auf dem sowohl
prozessuale Basis-Lösungen also auch Plus-Lösungen aufsetzen.

In diesem Dokument werden die modulübergreifenden technischen
Basis-Lösungen beschrieben.

# Rahmenbedingungen

Es gelten die folgenden Systemanforderungen:

- SAP-Systemarchitektur:

  - S/4 EWM embedded / dezentral

    - S/4HANA 2023 FPS02

Eine Installation auf älteren Releases bzw. ECC- oder SCM-Systemen ist
grundsätzlich nicht vorgesehen.

Zusätzlich werden die folgenden prismat-Lösungen vorausgesetzt:

- Abhängigkeiten:

  - Keine

Sofern die Bereitstellung der technischen Systemvoraussetzungen nicht
möglich ist, kann prismat eine Handlungsempfehlung bzgl. möglicher
Alternativen liefern.

# Definition

## Key Values - Schlüsselwerte

### Kontext

In diesem Kapitel wird der Umgang mit der Lösung für unterschiedliche
Objekte als höchste Hierarchiestufe, Key Values, beschrieben.

Mit „Key Values" ist es möglich, für diverse Schlüsselarten
Schlüsselwerte zu definieren.

### Prozessbeschreibung

Es ist eine Lösung geschaffen worden, um unterschiedliche Objekte als
höchste Hierarchiestufe hinterlegen zu können.

Dies soll als Grundlage für andere Lösungen dienen, damit diese sowohl
in reinen EWM-Umgebungen sowie auch in anderen Systemen wie z.B. ERP
oder S/4HANA eingesetzt werden können.

Eine Zugriffsklasse wird nicht benötigt.

### Ablaufbeschreibung

Zur Definition von Schlüsselwerten ist eine eigene Customizing-Tabelle
angelegt worden.

Diese Tabelle hat folgenden Aufbau:

- Schlüsselart

- Schlüsselwert

- Benutzername der letzten Änderung

- Datum der letzten Änderung

- Uhrzeit der letzten Änderung

Für die erlaubten Schlüsselarten existiert eine Eingabehilfe. Folgende
Schlüsselarten sind in der Standardauslieferung wählbar:

  ---------------------------------------------------------------------
  Schlüsselart                       Schlüsselwert
  ---------------------------------- ----------------------------------
  A                                  EWM Lagernummer

  B                                  ERP Lagernummer

  C                                  Benutzergruppe

  D                                  Buchungskreis

  E                                  Lagerort

  F                                  Produktionsversorgungsbereich

  G                                  Verkaufsorganisation

  H                                  Versandstelle

  I                                  Vertriebsweg

  J                                  Werk
  ---------------------------------------------------------------------

### Konfiguration

Die Definition von Schlüsselwerten sollte nur von dem Projektleiter, den
Entwicklungskoordinatoren oder den Mitarbeitern mit dem entsprechenden
technischen Hintergrund vorgenommen werden.

Sollten Sie keine dieser Positionen innehaben und Ihnen fehlen
Schlüsselwerte für Ihre Entwicklung, so wenden Sie sich bitte an Ihren
Hauptansprechpartner.

Andernfalls nehmen Sie die entsprechenden Einstellungen bitte, wie in
diesem Kapitel beschrieben vor.

#### Schlüsselarten

Die Schlüsselart beschreibt, um welches Element der
SAP-Organisationsstruktur es sich handelt.

„Key Values" umfasst in der Standardauslieferung die folgenden
Schlüsselarten:

  ---------------------------------------------------------------------
  Schlüsselart                       Schlüsselwert
  ---------------------------------- ----------------------------------
  A                                  EWM-Lagernummer

  B                                  ERP-Lagernummer

  C                                  Benutzergruppe

  D                                  Buchungskreis

  E                                  Lagerort

  F                                  Produktionsversorgungsbereich

  G                                  Verkaufsorganisation

  H                                  Versandstelle

  I                                  Vertriebsweg

  J                                  Werk
  ---------------------------------------------------------------------

Sollten die vorhandenen Schlüsselarten für Ihr Projekt nicht ausreichen,
so erweitern sie die Domäne /PRIS/MAIN_DO_KEY_TYPE bitte um einen
Festwert-Append mit den benötigten Werten.

#### Schlüsselwerte einstellen

Schlüsselwerte werden immer zu einer Schlüsselart hinterlegt. Ist die
Schlüsselart beispielsweise „EWM-Lagernummer", beschreibt der
Schlüsselwert eine konkrete Lagernummer, z.B. „RL01".

Schlüsselwerte werden über die Pflege-View /PRIS/KEY_VALUEV eingestellt.
Ein direkter Einstieg in die Pflege dieser Tabelle kann über die
Transaktion /PRIS/KEY_VALUE erfolgen.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image1.png){width="5.901388888888889in"
height="2.2930555555555556in"}

Bitte bedenken Sie dabei, dass Leerwerte, falls diese erlaubt sein
sollen, auch an dieser Stelle hinterlegt werden müssen.

Beachten Sie bitte, dass es sich bei der Tabelle hinter der Pflege-View
um eine mandantenspezifische Customizing-Tabelle handelt und somit zum
Ändern der Daten ein Customizing-Transport benötigt wird.

#### Zugriff auf Schlüsselwerte

Für den programmseitigen Zugriff auf Schlüsselwerte existiert das
Interface /PRIS/MAIN_IF_KEY_VALUES_C, welches für die Schlüsselarten des
Lieferumfangs Konstanten zur Verfügung stellt.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte Beschreibung](media/image2.png){width="5.901388888888889in"
height="2.426388888888889in"}

Falls projektspezifische Schlüsselarten definiert wurden, legen Sie
bitte ein neues Interface mit diesen Schlüsselarten als Konstanten an
und integrieren Sie in dieses das Interface /PRIS/MAIN_IF_KEY_VALUES_C,
damit in Ihrem Interface Konstanten zu allen Schlüsselarten zur
Verfügung stehen.

## CFG -- Konfigurations-Framework

### Kontext

In diesem Kapitel wird der Umgang mit der einheitlichen Lösung zur
Verwaltung von Parameter und Konstanten, CFG, beschrieben.

CFG entkoppelt Konstanten und Entwicklungsobjekte (z.B. Typgruppen oder
Interfaces) und vermindert somit die Gefahr von Konflikten im
Transportwesen.

Über die Zugriffsklasse, welche in den nachfolgenden Kapiteln noch
genauer beschrieben wird, ist dabei ein einfacher und einheitlicher
Zugriff auf Konstanten- und Parameterwerte möglich.

### Prozessbeschreibung

Mit CFG ist eine Lösung geschaffen worden, um Konstanten und
Entwicklungsobjekte (z.B. Typgruppen oder Interfaces) zu entkoppeln und
somit die Gefahr von Konflikten im Transportwesen zu vermindern.

Des Weiteren können auch allgemeine Parameter über diese Lösung
verwaltet werden.

Über eine Klasse ist ein einfacher und einheitlicher Zugriff auf diese
Konstanten- und Parameterwerte ermöglicht worden.

Seit Version 1.2 (Meilenstein 2022) besteht die Möglichkeit für
Parameter- und Konstanten-Werte Formatierungsinformationen zu
hinterlegen, welche beim Erfassen der Werte automatisch angewendet
werden. Dies dient dazu individuelle Konvertierungsschritte im Coding zu
reduzieren.

### Ablaufbeschreibung

Projektspezifische Entwicklungen sollen oftmals durch die Option der
Parametrisierung flexibel gehalten werden. Diese Lösung stellt ein
Framework zur Verfügung, mit dem Konstanten, Konstantengruppen,
Parameter und Parametergruppen angelegt und mit Werten befüllt werden
können.

Da die Lösung sowohl in reinen EWM-Umgebungen als auch in anderen
Systemen wie z.B. ERP oder S/4 eingesetzt werden kann, ist es möglich,
unterschiedliche Objekte als höchste Hierarchiestufe zu hinterlegen.
Wenn z.B. im EWM-Umfeld Konstanten und Parameter für eine bestimmte
Lagernummer gelten sollen, wäre als Schlüsselart „EWM-Lagernummer" und
als Schlüsselwert beispielsweise „0001" zu wählen.

Hierzu wird die Schlüsselwert-Tabelle aus „prismat/BASE_EWM-001a --
prismat/TECH -- Control Framework -- Key Values" verwendet. Die Details
der Konfiguration ist in einem separaten Dokument beschrieben und nicht
Gegenstand dieses Dokuments.

Zur Verwaltung von Konstanten und Parametern sind folgende Schritte
nötig:

1.  Ein neuer Parameter oder eine neue Konstante wird definiert.

2.  Der neue Parameter oder die neue Konstante wird dem Programm
    zugeordnet, in dem er/sie verwendet werden soll.

3.  Dem neuen Parameter oder der neuen Konstante werden Werte oder
    Wertegruppen zugeordnet.

Anschließend können projektspezifisch entwickelte Klassen anhand des
Konstanten- bzw. Parameternamens auf die hinterlegten Werte oder
Wertegruppen zugreifen.

Diese Klasse kann zu Schlüsselart, Schlüsselwert und Programmobjekt
automatisch die Werte aller zugewiesenen Konstanten und Parameter
einlesen und diese dem Aufrufer über einfach zu verstehende Methoden zur
Verfügung stellen.

### Konfiguration

#### Grundlegende Einstellungen

Alle Definitionen, Zuweisungen und Werte, welche über die Lösung CFG
hinterlegt werden können, setzen voraus, dass Schlüsselarten und
Schlüsselwerte definiert und gepflegt sind.

Bei einer Schlüsselart handelt es sich um die Hierarchieobjekte der
Organisationsstruktur, z.B die EWM-Lagernummer.

Der Schlüsselwert beschreibt darauf aufbauend ein konkretes Objekt, z.B.
„0001".

Die Schlüsselarten und Schlüsselwerte müssen projektspezifisch definiert
werden.

Zur Pflege der definierten Schlüsselarten und -werte, nehmen Sie die
Einstellungen bitte, wie in dem Benutzerhandbuch zu „prismat/BASE001a --
prismat/TECH -- Control Framework -- Key Values" beschrieben, vor.

#### Daten pflegen

Ziel ist es, für projektspezifische Entwicklungen Konstanten und
Parameter hinterlegen zu können. Als Sammelbegriff für „Konstanten und
Parameter" wird in der Lösung der Begriff „Attribut" verwendet.

Wie beschrieben sind zur Pflege die folgenden Schritte nötig, die
anschließend detailliert beschrieben werden:

1.  Definition von Attributen\
    Hier wird auch festgelegt, ob es sich um eine Konstante oder einen
    Parameter handeln soll und ob Einzelwerte oder Wertegruppen
    hinterlegt werden können.

2.  Zuordnung von Attributen zu Programmobjekten\
    Hierüber kann zum einen nachvollzogen werden, welche Programmobjekte
    ein Attribut verwenden und zum anderen ein vereinfachter Zugriff im
    Programm erfolgen.

3.  Werte zu Attributen hinterlegen

##### Definition von Attributen

Zum Definieren einer Konstante oder eines Parameters starten Sie bitte
die Transaktion /PRIS/CFG_SAD

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
mandanten-übergreifende Customizing-Tabelle ist und zum Ändern der Daten
somit ein Workbench-Transportauftrag benötigt wird.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image3.png){width="5.901388888888889in"
height="1.3402777777777777in"}

**[Hinweis:]{.underline}**

Die Definition von Parametern und Konstanten sollten von dem jeweiligen
Entwickler vorgenommen werden.

**[Hinweis 2:]{.underline}**

Wenn die Formatierungsinformationen (Groß-/Kleinschreibung, Länge,
Ausrichtung oder Füllzeichen) von bestehenden Attributen geändert wurden
wird eine Aktualisierung der bestehenden Werte automatisch im
Hintergrund angestoßen. Diese Aktualisierungen sind jedoch System
spezifisch. Daher sollte nach dem Transport von Änderungen an den
Formatierungsinformationen die Aktualisierung der Werte, in dem
jeweiligen System, explizit über die Transaktion /PRIS/CFG_FORMAT
angestoßen werden.

Die folgenden Spalten müssen pro Attribut befüllt werden:

+---------------------------+----------------------------------------+
| Spalte                    | Beschreibung                           |
+:=========================:+========================================+
| Art                       | Über die Spalte Attributart wird       |
|                           | angegeben, ob es ich bei dem Attribut  |
|                           | um eine Konstante oder einen Parameter |
|                           | handelt.                               |
+---------------------------+----------------------------------------+
| Name von Konstante /      | In dieser Spalte wird der Name des     |
| Parameter                 | neuen Attributs hinterlegt.            |
|                           |                                        |
|                           | Dieser Name ist                        |
|                           | attributarten-übergreifend eindeutig   |
|                           | zu wählen.                             |
|                           |                                        |
|                           | Machen Sie über ein Präfix kenntlich,  |
|                           | ob es sich um eine Konstante oder      |
|                           | einen Parameter handelt.               |
|                           |                                        |
|                           | Nehmen Sie bitte auch den              |
|                           | beschreibenden Teil von dem Namen des  |
|                           | Datenelements, auf den sich das        |
|                           | Attribut bezieht (z.B. LGNUM, LGPLA)   |
|                           | in den Namen auf.                      |
|                           |                                        |
|                           | Vermeiden Sie bitte soweit möglich     |
|                           | PSE-spezifische Bezeichnungen.         |
+---------------------------+----------------------------------------+
| Typ                       | Über diese Spalte wird gesteuert, ob   |
|                           | für das Attribut Einzelwerte oder      |
|                           | Wertegruppen hinterlegt werden.        |
+---------------------------+----------------------------------------+
| Kleinbuchstaben           | Über diese Spalte wird gesteuert, ob   |
|                           | auch Kleinbuchstaben im Wert erlaubt   |
|                           | sind.                                  |
+---------------------------+----------------------------------------+
| Zahl der Stellen          | Gibt an wie viele Zeichen der Wert     |
|                           | umfassen soll.                         |
|                           |                                        |
|                           | Der Wert der Spalte kann zwischen 1    |
|                           | und 45 liegen.                         |
|                           |                                        |
|                           | Wird kein Wert vorgegeben sind keine   |
|                           | rechtsbündigen Werte möglich.          |
+---------------------------+----------------------------------------+
| Rechtsbündig              | Über diese Spalte kann gesteuert       |
|                           | werden, ob der Wert des Attributs      |
|                           | rechtsbündig ausgerichtet werden soll. |
|                           |                                        |
|                           | Diese Option kann nur verwendet        |
|                           | werden, wenn die Spalte „Zahl der      |
|                           | Stellen" einen Wert enthält.           |
+---------------------------+----------------------------------------+
| Füllzeich.                | Über diese Spalte kann ein Füllzeichen |
|                           | hinterlegt werden.                     |
|                           |                                        |
|                           | Die Spalte wird nur ausgewertet, wenn  |
|                           | die Spalte „Zahl der Stellen" einen    |
|                           | Wert enthält.                          |
|                           |                                        |
|                           | Bleibt diese Spalte leer werden        |
|                           | Leerzeichen als Füllzeichen verwendet. |
+---------------------------+----------------------------------------+
| Text                      | Beschreibung des Attributs (in         |
|                           | Anmeldesprache).                       |
+---------------------------+----------------------------------------+

##### Zuordnung von Attributen zu Programmobjekten

Die Zuordnung von Attributen zu Programmobjekten dient der besseren
Nachvollziehbarkeit, welches Programm welche Attribute verwendet.
Darüber hinaus wird der Zugriff aus dem Programm heraus vereinfacht. Aus
diesem Grund ist die Pflege dieser Tabelle zwingend.

Zum Zuordnen einer Konstante oder eines Parameters starten Sie bitte die
Transaktion /PRIS/CFG_SAS.

Es ist möglich, mit demselben Eintrag einem Programm sowohl eine
Konstante als auch einen Parameter zuzuordnen. Somit kann die Anzahl der
benötigten Einträge kleiner gehalten werden.

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
mandanten-übergreifende Customizing-Tabelle ist und zum Ändern der Daten
somit ein Workbench-Transportauftrag benötigt wird.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte Beschreibung](media/image4.png){width="5.901388888888889in"
height="2.377083333333333in"}

**[Hinweis:]{.underline}**\
Zuordnung von Parametern und Konstanten sollte von dem jeweiligen
Entwickler vorgenommen werden.

Die folgenden Spalten müssen befüllt werden:

  ---------------------------------------------------------------------
                Spalte               Beschreibung
  ---------------------------------- ----------------------------------
             Programmname            Programm, Report,
                                     Funktionsbaustein oder Klasse in
                                     dem bzw. in der die Konstanten
                                     und/oder Parameter verwendet
                                     werden sollen.

                 Nr.                 Laufnummer der Zuordnung zu einem
                                     Programm. Um demselben Programm
                                     mehrere Attribute zuzuordnen,
                                     erzeugen Sie mehrere Einträge mit
                                     unterschiedlichen Nummern.

          Name der Konstante         Der Name der Konstante die dem
                                     Programm zugeordnet werden soll.

         Name des Parameters         Der Name des Parameters der dem
                                     Programm zugeordnet werden soll.
  ---------------------------------------------------------------------

Pro Zuordnungseintrag können sowohl ein Konstanten- als auch ein
Parametername hinterlegt werden.

Bitte beachten Sie, dass pro Zuordnungseintrag der Name einer Konstante
oder der Name eines Parameters eingetragen werden muss.

##### Werte zu Konstanten hinterlegen

Je nach Attributtyp der entsprechenden Konstante müssen Sie einen
Einzelwert oder eine Wertegruppe zu der Konstanten hinterlegen.

###### Einzelwerte

Zur Pflege von Konstanten als Einzelwerte starten Sie bitte die
Transaktion /PRIS/CFG_SCS.

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
mandantenspezifische Customizing-Tabelle ist und zum Ändern der Daten
somit ein Customizing-Transportauftrag benötigt wird.

![Ein Bild, das Text, Zahl, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image5.png){width="5.0in"
height="1.7510050306211724in"}

Die folgenden Spalten müssen befüllt werden:

+-----------------------+---------------------------------------------+
| Spalte                | Beschreibung                                |
+:=====================:+=============================================+
| Key-Art               | Die Schlüsselart gibt an auf welche         |
|                       | (oberste) Organisationseinheit sich der     |
|                       | Schlüsselwert bezieht.                      |
|                       |                                             |
|                       | Im EWM sollte immer die Schlüsselart A      |
|                       | (EWM-Lagernummer) verwendet werden.         |
+-----------------------+---------------------------------------------+
| Schlüsselwert         | Der Schlüsselwert ist nur in Kombination    |
|                       | mit der Schlüsselart eindeutig.             |
|                       |                                             |
|                       | Bei Verwendung von Schlüsselart A           |
|                       | (EWM-Lagernummer) würde demnach in dem Feld |
|                       | als Schlüsselwert die entsprechende         |
|                       | Lagernummer eingetragen.                    |
+-----------------------+---------------------------------------------+
| Name einer Konstanten | In diesem Feld wird der Name der Konstante  |
|                       | eingetragen.                                |
+-----------------------+---------------------------------------------+
| Wert                  | In diesem Feld wird der Wert der Konstante  |
|                       | eingetragen.                                |
+-----------------------+---------------------------------------------+

###### Wertegruppen

Zur Pflege von Konstanten als Wertegruppe starten Sie bitte die
Transaktion /PRIS/CFG_SCG.

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
mandantenspezifische Customizing-Tabelle ist und zum Ändern der Daten
somit ein Customizing-Transportauftrag benötigt wird.

![Ein Bild, das Text, Schrift, Zahl, Software enthält. Automatisch
generierte Beschreibung](media/image6.png){width="5.901388888888889in"
height="1.7548611111111112in"}

Die folgenden Spalten müssen befüllt werden:

+----------------------------------+----------------------------------+
| Spalte                           | Beschreibung                     |
+:================================:+==================================+
| Key-Art                          | Key-Art gibt an auf welche       |
|                                  | (oberste) Organisationseinheit   |
|                                  | sich der Schlüsselwert bezieht.  |
|                                  |                                  |
|                                  | Im EWM sollte immer die          |
|                                  | Schlüsselart A (EWM-Lagernummer) |
|                                  | verwendet werden.                |
+----------------------------------+----------------------------------+
| Schlüsselwert                    | Der Schlüsselwert ist nur in     |
|                                  | Kombination mit der Schlüsselart |
|                                  | eindeutig.                       |
|                                  |                                  |
|                                  | Bei Verwendung von Schlüsselart  |
|                                  | A (EWM-Lagernummer) würde        |
|                                  | demnach in dem Feld als          |
|                                  | Schlüsselwert die entsprechende  |
|                                  | Lagernummer eingetragen.         |
+----------------------------------+----------------------------------+
| Name einer Konstanten            | In diesem Feld wird der Name der |
|                                  | Konstante eingetragen.           |
+----------------------------------+----------------------------------+
| Nr.                              | Laufnummer eines Wertes zu der   |
|                                  | Konstanten                       |
+----------------------------------+----------------------------------+
| Wert                             | In diesem Feld wird ein Wert der |
|                                  | Konstante eingetragen.           |
+----------------------------------+----------------------------------+

##### Werte zu Parametern hinterlegen

Je nach Attributtyp des entsprechenden Parameters müssen Sie einen
Einzelwert oder eine Wertegruppe zu dem Parameter hinterlegen.

###### Einzelwerte

Zur Pflege von Parametern als Einzelwerte Sie bitte die Transaktion
/PRIS/CFG_SPS.

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
Stammdatentabelle ist und zum Ändern der Daten somit kein
Transportauftrag benötigt wird.

![Ein Bild, das Text, Zahl, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image7.png){width="5.901388888888889in"
height="1.8659722222222221in"}

Die folgenden Spalten müssen befüllt werden:

+---------------------------+----------------------------------------+
| Spalte                    | Beschreibung                           |
+:=========================:+========================================+
| Key-Art                   | Die Key-Art gibt an auf welche         |
|                           | (oberste) Organisationseinheit sich    |
|                           | der Schlüsselwert bezieht.             |
|                           |                                        |
|                           | Im EWM sollte immer die Schlüsselart A |
|                           | (EWM-Lagernummer) verwendet werden.    |
+---------------------------+----------------------------------------+
| Schlüsselwert             | Der Schlüsselwert ist nur in           |
|                           | Kombination mit der Schlüsselart       |
|                           | eindeutig.                             |
|                           |                                        |
|                           | Bei Verwendung von Schlüsselart A      |
|                           | (EWM-Lagernummer) würde demnach in dem |
|                           | Feld als Schlüsselwert die             |
|                           | entsprechende Lagernummer eingetragen. |
+---------------------------+----------------------------------------+
| Name eines Parameters     | In diesem Feld wird der Name des       |
|                           | Parameters eingetragen.                |
+---------------------------+----------------------------------------+
| Wert                      | In diesem Feld wird der Wert des       |
|                           | Parameters eingetragen.                |
+---------------------------+----------------------------------------+

###### Wertegruppen

Zur Pflege von Parametern als Wertegruppe starten Sie die Transaktion
/PRIS/CFG_SPG.

Beachten Sie bitte, dass die Tabelle hinter der Transaktion eine
Stammdatentabelle ist. Zum Ändern der Daten ist somit kein
Transportauftrag notwendig.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image8.png){width="5.901388888888889in"
height="1.9215277777777777in"}

Die folgenden Spalten müssen befüllt werden:

+----------------------------------+----------------------------------+
| Spalte                           | Beschreibung                     |
+:================================:+==================================+
| Key-Art                          | Die Key-Art gibt an auf welche   |
|                                  | (oberste) Organisationseinheit   |
|                                  | sich der Schlüsselwert bezieht.  |
|                                  |                                  |
|                                  | Im EWM sollte immer die          |
|                                  | Schlüsselart A (EWM-Lagernummer) |
|                                  | verwendet werden.                |
+----------------------------------+----------------------------------+
| Schlüsselwert                    | Der Schlüsselwert ist nur in     |
|                                  | Kombination mit der Schlüsselart |
|                                  | eindeutig.                       |
|                                  |                                  |
|                                  | Bei Verwendung von Schlüsselart  |
|                                  | A (EWM-Lagernummer) würde        |
|                                  | demnach in dem Feld als          |
|                                  | Schlüsselwert die entsprechende  |
|                                  | Lagernummer eingetragen.         |
+----------------------------------+----------------------------------+
| Name eines Parameters            | In diesem Feld wird der Name des |
|                                  | Parameters eingetragen.          |
+----------------------------------+----------------------------------+
| Nr.                              | Laufnummer eines Wertes zu dem   |
|                                  | Parameter.                       |
+----------------------------------+----------------------------------+
| Wert                             | In diesem Feld wird ein Wert des |
|                                  | Parameters eingetragen.          |
+----------------------------------+----------------------------------+

## SWT -- Schalter-Framework

### Kontext

In diesem Kapitel wird der Umgang mit der Schalterlösung für
Erweiterungen, SWT, beschrieben.

Mit „SWT" lassen sich einzelne Erweiterungen für einen Prozess bündeln
und komplett sowie einzeln verwalten.

Die nachfolgenden Kapitel beschreiben die bestehenden Abhängigkeiten,
Konfigurationsschritte und die programmseitige Verwendung der
Schalterlösung.

### Prozessbeschreibung

Es ist eine Lösung geschaffen worden, mit der schnell und einfach
Erweiterungen, wie z.B. User-Exits, BAdIs und Enhancement Points,
aktiviert und deaktiviert werden können.

Dies ist direkt in dem jeweiligen System möglich.

Über eine Klasse ist ein einfacher und einheitlicher Zugriff auf diese
Schalter möglich.

### Ablaufbeschreibung

Zur Verwaltung der Erweiterungen sind mehrere Tabellen definiert.

Da die Lösung sowohl in reinen EWM-Umgebungen, sowie auch in anderen
Systemen wie z.B. ERP oder S/4HANA eingesetzt werden können soll, ist es
möglich, unterschiedliche Objekte als höchste Hierarchiestufe zu
hinterlegen.

Dazu wird die Schlüsselwert-Tabelle aus der Lösung
„prismat/BASE_EWM-001a --prismat/TECH -- Control Framework -- Key
Values" verwendet.

Diese Tabelle hat den folgenden Aufbau:

- Schlüsselart

- Schlüsselwert

- Benutzername der letzten Änderung

- Datum der letzten Änderung

- Uhrzeit der letzten Änderung

Zur Definition von übergeordneten Erweiterungen existiert eine Tabelle
mit dem folgenden Aufbau:

- Name der übergeordneten Erweiterung

- Benutzername der letzten Änderung

- Datum der letzten Änderung

- Uhrzeit der letzten Änderung

Zur Definition von untergeordneten Erweiterungen existiert eine Tabelle
mit dem folgenden Aufbau:

- Name der übergeordneten Erweiterung

- Name der untergeordneten Erweiterung

- Benutzername der letzten Änderung

- Datum der letzten Änderung

- Uhrzeit der letzten Änderung

Zur Konfiguration von Erweiterungen existiert eine Tabelle mit dem
folgenden Aufbau:

- Mandant

- Schlüsselart

- Schlüsselwert

- Name der übergeordneten Erweiterung

- Name der untergeordneten Erweiterung

- Inaktivkennzeichen

- Benutzername der letzten Änderung

- Datum der letzten Änderung

- Uhrzeit der letzten Änderung

Auf die genannten Konfigurationsdaten kann über eine neue Klasse
zugegriffen werden.

### Konfiguration

#### Grundlegende Einstellungen

Die grundlegenden Einstellungen umfassen die möglichen Schlüsselwerte zu
den Schlüsselarten.

Diese Einstellungen sollten zu Projektbeginn von dem Projektleiter oder
dem Entwicklungskoordinator gepflegt werden.

Sollten Sie keine dieser Positionen innehaben und Ihnen fehlen
Schlüsselwerte zur Pflege von Konstanten- oder Parameterwerten, wenden
Sie sich bitte an Ihren Projektleiter oder ihrem
Entwicklungskoordinator.

Andernfalls nehmen Sie die entsprechenden Einstellungen bitte wie in dem
Benutzerhandbuch zu „prismat/BASE_EWM-001a -- prismat/TECH -- Control
Framework -- Key Values" beschrieben vor.

####  Daten pflegen

Zum Pflegen der Daten müssen Einträge in diversen Tabellen vorgenommen
werden.

Welche das sind, wie Sie am einfachsten darauf zugreifen können und
welche Art von Transportaufträgen benötigt werden, wird in diesem
Kapitel beschrieben.

##### Erweiterungen definieren

Zum Definieren der Erweiterungen rufen sie bitte den View-Cluster
/PRIS/SWT_DEFVC über die Transaktion /PRIS/SWT_DEF auf.

Da die Lösung „SWT" übergeordnete und untergeordnete Erweiterungen
vorsieht wird dieser Aufbau auch in der Dialogstruktur des View-Clusters
abgebildet.

![Ein Bild, das Text, Software, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image9.png){width="5.901388888888889in"
height="1.8208333333333333in"}

Die folgenden Spalten müssen pro übergeordneter Erweiterung befüllt
werden:

  ---------------------------------------------------------------------
  Spalte                             Beschreibung
  ---------------------------------- ----------------------------------
  Übergeordnete Erweiterung          In dieser Spalte wird der Name der
                                     übergeordneten Erweiterung
                                     hinterlegt.

  Text                               Beschreibung der Erweiterung (in
                                     Anmeldesprache).
  ---------------------------------------------------------------------

Ist die übergeordnete Erweiterung gepflegt, kann nach Markieren der
Zeile über einen Doppelklick auf den Knoten „Untergeordnete
Erweiterung", in der Dialogstruktur, in die Ansicht der untergeordneten
Erweiterungen abgesprungen werden.

![Ein Bild, das Text, Screenshot, Software, Schrift enthält. Automatisch
generierte Beschreibung](media/image10.png){width="5.901388888888889in"
height="1.6118055555555555in"}

Die folgenden Spalten müssen pro untergeordneter Erweiterung befüllt
werden:

  ---------------------------------------------------------------------
  Spalte                             Beschreibung
  ---------------------------------- ----------------------------------
  Untergeordneten Erweiterung        In dieser Spalte wird der Name der
                                     untergeordneten Erweiterung
                                     hinterlegt

  Text                               Beschreibung der Erweiterung (in
                                     Anmeldesprache)
  ---------------------------------------------------------------------

Beachten Sie bitte, dass es sich bei den Tabellen zur Definition von
Erweiterungen um mandantenübergreifende Customizing-Tabellen handelt und
daher zum Ändern der Daten ein Workbench-Transportauftrag benötigt wird.

**[Hinweis:]{.underline}**\
Die Definition von übergeordneten und untergeordneten Erweiterungen
sollten von dem jeweiligen Entwickler vorgenommen werden.

##### Erweiterungen konfigurieren

Zum Konfigurieren der Erweiterungen rufen sie bitte den View-Cluster
/PRIS/SWT_CONFVC über die Transaktion /PRIS/SWT_CONF auf.

Da SWT übergeordnete und untergeordnete Erweiterungen vorsieht wird
dieser Aufbau auch in der Dialogstruktur des View-Clusters abgebildet.

![Ein Bild, das Text, Software, Zahl, Webseite enthält. Automatisch
generierte Beschreibung](media/image11.png){width="5.901388888888889in"
height="2.1444444444444444in"}

Die folgenden Spalten müssen pro übergeordneter Erweiterung befüllt
werden:

+----------------------------------+----------------------------------+
| Spalte                           | Beschreibung                     |
+==================================+==================================+
| Key-Art                          | Die Key-Art gibt an auf welche   |
|                                  | (oberste) Organisationseinheit   |
|                                  | sich der Schlüsselwert bezieht.  |
|                                  |                                  |
|                                  | Im EWM sollte immer die          |
|                                  | Schlüsselart A (EWM-Lagernummer) |
|                                  | verwendet werden.                |
+----------------------------------+----------------------------------+
| Schlüsselwert                    | Der Schlüsselwert ist nur in     |
|                                  | Kombination mit der Schlüsselart |
|                                  | eindeutig.                       |
|                                  |                                  |
|                                  | Bei Verwendung von Schlüsselart  |
|                                  | A (EWM-Lagernummer) würde        |
|                                  | demnach in dem Feld als          |
|                                  | Schlüsselwert die entsprechende  |
|                                  | Lagernummer eingetragen.         |
+----------------------------------+----------------------------------+
| Übergeordnete Erweiterung        | In dieser Spalte wird der Name   |
|                                  | der übergeordneten Erweiterung   |
|                                  | hinterlegt.                      |
+----------------------------------+----------------------------------+
| Inaktiv                          | Über dieses Feld kann die        |
|                                  | komplette Erweiterung inklusive  |
|                                  | aller untergeordneten            |
|                                  | Erweiterungen deaktiviert        |
|                                  | werden.                          |
+----------------------------------+----------------------------------+

Ist die übergeordnete Erweiterung konfiguriert, kann nach Markieren der
Zeile über einen Doppelklick auf den Knoten „Untergeordneter
Erweiterung" in der Dialogstruktur in die Ansicht der untergeordneten
Erweiterungen abgesprungen werden.

![Ein Bild, das Text, Software, Screenshot, Schrift enthält. Automatisch
generierte Beschreibung](media/image12.png){width="5.901388888888889in"
height="2.011111111111111in"}

Die folgenden Spalten müssen zur Konfiguration einer untergeordneten
Erweiterung befüllt werden:

  ---------------------------------------------------------------------
  Spalte                             Beschreibung
  ---------------------------------- ----------------------------------
  Untergeordnete Erweiterung         In dieser Spalte wird der Name der
                                     untergeordnete Erweiterung
                                     hinterlegt.

  Inaktiv                            Über dieses Feld kann die
                                     untergeordnete Erweiterung
                                     deaktiviert werden.
  ---------------------------------------------------------------------

Beachten Sie bitte, dass es sich bei den Tabellen zur
Erweiterungskonfiguration um Stammdatentabellen handelt und daher zum
Ändern der Daten kein Transportauftrag benötigt wird.

## SDT Adjustment Report

### Kontext

Der Report /PRIS/MAIN_SDT_ADJUSTMENT dient dazu die Transportschicht und
das Quellsystem von Objekten der prismat Rakete im Kundensystem
entsprechend anzupassen.

Das ist nötig, um Problemen bzgl. SPAU-Abgleich und Anpassungen von
Z-Objekten in den Kundensystemen zu vermeiden.

Zusätzlich bietet der Report die Möglichkeit die Objekte direkt in einen
Transport zum Weitertransport der Rakete aufzunehmen.

### Prozessbeschreibung

Auf dem Selektionsbild des Reports /PRIS/MAIN_SDT_ADJUSTMENT werden die
Nummern der Workbenchtransporte der eingespielten Raketenlösungen
eingegeben.

Über diese Transporte soll der Report alle relevanten Objekte ermitteln.

Denn bei den Objekten muss sowohl die Transportschicht als auch das
Quellsystem angepasst werden.

Daher müssen auf dem Selektionsbild auch die Systemkennung des
Kundensystems und dessen Transportschicht eingetragen werden.

Über zwei Checkboxen kann gesteuert werden, ob die Transportschicht als
auch das Quellsystem angepasst werden soll und ob die Objekte in einem
Transportauftrag zum Weitertransport aufgenommen werden sollen.

Sobald die Selektion mit F8 bestätigt wird, werden die über die
Checkboxen ausgewählten Aktionen ausgeführt.

### Ablaufbeschreibung

Der Report /PRIS/MAIN_SDT_ADJUSTMENT wird über die Transaktion SM30
gestartet.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image13.png){width="5.901388888888889in"
height="2.0805555555555557in"}

Über die Mehrfachselektion für „Auftrag/Aufgabe" können alle
Workbench-Transporte eingegeben werden, mit denen die Lösungen der
prismat-Rakete in dem Kundensystem importiert wurden:

![](media/image14.png){width="5.901388888888889in"
height="0.3715277777777778in"}

Über das Feld „Originalsystem" wird die Kennung des Systems eingetragen:

![](media/image15.png){width="3.9172134733158357in"
height="0.3021259842519685in"}

Normalerweise ist das Feld bei Programmstart mit dem richtigen Wert
vorbelegt.

Über das Feld Transportschicht wird die Transportschicht eingetragen:

![](media/image16.png){width="3.3650524934383204in"
height="0.3229615048118985in"}

Das Feld verfügt über eine F4-Hilfe.

Über die Checkbox „Attribute anpassen" wird gesteuert, ob
Transportschicht und Quellsystem bei den Objekten angepasst werden
sollen:

![](media/image17.png){width="1.375191382327209in"
height="0.27087160979877517in"}

Über die Checkbox „Zu Transport hinzufügen" wird gesteuert, ob die
Objekte in einem Transport aufgenommen werden sollen:

![](media/image18.png){width="1.614808617672791in"
height="0.2604527559055118in"}

Sobald die Selektion mit F8 oder dem Button
![](media/image19.png){width="0.20836286089238845in"
height="0.21878062117235345in"} bestätigt wird, werden im ersten Schritt
alle Objekte aus den angegebenen Transporten eingelesen.

Wenn die Checkbox „Attribute anpassen" gesetzt ist werden alle Einträge
aus den Tabellen TADIR und TDEVC zu den Objekten eingelesen.

Es werden nur Einträge berücksichtigt, welche als Quellsystem eines der
prismat-Systeme hinterlegt haben.

Objekte, bei denen das Quellsystem bereits angepasst wurde, werden somit
bei einem weiteren Programmlauf nicht noch einmal angepasst.

Bei den Einträgen der entsprechenden Objekte werden die Felder
„Originalsystem" und Transportschicht entsprechend angepasst und auf die
Datenbank fortgeschrieben.

Wenn die Checkbox „Zu Transport hinzufügen" gesetzt ist wird ein modales
Dialogfenster zur Auswahl des Workbench-Transports angezeigt.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image20.png){width="3.858267716535433in"
height="1.4210750218722659in"}

Konnten alle ausgewählten Aktionen erfolgreich ausgeführt werden, wird
in der Statuszeile die Meldung „Erledigt" angezeigt.

Andernfalls wird in der Statuszeile die entsprechende Fehlermeldung
angezeigt.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Wizard

### Kontext

Entwicklung eines Wizards, der für die Migration der grundlegenden
Objekte zuständig ist, die bei der Einrichtung des EWM-Systems
kundenspezifisch ausgestaltet werden müssen.

Beim Aufruf im Kundensystem soll der Wizard dazu dienen, verschiedene
Komponenten der prismat/RAKETE initial zu konfigurieren.

### Prozessbeschreibung

Mit diesem Entwicklungspunkt soll ein Wizard zur geführten Erfassung der
Basiskonfigurationsdaten für Raketenlösungen entstehen.

Die jeweiligen Lösungen soll dafür ein Interface zur Verfügung gestellt
werden, welches sinnvolle Methoden für den Wizard definiert.

Beim Aufruf des Wizards soll dieser alle implementierenden Klassen des
Interfaces zur Laufzeit ermitteln und nacheinander die Interface
Methoden aufrufen.

Wenn dabei Einträge in Customizing Tabellen fortgeschrieben werden
sollen diese ebenfalls in einem Transport erfasst werden.

Für die Ermittlung von Klassen zu einem Interface kann die Lösung MBD
als Inspirationsquelle dienen.

Zur Arbeit mit Transporten existiert die Lösung TOT.

Das Ausimplementieren des Interfaces soll grundsätzlich pro Lösung
erfolgen und ist nicht Teil dieser Lösung.

### Ablaufbeschreibung

Der Report /PRIS/MAIN_WIZ wird über den Transaktionscode /PRIS/WIZ
gestartet.

Das Selektionsbild des Reports umfasst folgende Parameter für
Einzelwerte:

- Transport Customizing (mit F4-Hilfe)

- Transport Workbench (mit F4-Hilfe)

- Schlüsselart

- Schlüsselwert

Der Report ruft seinerseits die Methode EXECUTE_CONFIG der Logikklasse
/PRIS/MAIN_CL_SDT_WIZ auf.

Innerhalb dieser Methode wird im ersten Schritt eine Methode zur
Ermittlung aller Klassen aufgerufen, welche das Interface
/PRIS/MAIN_IF_SDT_WIZ implementieren.

Diese Klassen werden im Folgenden als Assistentenklassen bezeichnet.

Nachdem die Klassen ermittelt wurden, wird im nächsten Schritt die
Methode GET_SOLUTION_LIST des Wizards aufgerufen. In der Methode wird
für jede der Assistenzklassen die Methode GET_SOLUTION_INFO des
Interfaces aufgerufen, welche die Lösungsnummer, das Lösungskürzel, die
Versionsnummer und das Kennzeichen „Konfiguration erfolgt"
Vertriebsnummer" und Beschreibung pro Lösung zurückgeben.

Eine Liste mit diesen Informationen wird an den Report zurückgegeben und
entsprechend angezeigt.

Im Report kann der Benutzer dann pro Lösung, die Basiskonfiguration
anstoßen.

Sobald er das macht, wird die Methode GET_INPUTS der Assistenz-Methode
aufgerufen, welche eine Liste mit Feldnamen, zugehörigen Datenelementen
und Infos pro Feld bzgl. obligatorisch bzw. optional zurückgibt.

Anhand dieser Liste wird über den Funktionsbaustein
FREE_SELECTIONS_DIALOG dynamisch ein Selektionsbild zur Erfassung der
Daten angezeigt.

Nach der Eingabe der Daten werden diese an die Methode
COMPILE_BASE_CONFIG der jeweiligen Assistenzklasse übergeben.

Dort wird aus den Eingabedaten die Basiskonfigurationseinträge für
diverse Tabellen zusammengestellt und über eine verschachtelte Tabelle,
welche die jeweiligen Einträge zu dem jeweiligen Tabellennamen aufnimmt,
zurückgegeben.

Diese Daten werden dann vom Wizzard in die jeweiligen Tabellen
fortgeschrieben und wenn nötig dem Workbench- oder dem
Customizing-Transport zugeordnet.

Die jeweilige Lösung bekommt zum Abschluss das Kennzeichen
„Konfiguration erfolgt" gesetzt.

In einem Fehlerfall soll für die jeweilige Lösung visuell kenntlich
gemacht werden, dass die Konfiguration abgebrochen werden musste.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Generische Tabellenleseklasse

### Kontext

In diesem Kapitel wird die generische Tabellenleseklasse
/PRIS/MAIN_CL_GTB_TABLE_READ vorgestellt und deren Verwendung
beschrieben.

### Prozessbeschreibung

Zur Vermeidung von direkten Datenbankzugriffen beim Einlesen von
kundenspezifischen Stammdaten- und Customizing-Tabellen werden in der
Regel für jede dieser Tabellen spezifische Leseklassen angelegt.

Das bedeutet, dass pro Tabelle nicht nur eine Klasse angelegt, sondern
diese auch jedes Mal verprobt werden muss.

Zur Vermeidung dieser Aufwände und potenzieller Fehlerquellen wurde mit
dieser Lösung eine Klasse geschaffen, mit der jede kundenspezifische
Stammdaten- und Customizing-Tabelle eingelesen werden kann.

### Ablaufbeschreibung

Die Klasse /PRIS/MAIN_CL_GTB_TABLE_READ ermöglicht die Selektion von
Daten aus einer Datenbanktabelle.

Der Name der Datenbanktabelle muss bei der Instanziierung dem Parameter
IV_TABLE_NAME übergeben werden.

Mit dem optionalen Parameter IT_KEY_FIELDS kann eingeschränkt werden
welche Daten gepuffert werden sollen.

Es stehen die öffentlichen Methoden GET_MULTIPLE und GET_SINGLE zur
Verfügung.

Über die Methode GET_MULTIPLE können mehrere Datensätze aus dem Puffer
abgerufen werden.

Die Ergebnismenge kann dabei mit dem Parameter IT_FIELD_RANGE nach
bestimmten Feldwerten eingeschränkt werden.

Über die Methode GET_SINGLE kann ein einzelner Datensatz aus dem Puffer
abgerufen werden.

Dafür muss der Parameter IT_KEY_FIELDS mit den entsprechenden
Schlüsselwerten versorgt werden.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Transport Order Tool

### Kontext

Normalerweise werden Änderungen am Customizing oder an
Entwicklungsobjekten, von den entsprechenden Standardtransaktionen den
jeweiligen, Transportaufträgen zugeordnet.

Müssen die entsprechenden Elemente jedoch aus einem kundenspezifischen
Programm heraus angepasst werden greifen diese
Standardaufzeichnungsroutinen nicht.

Das Transport Order Tool kapselt die Standard-Funktionsbausteine zum
Auslesen und Fortschreiben von Transportaufträgen und ist somit eine
einheitliche und einfache Lösung für diese Problematik.

### Prozessbeschreibung

Die Klasse /PRIS/MAIN_CL_TOT stellt Methoden zum Einlesen von
Transportdaten und Übersetzungen zu Objekten, zum Anzeigen den
Transportauswahldialoges und zum Fortschreiben von Transportdaten zur
Verfügung.

Dafür stehen die folgenden acht Methoden zur Verfügung:

- GET_DATA_MULTIPLE

- GET_DATA_SINGLE

- GET_HEADERS

- GET_HEADER_WITH_TEXT

- GET_TRANSLATION_OBJECTS

- GET_TRANSLATION_OBJECTS_TRKORR

- INSERT_INTO_ORDER

- OPEN_ORDER_DIALOG

### Ablaufbeschreibung

#### Klasse /PRIS/MAIN_CL_TOT

##### Methode GET_DATA_MULTIPLE

Der Methode GET_DATA_MULTIPLE werden Kopfdaten zu einem oder mehreren
Transportaufträgen als Tabellentyp vom Typ E070_T übergeben.

Über das Flag IV_FLG_OBJECTS kann gesteuert werden, ob Objekt-Einträge
zu den Transporten ermittelt werden sollen.

In diesem Fall würden die Objekt-Einträge als Tabellentyp vom Typ E071_T
zurückgegeben.

Über das Flag IV_FLG_ENTRIES kann gesteuert werden, ob
Schlüssel-Einträge zu den Transporten ermittelt werden sollen.

In diesem Fall würden die Schlüssel-Einträge als Tabellentyp vom Typ
E071K_T zurückgegeben.

Die beiden Flags sind in der Schnittstelle mit ABAP_TRUE vorbelegt.

##### Methode GET_DATA_SINGLE

Der Methode GET_DATA_SINGLE die Nummer eines Transportauftrags als Feld
vom Typ TRKORR übergeben.

Über das Flag IV_HEADER kann gesteuert werden, ob die Kopfdaten zum
Transport ermittelt werden sollen.

In diesem Fall werden die Kopfdaten in einer Struktur vom Typ E070
zurückgegeben.

Über das Flag IV_FLG_OBJECTS kann gesteuert werden, ob Objekt-Einträge
zu dem Transport ermittelt werden sollen.

In diesem Fall würden die Objekt-Einträge als Tabellentyp vom Typ E071_T
zurückgegeben.

Über das Flag IV_FLG_ENTRIES kann gesteuert werden, ob
Schlüssel-Einträge zu dem Transport ermittelt werden sollen.

In diesem Fall würden die Schlüssel-Einträge als Tabellentyp vom Typ
E071K_T zurückgegeben.

Die drei Flags sind in der Schnittstelle mit ABAP_TRUE vorbelegt.

##### Methode GET_HEADERS

Der Methode GET_HEADERS werden die Nummern zu einem oder mehreren
Transporten als Range vom Typ RSELOPTION übergeben.

Die gefundenen Kopfdaten werden als Tabellentyp vom Typ E070_T
zurückgegeben.

##### Methode GET_HEADER_WITH_TEXT

Der Methode GET_HEADER_WITH_TEXT werden die Nummer eines Transports als
Feld vom Typ TRKORR und ein Sprachschlüssel als Feld vom Typ SYLANGU
übergeben.

Der Parameter für den Sprachschlüssel ist mit dem Schlüssel der
Anmeldesprache vorbelegt.

Die Kopfdaten werden in einer Struktur vom Typ E070 zurückgegeben.

Die Beschreibung des Transports wird in einer Struktur vom Typ E070_T
zurückgegeben.

##### Methode GET_TRANSLATION_OBJECTS

Der Methode GET_TRANSLATION_OBJECTS werden ein Sprachschlüssel als Feld
vom Typ SYLANGU und Objekt-Einträge als Tabellentyp vom Typ E071_T, für
die die Übersetzungen ermittelt werden sollen, übergeben.

Die Methode kann Übersetzungen zu Datenelementen, Domänen,
Funktionsgruppen, Nachrichtenklassen, Programmen, Suchhilfen,
Datenbanktabellen, Tabellentypen und Views ermitteln.

Die Objekt-Einträge inklusive der Übersetzungen werden als Tabellentyp
vom Typ E071_T zurückgegeben.

##### Methode GET_TRANSLATION_OBJECTS_TRKORR

Der Methode GET_TRANSLATION_OBJECTS_TRKORR werden ein Sprachschlüssel
als Feld vom Typ SYLANGU und die Nummer eines Transports als Feld vom
Typ TRKORR übergeben.

Die Methode kann Übersetzungen zu Datenelementen, Domänen,
Funktionsgruppen, Nachrichtenklassen, Programmen, Suchhilfen,
Datenbanktabellen, Tabellentypen und Views ermitteln.

Die Objekt-Einträge inklusive der Übersetzungen werden als Tabellentyp
vom Typ E071_T zurückgegeben.

##### Methode INSERT_INTO_ORDER

Der Methode INSERT_INTO_ORDER werden die Nummer eines Transports als
Feld vom Typ TRKORR, Objekt-Einträge als Tabellentyp vom Typ E071_T,
Schlüssel-Einträge als Tabellentyp vom Typ E071K_T, eine
Mandantenkennung als Feld vom Typ SYMANDT und ein Sprachschlüssel als
Feld vom Typ SYLANGU übergeben.

Die Parameter für Mandantenkennung und Sprachschlüssel sind mit
Standardwerten vorbelegt.

Ist der Transport, in dem die Objekte aufgenommen werden sollen, nicht
vorhanden wird die klassische Ausnahme NOT_FOUND mit einem Fehlertext
geworfen.

Falls die Objekte nicht in den Transport aufgenommen werden können, wird
die klassische Ausnahme INSERTION_FAILED geworfen.

##### Methode OPEN_ORDER_DIALOG

Die Methode OPEN_ORDER_DIALOG wird mit den Flags
IV_ORDER_TYPE_WORKBENCH, IV_ORDER_TYPE_CUSTOMIZING,
IV_TASK_TYPE_DEVELOPMENT und IV_TASK_TYPE_REPAIR aufgerufen.

Die Flags IV_ORDER_TYPE_WORKBENCH und IV_TASK_TYPE_DEVELOPMENT sind mit
ABAP_TRUE vorbelegt.

Die Nummer des Transports wir als Feld vom Typ TRKORR zurückgegeben.

Die Nummer der Transportaufgabe wir als Feld vom Typ TRKORR
zurückgegeben.

Falls der Benutzer die Eingabe im Dialog abbricht, ist der Parameter
EV_CANCELED mit ABAP_TRUE gefüllt.

Falls es Probleme mit dem Dialog gibt, wird die klassische Ausnahme
ERROR mit einem Fehlertext geworfen.

#### Report /PRIS/MAIN_TOT_ADD_LANG

Der Report /PRIS/MAIN_TOT_ADD_LANG dient dazu Übersetzungen für die
Objekte eines Transports zu Ermitteln und in einen Transport
fortzuschreiben.

Das Selektionsbild des Reports umfass die Felder Quelltransportauftrag,
Sprachschlüssel und Zieltransportauftrag.

![Ein Bild, das Text, Screenshot, Software, Display enthält. Automatisch
generierte Beschreibung](media/image21.png){width="5.901388888888889in"
height="3.76875in"}

Die Felder zu Quelltransportauftrag und Sprachschlüssel sind
obligatorisch.

Das Feld zum Zieltransportauftrag ist optional.

Wird das Feld zum Zieltransportauftrag leer gelassen werden die
Übersetzungen zum Quelltransportauftrag hinzugefügt.

Existieren keine Übersetzungstexte wird die Meldung \"Keine
Übersetzungsobjekte für Auftrag &1 gefunden!\" ausgegeben.

Ist beim Hinzufügen der Übersetzungstexte zum Transport ein Fehler
aufgetreten wird die entsprechende Fehlermeldung ausgeben.

Wurden Übersetzungstexte gefunden und konnten dem Transport hinzugefügt
werden wird die Meldung \"&1 Objekte in Sprache &2 zu Auftrag &3
hinzugefügt\" ausgegeben.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Generische Suchhilfe

### Kontext

Zur Erstellung einer Suchhilfe ist in den meisten Fällen keine explizite
Programmierung erforderlich und die gewünschten Daten können einfach
einer Datenquelle entnommen werden.

Ist dies jedoch mal nicht der Fall ist die Erstellung eines
Suchhilfe-Exits erforderlich.

Bei einem Suchhilfe-Exit handelt es sich um einen Funktionsbaustein mit
einer fest definierten Schnittstelle, welcher in der jeweiligen
Suchhilfe hinterlegt wird.

Innerhalb eines solchen Funktionsbausteins werden Programmblöcke zur
Ausführung der Schrittfolge einer Suchhilfe erwartet.

Die Programmblöcke und Schritte müssen Beispielquelltexten oder anderen
Suchhilfe-Exits entnommen werden, was die Implementierung eines
Suchhilfe-Exits deutlich erschwert.

Diese Lösung umfasst daher eine Basisklasse für die Umsetzung der
Schrittfolge der Ausführungslogik.

Zusätzlich ist eine Beispiel-Suchhilfe, deren Logikklasse von der
Basisklasse erbt Teil dieser Lösung.

### Prozessbeschreibung

Innerhalb der jeweiligen Suchhilfe wird auf den Funktionsbaustein des
Suchhilfe-Exits verwiesen.

Innerhalb des Funktionsbausteins werden Methoden der Logikklasse
aufgerufen, welche von der Basisklasse erbt.

Innerhalb der Logikklasse wurden die benötigten Methode redefiniert und
Anwendungsspezifisch ausimplementiert.

### Ablaufbeschreibung

Über F4 oder einen Klick auf den entsprechenden Button wird die
Suchhilfe zu einem GUI-Element aufgerufen.

Da die angeforderten Daten keiner einfachen Datenquelle entnommen werden
können wurde in der Suchhilfe ein Suchhilfe-Exit hinterlegt.

In dem entsprechenden Funktionsbaustein wir die Logikklasse instanziiert
und die Methode EXECUTE_LOGIC der Instanz aufgerufen.

Innerhalb der Methode sind Programmblöcke für die Schritte DISP,
PRESEL1, SELECT und SELONE hinterlegt.

Je nach Schritt wird eine der Methoden EXECUTE_STEP_CHOOSE_SH,
EXECUTE_STEP_DISPLAY, EXECUTE_STEP_SELECT oder EXECUTE_STEP_SELECT_COND
aufgerufen.

Entsprechend der Anforderung wurden 1 bis n dieser Ausführungsmethoden
redefiniert und Anwendungsspezifisch ausimplementiert.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## CSV-Handling

### Kontext

Diese Lösung dient dazu, CSV-Dateien im SAP-System zu verarbeiten.

### Prozessbeschreibung

Beim Austausch von Daten zwischen einem externen System und einem
SAP-System wird häufig das standardisierte CSV-Datei Format eingesetzt.\
Ziel dieser Lösung ist, diesen Austausch mit Hilfe einer
vorimplementieren Lösung zu vereinfachen.

Mithilfe dieser Lösung können CSV-Dateien in einem SAP-System
verarbeitet werden.

Folgende Funktionalitäten werden mit der Lösung bereitgestellt:

- Umwandeln von CSV-Dateien in ABAP-Tabellen

- Umwandeln von ABAP-Tabellen in CSV-Dateien

- Ablage der CSV-Dateien in einem lokalen Pfad oder auf einem
  SAP-Applikationsserver

- Bereitstellung eines Reports zur manuellen oder automatisierten
  Ausführung (bspw. über einen periodischen Job) der CSV-Verarbeitung im
  Hintergrund

### Ablaufbeschreibung

Beim Austausch von Daten zwischen einem externen System und einem
SAP-System wird häufig das standardisierte CSV-Datei Format eingesetzt.\
Ziel dieser Lösung ist, diesen Austausch mit Hilfe einer
vorimplementieren Lösung zu vereinfachen.

Die Lösung kann entweder mit Hilfe der bereitgestellten Funktionen der
ABAP-Klasse */PRIS/MAIN_CL_GTB_CSV_HANDLING* verwendet, oder über den
ausgelieferten Report */PRIS/MAIN_GTB_CSV_HANDLING* ausgeführt werden.

Zur Verarbeitung von CSV-Dateien mit Hilfe des Reports sind folgende
Schritte nötig:

**Schritt 1:** Für die Report-Verarbeitung implementiert eine Klasse die
Schnittstelle */PRIS/MAIN_IF_GTB_CSV_HANDLING*, welche im Report
hinterlegt werden kann.

**Schritt 2:** Das Programm kann über die Transaktion
*/PRIS/MAIN_GTB_CSV* gestartet werden.

**Schritt 3:** In den Grundeinstellungen muss die Schlüsselart, der
Schlüsselwert sowie die Klasse mit der implementierten Schnittstelle
angegeben werden.

![Ein Bild, das Text, Reihe, Schrift, Screenshot enthält. Automatisch
generierte Beschreibung](media/image22.png){width="5.895833333333333in"
height="1.4166666666666667in"}

**\
Schritt 4:** In den CSV-Einstellungen wird ausgewählt, ob eine CSV
gelesen oder geschrieben werden soll. Zusätzlich wird noch die
Tabellenstruktur der Tabelle mitgegeben. Diese entspricht dem Aufbau der
Spalten der CSV-Datei.\
Als letztes wird der Dateipfad für die CSV-Datei festgelegt. Dies kann
entweder ein lokaler Pfad des Rechners oder ein Anwendungsserver
sein.![Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. Automatisch
generierte Beschreibung](media/image23.png){width="5.901388888888889in"
height="2.6333333333333333in"}

**Schritt 5:** In den optionalen Einstellungen kann der Separator
(Trennzeichen) und das Escape Zeichen geändert werden.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image24.png){width="3.8958333333333335in"
height="1.2395833333333333in"}

**Schritt 6:** Im Hintergrund wird bei Ausführung des Reports eine
CSV-Datei mithilfe des angegebenen Dateipfads eingelesen oder erstellt.

**Schritt 7:** Falls eine CSV-Datei eingelesen wurde, wird der Inhalt
der CSV-Datei in eine ABAP-Tabelle konvertiert und kann anschließend im
SAP-System weiterverarbeitet werden. Wenn eine CSV-Datei geschrieben
werden soll, kann mit Hilfe der Verarbeitungsklasse bspw. eine
Datenbanktabelle ausgelesen und anschließend der Inhalt dieser Tabelle
für den Austausch mit externen Systemen in eine CSV-Datei konvertiert
werden.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Access Control Definition - Zugriffsfolgen

### Kontext

In diesem Kapitel wird die Tabellenleseklasse über Zugriffsfolgen
/PRIS/MAIN_CL_GTB_ACCESS_SEQ vorgestellt und deren Verwendung
beschrieben.

### Prozessbeschreibung

Diese Lösung erlaubt es, Datensätze aus einer Datenbanktabelle über eine
auf diese angepasste Zugriffsfolgetabelle zu ermitteln.

Die Zugriffsfolgetabelle enthält dabei mindestens alle Schlüsselfelder
der Datenbanktabelle und definiert verschiedene Zugriffsfolgen mit
unterschiedlicher Gewichtung, um auch mit weniger als der angegebenen
Parameter einen Datensatz ermitteln zu können.

### Ablaufbeschreibung

Auf Basis der Klasse /PRIS/EWM_CL_MAC_CONTROL_AQ wurde eine neue Klasse
mit einer angepassten Logik erstellt.

#### Lagernummer unabhängige Logik

Damit die Klasse auch im ERP genutzt werden kann, funktioniert die Logik
unabhängig von der Lagernummer.

#### Filter

Die Lösung nutzt eine generische Filterung, für die bei der
Instanziierung ein Schlüsselfeld und ein Schlüsselwert übergeben wird.

#### Logging

Die Verwendung eines Logobjekts ist optional, da eine interne Tabelle
existiert, in der die erzeugten Nachrichten gespeichert werden. Die
Tabelle wird nach der Ermittlung der Daten an den Aufrufer zurückgeben.
Beim Auftritt einer Ausnahme, wird die Tabelle über das Ausnahmeobjekt
an den Aufrufer zurückgegeben.

#### Prüfung der Suchfolgen

Alle ermittelten Datensätze aus den Daten werden alle Felder, die nicht
in der Suchfolge enthalten waren auf Leerheit geprüft. Über den
Importparameter IV_CHECK_KEYFIELDS der Ermittlungsmethoden kann gewählt
werden, ob dabei die Schlüsselwerte oder Nicht-Schlüsselwerte der
Suchfolge geprüft werden.

#### Ermittlungsmöglichkeiten erweitern

Die Ermittlungsmethoden bieten den Importparameter
IT_FIELD_COMPARE_OPERATORS, der eine Tabelle mit Feldnamen und
Vergleichsoperator darstellt. Dadurch lassen sich Felder der Daten mit
allen in ABAP verfügbaren Vergleichsoperatoren (NE, LE, GT, ...) mit den
Selektionsdaten vergleichen.

#### Wildcard

Wenn in der Datentabelle ein \* in einem Feld steht ist es für
Suchfolgen, die auf dieses Feld prüfen für jeden Wert Wahr. Für
Suchfolgen, die dieses Feld nicht Prüfen, wird es als leer betrachtet.

#### Statischer Speicher

Alle erzeugten Instanzen werden in einer statischen Tabelle der Klasse
gespeichert. Dadurch werden häufige Zugriffe auf die Datenbank
vermindert, da die selektierten Daten und Suchfolgen, sowie die
Schlüsselfelder und -werte in der Instanz gespeichert werden. Diese
machen die Instanz eindeutig unterscheidbar.\
Um die Daten erneut von der Datenbank zu selektieren, lässt sich die
Erzeugung einer neuen Instanz erzwingen, die die alte Instanz
überschreibt.

### Konfiguration

#### Protokollierung

Die Lösung kann sowohl mit als auch ohne eine Instanz der Klasse\
/PRIS/MAIN_CL_LOG verwendet werden.\
Soll eine Instanz der Log-Klasse verwendet werden, wird diese der
Methode GET_INSTANCE übergeben. Ansonsten wird eine Tabelle mit den
Nachrichten beim Aufruf der Methoden GET_DATA und GET_DATA_MULT
zurückgegeben. Falls eine Ausnahme geworfen wird, ist in dem
entsprechenden Ausnahmeobjekt ebenfalls eine Tabelle mit den Nachrichten
als Attribut verfügbar.

#### Tabellenpflege

Falls für eine Lösung eine Suchfolge benötigt wird, müssen zwei
entsprechende Tabellen angelegt werden. Die Datentabelle, die alle
relevanten Daten, und die Suchfolgetabelle, die die Suchfolgen zur
Datenermittlung enthält.\
(Auf das Mandantenfeld wird hier nicht eingegangen, da dieses
selbsterklärend ist)

Für die Suchfolge sind nur die Schlüsselfelder der Datentabelle
relevant.

Alle Schlüsselfelder der Datentabelle müssen in der Suchfolgetabelle
enthalten sein. Dabei werden die Feldbezeichnungen übernommen, doch die
Typisierung für die Felder, die die Suchfolge darstellen, erfolgt als
XFELD.\
Zusätzlich enthält die Suchfolgetabelle ein Feld für die Reihenfolge
(SEQNO).

Der Schlüssel der Suchfolgetabelle setzt sich aus Feldern der höchsten
Hierarchiestufe (Mandant, z.B. Lagerort und/oder Lagernummer) und dem
Feld für die Reihenfolge (SEQNO) zusammen.

Zur Veranschaulichung eine Gegenüberstellung der Datentabelle und der
Suchfolgetabelle mit den jeweiligen Feldeigenschaften:

**Beispiel Datentabelle:**

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image25.png){width="5.901388888888889in"
height="1.2520833333333334in"}

In der Datentabelle sind drei Felder enthalten, die zusätzliche Daten
für Folgeaktionen beinhalten können. Alle anderen Felder sind
Schlüsselfelder.

**Beispiel Suchfolgetabelle:**

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image26.png){width="5.901388888888889in"
height="1.5444444444444445in"}

Alle für die Suchfolge relevanten Felder sind als X-Feld typisiert und
sind kein Schlüsselfeld. Nur die Sequenznummer (SEQNO) und das Feld für
die Filterung (LGNUM) sind Schlüsselfelder.

**Beispiel Selektionsdaten:**

![](media/image27.png){width="5.901388888888889in"
height="0.3798611111111111in"}

Die Selektionsdaten müssen als Struktur der Datentabelle erzeugt werden.

**Beispiel Datenermittlung:**

![](media/image28.png){width="5.901388888888889in"
height="0.3798611111111111in"}

Für die obenstehenden Beispieldaten wird dieses Ergebnis aus den
Methoden GET_DATA und GET_DATA_MULT ermittelt.

## Generischer Löschreport

### Kontext

Kundenspezifische Tabellen für Bewegungsdaten sollten nach einer
gewissen Zeit um alte Einträge bereinigt werden. Das ist nötig, damit
diese Tabellen nicht überlaufen.

Daher werden in der Regel pro Tabelle eigene Löschreports umgesetzt und
als Jobs eingeplant.

Diese Reports sind dabei oft weitgehend identisch und enthalten somit
überwiegend redundantes Coding.

Der generische Löschreport /PRIS/MAIN_GTB_RTAB setzt daher im
Auslieferzustand zum einen den kleinsten gemeinsamen Nenner um und ist
des Weiteren auch noch über ein Framework erweiterbar.

### Prozessbeschreibung

Der Report /PRIS/MAIN_GTB_RTAB wird zu einer Schlüsselart und einem
Schlüsselwert gestartet.

Zur Schlüsselart und dem Schlüsselwert werden alle Einstellungseinträge
aus der Tabelle /PRIS/GTB_RTABC eingelesen.

Je nach Einstellungseintrag werden entweder Einträge aus der jeweiligen
Tabelle gelöscht, die älter als die vorgegebene Anzahl an Tagen sind
oder ein kundenspezifische Löschlogik durchlaufen.

### Ablaufbeschreibung

Der Report /PRIS/MAIN_GTB_RTAB wird über die Transaktion
/PRIS/MAIN_GTB_RTAB gestartet.

Im Selektionsbild des Reports müssen eine Schlüsselart und ein
Schlüsselwert eingegeben werden.

![Ein Bild, das Text, Screenshot, Software, Computersymbol enthält.
Automatisch generierte
Beschreibung](media/image29.png){width="5.901388888888889in"
height="2.870138888888889in"}

Nach Bestätigung der Eingabe liest der Report die Einstellungen aus der
Tabelle /PRIS/GTB_RTABC ein und verwirft ungültige Einträge.

Falls für eine Tabelle eine Klasse für eine kundenspezifische Löschlogik
hinterlegt wurde, wird versucht eine Instanz der Klasse zu erzeugen.

Klassen für kundenspezifische Löschlogiken müssen zwingend das Interface
/PRIS/MAIN_IF_GTB_RTAB implementieren.

Für alle hinterlegten Klassen werden die IS_RELEVANT-Methoden
aufgerufen, um zu validieren, dass die jeweiligen Tabellen zum aktuellen
Zeitpunkt relevant für den Löschvorgang sind.

Alle nicht relevanten Tabellen werden verworfen.

Wurden bis hierher alle Tabellen, für die Einträge in der
Einstellungstabelle /PRIS/GTB_RTABC hinterlegt sind, verworfen so wird
die Verarbeitung abgebrochen.

Falls nicht alle Tabellen verworfen wurden, wird im Anschluss pro
Tabelle der Löschvorgang ausgeführt.

Bei Tabellen ohne hinterlegte Klassen werden alle Einträge gelöscht, die
ihre maximale Lebenszeit in Tagen überschritten haben.

Bei Tabellen mit hinterlegter Klasse wird die Methode DELETE_ENTRIES
aufgerufen, um die kundenspezifische Löschlogik auszuführen.

### Konfiguration

#### Tabellenpflege

Der Report /PRIS/MAIN_GTB_RTAB wird über die Tabelle /PRIS/GTB_RTABC
konfiguriert.

![Ein Bild, das Text, Screenshot, Display, Software enthält. Automatisch
generierte Beschreibung](media/image30.png){width="5.901388888888889in"
height="4.9118055555555555in"}

![Ein Bild, das Text, Software, Computersymbol, Zahl enthält.
Automatisch generierte
Beschreibung](media/image31.png){width="5.901388888888889in"
height="2.4444444444444446in"}

Die Tabelle umfasst die folgenden Spalten:

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  KEY_TYPE                            Schlüsselart

  KEY_VALUE                           Schlüsselwert

  TABNAME                             Tabellenname

  FIELDNAME                           Feldname

  OLDER_DAYS                          älter als \[in Tagen\]

  CLASSNAME                           Klassenname

  INACT                               Inaktivkennzeichen
  -----------------------------------------------------------------------

## GTB HTTP-Request

### Kontext

Zum Versenden von Anfragen über das HTTP-Protokoll existiert im Standard
die Klasse CL_HTTP_CLIENT.

Für eine HTTP-Anfrage über diese Klasse müssen diverse Methoden der
Klasse in einer bestimmten Reihenfolge aufgerufen werden.

Die Klasse /PRIS/MAIN_CL_GTB_HTTP_REQUEST kapselt diesen Ablauf und
dient somit dazu das Versenden von HTTP-Anfragen deutlich zu
vereinfachen.

### Prozessbeschreibung

Im ersten Schritt wird die entsprechende Anfrage in einem gängigen
Web-Format wie z.B. XML erfasst.

Sobald das geschehen ist, wird eine Instanz der Klasse
/PRIS/MAIN_CL_GTB_HTTP_REQUEST erzeugt.

Im Anschluss wird die Anfrage über die Instanz versendet und die Antwort
empfangen.

Für die Auswertung der Antwort ist der Aufrufer verantwortlich.

### Ablaufbeschreibung

Zum Versenden einer HTTP-Anfrage muss zunächst die Anfrage selbst
erstellt werden.

Die Anfrage sollte in einem gängigen Web-Format wie z.B. XML erfasst
werden.

Da Anfragen und Antworten je nach gewähltem Format sehr viele Zeichen
umfassen können wird für Anfragen und Antworten der Datentyp STRING_T
verwendet.

Bei dem Datentyp STRING_T handelt es sich um einen Tabellentyp für
Zeichenketten.

Danach wird eine Instanz der Klasse /PRIS/MAIN_CL_GTB_HTTP_REQUEST
erzeugt und dieser der Name des Servers übergeben.

![](media/image32.png){width="5.901388888888889in" height="0.375in"}

Im Anschluss kann die Anfrage über die Methode SEND der Instanz
versendet werden.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image33.png){width="4.333333333333333in"
height="1.6875in"}

Über den Importing-Parameter IV_REQ_URI wird der Name des Services
übergeben.

Die Anforderung wird über den Importing-Parameter IT_REQUEST übergeben.

Über den Exporting-Parameter wird die Antwort des Services
zurückgegeben.

Die Exporting-Parameter EV_STATUS_CODE und EV_STATUS_REASON können
verwendet werden, um auszuwerten, ob der Aufruf erfolgreich war.

Bei einer erfolgreichen HTTP-Anfrage wird über den Parameter
EV_STATUS_CODE in der Regel der Wert 200 zurückgegeben.

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## GTB Timer

### Kontext

In diesem Kapitel wird der Umgang mit der Timer-Lösung beschrieben.
Diese Lösung dient dazu, GUI-Funktionen basierend auf einem Timer
auszulösen. Die bereitgestellte Klasse, welche die Funktionen dieser
Lösung kapselt, wird in den nachfolgenden Kapiteln genauer beschrieben.

### Prozessbeschreibung

Die Timer-Lösung dient der Ausführung von Funktionen von
Dialogprogrammen in bestimmten Zeitintervallen. Das wird erreicht, indem
man einen Timer anlegt, nach dessen Ablauf eine Funktion (z.B. Auslösen
von der ENTER Funktionstaste) ausgelöst wird. Diese Lösung fasst die
dafür notwendigen Entwicklung in einer einheitlichen Schnittstelle
zusammen.

### Ablaufbeschreibung

Die Lösung liefert eine einzige Klasse, die folgende Funktionalitäten
anbietet, um die periodische Ausführung von Funktionen während der
Ausführung von Dialogprogrammen zu planen:

- Timer anlegen

> Bei der Anlage des Timers müssen folgende Angaben gemacht werden:

- Das Zeitintervall, nachdem der Timer reagieren soll

- Der OK-Code, über welchen der Benutzer die Funktion im Vordergrund
  auslöst

<!-- -->

- Timer starten

- Timer beenden

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## Generische Berechtigungsprüfung

### Kontext

Die Lösung definiert ein modulübergreifendes Berechtigungsobjekt
/PRIS/MAIN und eine Klasse, welche die Berechtigungsprüfung zu diesem
Berechtigungsobjekt kapselt.

Als Attribute für die Berechtigungsprüfung sind Aktivität, Schlüsselart,
Schlüsselwert und Lösungskürzel vorgesehen.

### Prozessbeschreibung

Das Berechtigungsobjekt /PRIS/MAIN muss im Zielsystem über
entsprechenden Rollen zu den benötigten Attributen ausgeprägt werden.

Die Prüfung auf das Berechtigungsobjekt erfolgt über die Methode
CHECK_ALL der Klasse /PRIS/MAIN_CL_GTB_AUTH_CHECK.

Bei Fehlender Berechtigung wird eine Ausnahme vom Typ
/PRIS/CX_MAIN_GTB_AUTH_CHECK geworfen.

### Ablaufbeschreibung

Zur Prüfung auf das Berechtigungsobjekt /PRIS/MAIN muss zunächst eine
Instanz der Klasse /PRIS/MAIN_CL_GTB_AUTH_CHECK erzeugt werden.

Im Anschluss wird zum Ausführen der Prüfung die Methode CHECK_ALL der
Instanz mit Aktivität, Schlüsselart, Schlüsselwert und Lösungskürzel
aufgerufen.

Die gültigen Werte für die Aktivität können Sie der Datenbanktabelle
TACT entnehmen.

Falls die Berechtigungsprüfung erfolgreich ist wir kein Wert
zurückgegeben.

Bei einer negativen Prüfung wird eine Ausnahme vom Typ
/PRIS/CX_MAIN_GTB_AUTH_CHECK geworfen.

Je nach Fehlersituation kann die Ausnahme einen der drei folgenden Texte
enthalten:

- Fehlende Berechtigungen für Berechtigungsobjekt &1

- Ungültiger Benutzername

- Unbekannter Fehler Berechtigungsprüfung &1 User: &2 Prog: &3

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## BAdI and Enhancement Framework 

### Kontext

Im Standard können bei den meisten Business Add-Ins mehrere
Implementierungen pro Filter hinterlegt werden.

Das ist jedoch nicht bei allen Business Add-Ins der Fall, so dass kein
einheitlicher Weg im Standard existiert, um mehrere Implementierungen zu
allen BAdIs zu hinterlegen.

Bei Business Add-Ins, welche nur eine Implementierung erlauben, werden
oft Workarounds in der Form abgebildet, dass die Implementierungen,
welche über die Standard-Transaktionen hinterlegt wurden, ihrerseits die
weiteren Implementierungen aufrufen.

Das hat zur Folge, dass über die Standard-Transaktionen nicht
ersichtlich ist, was wirklich alles aufgerufen wird.

Hinzu kommt, dass man auch bei Business Add-Ins, welche mehrere
Implementierungen erlauben, keinen Einfluss darauf hat in welcher
Reihenfolge die Implementierungen aufgerufen werden.

Daher soll ein Framework geschaffen werden, über das für jedes Business
Add-In mehrerer Implementierungen hinterlegt werden können.

### Prozessbeschreibung

Für die Implementierungen pro Business Add-In soll die Reihenfolge, in
welcher die Implementierungen aufgerufen werden, vorgegeben werden
können.

Zusätzlich soll es möglich sein das Ergebnis der vorher aufgerufenen
Implementierung an die nachfolgend aufgerufene Implementierung zu
übergeben.

Dazu ist es notwendig, für die Implementierungen die Standard-Interfaces
der Business Add-Ins zu kopieren und alle Exporting- und
Returning-Parameter durch Changing-Parameter zu ersetzen.

Zusätzlich sollen die Interfaces auch um die folgenden Parameter zur
Steuerung des Frameworks und zur Protokollierung erweitert werden:

- CV_STD_CALLED (Kennzeichen, dass eine Standard-Implementierung
  aufgerufen wurde)

- EV_BEF_ABORT (Kennzeichen, dass die Verarbeitung im Framework
  abgebrochen werden soll)

- IO_PRISLOG vom Typ /PRIS/MAIN_CL_LOG (Modulübergreifende Lösung zur
  Protokollierung)

Die kopierten und angepassten Interfaces müssen über eine neu zu
definierende Tabelle dem Framework bekannt gemacht werden.

Dieses Framework soll die prismat-Lösung SWT integrieren um
Implementierungen zu Business Add-Ins pro Schlüsselwert (im EWM die
Lagernummer) schaltbar zu machen.

Welche Implementierungen pro Schlüsselwert aktiv sind soll über eine neu
zu schaffende Transaktion übersichtlich angezeigt werden.

Über diese Transaktion soll es auch möglich sein die Implementierungen
zu aktivieren bzw. zu deaktivieren.

Die Aufrufreihenfolge der Implementierung soll ebenfalls, über Hoch- und
Runter-Buttons, angepasst werden können.

Zusätzlich soll die Transaktion eine Möglichkeit bieten, um die
Einstellungen in einen Customizing-Transport aufzunehmen.

Obwohl das beschriebene Framework ursprünglich nur für Business Add-Ins
angedacht war, soll die Implementierung des Frameworks auch für
klassische BAdIs, Enhancement Points, User Exits und prismat spezifische
Erweiterungen nutzbar sein.

Es soll der Änderungsmodus des Reports /PRIS/MAIN_BEF_CONFIG um einen
„Anlegen"-Button erweitert werden.

Sobald der Anwender auf diesen Button klickt, soll ein neues
Dialogfenster mit den folgenden Eingabefeldern eingeblendet werden:

- Erweiterungsart mit F4-Hilfe

- Name der Erweiterung mit F4-Hilfe

- Name des Interfaces mit F4-Hilfe

- Name der Klasse

Durch Bestätigung des Dialogfensters sollen die entsprechenden Objekte
erzeugt werden.

Nach der Erzeugung der Objekte ist die Anzeige im Report zu
aktualisieren.

### Ablaufbeschreibung

Das BAdI- und Erweiterungs-Framework wird über den Einführungsleitfaden
(Transaktionscode SPRO) eingestellt.

Der Pfad zu den Einstellungen lautet für EWM wie folgt:

- SAP Customizing Einführungsleitfaden

  - prismat RAKETE

    - Extended Warehouse Management

      - BAdI Framework

        - BAdI Framework

          - BEF: Definition

Der Pfad zu den Einstellungen lautet für ERP wie folgt:

- SAP Customizing Einführungsleitfaden

  - prismat RAKETE

    - Enterprise Resource Planning

      - BAdI Framework

        - BAdI Framework

          - BEF: Definition

Das BAdI- und Erweiterungs-Framework wird über den Bereichsmenu wie folg
eingestellt:

- SAP Menu

  - prismat Rakete

    - BAdI Framework

      - Definition

      - Konfiguration

      - Übersicht

Über den Knoten "Erweiterung definieren" wird zu einer Erweiterung
hinterlegt, ob es sich um ein Business Add-In, ein klassisches BAdI,
einen Enhancement Point, einen User Exit oder eine prismat-Erweiterung
handelt und welches Interface verwendet werden soll.

Über den Knoten "Konfiguration" wird in das Report /PRIS/MAIN_BEF_CONFIG
gesprungen:

![Ein Bild, das Text, Zahl, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image34.png){width="5.4375in"
height="1.3333333333333333in"}

Die auszurufenden Klassen und deren Reihenfolge werden beim Abruf des
Reports generiert und in der /PRIS/BEF_CFG gespeichert.

Der Report dient dazu die Einträge zu aktivieren bzw. deaktivieren und
die Reihenfolge der aufzurufenden implementierenden Klassen anzupassen.

Über den Knoten „Übersicht" wird in das Programm /PRIS/MAIN_BEF_OVERVIEW
abgesprungen.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image35.png){width="5.4375in"
height="2.0520833333333335in"}

Es soll ein Interface mit dem Namen /PRIS/MAIN_IF_BEF erstellt werden.

Das Interface soll über die Methode GET_DEFINITION_DATA verfügen welche
einen Rückgabeparameter des Typen /PRIS/BEF_DEF enthält.

Zusätzlich soll der Änderungsmodus des Reports /PRIS/MAIN_BEF_CONFIG um
einen „Anlegen"-Button erweitert werden.

Sobald der Anwender auf diesen Button klickt, soll ein neues
Dialogfenster mit den folgenden Eingabefeldern eingeblendet werden:

- Erweiterungsart mit F4-Hilfe

- Name der Erweiterung mit F4-Hilfe

- Name des Interfaces mit F4-Hilfe

- Name der Klasse

Alle Felder des Dialogfensters sollen obligatorisch sein.

Die F4-Hilfe für den Namen des Interfaces soll die Tabelle /PRIS/BEF_DEF
als Datengrundlage verwende.

Sobald der Dialog bestätigt wird muss zunächst geprüft werden welche
Erweiterungsart ausgewählt wurde.

Wenn als Erweiterungsart „Business Add-In", „Classic BAdI" oder „User
Exit" ausgewählt wurde soll die \"Methode zum Prüfen, ob Implementierung
zu einem BAdI oder User Exit vorhanden ist\" aufgerufen werden, um zu
ermitteln, ob eine Implementierung angelegt werden muss.

Ist dies der Fall sollen die dafür benötigten Informationen über
zusätzliche Dialogfenster abgefragt werden.

Liegen alle benötigten Informationen vor, kann die Erstellung der
Implementierung über die \"Methode zum Anlegen einer Implementierung zu
einem BAdI oder User Exit\" erfolgen.

Im nächsten Schritt wird über die \"Methode zum Prüfen, ob ein
Z-Interface zu einem BAdI oder User Exit vorhanden ist\" geprüft ob zu
der Erweiterung schon ein Interface existiert.

Wenn dem so ist muss der im Dialogfenster eingegebene Interface-Name mit
dem Namen des Interfaces aus dem entsprechenden Datensatz der Tabelle
/PRIS/BEF_DEF verglichen werden.

Sind die Namen nicht identisch muss eine klassenbasierte Ausnahme
geworfen werden.

Falls noch kein Interface zur Erweiterung vorhanden ist, soll es über
die \"Methode zum Anlegen eines Z-Interfaces zu einem BAdI oder User
Exit\" angelegt werden.

Im Anschluss soll über die \"Methode zum Anlegen einer implementierenden
Klasse zu einem Z-Interface\" die Klasse zum Interface implementiert
werden.

Zum Abschluss sollen die angezeigten Daten aktualisiert werden, so dass
auch die ggf. neuangelegten Objekte angezeigt werden.

### Konfiguration

#### Konstanten- und Parameterwerte

Es gibt keine Konstanten- und Parameterwerte.

#### Schaltereinstellungen

Es gibt keine Schaltereinstellungen.

#### Protokollierung

  -----------------------------------------------------------------------
  Objekt                              Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN                          ERP/EWM/TM übergreifend

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  Sub-Objekt                          Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_BEF                      BEF: ERP/EWM/TM übergreifend

  -----------------------------------------------------------------------

#### Checkpoint-Gruppen

Es gibt keine Checkpoint-Gruppen

#### Tabellenpflege

Über den View /PRIS/BEF_DEFV erfolgt eine Zuordnung zwischen Enhancement
und Interface.

![](media/image36.png){width="5.427083333333333in" height="0.59375in"}

## GTB System

### Kontext

Die Klasse /PRIS/MAIN_CL_GTB_SYSTEM dient zur Abfrage von Systemdaten.

Dazu gehören die Art des Systems, die Art des Mandanten und die Art des
Pakets.

Je nach Methode werden entweder boolesche Werte zurückgegeben oder
Ausnahmen vom Typ /PRIS/CX_MAIN_GTB_SYSTEM geworfen.

### Prozessbeschreibung

Nach Instanziierung der Klasse /PRIS/MAIN_CL_GTB_SYSTEM über die
statische Methode GET_REFERENCE können die folgenden zwölf Methoden
aufgerufen werden:

- CHECK_DEVELOPMENT

  - Prüfen, ob es sich bei dem System um ein Entwicklungssystem handelt

- CHECK_OPEN

  - Prüfen, ob das System für Customizing geöffnet ist

- CHECK_PACKAGE_NOT_LOCAL

  - Prüfen, ob das übergebene Paket global ist

- IS_CUSTOMIZING

  - Gibt zurück, ob es sich um einen Customizing-Mandanten handelt

- IS_DEMO

  - Gibt zurück, ob es sich um einen Demo-Mandanten handelt

- IS_DEVELOPMENT

  - Gibt zurück, ob es sich um einen Entwicklungs-Mandanten handelt

- IS_OPEN

  - Gibt zurück, ob das System offen für Änderungen ist

- IS_PACKAGE_LOCAL

  - Gibt zurück, ob das Paket lokal ist

- IS_PRODUCTIVE

  - Gibt zurück, ob es sich um ein Produktivsystem handelt

- IS_SAP_REFERENCE

  - Gibt zurück, ob es sich um einen Referenz-Mandanten handelt

- IS_TEST

  - Gibt zurück, ob es sich um einen Test-Mandanten handelt

- IS_TRAINING

  - Gibt zurück, ob es sich um einen Trainings-Mandanten handelt

Die folgenden Methoden geben dieselben Informationen zurück und
unterscheiden sich nur bzgl. ihren Schnittstellen:

- CHECK_DEVELOPMENT und IS_DEVELOPMENT

- CHECK_OPEN und IS_OPEN

- CHECK_PACKAGE_NOT_LOCAL und IS_PACKAGE_LOCAL

### Ablaufbeschreibung

Zur Verwendung der Klasse /PRIS/MAIN_CL_GTB_SYSTEM muss diese im ersten
Schritt über die statische Methode GET_INSTANCE instanziiert werden.

![](media/image37.png){width="5.901388888888889in"
height="0.45902777777777776in"}

Nach der Instanziierung können über das entsprechende Objekt die
benötigten Methoden aufgerufen werden.

#### CHECK_DEVELOPMENT

Die Methode CHECK_DEVELOPMENT prüft, ob es sich bei dem System um ein
Entwicklungssystem handelt.

Die Schnittstelle der Methode umfasst nur eine Ausnahme vom Typ
/PRIS/CX_MAIN_GTB_SYSTEM.

![](media/image38.png){width="3.3546347331583553in"
height="0.5834142607174103in"}

#### CHECK_OPEN

Die Methode CHECK_OPEN prüft, ob das System für Änderungen geöffnet ist.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode die folgenden Import-Parameter:

![Ein Bild, das Text, Schrift, Zahl, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image39.png){width="5.901388888888889in"
height="1.45625in"}

#### CHECK_PACKAGE_NOT_LOCAL

Die Methode CHECK_PACKAGE_NOT_LOCAL prüft, ob das übergebene Paket
global ist.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Import-Parameter IV_DEVCLASS.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image40.png){width="3.4692344706911635in"
height="0.9063768591426071in"}

#### IS_CUSTOMIZING

Die Methode IS_CUSTOMIZING gibt zurück, ob es sich um einen
Customizing-Mandanten handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Screenshot enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image41.png){width="3.4171434820647417in"
height="0.9063768591426071in"}

#### IS_DEMO

Die Methode IS_DEMO gibt zurück, ob es sich um einen Demo-Mandanten
handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Screenshot enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image42.png){width="3.4692344706911635in"
height="0.9480489938757656in"}

#### IS_DEVELOPMENT

Die Methode IS_DEVELOPMENT gibt zurück, ob es sich um einen
Entwicklungs-Mandanten handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Screenshot enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image43.png){width="3.5734153543307086in"
height="0.9480489938757656in"}

#### IS_OPEN

Die Methode IS_OPEN gibt zurück, ob das System offen für Änderungen ist.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode die folgenden Parameter:

![Ein Bild, das Text, Schrift, Zahl, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image44.png){width="5.901388888888889in"
height="1.551388888888889in"}

#### IS_PACKAGE_LOCAL

Die Methode IS_PACKAGE_LOCAL gibt zurück, ob das übergebene Paket lokal
ist.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Import-Parameter IV_DEVCLASS und den
Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image45.png){width="3.5838331146106737in"
height="1.3022648731408575in"}

#### IS_PRODUCTIVE

Die Methode IS_PRODUCTIVE gibt zurück, ob es sich um ein Produktivsystem
handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image46.png){width="3.3963068678915134in"
height="0.9063768591426071in"}

#### IS_SAP_REFERENCE

Die Methode IS_SAP_REFERENCE gibt zurück, ob es sich um einen
Referenz-Mandanten handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image47.png){width="3.427561242344707in"
height="0.9063768591426071in"}

#### IS_TEST

Die Methode IS_TEST gibt zurück, ob es sich um einen Test-Mandanten
handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image48.png){width="3.4692344706911635in"
height="0.9272123797025372in"}

#### IS_TRAINING

Die Methode IS_TRAINING gibt zurück, ob es sich um einen
Trainings-Mandanten handelt.

Neben der Ausnahme vom Typ /PRIS/CX_MAIN_GTB_SYSTEM umfasst die
Schnittstelle der Methode den Rückgabe-Parameter RV_BOOL.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image49.png){width="3.406725721784777in"
height="0.9376312335958005in"}

### Konfiguration

Für diese Lösung ist keine Konfiguration notwendig.

## GTB - Kleine Werkzeuge

### Kontext

Neben den bisher vorgestellten ausgewachsenen Hilfs- und Werkzeugklassen
umfasst die General Toolbox auch noch fünf weitere kleine Klassen zur
Unterstützung von technischen Implementationen.

Dabei handelt es sich um die folgenden Klassen:

- /PRIS/MAIN_CL_GTB_CLASS_DET

- /PRIS/MAIN_CL_GTB_DATA

- /PRIS/MAIN_CL_GTB_ENQUEUE

- /PRIS/MAIN_CL_GTB_SALV

- /PRIS/MAIN_CL_GTB_SAP_GUI

### Prozessbeschreibung

Die Klasse /PRIS/MAIN_CL_GTB_CLASS_DET dient zur Ermittlung von Klassen,
die das übergebene Interface implementieren oder von der übergebenen
Klasse erben.

Die Klasse /PRIS/MAIN_CL_GTB_DATA dient zur Ermittlung von Informationen
zu übergebenen Datentypen.

Die Klasse /PRIS/MAIN_CL_GTB_ENQUEUE dient zum Erstellen von
Sperreinträgen, für Tabellen, für die keine Sperrobjekte existieren.

Es handelt sich hierbei somit um eine Klasse zur generischen Erstellung
von Sperreinträgen.

Die Klasse /PRIS/MAIN_CL_GTB_SALV dient zum vereinfachten Einsatz der
Standardklasse CL_SALV_TABLE.

Die Klasse /PRIS/MAIN_CL_GTB_SAP_GUI dient zur Unterstützung von
Entwicklungen im Dynpro-Umfeld.

### Ablaufbeschreibung

Zur Verwendung der jeweiligen Klasse muss diese im ersten Schritt
instanziiert werden.

Je nach Klasse geschieht dies über Anweisung CREATE OBJECT oder den
Aufruf der statischen Methode GET_INSTANCE.

#### /PRIS/MAIN_CL_GTB_CLASS_DET

Bei der Instanziierung der Klasse wird ein Interface- oder ein
Klassenname über den Parameter IV_BASE_CLASS übergeben.

Die Instanz-Methoden GET_POSSIBLE_CLASSES und GET_RANGE geben die Namen
der gefunden Klassen als Liste vom Typ /PRIS/MAIN_TT_GTB_LOGIC_CLASS
bzw. als Range vom Typ RSELOPTION zurück.

#### /PRIS/MAIN_CL_GTB_DATA

Die Instanz-Methode DESCRIBE_BY_NAME gibt zu dem übergebenen Namen eines
Datentyps (Datenelement, Struktur, Tabelle, Tabellentyp usw.) eine
Descriptor-Instanz zurück (Elternklasse CL_ABAP_TYPEDESCR).

Die Instanz-Methode DESCRIBE_BY_VALUE gibt zu der übergebenen Variable
eine Descriptor-Instanz zurück (Elternklasse CL_ABAP_TYPEDESCR).

Die Instanz-Methode GET_DOMVALUE_TEXT gibt zu dem übergebenen
Domänennamen und -wert die Beschreibung des Domänenwertes in der
übergebenen Sprache zurück.

Die Instanz-Methode GET_INTERNAL_TYPE_BY_NAME gibt zu dem übergebenen
Namen eines Datentyps (Datenelement, Struktur, Tabelle, Tabellentyp
usw.) den internen ABAP-Datentyp zurück.

Die Instanz-Methode GET_INTERNAL_TYPE_BY_VALUE gibt zu der übergebenen
Variable den internen ABAP-Datentyp zurück.

Die Instanz-Methode GET_TABLE_FIELDS_BY_NAME gibt zu dem übergebenen
Namen einer Tabelle oder einer Struktur eine Liste der Felder vom Typ
DDFIELDS zurück.

Die Instanz-Methode GET_TABLE_FIELDS_BY_VALUE gibt zu der übergebenen
Variable einer Tabelle oder einer Struktur eine Liste der Felder vom Typ
DDFIELDS zurück.

#### /PRIS/MAIN_CL_GTB_ENQUEUE

Bei der Instanziierung der Klasse werden über den Parameter IT_RSTABLE
vom Typ /PRIS/MAIN_TT_GTB_RSTABLE 1 bis n Tabellennamen und
Schlüsselzeichenketten (Alle Werte der Schlüsselfelder als ein String)
übergeben.

Die Instanz-Methode SET_LOCK dient zum Setzen der Sperr(en).

Die Instanz-Methode RESET_LOCK dient zum Aufheben der Sperr(en).

#### /PRIS/MAIN_CL_GTB_SALV

Die Instanz-Methode BUILD_CONTAINER dient zur Erzeugung einer Instanz
der Klasse CL_SALV_TABLE, zum Setzen von Einstellungen der Instanz und
zur Anzeige des SALV-Grids.

Die Instanz-Methode GET_SELECTED_ROWS gibt die markierten Zeilen des
SALV-Grids zurück.

Die Instanz-Methode LOAD_CONTAINER dient zur Initialisierung von einem
Custom Container, zur Initialisierung eines ALV-Grids, zum Anzeigen des
ALV-Grids.

Die Instanz-Methode SET_FUNCTIONS_STATUS dient zur Steuerung, welche
Funktionen des SALV-Grids angezeigt und aktiviert werden sollen.

Die Instanz-Methode SET_SELECTED_ROWS dient zur Markierung von Zeilen
des SALV-Grids.

#### /PRIS/MAIN_CL_GTB_SALV

Die Methode CALL_POPUP_GET_VALUES dient zur Anzeige eines Dialogfensters
mit Eingabefeldern zu allen Feldern einer Struktur.

## Easy Mapper

### Kontext

Der Easy-Mapper ist ein Tool für Entwickler zum Konvertieren von
EWM-Objekten. Die Funktionalitäten können als Methodenaufrufe im Code
eines jeden Programms verwendet werden.

### Prozessbeschreibung

Im SAP-Standard existiert eine Vielzahl an Konvertierungs-Klassen und
Funktionsbausteinen. Für neue Mitarbeiter sind einige dieser
Möglichkeiten zum Konvertieren oft nicht direkt ersichtlich.

Zusätzlich führt diese Vielzahl an Möglichkeiten dazu, dass es keinen
einheitlichen Einstiegspunkt für Konvertierungen gibt.

Hier greift der Easy-Mapper, der für die wichtigsten EWM-Objekte eine
einheitliche Vorgehensweise zur Verfügung stellt. Dazu gehören die
folgenden Objekte:

- Lieferbelege

- Positionsnummern

- Handling Unit-Identifikationen

- Produktnummern (EWM & APO)

- Chargen

### Ablaufbeschreibung

Über ein Objekt des Easy-Mappers kann eine beliebige Methode zum
Konvertieren eines EWM-Objektes aufgerufen werden.

Der Easy-Mapper unterstützt dabei sowohl Einzel- als auch
Mehrfach-Konvertierungen, wobei bei Einzelkonvertierungen eine Ausnahme
ausgelöst wird, wenn die Konvertierung fehlschlägt.

Bei der Mehrfach-Konvertierung hingegen wird eine Ausnahme nur
ausgelöst, wenn bei jedem Wert die Konvertierung fehlschlägt.

Ergänzend stehen Methoden zur Verfügung, um Selektions-Ranges in die für
die Methoden-Parameter vorgesehen Tabellen zu konvertieren.

Zudem existiert ein Report, über den ein Nutzer auf einem Bildschirm
seine gewünschte Konvertierungsart per Buttonklick auswählen und die
Werte auf einem spezifischen Selektionsbild eingeben kann, sodass er
anschließend die Ergebnisse per ALV-Grid angezeigt bekommt. Der Report
ist über die Transaktion /PRIS/EWM_MAP aufrufbar.

### Konfiguration

#### Protokollierung

  -----------------------------------------------------------------------
  Log-Objekt                          Log-Subobjekt
  ----------------------------------- -----------------------------------
  /PRIS/EWM                           /PRIS/EWM_MAP

  -----------------------------------------------------------------------

#### Checkpoint-Gruppen

  -----------------------------------------------------------------------
  Checkpoint-Gruppe                   Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/EWM                           Extended Warehouse Management

  /PRIS/EWM_CORE                      Prozessübergreifende Objekte

  /PRIS/EWM_MAP                       Easy Mapper
  -----------------------------------------------------------------------

## RFC Hilfsklasse

### Kontext

Wenn eine Implementierung im EWM-System Funktionsbausteine im ERP-System
aufrufen soll, muss dafür die RFC-Destination des ERP-Systems bekannt
sein.

Damit nicht jede Implementierung die RFC-Destination selber ermitteln
muss, wird als Teil von BASE001h eine Hilfeklasse für die
ERP-Kommunikation implementiert, in der die Ermittlung der
RFC-Destination gekapselt ist.

### Prozessbeschreibung

Die Hilfsklasse zur ERP-Kommunikation stellt öffentliche Methoden zur
Verfügung, mit denen jeweils das logische System und die RFC-Destination
des ERP-Systems ermittelt werden können.

Zur Verwendung der Klasse muss nur die Lagernummer bekannt sein.

### Ablaufbeschreibung

Die Hilfsklasse zur ERP-Kommunikation stellt öffentliche Methoden zur
Verfügung, mit denen jeweils das logische System und die RFC-Destination
des ERP-Systems ermittelt werden können.

Zu übergeben ist der Hilfsklasse zwingend nur die Lagernummer.

Optional kann auch das Applikations-Log-Objekt des Aufrufers übergeben
werden -- andernfalls erzeugt die Klasse ein eigenes.

Mit der zurückgegebenen RFC-Destination ist es möglich, RFC-fähige
Funktionsbausteine im ERP-System aufzurufen.

### Konfiguration

#### Protokollierung

  -----------------------------------------------------------------------
  Log-Objekt                     Log-Subobjekt
  ------------------------------ ----------------------------------------
  /PRIS/EWM                      /PRIS/EWM_HLP_RFC

  -----------------------------------------------------------------------

#### Checkpoint-Gruppen

  -----------------------------------------------------------------------
  Checkpointgruppe                  Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/EWM                         Extended Warehouse Management

  /PRIS/EWM_EXT                     external systems
  -----------------------------------------------------------------------

# [Implementierung]{.mark}

## Key Values - Schlüsselwerte

### Ablaufbeschreibung

Schlüsselwerte werden über die Pflege-View /PRIS/KEY_VALUEV eingestellt.
Dafür steht ein Pflegedialog zur Verfügung welche entweder über die
Transaktion SM30 oder direkt über die Transaktion /PRIS/KEY_VALUE, der
der Pflegedialog zugewiesen ist, aufgerufen werden kann.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image1.png){width="5.901388888888889in"
height="2.2930555555555556in"}

Beachten Sie bitte, dass es sich bei der Tabelle hinter der Pflege-View
um eine mandantenspezifische Customizing-Tabelle handelt und somit zum
Ändern der Daten ein Customizing-Transport benötigt wird.

## CFG -- Konfigurations-Framework

### Ablaufbeschreibung

Im ersten Schritt müssen Schlüsselwerte über die Pflege-View
/PRIS/KEY_VALUEV eingestellt werden. Dafür steht ein Pflegedialog zur
Verfügung welcher über die Transaktion /PRIS/KEY_VALUE aufgerufen werden
kann.

Beachten Sie bitte, dass es sich bei der Tabelle hinter der Pflege-View
/PRIS/KEY_VALUEV um eine mandantenspezifische Customizing-Tabelle
handelt und somit zum Ändern der Daten ein Customizing-Transportauftrag
benötigt wird.

Die Pflege der lösungspezifischen Tabellen erfolgt über jeweils eigene
Transaktionen. Dabei sind die Tabellen in die drei Schritte
„Definition", „Werte zu Konstanten hinterlegen" und „Werte zu Parametern
hinterlegen" zu unterteilen.

**Definition:**

- Definition von Attributen

- Zuordnung von Attributen zu Programmobjekten

**Werte zu Konstanten hinterlegen:**

- Erfassung von Gruppenwerten zu Konstanten

- Erfassung von Einzelwerten zu Konstanten

**Werte zu Parametern hinterlegen:**

- Erfassung von Gruppenwerten zu Parametern

- Erfassung von Einzelwerten zu Parametern

Grundsätzlich muss immer zuerst eine Definition erfolgen bevor ein Wert
hinterlegt werden kann.

Beachten Sie bitte, dass die Tabellen im Schritt „Definition"
mandantenübergreifende Customizing-Tabellen sind und somit zum Ändern
der Daten Workbench-Transportaufträge benötigt werden.

Beachten Sie darüber hinaus bitte auch, dass die Tabellen im Schritt
„Werte zu Konstanten hinterlegen" dagegen mandantenspezifische
Customizing-Tabellen sind und somit zum Ändern der Daten
Customizing-Transportaufträge benötigt werden.

## SWT -- Schalter-Framework

### Ablaufbeschreibung

Im ersten Schritt müssen Schlüsselwerte über den Pflege-View
/PRIS/KEY_VALUEV eingestellt werden. Dafür steht ein Pflegedialog zur
Verfügung welcher über die Transaktion /PRIS/KEY_VALUE aufgerufen werden
kann.

Beachten Sie bitte, dass es sich bei der Tabelle hinter dem Pflege-View
um eine mandantenspezifische Customizing-Tabelle handelt und somit zum
Ändern der Daten ein Customizing-Transportauftrag benötigt wird.

Zur Definition der Erweiterungen wird der View-Cluster /PRIS/SWT_DEFVC
verwendet. Der View-Cluster kann direkt über die Transaktion
/PRIS/SWT_DEF aufgerufen werden.

![Ein Bild, das Text, Screenshot, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image50.png){width="5.901388888888889in"
height="1.8291666666666666in"}

Zur Konfiguration von Erweiterungen wird der View-Cluster
/PRIS/SWT_CONFVC verwendet. Die View-Cluster werden über die Transaktion
/PRIS/SWT_CONF aufgerufen.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image51.png){width="5.901388888888889in"
height="1.3569444444444445in"}

Bei der Konfiguration handelt es sich um Stammdaten. Somit wird kein
Transportauftrag zur Pflege benötigt.

## SDT Adjustment Report

### Ablaufbeschreibung

Der Report /PRIS/MAIN_SDT_ADJUSTMENT wird nur in Systemen ausgeführt, in
den die Lösungen der Rakete über externe Transporte eingespielt wurden.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image13.png){width="5.901388888888889in"
height="2.0805555555555557in"}

Sind die Lösungen der Rakete über die reguläre Transportschiene
übertragen worden, ist es in der Regel nicht nötig diesen Report
auszuführen.

Zur Ausführung des Reports müssen im ersten Schritt die Nummern der
externen Workbench-Transporte identifiziert und im Feld
„Auftrag/Aufgabe" werden.

![](media/image14.png){width="5.901388888888889in"
height="0.3715277777777778in"}

Als „Originalsystem" wird der Name des Systems eingetragen, in das die
Lösungen eingespielt wurden.

![](media/image15.png){width="3.9172134733158357in"
height="0.3021259842519685in"}

Normalerweise ist das Feld bei Programmstart mit dem richtigen Wert
vorbelegt.

Über das Feld Transportschicht wird die Transportschicht eingetragen:

![](media/image16.png){width="3.3650524934383204in"
height="0.3229615048118985in"}

Das Feld verfügt über eine F4-Hilfe.

Über die Checkbox „Attribute anpassen" wird gesteuert, ob
Transportschicht und Quellsystem bei den Objekten angepasst werden
sollen:

![](media/image17.png){width="1.375191382327209in"
height="0.27087160979877517in"}

Über die Checkbox „Zu Transport hinzufügen" wird gesteuert, ob die
Objekte in einem Transport aufgenommen werden sollen:

![](media/image18.png){width="1.614808617672791in"
height="0.2604527559055118in"}

Sobald die Selektion mit F8 oder dem Button
![](media/image19.png){width="0.20836286089238845in"
height="0.21878062117235345in"} bestätigt wird, werden im ersten Schritt
alle Objekte aus den angegebenen Transporten eingelesen.

Wenn die Checkbox „Attribute anpassen" gesetzt ist werden alle Einträge
aus den Tabellen TADIR und TDEVC zu den Objekten eingelesen.

Es werden nur Einträge berücksichtigt, welche als Quellsystem eines der
prismat-Systeme hinterlegt haben.

Objekte, bei denen das Quellsystem bereits angepasst wurde, werden somit
bei einem weiteren Programmlauf nicht noch einmal angepasst.

Bei den Einträgen der entsprechenden Objekte werden die Felder
„Originalsystem" und Transportschicht entsprechend angepasst und auf die
Datenbank fortgeschrieben.

Wenn die Checkbox „Zu Transport hinzufügen" gesetzt ist wird ein modales
Dialogfenster zur Auswahl des Workbench-Transports angezeigt.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image20.png){width="3.858267716535433in"
height="1.4210750218722659in"}

Konnten alle ausgewählten Aktionen erfolgreich ausgeführt werden, wird
in der Statuszeile die Meldung „Erledigt" angezeigt.

Andernfalls wird in der Statuszeile die entsprechende Fehlermeldung
angezeigt.

**[Hinweis:]{.underline}**

Der Report /PRIS/MAIN_SDT_ADJUSTMENT ist **nur** für
Workbench-Transporte vorgesehen. Sollen auch Einträge aus externen
Customizing-Transporten in interne Customizing-Transporte, welche über
die Transportschicht in weitere Systeme übertragen werden, übernommen
werden muss dies manuell über die entsprechenden Standardtransaktionen
(z.B. SE01, SE10 usw.) erfolgen.

## Wizard

### Ablaufbeschreibung

Der Wizard stellt ein Interface bereit, über das Klassen implementiert
werden können, welche die Basis-Konfiguration der jeweiligen Lösungen
abbilden. Alle Klassen, die dieses Interface implementieren, werden
dynamisch zur Laufzeit ermittelt. Diese Klassen werden als
„Assistentenklassen" bezeichnet.

Für die jeweilige Lösung wird eine Ausgabeliste mit relevanten
Informationen zu dem Konfigurationsstand erwartet.

Nachdem der Benutzer die Konfiguration gestartet hat, wird ein modaler
Dialog mit einer dynamisch generierten Eingabemaske eingeblendet, über
die die erforderlichen Daten erfasst werden können.

Die durch den Benutzer erfassten Konfigurationseinträge werden in die
jeweiligen Datenbanktabellen geschrieben. Falls erforderlich, werden die
Daten auch in einem Transportauftrag fortgeschrieben werden.

Nach der erfolgreichen Durchführung der Konfiguration wird dem Benutzer
eine aktualisierte Ergebnisliste angezeigt.

## Generische Tabellenleseklasse

### Ablaufbeschreibung

Um mehrere Zeilen aus einer Tabelle mit der generischen
Tabellenleseklasse einzulesen sind die folgenden Schritte nötig:

1.  Instanziieren:\
    ![](media/image52.png){width="5.895833333333333in"
    height="2.1354166666666665in"}

2.  Daten aus Puffer holen:\
    ![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
    generierte
    Beschreibung](media/image53.png){width="5.901388888888889in"
    height="3.5701388888888888in"}

3.  Daten in Ziel-Datentyp übernehmen:\
    ![](media/image54.png){width="2.6770833333333335in"
    height="0.3854166666666667in"}

Um eine einzelne Zeile aus einer Tabelle mit der generischen
Tabellenleseklasse einzulesen sind die folgenden Schritte nötig:

1.  Instanziieren:\
    ![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
    generierte
    Beschreibung](media/image52.png){width="5.895833333333333in"
    height="2.1354166666666665in"}

2.  Daten aus Puffer holen:\
    ![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
    generierte
    Beschreibung](media/image55.png){width="5.239583333333333in"
    height="2.3333333333333335in"}

3.  Daten in Ziel-Datentyp übernehmen (mehrere Zeilen):\
    ![](media/image56.png){width="3.9895833333333335in"
    height="0.40625in"}

Beispiel:

![Ein Bild, das Text, Screenshot, Schrift enthält. Automatisch
generierte Beschreibung](media/image57.png){width="5.895833333333333in"
height="5.5in"}

## Transport Order Tool

### Ablaufbeschreibung

Da es sich bei dem Transport Order Tool um eine Hilfsklasse handelt
werden in diesem Kapitel nur ihre wichtigsten Funktionen beschrieben.

#### Instanziierung

Die Instanziierbarkeit der Klasse /PRIS/MAIN_CL_TOT ist öffentlich und
der Konstruktor umfasst keinerlei Parameter. Daher kann die
Instanziierung einfach über CREATE OBJECT oder NEW erfolgen.

![](media/image58.png){width="3.4692344706911635in"
height="0.29170713035870516in"}

#### Kopfdaten der Transporte einlesen

Zur Ermittlung der Kopfdaten stehen die Methoden GET_HEADERS und
GET_HEADER_WITH_TEXT zur Verfügung.

Die Methode GET_HEADERS gibt die Kopfdaten zu mehreren Transporten
zurück.

Der Importparameter IRT_TRKORR ist vom Typ RSELOPTION.

Der Rückgabeparameter RT_E070 ist vom Typ E070_T.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image59.png){width="5.573694225721785in"
height="1.3126837270341207in"}

Werden zu den übergebenen Transporten kein Kopfdaten gefunden wird eine
leere Ergebnismenge zurückgegeben.

Die Methode GET_HEADER_WITH_TEXT gibt die Kopfdaten und die Beschreibung
zu einem Transport zurück.

Der Importparameter IV_TRKORR ist vom Typ TRKORR und der optionale
Importparameter IV_LANGUAGE ist vom Typ SYLANGU.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image60.png){width="4.021394356955381in"
height="3.2191994750656168in"}

Werden zu dem Transport keine Daten gefunden wird die klassische
Ausnahme NOT_FOUND mit einer entsprechenden Fehlermeldung geworfen.

#### Übersetzungsobjekte einlesen

Zur Ermittlung der Übersetzungsobjekte stehen die Methoden
GET_TRANSLATION_OBJECTS und GET_TRANSLATION_OBJECTS_TRKORR zur
Verfügung.

Die Methode GET_TRANSLATION_OBJECTS ermittelt zu den übergebenen
Objekten zusätzliche Übersetzungsobjekte und gibt diese zurück.

Der Importparameter IT_OBJECT ist vom Typ E071_T und der optionale
Parameter IV_SPRAS ist vom Typ SYLANGU.

Der Rückgabeparameter RT_OBJECT ist vom Typ E071_T.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image61.png){width="5.46951334208224in"
height="0.7917771216097987in"}

Werden keine Übersetzungsobjekte gefunden wird eine leere Ergebnismenge
zurückgegeben.

Die Methode GET_TRANSLATION_OBJECTS ermittelt zu den übergebenen
Objekten zusätzliche Übersetzungsobjekte und gibt diese zurück.

Der Importparameter IV_TRKORR ist vom Typ TRKORR und der optionale
Parameter IV_SPRAS ist vom Typ SYLANGU.

Der Rückgabeparameter RT_OBJECT ist vom Typ E071_T.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image62.png){width="5.75080271216098in"
height="0.645923009623797in"}

Werden keine Übersetzungsobjekte gefunden wird eine leere Ergebnismenge
zurückgegeben.

#### Objekte und Einträge einlesen

Zur Ermittlung der Objekte und Einträge von Transporten stehen die
Methoden GET_DATA_MULTIPLE und GET_DATA_SINGLE zur Verfügung.

Die Methode GET_DATA_MULTIPLE ermittelt zu den übergebenen Kopfdaten
eines Transportes oder von mehreren Transporten die Objekte und
Einträge.

Der Import-Parameter IT_HEADER ist vom Typ E070_T.

Die beiden optionalen Import-Parameter IV_FLG_OBJECTS und IV_FLG_ENTRIES
sind vom Typ BOOLE_D.

Der Export-Parameter ET_OBJECT ist vom Typ E071_T und der
Export-Parameter ET_ENTRY ist vom Typ E071K_T.

![Ein Bild, das Text, Screenshot, Schrift, Quittung enthält.
KI-generierte Inhalte können fehlerhaft
sein.](media/image63.png){width="3.1983628608923884in"
height="1.7398261154855643in"}

Wurden keine Objekte zu den Transporten gefunden enthält ET_OBJECT eine
leere Ergebnismenge.

Wurden keine Einträge zu den Transporten gefunden enthält ET_ENTRY eine
leere Ergebnismenge.

Die Methode GET_DATA_SINGLE ermittelt zu dem übergebenen Transport die
Kopfdaten, Objekte und Einträge.

Der Import-Parameter IV_TRKORR ist vom Typ TRKORR.

Die drei optionalen Import-Parameter IV_FLG_HEADER, IV_FLG_OBJECTS und
IV_FLG_ENTRIES sind vom Typ BOOLE_D.

Der Export-Parameter ES_HEADER ist vom Typ E070.

Der Export-Parameter ET_OBJECT ist vom Typ E071_T und der
Export-Parameter ET_ENTRY ist vom Typ E071K_T.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image64.png){width="3.06292760279965in"
height="2.073206474190726in"}

Wurden keine Kopfdaten gefunden wird für ES_HEADER eine initiale
Struktur zurück gegeben.

Wurden keine Objekte zu den Transporten gefunden enthält ET_OBJECT eine
leere Ergebnismenge.

Wurden keine Einträge zu den Transporten gefunden enthält ET_ENTRY eine
leere Ergebnismenge.

#### Dialog zur Transportauswahl einblenden

Die Methode OPEN_ORDER_DIALOG dient zur grafischen Auswahl eines
Transports.

Die vier optionalen Import-Parameter IV_ORDER_TYPE_WORKBENCH,
IV_ORDER_TYPE_CUSTOMIZING, IV_TASK_TYPE_DEVELOPTMENT und
IV_TASK_TYPE_REPAIR sind vom Typ BOOLE_D.

Über IV_ORDER_TYPE_WORKBENCH und IV_ORDER_TYPE_CUSTOMIZING wird
gesteuert, ob ein Workbench- oder ein Customizing-Transport ausgewählt
werden soll.

Daher dürfen die beiden Parameter nicht beide auf ABAP_TRUE oder
ABAP_FALSE gesetzt werden.

Über IV_TASK_TYPE_DEVELOPTMENT und IV_TASK_TYPE_REPAIR wird gesteuert,
ob eine Transportaufgabe vom Typ Entwicklung oder Reparatur ausgewählt
werden soll.

Daher dürfen die beiden Parameter nicht beide auf ABAP_TRUE oder
ABAP_FALSE gesetzt werden.

**Hinweis:\**
IV_TASK_TYPE_DEVELOPTMENT und IV_TASK_TYPE_REPAIR sind nur für
Workbench-Transporte relevant.

Wenn also IV_ORDER_TYPE_WORKBENCH auf ABAP_TRUE gesetzt wird kann die
Angabe von IV_TASK_TYPE_DEVELOPTMENT und IV_TASK_TYPE_REPAIR entfallen.

Die beiden Export-Parameter EV_ORDER und EV_TASK sind vom Typ TRKORR.

Der Export-Parameter EV_CANCELED ist vom Typ BOOLE_D.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image65.png){width="5.052788713910761in"
height="3.958885608048994in"}

Über den Dialog hat der Nutzer die Möglichkeit einen bestehenden
Transport auszuwählen oder einen neuen Transport zu erstellen.

![Ein Bild, das Text, Screenshot, Schrift, Display enthält.
KI-generierte Inhalte können fehlerhaft
sein.](media/image66.png){width="5.901388888888889in"
height="2.1847222222222222in"}

Wird die Eingabe abgebrochen wird der Export-Paramater EV_CANCELED auf
ABAP_TRUE gesetzt.

#### Objekte und Einträge in einem Transport einfügen

Die Methode INSERT_INTO_ORDER dient dazu Objekte und Einträge in einem
Transport einzufügen.

Der Import-Parameter IV_TRKORR ist vom Typ TRKORR.

Der Import-Parameter IT_OBJECT ist vom Typ E071_T und der
Import-Parameter IT_ENTRY ist vom Typ E071K_T.

Der optionale Parameter IV_CLIENT ist vom Typ SYMANDT.

Der optionale Parameter IV_LANGUAGE ist vom Typ SYLANGU.

Der optionale Parameter IV_OVERWRITE ist vom Typ BOOLE_D.

Wird IV_OVERWRITE auf ABAP_FALSE (default) gesetzt werden die Objekte
und Einträge dem aktuellen Inhalt des Transports hinzugefügt.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image67.png){width="3.9276312335958004in"
height="3.615087489063867in"}

Wurde der in IV_TRKORR angegebene Transport nicht gefunden wird die
klassische Ausnahme NOT_FOUND geworfen.

Ist beim Einfügen der Objekte oder Einträge ein Fehler aufgetreten wird
die klassische Ausnahme INSERTION_FAILED geworfen.

## Generische Suchhilfe

### Ablaufbeschreibung

Ist für eine Suchhilfe die Datenbeschaffung nicht über Datenbanktabellen
oder Views möglich muss ein Suchhilfe-Exit erstellt werden.

Dabei handelt es sich um einen Funktionsbaustein mit einer fest
definierten Schnittstelle, welcher in der jeweiligen Suchhilfe
hinterlegt wird.

Die Schnittstelle umfasst die folgenden Parameter:

- Changing:

  - SHLP vom Typ SHLP_DESCR

  - CALLCONTROL vom Typ DDSHF4CTRL

- Tables

  - SHLP_TAB vom Typ SHLP_DESCT

  - RECORD_TAB vom Typ SEAHLPRES

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image68.png){width="5.901388888888889in"
height="1.0743055555555556in"}

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image69.png){width="5.901388888888889in"
height="1.4027777777777777in"}

In dem Funktionsbausteins werden bestimmte Programmblöcke zur Ausführung
der Schrittfolge einer Suchhilfe erwartet.

Diese Lösung umfasst daher eine Basisklasse für die Umsetzung der
Schrittfolge der Ausführungslogik.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image70.png){width="4.566929133858268in"
height="1.847636701662292in"}

Die Methode EXECUTE_LOGIC ruft die entsprechenden Methoden anhand der
Schrittfolge auf:

![Ein Bild, das Text, Screenshot, Display, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image71.png){width="4.133858267716535in"
height="5.008987314085739in"}

Somit müssen ableitende Klassen nur eine oder mehrere der folgenden
geschützten Methoden redefinieren:

- EXECUTE_STEP_CHOOSE_SH

- EXECUTE_STEP_DISPLAY

- EXECUTE_STEP_SELECT

- EXECUTE_STEP_SELECT_COND

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image72.png){width="4.724409448818897in"
height="2.1709514435695536in"}

Die geschützte Methode MAP_TO_RESULT_TAB dient dazu die Ergebnismenge
der Datenselektion in die Datenstrukturen der Suchhilfe zu überführen.

![Ein Bild, das Text, Elektronik, Screenshot, Software enthält.
KI-generierte Inhalte können fehlerhaft
sein.](media/image73.png){width="5.433070866141732in"
height="4.2017104111986in"}

Die Lösung umfasst zusätzlich die Suchhilfe
/PRIS/MAIN_SH_GSH_EXAMPL_T100 den Suchhilfe-Exit
/PRIS/MAIN_SH_GSH_EXAMPL_T100 und die Klasse /PRIS/MAIN_CL_GSH_FIELD.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image74.png){width="5.118110236220472in"
height="3.160119203849519in"}

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image75.png){width="5.708661417322834in"
height="4.576062992125984in"}

## CSV-Handling

### Ablaufbeschreibung

**Schritt 1:**\
Im Konstruktor der Klasse */PRIS/MAIN_CL_GTB_CSV_HANDLING* muss ein
Applikationlog sowie der Schlüsselwert und die Schlüsselart übergeben
werden.

**Schritt 2:**\
Als nächstes muss die Methode *SETUP* aufgerufen werden. In dieser muss
der Parameter *IV_USE_GUI* übergeben werden. Dieser gibt an, ob der
Prozess eine lokale Datei oder eine Datei von einem Server verarbeiten
soll.\
Zusätzlich gibt es noch drei optionale Parameter *IV_IGNORE_FIRST_LINE*,
*IV_SEPERATOR* und *IV_ESCAPE*.\
*IV_IGNORE_FIRST_LINE* muss gesetzt werden, wenn die erste Zeile beim
Lesen einer CSV-Datei ignoriert werden soll, z.B. wenn in der ersten
Zeile die Spaltennamen stehen.\
*IV_SEPERATOR* gibt das Trennsymbol der CSV-Datei an.\
*IV_ESCAPE* gibt das Escapezeichen an.

**Schritt 3:\**
Als nächstes wird entweder die Methode *READ_CSV* (CSV-Datei lesen) oder
*WRITE_CSV* (CSV-Datei schreiben) ausgeführt.

I.: READ_CSV

> 1\. In der Methode wird ein Dateipfad und ein Dateiname erwartet.
> Damit wird die Datei entweder aus den lokalen Dateien oder vom
> Applikationsserver geladen.
>
> 2\. Zum Schluss wird die eingelesene Datei an die Methode
> *BUILD_TABLE_FROM_CSV* übergeben, die nun abschließend die CSV-Datei
> in eine ABAP-Tabelle umwandelt und diese zurückgibt.
>
> II.: WRITE_CSV
>
> 1\. Die Methode benötigt eine ABAP-Tabelle und einen Dateinamen.
>
> 2\. Die Methode *CONVERT_TABLE_TO_CSV* konvertiert die interne\
> Tabelle in das CSV-Format.
>
> 3\. Die Tabelle im CSV-Format wird unter dem mitgegeben Dateinamen
> entweder lokal oder auf dem Applikationsserver gespeichert.

[\
Testprogramm */PRIS/MAIN_GTB_CSV_HANDLING*]{.underline}

Um das Testprogramm nutzen zu können muss eine Verarbeitungsklasse
erstellt werden, welche die Schnittstelle
*/PRIS/MAIN_IF_GTB_CSV_HANDLING* implementiert.![Ein Bild, das Text,
Screenshot enthält. Automatisch generierte
Beschreibung](media/image76.png){width="5.901388888888889in"
height="3.38125in"}

In den Grundeinstellungen muss die Schlüsselart, der Schlüsselwert sowie
die zu nutzende Verarbeitungsklasse angegeben werden.

Über die CSV-Einstellungen kann man zwischen dem Lesen und dem Schreiben
einer CSV-Datei auswählen. Außerdem werden dort die Tabellenstruktur und
der Dateipfad der Datei angegeben. In den optionalen Einstellungen kann
man das Trennzeichen und das Escapezeichen ändern.

Um eine CSV-Datei mit dem Testprogramm zu Lesen, muss die Methode
*PROCESSS_AFTER_READ* implementiert werden. Diese bekommt eine
ABAP-Tabelle mit den CSV-Daten der ausgewählten Datei zurück.\
Zusätzlich werden noch der Dateipfad, die Struktur sowie die
Schlüsselart und der Schlüsselwert übergeben.

Zum Schreiben (Erstellen) einer CSV-Datei ist es notwendig, dass die
Methode *PROCESS_BEFORE_WRITE* implementiert ist. In dieser bekommt man
die Schlüsselart und den Schlüsselwert zur Verfügung gestellt und gibt
eine ABAP-Tabelle zurück.

## Access Control Definition - Zugriffsfolgen

### Ablaufbeschreibung

Zur Instanziierung der Klasse wird die statische Methode GET_INSTNACE
aufgerufen. Es muss mindestens ein Schlüsselfeld und -wert der
Suchfolgetabelle und die Namen der Daten- und Suchfolgetabelle übergeben
werden. In der Methode wird geprüft, ob bereits eine Instanz mit den
gleichen Daten existiert. Dies soll häufige Zugriffe auf die Datenbank
durch diese Lösung minimieren.

Optional können Vergleichsoperatoren mit Feldbezeichner für die
Filterung übergeben werden.

Beim Erzeugen einer neuen Instanz, wird durch die übergebenen Schlüssel
und eventuell Vergleichsoperatoren, dynamisch eine WHERE-Bedingung zur
Filterung der Daten. Dadurch wird die Datenmenge, die später während der
Ermittlung der Daten von der Logik durchlaufen wird, minimiert und sorgt
somit für eine bessere Performance.

Im nächsten Schritt erfolgt die Datenermittlung, welche durch den
Aufrufer über die Methoden GET_DATA oder GET_DATA_MULT angestoßen wird.

Es muss eine Struktur vom Typ der Datentabelle, gefüllt mit
Selektionsdaten übergeben werden. Zusätzlich können Vergleichsoperatoren
über den Parameter IT_FIELD_COMPARE_OPERATORS für die jeweiligen Felder
übergeben werden, falls nicht auf Gleichheit zwischen Selektionsdaten
und Daten geprüft werden soll.

Pro Eintrag der Suchfolgentabelle wird für jedes angekreuzte Feld, der
jeweilige Wert des entsprechenden Feldes der Datentabelle mit dem
jeweiligen Wert des Feldes der Selektionsdaten verglichen. Wird eine
Zeile der Datentabelle als passend ermittelt, werden alle Felder, die in
der Suchfolge nicht angekreuzt waren, auf Initialwert geprüft. Hierbei
kann über den Importparameter IV_CHECK_KEYFIELDS gesteuert werden, ob
Schlüssel oder Nicht-Schlüsselfelder auf Initialwerte geprüft werden
sollen. Sind die Felder nicht initial und beinhalten keine Wildcards
(**\***), wird die Zeile als nicht passend angesehen und die nächste
Zeile (falls vorhanden) der Datentabelle wird mit den Selektionsdaten
abgeglichen.

## Generischer Löschreport

### Ablaufbeschreibung

Der Report /PRIS/MAIN_GTB_RTAB wird über die Transaktion
/PRIS/MAIN_GTB_RTAB gestartet.

Im Selektionsbild des Reports müssen eine Schlüsselart und ein
Schlüsselwert eingegeben werden.

![Ein Bild, das Text, Screenshot, Software, Computersymbol enthält.
Automatisch generierte
Beschreibung](media/image29.png){width="5.901388888888889in"
height="2.870138888888889in"}

Nach Bestätigung der Eingabe liest der Report die Einstellungen aus der
Tabelle /PRIS/GTB_RTABC ein und verwirft ungültige Einträge.

![Ein Bild, das Text, Software, Computersymbol, Zahl enthält.
Automatisch generierte
Beschreibung](media/image31.png){width="5.901388888888889in"
height="2.4444444444444446in"}

Falls nicht alle Tabellen verworfen wurden, wird im Anschluss pro
Tabelle der Löschvorgang ausgeführt.

Bei Tabellen ohne hinterlegte Klassen werden alle Einträge gelöscht, die
ihre maximale Lebenszeit in Tagen überschritten haben.

Die Tabelle /PRIS/GTB_RTABC umfasst die folgenden Spalten:

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  KEY_TYPE                            Schlüsselart

  KEY_VALUE                           Schlüsselwert

  TABNAME                             Tabellenname

  FIELDNAME                           Feldname

  OLDER_DAYS                          älter als \[in Tagen\]

  CLASSNAME                           Klassenname

  INACT                               Inaktivkennzeichen
  -----------------------------------------------------------------------

Klassen, welche in der Spalte CLASSNAME hinterlegt werden sollen, müssen
das Interface /PRIS/MAIN_IF_GTB_RTAB implementieren.

![Ein Bild, das Text, Schrift, Zahl, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image77.png){width="5.901388888888889in" height="1.525in"}

Die Methode IS_RELEVANT dient dazu, zu prüfen, ob die Tabelle Einträge
enthält, welche gelöscht werden sollen.

Die Methode DELETE_ENTRIES dient dazu, die entsprechenden Einträge zu
löschen oder zu archivieren.

## GTB HTTP-Request

### Ablaufbeschreibung

#### Instanziierung

Bei der Instanziierung der Klasse /PRIS/MAIN_CL_GTB_HTTP_REQUEST wird
der Name des Servers übergeben.

![](media/image32.png){width="5.901388888888889in" height="0.375in"}

Kann zu dem übergebenen Servernamen kein http-Client-Objekt erzeugt
werden wird eine klassenbasierte Ausnahme vom Typ
/PRIS/CX_MAIN_GTB_HTTP_REQUEST geworfen.

#### Anfrage senden

Die Methode SEND dient zum Versenden von http-Anfragen.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image33.png){width="4.333333333333333in"
height="1.6875in"}

Über den Importing-Parameter IV_REQ_URI wird der Name des Services
übergeben.

Die Anforderung wird über den Importing-Parameter IT_REQUEST übergeben.

Über den Exporting-Parameter ET_RESPONSE wird die Antwort des Services
zurückgegeben.

Die Exporting-Parameter EV_STATUS_CODE und EV_STATUS_REASON können
verwendet werden, um auszuwerten, ob der Aufruf erfolgreich war.

Bei einer erfolgreichen HTTP-Anfrage wird über den Parameter
EV_STATUS_CODE in der Regel der Wert 200 zurückgegeben.

In einem Fehlerfall wird eine klassenbasierte Ausnahme vom Typ
/PRIS/CX_MAIN_GTB_HTTP_REQUEST geworfen.

## GTB Timer

### Ablaufbeschreibung

Die Lösung besteht aus einer einzigen Klasse
**/PRIS/MAIN_CL_GTB_TIMER**. Über diese Klasse können Anwendungen
bestimmte Verhalten wiederkehrend nach Ablauf eines festgelegten Timers
auslösen. Dafür muss die Anwendung die folgenden Funktionalitäten der
Klasse in der angegebenen Reihenfolge aufrufen:

1)  **/PRIS/MAIN_CL_GTB_TIMER\~CONSTRUCTOR**

Die Erstellung von Instanzen dieser Klasse erfordert 2 Argumente:

- **IV_INTERVAL**: Timer-Ablauf in Sekunden

- **IV_TRIGGER_OKCODE**: OK-Code vom Funktionscode, der nach Ablauf des
  Timers ausgelöst wird. Dieser Parameter ist optional und hat
  standardmäßig den Wert „ENT".

2)  **/PRIS/MAIN_CL_GTB_TIMER\~LAUNCH**

Diese Methode startet den Timer und legt die Auslösung des im
Konstruktor angegebenen OK-Codes als Reaktion auf das Ereignis FINISHED
des Timers fest.

3)  **/PRIS/MAIN_CL_GTB_TIMER\~UNREGISTER_TIMER_FINISHED**

Die Methode stoppt den Timer ordnungsgemäß und sorgt dafür, dass das
periodische Verhalten beendet wird.

### Ablaufdiagramm

Für einen reibungslosen Ablauf der Lösung müssen die Methoden der Klasse
in der folgenden Reihenfolge aufgerufen werden.

## Generische Berechtigungsprüfung

### Ablaufbeschreibung

#### Instanziierung

Für modulübergreifende Entwicklungspunkte sollte die Instanz zur Klasse
/PRIS/MAIN_CL_GTB_AUTH_CHECK erzeugt werden.

![](media/image78.png){width="4.917352362204724in"
height="0.35421587926509185in"}

Für EWM-spezifische Entwicklungspunkte sollte die Instanz zur Klasse
/PRIS/EWM_CL_GTB_AUTH_CHECK erzeugt werden.

![](media/image79.png){width="4.927771216097987in"
height="0.2604527559055118in"}

#### Prüfung der Berechtigung

Bei einer Instanz der Klasse /PRIS/MAIN_CL_GTB_AUTH_CHECK kann die
Prüfung über die Methode CHECK_ALL ausgeführt werden.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image80.png){width="5.250732720909887in"
height="2.635784120734908in"}

Ist die Prüfung erfolgreich wird keine Ausnahme geworfen.

Ist die Prüfung jedoch nicht erfolgreich wird eine klassenbasierte
Ausnahme vom Typ /PRIS/CX_MAIN_GTB_AUTH_CHECK geworfen.

Bei einer Instanz der Klasse /PRIS/EWM_CL_GTB_AUTH_CHECK steht
zusätzlich noch die Methode CHECK_WHSNO zur Verfügung.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image81.png){width="5.302823709536308in"
height="2.427422353455818in"}

Auch hier gilt, dass nur eine Ausnahme geworfen wird, wenn die Prüfung
nicht erfolgreich ist.

## BAdI and Enhancement Framework

### Ablaufbeschreibung

#### Konfiguration

Das BAdI- und Erweiterungs-Framework wird über den Einführungsleitfaden
(Transaktionscode SPRO) eingestellt.

Der Pfad zu den Einstellungen lautet für EWM wie folgt:

- SAP Customizing Einführungsleitfaden

  - prismat RAKETE

    - Extended Warehouse Management

      - BAdI Framework

        - BAdI Framework

          - Definition

Im SAP Menübereich

- SAP MENU

  - Prismat RAKETE

    - Extended Warehouse Management

      - BAdI Framework

        - Definition

        - Übersicht

        - Konfiguration

    - Enterprise Resource Planning

      - BAdI Framework

        - Definition

        - Übersicht

        - Konfiguration

Über den Knoten „Definition" wird zu einer Erweiterung hinterlegt, ob es
sich um ein Business Add-In, ein klassisches BAdI, einen Enhancement
Point, einen User Exit oder eine prismat-Erweiterung handelt und welches
Interface verwendet werden soll.

Über den Knoten „Konfiguration" wird in das Programm
/PRIS/MAIN_BEF_CONFIG abgesprungen werden.

Über den Knoten „Übersicht" wird in das Programm /PRIS/MAIN_BEF_OVERVIEW
abgesprungen werden.

#### Erweiterung definieren

Der Pflegedialog zu dem View /PRIS/BEF_DEFV wird über den oben genannten
Pfad des Einführungsleitfadens oder über den Transaktionscode
/PRIS/BEF_DEF gestartet.

Die View umfasst die folgenden Felder:

  ----------------------------------------------------------------------------
  **Feldname**     **Schlüssel**   **Datentyp**           **Beschreibung**
  ---------------- --------------- ---------------------- --------------------
  ENH_TYPE         Ja              /PRIS/MAIN_DE_BEF\_\   Art der Erweiterung
                                   ENH_TYPE               

  ENH_NAME         Ja              /PRIS/MAIN_DE_BEF\_\   Name der Erweiterung
                                   ENH_NAME               

  INTF_NAME        Nein            /PRIS/MAIN_S_BEF\_\    Name der
                                   INTF_NAME              Schnittstelle

  DESCRIPT         Nein            TEXT100                Beschreibung
  ----------------------------------------------------------------------------

Das Datenelement des Feldes ENH_TYPE verweist auf die Domäne
/PRIS/MAIN_DO_BEF_ENH_TYPE.

Folgende Erweiterungsarten sind als Festwerte an der Domäne hinterlegt:

  -----------------------------------------------------------------------
  **Domänenfestwert**                 **Beschreibung**
  ----------------------------------- -----------------------------------
  BADI                                Business Add-In

  BADI_OLD                            Klassisches BAdI

  ENH_POINT                           Enhancement Point

  USER_EXIT                           User Exit

  PRISMAT                             prismat-Erweiterung
  -----------------------------------------------------------------------

Die Beschreibungen der Festwerte stehen somit als Dropdown-Liste im Feld
ENH_TYPE zur Verfügung.

Für das Feld ENH_NAME gibts eine Suchhilfe, welche anhand der
Erweiterungsart die möglichen Erweiterungen mit ihren Beschreibungen
anzeigt.

An das Feld INTF_NAME ist ebenfalls eine Suchhilfe angebunden.

Das Feld DESCRIPT wird bzgl. der vordefinierten Erweiterungsarten nur
für Erweiterungen vom Typ PRISMAT gefüllt.

Für die Erweiterungen der anderen vordefinierten Arten werden die
entsprechenden Beschreibungstexte aus den Standardtabellen angezeigt.

![](media/image36.png){width="5.427083333333333in" height="0.59375in"}

#### Erweiterung konfigurieren

Das Programm /PRIS/MAIN_BEF_CONFIG wird über den oben genannten Pfad des
Einführungsleitfadens oder über Transaktionscode /PRIS/BEF_CFG
gestartet.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image82.png){width="5.901388888888889in"
height="1.145138888888889in"}

In dem Selektionsbild des Programms stehen Parameterfelder für
Schlüsselart und Schlüsselwert zur Verfügung. Das Feld Schlüsselart ist
obligatorisch.

Neben expliziten Schlüsselwerten können auch die Werte leer und Stern
(\*) eingetragen werden können.

Der Wert Stern (\*) wird für Schlüsselwertübergreifende Einstellungen
verwendet.

Der Wert leer wird für Erweiterungen verwendet, in denen zu der
Schlüsselart kein Wert verfügbar ist.

Im nächsten Screen werden zur Selektion alle Erweiterungen und die
zugehörigen Implementierungen angezeigt.

![Ein Bild, das Text, Zahl, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image34.png){width="5.4375in"
height="1.3333333333333333in"}

Die Ergebnismenge umfasst dabei die folgenden Felder:

  ------------------------------------------------------------------------
  Feldname        Datentyp                           Beschreibung
  --------------- ---------------------------------- ---------------------
  KEY_TYPE        /PRIS/MAIN_DE_KEY_TYPE             Schlüsselart

  KEY_VALUE       /PRIS/MAIN_DE_KEY_VALUE            Schlüsselwert

  ENH_TYPE        /PRIS/MAIN_DE_BEF_ENH_TYPE         Art der Erweiterung

  ENH_NAME        /PRIS/MAIN_DE_BEF_ENH_NAME         Name der Erweiterung

  SEQNO           /PRIS/MAIN_DE_BEF_SEQNO            Reihenfolge der
                                                     Implementierungen

  STATUS          /PRIS/MAIN_DE_BEF_STATUS           Status (Ampel -\>
                                                     Grün = Aktiv, Rot =
                                                     inaktiv)

  CLASS_NAME      /PRIS/MAIN_DE_BEF_CLASS_NAME       Name der Klasse

  DESCRIPT        SEODESCR                           Kurzbeschreibung
  ------------------------------------------------------------------------

Pro Schlüsselart und Schlüsselwert gibt es eine gelb markierte
Kopfzeile. ![](media/image83.png){width="5.427083333333333in"
height="0.19791666666666666in"}

Für jede Erweiterung gibt es eine grün markierte Kopfzeile, in der die
Beschreibung und der Gesamtstatus der Erweiterung selbst angezeigt
werden. ![](media/image84.png){width="5.4375in" height="0.5in"}

Für die Implementierungen kann der Status grün oder rot sein.

Dies bedeutet, dass die Erweiterung in der SWT-Lösung aktiv oder inaktiv
ist. Zusätzlich kann für die grün markierten Datensätze auch ein gelber
Status existieren. Das bedeutet das es aktive und inaktive
Implementierungen gibt.

Die Spalte „Reihenfolge" dient dazu anzuzeigen in welcher Reihenfolge
die Implementierung pro Erweiterung aufgerufen werden sollen.

Über die Funktionstaste „Ändern" kann in den Änderungsmodus gewechselt
werden. Dabei wird versucht, eine Sperre auf die Konfigurationstabellen
(/PRIS/BEF_CFG) und auf die Switch-Framework-Tabellen (/PRIS/SWT_ECO,
/PRIS/SWT_DTE, /PRIS/SWT_DSE) zu setzen.

Wenn die Sperren nicht gesetzt werden können, wird eine Fehlermeldung
ausgegeben:

![Ein Bild, das Text, Screenshot, Software, Schrift enthält. Automatisch
generierte Beschreibung](media/image85.png){width="5.427083333333333in"
height="2.2916666666666665in"}

In der Symbolleiste stehen im Anzeigemodus folgende Funktionen zur
Verfügung:![](media/image86.png){width="5.427083333333333in"
height="0.28125in"}

In der Symbolleiste stehen im Änderungs-modus folgende Funktionen zur
Verfügung:![](media/image87.png){width="5.4375in"
height="0.3229166666666667in"}

Über die Funktionstaste „Activate Enhancement" in der Maske ist es
möglich, eine oder mehrere Erweiterungen zu aktivieren bzw. zu
deaktivieren.

Mit den Funktionstasten „Move Up" und „Move Down" kann die Reihenfolge
der einzelnen Implementierungen einer Erweiterung geändert werden.

Über die Funktionstaste „Speichern" werden die Parametertabellen der
Lösung SWT und BEF fortgeschrieben. Dazu besteht die Möglichkeit, diese
Datensätze in einen Transport aufzunehmen.

Über die Funktionstaste „Refresh" werden die Einträge neu ermittelt und
der Screen aktualisiert.

Über die Funktionstaste „Transport Status" werden die Datensätze der
SWT-Konfigurationstabellen in einem Transport aufgenommen.

#### Übersicht

Das Programm /PRIS/MAIN_BEF_OVERVIEW wird über den oben genannten Pfad
des Einführungsleitfadens oder Transaktionscode /PRIS/ gestartet und
dient dazu den Status von Erweiterungen auszuwerten.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. Automatisch
generierte Beschreibung](media/image88.png){width="5.4375in"
height="1.4583333333333333in"}

In dem Selektionsbild des Programms stehen ein Parameterfeld für die
Schlüsselart und Mehrfachselektionen für die Felder Schlüsselwert,
Erweiterungstyp, Erweiterungsname zur Verfügung.

Im nächsten Screen werden zur Selektion alle Erweiterungen und die
zugehörigen Implementierungen angezeigt.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image89.png){width="5.427083333333333in"
height="2.0625in"}

Die Ergebnismenge umfasst dabei die folgenden Felder:

  ------------------------------------------------------------------------
  Feldname        Datentyp                           Beschreibung
  --------------- ---------------------------------- ---------------------
  KEY_TYPE        /PRIS/MAIN_DE_KEY_TYPE             Schlüsselart

  KEY_VALUE       /PRIS/MAIN_DE_KEY_VALUE            Schlüsselwert

  ENH_TYPE        /PRIS/MAIN_DE_BEF_ENH_TYPE         Art der Erweiterung

  ENH_NAME        /PRIS/MAIN_DE_BEF_ENH_NAME         Name der Erweiterung

  SEQNO           /PRIS/MAIN_DE_BEF_SEQNO            Reihenfolge der
                                                     Implementierungen

  STATUS          /PRIS/MAIN_DE_BEF_STATUS           Status (Ampel -\>
                                                     Grün = Aktiv, Rot =
                                                     inaktiv)

  CLASS_NAME      /PRIS/MAIN_DE_BEF_CLASS_NAME       Name der Klasse

  DESCRIPT        SEODESCR                           Kurzbeschreibung
  ------------------------------------------------------------------------

Pro Schlüsselart und Schlüsselwert gibt es eine gelb markierte
Kopfzeile.![](media/image83.png){width="5.427083333333333in"
height="0.19791666666666666in"}

Für jede Erweiterung gibt es eine grün markierte Kopfzeile, in der die
Beschreibung und der Gesamtstatus der Erweiterung selbst angezeigt
werden. ![](media/image84.png){width="5.4375in" height="0.5in"}

Für die Implementierungen kann der Status grün oder rot sein.

Dies bedeutet, dass die Erweiterung in der SWT-Lösung aktiv oder inaktiv
ist. Zusätzlich kann für die grün markierten Datensätze auch ein gelber
Status existieren. Das bedeutet das es aktive und inaktive
Implementierungen gibt.

Die Spalte „Reihenfolge" dient dazu anzuzeigen in welcher Reihenfolge
die Implementierung pro Erweiterung aufgerufen werden sollen.

Über die Funktionstaste „Set Filter" hat man die Möglichkeit einen
Filter auf die Tabelle anzuwenden.

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. Automatisch
generierte Beschreibung](media/image90.png){width="5.4375in"
height="2.2395833333333335in"}

Über die Funktionstaste „Reset Filter" hat man die Möglichkeit alle
gesetzten Filter zu entfernen.

![Ein Bild, das Text, Schrift, Zahl, Reihe enthält. Automatisch
generierte Beschreibung](media/image91.png){width="5.4375in"
height="1.0520833333333333in"}

### Aufruf des Frameworks in einer Erweiterungsimplementierung

Um das BAdI and Enhancement Framework für eine Erweiterung zu nutzen,
muss es in der eigentlichen Implementierung eingebunden werden.

Bei einem Business Add-In müsste der Aufruf somit in der Klasse
aufgerufen werden, die in der BAdI-Implementierung zur
Erweiterungsimplementierung hinterlegt ist.

Dazu muss zunächst über die Methode GET_INSTANCE der Klasse
/PRIS/MAIN_CL_BEF eine Instanz zum Framework ermittelt werden.

Die Methode GET_INSTANCE verfügt über die folgenden Parameter:

  ----------------------------------------------------------------------------
  Parametername      Art       Datentyp                Beschreibung
  ------------------ --------- ----------------------- -----------------------
  IV_KEY_TYPE        Import    /PRIS/MAIN_DE_KEY\_\    Schlüsselart
                               TYPE                    

  IV_KEY_VALUE       Import    /PRIS/MAIN_DE_KEY\_\    Schlüsselwert
                               VALUE                   

  IV_BALOBJ          Import    BALOBJ_D                Anwendungs-Log:
                                                       Objektname
                                                       (Applikations-kürzel)

  IV_BALSUBOBJ       Import    BALSUBOBJ               Anwendungs-Log:
                                                       Unterobjekt

  IV_BALNREXT        Import    BALNREXT                Anwendungs-Log: Externe
                                                       Identifikation

  RO_INSTANCE        Return    /PRIS/MAIN_CL_BEF       BAdI and Enhancement
                                                       Framework
  ----------------------------------------------------------------------------

Über die Methode EXECUTE der Instanz wird die Ausführung des Frameworks
angestoßen.

Die Methode EXECUTE verfügt über die folgenden Parameter:

  --------------------------------------------------------------------------------
  Parameter-name     Art         Datentyp               Beschreibung
  ------------------ ----------- ---------------------- --------------------------
  IV_ENH_TYPE        Import      /PRIS/MAIN_DE_BEF\_\   Art der Erweiterung
                                 ENH_TYPE               

  IV_ENH_NAME        Import      /PRIS/MAIN_DE_BEF\_\   Name der Erweiterung
                                 ENH_NAME               

  CS_METHOD\_\       Changing    /PRIS/MAIN_S_BEF\_\    Daten für den Aufruf der
  DATA                           METHOD_DATA            Methode

  ES_EXCEPTION       Export      /PRIS/MAIN_S_BEF\_\    Daten der geworfenen
                                 EXCEPTION              Ausnahme

  EV_STD_CALLED      Export      /PRIS/MAIN_DE_BEF\_\   Standard-Implementierung
                                 STD_CALLED             wurde aufgerufen
  --------------------------------------------------------------------------------

Die Struktur von Parameter CS_METHOD_DATA umfasst die Felder
METHOD_NAME, T_PARAMETER und T_EXCEPTION.

Die Felder T_PARAMETER und T_EXCEPTION verweisen auf Tabellentypen und
können somit mehrere Zeilen aufnehmen.

Das Feld T_EXCEPTION muss nur befüllt werden, wenn die aufzurufende
Methode klassische Ausnahmen verwendet.

Über das Feld werden Return Codes zu den klassischen Ausnahmen
hinterlegt.

Über das Feld T_PARAMETER werden Name, Art und die Referenzen auf die
Werte der Parameter übergeben.

Der Aufruf einer Methode mit klassischen Ausnahmen könnte somit wie
folgt aussehen:

**METHOD** /scwm/if_ex_core_cr_post\~post.\
    *\" Framework aufrufen*\
    DATA ls_exception    TYPE /pris/main_s_bef_exception.\
    DATA ls_method_data  TYPE /pris/main_s_bef_method_data.\
    DATA lo_bef          TYPE REF TO /pris/main_cl_bef.\
\
    DATA: lv_std_called       TYPE /pris/main_de_bef_std_called,\
          lo_prislog          TYPE REF TO /pris/main_cl_log,\
        lv_abort_framework  TYPE xfeld.\
\
*    \" instanz des frameworks holen*\
    lo_bef =\
      /pris/main_cl_bef=\>get_instance( iv_key_type  = \'A\'\
                                       iv_key_value = CONV #( iv_lgnum )\
                                       iv_balobj    = \'/PRIS/EWM\'\
                                       iv_balsubobj = \'/PRIS/EWM_CORE\' ).\
\
*    \" Daten zum aufruf der methode der erweiterung zuweisen*\
    ls_method_data-method_name = \'POST\'.\
    ls_method_data-t_parameter =\
      VALUE #( ( name  = \'IV_LGNUM\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_exporting\
                 value = REF #( iv_lgnum ) )\
               ( name  = \'IT_LTAP_VB\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_exporting\
                 value = REF #( it_ltap_vb ) )\
               ( name  = \'IT_ORDIM_O\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_exporting\
                 value = REF #( it_ordim_o ) )\
               ( name  = \'IT_ORDIM_OS\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_exporting\
                 value = REF #( it_ordim_os ) )\
               ( name  = \'CV_STD_CALLED\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_changing\
                 value = REF #( lv_std_called ) )\
               ( name  = \'EV_BEF_ABORT\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_importing\
                 value = REF #( lv_abort_framework ) )\
               ( name  = \'IO_PRISLOG\'\
                 kind  = /pris/main_cl_bef=\>c_param_kind_exporting\
                 value = REF #( lo_prislog ) )\
                  ).

*    \" Framework aufrufen*\
    lo_bef-\>execute(\
      EXPORTING\
        iv_enh_type   = \'BADI\'\
        iv_enh_name   = \'/SCWM/EX_CORE_CR_POST\'\
      IMPORTING\
*\*    es_exception   = ls_exception*\
        ev_std_called  = lv_std_called\
      CHANGING\
        cs_method_data = ls_method_data\
    ).\
*\" Falls noch keine Standard-Implementierung aufgerufen wurde,\
\" dies ggf. an dieser Stelle tun*\
    IF lv_std_called EQ abap_false.\
     *\" Fallback-Klasse aufrufen*\
    ENDIF.

**ENDMETHOD.**

Über den Parameter CV_STD_CALLED kann den anderen Implementierungen zu
einer Erweiterung mitgeteilt werden, dass die Standard-Implementierung
bereits aufgerufen wurde.\
Dies dient dazu zu vermeiden, dass mehrere Implementierungen
unnötigerweise die Standard-Implementierung aufrufen.

Über den Parameter EV_BEF_ABORT kann eine Implementierung dem Framework
mitteilen, dass eine Konstellation erkannt wurde, bei welcher keine
weitere Implementierung zur Erweiterung mehr aufgerufen werden soll.

Welche Methoden das Interface umfassen soll bzw. muss hängt von der
jeweiligen Erweiterung ab.

Bei Erweiterungen vom Erweiterungstyp BAdI sollte das Interface alle
Methoden des Standard-Interfaces zum BAdI enthalten.

Dabei ist jedoch zu beachten, dass alle Export- und Return-Parameter der
Methoden des Standard-Interfaces im Interface für das BAdI and
Enhancement Framework zu Changing-Parametern geändert werden sollten.

Das sorgt dafür, dass Implementierungen zu einem BAdI ihr Ergebnisse an
die anderen Implementierungen weitergeben können und deren Business
Logiken somit diese Ergebnisse mitberücksichtigen können.

Bei Methoden ohne Ausnahmen und Methoden die Ausnahmeklassen verwenden
kann das Feld T_EXCEPTION des Parameters CS_METHOD_DATA leer bleiben.

Verwendet die Methode Ausnahmeklassen wird, falls eine solche Ausnahme
geworfen wurde, der Name der Ausnahme im Feld NAME und die Instanz der
Ausnahme im Feld OBJECT des Parameters ES_EXCEPTION zurückgegeben.

Das Feld VALUE würde in diesem Fall den Wert 99 enthalten.

Da OBJECT vom Typ CX_ROOT ist muss die Instanz der Ausnahme ggf. in den
richtigen Datentyp gecastet werden, um sie weiter zu reichen.

Beispiel:

DATA lx_basics TYPE REF TO /scwm/cx_basics.

...

IF ls_exception-value NE 0.\
lx_basics ?= ls_exception-object.

RAISE EXCEPTION lx_basics.\
ENDIF.

### Technische Implementierung einer Erweiterung

Jede Implementierung zu einer Erweiterung setzt eine passende
Schnittstelle voraus.

In objekt-orientierten Programmiersprachen, wie ABAP OO, werden diese
über sogenannte Interfaces abgebildet.

Ein Interface definiert dabei welche Methoden es gibt und welche
Parameter bzw. Ausnahmen diese zur Verfügung stellen müssen.

Bei Interfaces für das BAdI and Enhancement Framework müssen die
Methoden immer zu mindestens die folgenden Parameter zur Verfügung
stellen.

  ---------------------------------------------------------------------------------
  Parameter-name     Art          Datentyp               Beschreibung
  ------------------ ------------ ---------------------- --------------------------
  IO_PRISLOG         Import       /RIS/MAIN_CL_LOG       Applikationslog

  CV_STD_CALLED      Changing     /PRIS/MAIN_DE_BEF\_\   Standard-Implementierung
                                  STD_CALLED             wurde aufgerufen

  EV_BEF_ABORT       Export       /PRIS/MAIN_DE_BEF\_\   Logik zur Erweiterung
                                  ABORT                  abbrechen
  ---------------------------------------------------------------------------------

Über den Parameter CV_STD_CALLED kann den anderen Implementierungen zu
einer Erweiterung mitgeteilt werden, dass die Standard-Implementierung
bereits aufgerufen wurde.\
Dies dient dazu zu vermeiden, dass mehrere Implementierungen
unnötigerweise die Standard-Implementierung aufrufen.

Über den Parameter EV_BEF_ABORT kann eine Implementierung dem Framework
mitteilen, dass eine Konstellation erkannt wurde, bei welcher keine
weitere Implementierung zur Erweiterung mehr aufgerufen werden soll.

Welche Methoden das Interface umfassen soll bzw. muss hängt von der
jeweiligen Erweiterung ab.

Bei Erweiterungen vom Erweiterungstyp BAdI sollte das Interface alle
Methoden des Standard-Interfaces zum BAdI enthalten.

Dabei ist jedoch zu beachten, dass alle Export- und Return-Parameter der
Methoden des Standard-Interfaces im Interface für das BAdI and
Enhancement Framework zu Changing-Parametern geändert werden sollten.

Das sorgt dafür, dass Implementierungen zu einem BAdI ihr Ergebnisse an
die anderen Implementierungen weitergeben können und deren Business
Logiken somit diese Ergebnisse mitberücksichtigen können.

### Erzeugen einer Implementierung über die Transaktion /PRIS/BEF_CFG

#### Button zur Anlage einer neuen Implementierung

![Ein Bild, das Text, Zahl, Schrift, Software enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image92.png){width="5.895833333333333in"
height="1.8541666666666667in"}

Über einen neuen Button kann über die Funktionalitäten der Hilfsklasse
eine Implementierung angelegt werden.

Dafür werden nacheinander Popups aufgerufen, welche die notwendigen
Werte vom Benutzer einfordern.

#### Art und Namen der Erweiterung definieren

In dem Dialogfenster werden die Art der Erweiterung und der Name, zu dem
die Implementierung angelegt werden soll eingeben.

![Ein Bild, das Text, Screenshot, Reihe, Schrift enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image93.png){width="5.901388888888889in"
height="2.1145833333333335in"}

#### Erfassen zusätzlicher Daten...

Abhängig von der Art der Erweiterung wird im Anschluss ein Dialogfenster
zur Erfassung zusätzlicher Daten geöffnet.

Folgende übergreifende Daten werden in jedem Dialogfenster abgefagt:

- Interfacename

- Klassenname

- Paket

- Schlüsseltyp für den generierten Code der Klasse die das BEF aufruft

- Parameter- und Feldname (optional) zur Ermittlung des Schlüsselwertes
  für den generierten Code der Klasse, die das BEF aufruft

- Protokollobjekt, Protokollunterobjekt und externe Identifikation
  (optional) für den generierten Code der Klasse die das BEF aufruft

##### ...für neue BAdIs

Zusätzlich zu den übergreifenden Daten werden in dem Dialogfenster für
neue BAdIs die folgenden Daten abgefragt:

- Name der Erweiterungsimplementierung

- Name der BAdI-Implementierung

- Kennzeichen, dass kein Aufruf einer Standardimplementierung (oder
  Fallbackimplementierung) generiert werden soll

  - Diese würde sonst aufgerufen werden, wenn kein eigener BAdI das
    Kennzeichen CV_STD_CALLED setzt

![Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image94.png){width="5.901388888888889in"
height="3.183333333333333in"}

##### ...für klassische BAdIs

Zusätzlich zu den übergreifenden Daten wird in dem Dialogfenster für
klassische BAdIs der Name der Erweiterungsimplementierung abgefragt.

![Ein Bild, das Text, Screenshot, Zahl, Reihe enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image95.png){width="5.901388888888889in"
height="2.8361111111111112in"}

##### ...für User Exits

Zusätzlich zu den übergreifenden Daten werden im Dialogfenster für User
Exits die folgenden Werte abgefragt:

- Name des Projekts in der Transaktion CMOD

- Interfacename des zweiten Interfaces (nicht Z-Interface für die
  Logikklassen), welche das SAP-Interface von BAdIs abbildet

  - Dieses Interface hat je Funktionsbaustein eines User Exits eine
    Methode

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image96.png){width="5.901388888888889in"
height="3.0145833333333334in"}

#### Anlage der Logikklasse

Nach dem alle Daten zur jeweiligen Erweiterung erfasst wurden wird der
Name der anzulegenden Logikklasse in einem Dialogfenster abgefragt.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image97.png){width="5.901388888888889in"
height="2.963888888888889in"}

#### Angabe des Workbench-Transportauftrags

Nach der Erfassung der Daten zur Erweiterung und dem Namen der
Logikklasse wird zum Abschluss der zu verwendende
Workbench-Transportauftrag über ein weiteres Dialogfenster abgefragt.

![Ein Bild, das Text, Schrift, Reihe, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image98.png){width="5.901388888888889in"
height="1.8972222222222221in"}

#### Auswahl fehlender Daten

Gibt die Hilfsklasse die Information zurück, dass für die spezifische
Erweiterung weitere Benutzerangaben erforderlich sind, so wird erneut
ein Dialogfenster aufgerufen, in dem die validen Werte tabellarisch zur
Auswahl angezeigt werden.

##### Filterwerte für alte BAdIs

Es können mehrere Werte ausgewählt und per ENTER oder dem
„Continue"-Button bestätigt werden.

Ein Abbruch ist über F12 oder den „Cancel"-Button möglich.

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image99.png){width="4.015748031496063in"
height="5.0511329833770775in"}

Bei einer Bestätigung, ohne ausgewähltem Wert erscheint eine
Fehlermeldung und das Popup öffnet sich erneut.

##### Standardimplementierung für neue BAdIs

Es kann eine Implementierung ausgewählt und per ENTER oder dem
„Continue"-Button bestätigt werden.

Ein Abbruch ist über F12 oder den „Cancel"-Button möglich.

Wird das Dialogfenster ohne Auswahl einer Implementierung bestätigt wird
im generierten Coding keine Standardimplementierung aufgerufen.

### Erzeugen einer Logikklasse über die Transaktion /PRIS/BEF_CFG

#### Button zur Anlage einer neuen Logikklasse

![Ein Bild, das Text, Zahl, Schrift, Software enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image100.png){width="5.901388888888889in"
height="1.8319444444444444in"}

Über einen neuen Button kann über die Funktionalitäten der Hilfsklasse
eine Logikklasse angelegt werden. Eine Logikklasse implementiert ein
Z-Interface, welche in der /PRIS/BEF_DEF hinterlegt ist, und das
/PRIS/MAIN_IF_BEF, um seine Erweiterungsdetails weitergeben zu können.

Hierbei ist zu beachten, dass eine eindeutige Erweiterung in der
tabellarischen Ansicht des BEFs markiert sein muss.

Zu dieser Erweiterung wird dann die Logikklasse erstellt.

Es wird ein Dialogfenster aufgerufen, um den Klassenname und das Paket
abzufragen.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image101.png){width="5.901388888888889in"
height="2.9680555555555554in"}

## GTB System

Alle Informationen zur Implementierung der Klasse
/PRIS/MAIN_CL_GTB_SYSTEM sind in Kapitel 3.16 beschrieben.

Für die Lösung GTB System liegen keine weiteren internen Informationen
zur Implementierung vor.

## GTB - Kleine Werkzeuge

Alle Informationen den Klasses sind in Kapitel 3.17 beschrieben.

Für die Klassen liegen keine weiteren internen Informationen vor.

## Easy Mapper

### Ablaufbeschreibung

Die Konvertierungsmethoden dienen grundsätzlich als vereinheitlichte
Schnittstelle zu den bereits im Standard vorhandenen Methoden und
Funktionsbausteinen. Für EWM-Objekte, für die keine solche
Funktionalitäten existieren, werden diese durch den Easy *Mapper*
ergänzt.

Zusätzlich kann über die Transaktion /PRIS/EWM_MAP ein Nutzer auf einem
Bildschirm seine gewünschte Konvertierungsart per Buttonklick auswählen
und die Werte auf einem spezifischen Selektionsbild eingeben, sodass er
anschließend die Ergebnisse per ALV-Grid angezeigt bekommt.

## RFC Hilfsklasse

Es wurde eine neue Klasse /PRIS/EWM_CL_HLP_RFC implementiert, die
öffentliche Methoden für die Ermittlung des logischen Systems und die
Ermittlung der RFC-Destination zur Verfügung stellt.

Zur Verwendung der Methoden muss zuerst ein Objekt der Klasse erzeugt
werden, wobei die Lagernummer und optional das Applog-Objekt übergeben
werden.

Die Methode GET_ERP_LOGSYS ermittelt das logische System des
ERP-Systems.\
Dafür liest sie den Verfügungsberechtigten zur Lagernummer nach.\
Zum Verfügungsberechtigten wird dann das logische System ermittelt und
zurückgegeben.

Die Methode GET_RFC_DEST ermittelt die RFC-Destination des ERP-Systems.\
Dafür wird zuerst das logische System mit GET_ERP_LOGSYS ermittelt.\
Zum logischen System wird dann die RFC-Destination nachgelesen und
zurückgegeben.

# [Technische Dokumentation]{.mark}

## Key Values - Schlüsselwerte

### Dictionary Objekte

#### Domänen

  -------------------------------------------------------------------------
  Name                        Beschreibung     Datentyp      Festwerte
  --------------------------- ---------------- ------------- --------------
  /PRIS/MAIN_DO_KEY_TYPE      Schlüsselart     CHAR 1        A - EWM-Lgnr.\
                                                             B - ERP-Lgnr.\
                                                             C --
                                                             Benutzerg.\
                                                             D --
                                                             Buchngsk.\
                                                             E -- Lagerort\
                                                             F -- PVB\
                                                             G --
                                                             Verk.org.\
                                                             H --
                                                             Versandst.\
                                                             I --
                                                             Vertriebsw.\
                                                             J - Werk

  -------------------------------------------------------------------------

#### Datenelemente

  -----------------------------------------------------------------------
  Name                         Beschreibung        Domäne
  ---------------------------- ------------------- ----------------------
  /PRIS/MAIN_DE_KEY_TYPE       Schlüsselart        ZEWM_DO_KEY_TYPE

  /PRIS/MAIN_DE_KEY_VALUE      Schlüsselwert       CHAR20
  -----------------------------------------------------------------------

#### Datenbanktabellen

  ---------------------------------------------------------------------------
  Name                Beschreibung              C-Transp.      W-Transp.
  ------------------- ------------------------- -------------- --------------
  /PRIS/KEY_VALUE     Schlüsselwertdefinition   X              

  ---------------------------------------------------------------------------

#### Tabellentypen

  ----------------------------------------------------------------
  Name                         Beschreibung
  ---------------------------- -----------------------------------
  /PRIS/MAIN_TT_KEY_VALUE      Schlüsselwertdefinition

  ----------------------------------------------------------------

#### Pflege-Views

  --------------------------------------------------------------------------
  Name                 Beschreibung              C-Transp.     W-Transp.
  -------------------- ------------------------- ------------- -------------
  /PRIS/KEY_VALUEV     Schlüsselwertdefinition   X             

  --------------------------------------------------------------------------

### Klassenbibliotheken

  -------------------------------------------------------------------
  Name                            Beschreibung
  ------------------------------- -----------------------------------
  /PRIS/MAIN_IF_KEY_VALUES_C      Konstanten für Schlüsselarten

  -------------------------------------------------------------------

### Funktionsgruppen

  -------------------------------------------------------------------
  Name                       Beschreibung
  -------------------------- ----------------------------------------
  /PRIS/KEY_VALUEV           Pflegedialog zum View /PRIS/KEY_VALUEV

  -------------------------------------------------------------------

## CFG -- Konfigurations-Framework

### Dictionary Objekte

#### Domänen

  ------------------------------------------------------------------------------
              Name              Beschreibung          Datentyp    Festwerte
  ----------------------------- --------------------- ----------- --------------
   /PRIS/MAIN_DO_ATTR_CATEGORY  Attributtyp:          CHAR 6      SINGLE\
                                Einzelwert oder                   GROUP
                                Wertegruppe                       

     /PRIS/MAIN_DO_ATTR_TYPE    Attributart           CHAR 10     CONSTANT\
                                                                  PARAMETER

    /PRIS/MAIN_DO_ATTR_VALUE    Wert eines Attributs  CHAR 45     
  ------------------------------------------------------------------------------

#### Datenelemente

  ---------------------------------------------------------------------------
            Name           Beschreibung                Domäne
  ------------------------ --------------------------- ----------------------
    /PRIS/MAIN_DE_ATTR\    Attributtyp - Einzelwert    /PRIS/MAIN_DO_ATTR\
         \_CATEGORY        oder Wertegruppe            \_CATEGORY

    /PRIS/MAIN_DE_ATTR\    Name einer Konstanten oder  CHAR60
           \_NAME          eines Parameters            

    /PRIS/MAIN_DE_ATTR\    Attributart - Konstante     /PRIS/MAIN_DO_ATTR\
           \_TYPE          oder Parameter              \_TYPE

    /PRIS/MAIN_DE_ATTR\    Wert eines Attributs        CHAR45
          \_VALUE                                      

    /PRIS/MAIN_DE_CONST\   Name einer Konstanten       CHAR60
           \_NAME                                      

    /PRIS/MAIN_DE_PARAM\   Name eines Parameters       CHAR60
           \_NAME                                      

    /PRIS/MAIN_DE_ATTR\    Wert eines Attributs        /PRIS/MAIN_DO_ATTR\
          \_VALUE                                      \_VALUE

      /PRIS/MAIN_DE\_\     Änderungszeit-Zeitstempel   TZNTSTMPS
       CHANGED_TSTMP                                   

   /PRIS/MAIN_DE_FILLER\   Füllzeichen                 CHAR1
        \_CHARACTER                                    

    /PRIS/MAIN_DE_RIGHT\   Rechtsbündig                XFELD
        \_JUSTIFIED                                    
  ---------------------------------------------------------------------------

#### Strukturen

  -----------------------------------------------------------------------
               Name               Beschreibung
  ------------------------------- ---------------------------------------
    /PRIS/MAIN_S_CFG_ATTR_DATA    Attribute mit den zugehörigen Daten

     /PRIS/MAIN_S_CFG_ATTR_SH     CFG: Attributdaten für Suchhilfe

     /PRIS/MAIN_S_CFG_CONST_SH    CFG: Konstantendaten für Suchhilfe

     /PRIS/MAIN_S_CFG_PARAM_SH    CFG: Parameterdaten für Suchhilfe
  -----------------------------------------------------------------------

#### Datenbank-Tabellen

  ------------------------------------------------------------------------
          Name          Beschreibung             C-Transp.     W-Transp.
  --------------------- ------------------------ ------------ ------------
      /PRIS/CFG_SAD     CFG: Definition von                        X
                        Attributsdaten                        

     /PRIS/CFG_SADT     Texttabelle zu                             X
                        /PRIS/CFG_SAD                         

      /PRIS/CFG_SAS     CFG: Zuordnung der                         X
                        Attribute                             

      /PRIS/CFG_SCG     CFG: Gruppenwerte zu     X            
                        Konstanten                            

      /PRIS/CFG_SCS     CFG: Einzelwerte zu      X            
                        Konstanten                            

      /PRIS/CFG_SPG     CFG: Gruppenwerte zu                  
                        Parametern                            

      /PRIS/CFG_SPS     CFG: Einzelwerte zu                   
                        Parametern                            

     /PRIS/CFG_FCHG     CFG: Format-Änderungen                
  ------------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
                Name               Beschreibung
  -------------------------------- --------------------------------------
    /PRIS/MAIN_TT_CFG_ATTR_DATA    Attribute mit den zugehörigen Daten

     /PRIS/MAIN_TT_CFG_ATTR_SH     CFG: Attributdaten für Suchhilfe

     /PRIS/MAIN_TT_CFG_CONST_SH    CFG: Konstantendaten für Suchhilfe

     /PRIS/MAIN_TT_CFG_PARAM_SH    CFG: Parameterdaten für Suchhilfe

       /PRIS/MAIN_TT_CFG_SAD       CFG: Definition der Attributdaten
  -----------------------------------------------------------------------

#### Pflege-Views

  -----------------------------------------------------------------------
                 Name                Beschreibung
  ---------------------------------- ------------------------------------
            /PRIS/CFG_SADV           CFG: Definition von Attributsdaten

            /PRIS/CFG_SASV           CFG: Zuordnung der Attribute

            /PRIS/CFG_SCGV           CFG: Gruppenwerte zu Konstanten

            /PRIS/CFG_SCSV           CFG: Einzelwerte zu Konstanten

            /PRIS/CFG_SPGV           CFG: Gruppenwerte zu Parametern

            /PRIS/CFG_SPSV           CFG: Einzelwerte zu Parametern
  -----------------------------------------------------------------------

#### Suchhilfen

  -----------------------------------------------------------------------
                Name                Beschreibung
  --------------------------------- -------------------------------------
      /PRIS/MAIN_SH_CFG_ASSIGN\     CFG: Suchhilfe zur Ermittlung von
               \_CONST              Konstanten für Zuweisungen

      /PRIS/MAIN_SH_CFG_ASSIGN\     CFG: Suchhilfe zur Ermittlung von
               \_PARAM              Parametern für Zuweisungen

      /PRIS/MAIN_SH_CFG_CONST\      CFG: Suchhilfe zur Ermittlung von
               \_GROUP              Konstantengruppen

      /PRIS/MAIN_SH_CFG_CONST\      CFG: Suchhilfe zur Ermittlung von
              \_SINGLE              Einzel-Konstanten

      /PRIS/MAIN_SH_CFG_PARAM\      CFG: Suchhilfe zur Ermittlung von
               \_GROUP              Parametergruppen

      /PRIS/MAIN_SH_CFG_PARAM\      CFG: Suchhilfe zur Ermittlung von
              \_SINGLE              Einzel-Parameter
  -----------------------------------------------------------------------

### Klassen

  -----------------------------------------------------------------------
                Name                Beschreibung
  --------------------------------- -------------------------------------
          /PRIS/MAIN_CL_CFG         CFG: Zugriffsklasse

      /PRIS/MAIN_CL_CFG_FORMAT      CFG: Format auf existierende
                                    Attributwerte anwenden

        /PRIS/MAIN_CL_CFG_SH        CFG: Suchhilfe-Klasse

       /PRIS/CX_MAIN_CFG_ERROR      CFG: Ausnahme für
                                    Konfigurationsfehler

      /PRIS/CX_MAIN_CFG_MISSING     CFG: Ausnahme für fehlende Attribute

          /PRIS/EWM_CL_CFG          CFG: Zugriffsklasse für EWM
  -----------------------------------------------------------------------

### Klassen (falls Lösung im EWM)

  -----------------------------------------------------------------------
                Name                Beschreibung
  --------------------------------- -------------------------------------
          /PRIS/EWM_CL_CFG          CFG: Zugriffsklasse für EWM

  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
                Name                Beschreibung
  --------------------------------- -------------------------------------
           /PRIS/MAIN_CFG           Nachrichten zu CFG

  -----------------------------------------------------------------------

### Funktionsgruppen

  ----------------------------------------------------------------------
             Name             Beschreibung
  --------------------------- ------------------------------------------
        /PRIS/CFG_SADV        Pflegedialog zu View /PRIS/CFG_SADV

        /PRIS/CFG_SASV        Pflegedialog zu View /PRIS/CFG_SASV

        /PRIS/CFG_SCGV        Pflegedialog zu View /PRIS/CFG_SCGV

        /PRIS/CFG_SCSV        Pflegedialog zu View /PRIS/CFG_SCSV

        /PRIS/CFG_SPGV        Pflegedialog zu View /PRIS/CFG_SPGV

        /PRIS/CFG_SPSV        Pflegedialog zu View /PRIS/CFG_SPSV

      /PRIS/MAIN_CFG_RFC      CFG: RFC-Funktionsbausteine

    /PRIS/MAIN_CFG_SH_EXITS   CFG: Search Help Exits
  ----------------------------------------------------------------------

### Programme

  ---------------------------------------------------------------------
             Name            Beschreibung
  -------------------------- ------------------------------------------
     /PRIS/MAIN_CFG_MENU     Auswahlmenü für CFG-Einstellungen

  ---------------------------------------------------------------------

### Transaktionscodes

  ---------------------------------------------------------------------
             Name            Beschreibung
  -------------------------- ------------------------------------------
        /PRIS/CFG_MENU       Auswahlmenü für CFG-Einstellungen

       /PRIS/CFG_FORMAT      Formateinstellungen auf Werte anwenden

        /PRIS/CFG_SAD        Definition von Attributsdaten

        /PRIS/CFG_SAS        Zuordnung der Attribute

        /PRIS/CFG_SCG        Gruppenwerte zu Konstanten

        /PRIS/CFG_SCS        Einzelwerte zu Konstanten

        /PRIS/CFG_SPG        Gruppenwerte zu Parametern

        /PRIS/CFG_SPS        Einzelwerte zu Parametern
  ---------------------------------------------------------------------

## SWT -- Schalter-Framework

### Dictionary Objekte

#### Datenelemente

  ---------------------------------------------------------------------
  Name                   Beschreibung             Domäne
  ---------------------- ------------------------ ---------------------
  /PRIS/MAIN_DE_TOP\_\   Name der übergeordneten  CHAR40
  ENHANCEMENT_NAME       Erweiterung              

  /PRIS/MAIN_DE_SUB\_\   Name der                 CHAR40
  ENHANCEMENT_NAME       untergeordnet-en         
                         Erweiterung              
  ---------------------------------------------------------------------

#### Datenbank-Tabellen

  --------------------------------------------------------------------------
  Name               Beschreibung                C-Transp.    W-Transp.
  ------------------ --------------------------- ------------ --------------
  /PRIS/SWT_DSE      SWT: Definition von                      X
                     untergeordneten                          
                     Erweiterungen                            

  /PRIS/SWT_DSET     SWT: Texttabelle zu                      X
                     /PRIS/SWT_DSE                            

  /PRIS/SWT_DTE      SWT: Definition von                      X
                     übergeordneten                           
                     Erweiterungen                            

  /PRIS/SWT_DTET     SWT: Texttabelle zu                      X
                     /PRIS/SWT_DTE                            

  /PRIS/SWT_ECO      SWT:                                     
                     Erweiterungskonfiguration                
  --------------------------------------------------------------------------

#### Pflege-Views

  ---------------------------------------------------------------------
  Name                   Beschreibung
  ---------------------- ----------------------------------------------
  /PRIS/SWT_ECOSV        SWT: Konfiguration untergeordneter
                         Erweiterungen

  /PRIS/SWT_ECOTV        SWT: Konfiguration übergeordneter
                         Erweiterungen

  /PRIS/SWT_DSEV         SWT: Definition untergeordneter Erweiterungen

  /PRIS/SWT_DTEV         SWT: Definition übergeordneter Erweiterungen
  ---------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  Name                       Beschreibung
  -------------------------- --------------------------------------------
  /PRIS/MAIN_TT_SWT_ECO      SWT: Erweiterungskonfiguration

  /PRIS/MAIN_TT_SWT_DSE      SWT: Definition von untergeordneten
                             Erweiterungen

  /PRIS/MAIN_TT_SWT_DTE      SWT: Definition von übergeordneten
                             Erweiterungen
  -----------------------------------------------------------------------

### Klassen

  -----------------------------------------------------------------------
  Name                            Beschreibung
  ------------------------------- ---------------------------------------
  /PRIS/MAIN_CL_SWT               SWT: Zugriffsklasse

  /PRIS/CX_MAIN_SWT_INACTIVE      SWT: Inaktive Erweiterung

  /PRIS/CX_MAIN_SWT_INVALID       SWT: Ungültiger Aufruf

  /PRIS/CX_MAIN_SWT_MISSING       SWT: Fehlende Einträge in Steuertabelle

  /PRIS/CX_MAIN_SWT_UNKNOWN       SWT: Unbekannte Erweiterung

  /PRIS/EWM_CL_SWT                SWT: Zugriffsklasse (EWM)
  -----------------------------------------------------------------------

### Klassen (falls Lösung im EWM)

  -----------------------------------------------------------------------
  Name                          Beschreibung
  ----------------------------- -----------------------------------------
  /PRIS/EWM_CL_SWT              SWT: Zugriffsklasse (EWM)

  -----------------------------------------------------------------------

### Funktionsgruppen

  ---------------------------------------------------------------------
  Name                       Beschreibung
  -------------------------- ------------------------------------------
  /PRIS/SWT_ECOSV            Pflegedialog zu View /PRIS/SWT_ECOSV

  /PRIS/SWT_ECOTV            Pflegedialog zu View /PRIS/SWT_ECOTV

  /PRIS/SWT_DSEV             Pflegedialog zu View /PRIS/SWT_DSEV

  /PRIS/SWT_DTEV             Pflegedialog zu View /PRIS/SWT_DTEV
  ---------------------------------------------------------------------

### Nachrichtenklassen

  ---------------------------------------------------------------------
  Name                       Beschreibung
  -------------------------- ------------------------------------------
  /PRIS/MAIN_SWT             Nachrichten zu SWT

  ---------------------------------------------------------------------

### Viewcluster

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/SWT_CONFVC                    SWT: Erweiterungskonfiguration

  /PRIS/SWT_DEFVC                     SWT: Erweiterungsdefinition
  -----------------------------------------------------------------------

### Transaktionscodes

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/SWT_CONF                      Schalterkonfiguration

  /PRIS/SWT_DEF                       Schalterdefinition
  -----------------------------------------------------------------------

## SDT Adjustment Report

### Klassen

  -----------------------------------------------------------------------
  Name                             Beschreibung
  -------------------------------- --------------------------------------
  /PRIS/MAIN_CL_SDT_ADJUSTMENT     Solution Deployment Tools -
                                   Attributanpassung

  -----------------------------------------------------------------------

### Programme

  -----------------------------------------------------------------------
  Name                            Beschreibung
  ------------------------------- ---------------------------------------
  /PRIS/MAIN_SDT_ADJUSTMENT       Solution Deployment Tools -
                                  Attributanpassung

  -----------------------------------------------------------------------

## Wizard

### Dictionary Objekte

#### Strukturen

  -----------------------------------------------------------------------
  Name                              Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/MAIN_S_SDT_WIZ_CLASS        Wizard: Assistensklassen

  /PRIS/MAIN_S_SDT_WIZ_INSTANCE     Wizard: Instanzen zu Assistensklassen

  /PRIS/MAIN_S_SDT_WIZ_DATA         Wizard: Daten

  /PRIS/MAIN_S_SDT_WIZ_SOL_LIST     Wizard: Liste mit Daten zu den
                                    Lösungen
  -----------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  Name                              Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/MAIN_TT_SDT_WIZ_CLASS       Wizard: Assistensklassen

  /PRIS/MAIN_TT_SDT_WIZ_INSTANCE    Wizard: Instanzen zu Assistensklassen

  /PRIS/MAIN_TT_SDT_WIZ_DATA        Wizard: Daten

  /PRIS/MAIN_TT_SDT_WIZ_SOL_LIST    Wizard: Liste mit Daten zu den
                                    Lösungen

  /PRIS/MAIN_TT_SDT_WIZ_SELECT      Wizard: Felder für Selektion
  -----------------------------------------------------------------------

### Klassenbibliotheken

  -----------------------------------------------------------------------
  Name                              Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/MAIN_CL_SDT_WIZ             Wizard: Logikklasse

  /PRIS/MAIN_CL_GTB_DATA            GTB: Methods to get Information about
                                    Data Types

  /PRIS/CX_MAIN_SDT_WIZ             Wizard Exception Class

  /PRIS/MAIN_IF_SDT_WIZ             Wizard: Interface für
                                    Assistenzklassen
  -----------------------------------------------------------------------

### Transaktionscode

  -----------------------------------------------------------------------
  Name                              Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/WIZARD                      Wizard

  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  Name                              Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/MAIN_WIZ_MSG                Wizard: Nachrichtklasse

  -----------------------------------------------------------------------

## Generische Tabellenleseklasse

### Dictionary Objekte

#### Datenelemente

  -----------------------------------------------------------------------
  Datenelement                        Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_DE_TABLE_NAME            Tabellenname

  /PRIS/MAIN_DE_FIELD_NAME            Feldname

  /PRIS/MAIN_DE_FIELD_VALUE           Feldwert
  -----------------------------------------------------------------------

#### Strukturen

  -----------------------------------------------------------------------
  Struktur                            Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_S_KEY_FIELDS             Struktur für Schlüsselfelder

  /PRIS/MAIN_S_FIELD_RANGE            Struktur für Range
  -----------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  Tabellentyp                         Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_TT_KEY_FIELDS            Tabellentyp für Schlüsselfelder

  /PRIS/MAIN_TT_FIELD_RANGE           Tabellentyp für Range
  -----------------------------------------------------------------------

### Klassen

  -----------------------------------------------------------------------
  Klasse                              Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_CL_GTB_TABLE_READ        Generische Tabellen Leseklasse

  /PRIS/CX_MAIN_GTB_TABLE_READ        Ausnahmeklasse für generisches
                                      Tabellenlesen
  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  Nachrichtenklasse                   Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_GTB_TREAD                Nachrichten für generisches
                                      Tabellenlesen

  -----------------------------------------------------------------------

## Transport Order Tool

### Klassen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_CL_TOT                   Transport Order Tool

  -----------------------------------------------------------------------

### Reports

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_TOT_ADD_LANG             Transportauftrags-Tool -
                                      Übersetzungsobjekte hinzufügen

  -----------------------------------------------------------------------

## Generische Suchhilfe

### Dictionary Objekte

#### Suchhilfe

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_SH_GSH_EXAMPL_T100       GSH: Beispiel-Suchhilfe für Tabelle
                                      T100

  -----------------------------------------------------------------------

### Interfaces

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_IF_GSH_C                 GSH: Konstanten für generische
                                      Suchhilfen

  -----------------------------------------------------------------------

### Klassen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_CL_GSH_BASE              GSH: Basisklasse für Suchhilfen

  /PRIS/MAIN_CL_GSH_FIELD             GSH: Suchhilfelogik zur Ermittlung
                                      von Feldern einer Tabelle oder
                                      Struktur
  -----------------------------------------------------------------------

### Funktionsgruppen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_GSH_EXAMPLE_EXI          GSH: Beispiel-Suchhilfe-Exits

  -----------------------------------------------------------------------

### Funktionsbausteine

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_GSG_EXIT_T100            GSH: Beispiel Suchhilfe-Exit für
                                      Tabelle T100

  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_HTTP_REQ                 Nachrichten zur Hilfsklasse für
                                      HTTP-Requests

  -----------------------------------------------------------------------

## CSV-Handling

### Dictionary Objekte

#### Strukturen

  -----------------------------------------------------------------------
  **Struktur**                         **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_S_GTB_LOGIC_CLASS         GTB: Name der Logik Klasse

  /PRIS/MAIN_S_KEY_VALUE_F4            Schlüsselwert F4 Hilfe
  -----------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  **Tabellentypen**                    **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_TT_GTB_LOGIC_CLASS        GTB: Name der Logik Klasse

  -----------------------------------------------------------------------

#### Suchhilfen

  -----------------------------------------------------------------------
  **Suchhilfen**                       **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_SH_CSV_CLASS              Alle Klassen die das CSV-Interface
                                       implementiert haben lesen

  /PRIS/MAIN_SH_GTB_CSV_CLASS          GTB: Suchhilfe um den Namen der
                                       CSV Logik Klasse zu bekommen

  /PRIS/MAIN_SH_KEY_VALUE              Schlüsselwert Suchhilfe
  -----------------------------------------------------------------------

### Klassenbibliothek

  -----------------------------------------------------------------------
  **Ausnahmeklasse**                   **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/CX_MAIN_GTB_CSV_HANDLING       Ausnahme für CSV Handling

  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  **Klasse**                           **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_CL_GTB_CLASS_DET          GTB: Logik zur Klassenbestimmung

  /PRIS/MAIN_CL_GTB_CSV_HANDLING       GTB: CSV Handling

  /PRIS/MAIN_CL_GTB_SH_CSV_CLASS       GTB: Logik für Suchhilfe um Namen
                                       der CSV Klasse zu bekommen
  -----------------------------------------------------------------------

  -----------------------------------------------------------------------
  **Interface**                        **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_IF_GTB_CSV_HANDLING       GTB: CSV HANDLING

  -----------------------------------------------------------------------

### Programme

  -----------------------------------------------------------------------
  **Programm**                         **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_GTB_CSV_HANDLING          Programm
                                       /PRIS/MAIN_GTB_CSV_HANDLING

  -----------------------------------------------------------------------

### Funktionsgruppe

  -----------------------------------------------------------------------
  **Funktionsgruppe**                  **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_GTB_SH_EXITS              GTB: Suchhilfen Exit

  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  **Nachrichtenklasse**                **Beschreibung**
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_GTB_CSV                   Nachrichten für CSV Handling

  -----------------------------------------------------------------------

## Access Control Definition - Zugriffsfolge

### Dictionary Objekte

#### Domänen

  -----------------------------------------------------------------------------
  Name                             Beschreibung                    Datentyp
  -------------------------------- ------------------------------- ------------
  /PRIS/MAIN_DO_COMPARE_OPERATOR   Vergleichsoperator              CHAR 2

  -----------------------------------------------------------------------------

#### Datenelemente

  ----------------------------------------------------------------------------
  Name                             Beschreibung
  -------------------------------- -------------------------------------------
  /PRIS/MAIN_DE_COMPARE_OPERATOR   Vergleichsoperator

  ----------------------------------------------------------------------------

#### Strukturen

  ---------------------------------------------------------------------------
  Name                            Beschreibung
  ------------------------------- -------------------------------------------
  /PRIS/MAIN_S_GTB_FILTER_KEY     Filterschlüssel bestehend aus: Feldname und
                                  -wert

  /PRIS/MAIN_S_GTB_FIELD_COMPAR   Feldvergleich bestehend aus: Feldname und
                                  Vergleichsoperator
  ---------------------------------------------------------------------------

#### Tabellentypen

  ----------------------------------------------------------------------------
  Name                             Beschreibung
  -------------------------------- -------------------------------------------
  /PRIS/MAIN_TT_GTB_FILTER_KEY     Filterschlüssel bestehend aus: Feldname und
                                   -wert

  /PRIS/MAIN_TT_GTB_FIELD_COMPAR   Feldvergleich bestehend aus: Feldname und
                                   Vergleichsoperator
  ----------------------------------------------------------------------------

### Klassenbibliothek

  --------------------------------------------------------------------------
  Name                           Beschreibung
  ------------------------------ -------------------------------------------
  /PRIS/MAIN_CL_GTB_ACCESS_SEQ   Logikklasse

  /PRIS/CX_MAIN_GTB_ACCESS_SEQ   Ausnahmeklasse
  --------------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                        Beschreibung
  --------------------------- -------------------------------------------
  /PRIS/MAIN_GTB_MSG          Nachrichtenklasse

  -----------------------------------------------------------------------

## Generischer Löschreport

### Dictionary Objekte

#### Datenbanktabellen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/GTB_RTABC                     Steuerdaten für den Report zum
                                      Löschen von Bewegungsdaten

  -----------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_TT_GTB_RTABC             Steuerdaten für den Report zum
                                      Löschen von Bewegungsdaten

  -----------------------------------------------------------------------

### Klassenbibliothek

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/CX_MAIN_GTB_RTAB              Ausnahmeklasse für Löschreport

  /PRIS/MAIN_CL_GTB_RTAB              Werkzeug zum Entfernen von
                                      Einträgen aus
                                      Bewegungsdaten-tabellen
  -----------------------------------------------------------------------

### Interfaces

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_IF_GTB_RTAB              Schnittstelle: Einträge aus
                                      Bewegungsdatentabellen löschen

  -----------------------------------------------------------------------

### Funktionsgruppe

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/GTB_RTABC                     Extended Table Maintenance
                                      (Generated)

  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_HTTP_REQ                 Nachrichten zur Hilfsklasse für
                                      HTTP-Requests

  -----------------------------------------------------------------------

## GTB HTTP-Request

### Klassenbibliothek

  -----------------------------------------------------------------------
  Name                                 Beschreibung
  ------------------------------------ ----------------------------------
  /PRIS/CX_MAIN_GTB_HTTP_REQUEST       Ausnahmeklasse für HTTP-Anfragen

  /PRIS/MAIN_CL_GTB_HTTP_REQUEST       Hilfsklasse zum Senden von
                                       HTTP-Anfragen
  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_HTTP_REQ                 Nachrichten zur Hilfsklasse für
                                      HTTP-Requests

  -----------------------------------------------------------------------

## GTB Timer

### Klassenbibliothek

  ------------------------------------ ----------------------------------
  **Klasse**                           **Beschreibung**

  /PRIS/MAIN_CL_GTB_TIMER              GTB: \_EWM-001h - Hilfsklasse --
                                       Timer
  ------------------------------------ ----------------------------------

## Generische Berechtigungsprüfung

### Dictionary Objekte

#### Domänen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_DO_SOLUTION_CODE         Lösungskürze

  -----------------------------------------------------------------------

#### Datenelemente

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_DE_SOLUTION_CODE         Lösungskürze

  -----------------------------------------------------------------------

### Klassenbibliothek

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/CX_MAIN_GTB_AUTH_CHECK        Ausnahme für Berechtigungsprüfung
                                      /PRIS/MAIN_CL_GTB_AUTH_CHECK

  /PRIS/MAIN_CL_GTB_AUTH_CHECK        GTB: prismat-Berechtigungsprüfung

  /PRIS/EWM_CL_GTB_AUTH_CHECK         GTB: prismat-Berechtigungsprüfung
                                      EWM
  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_AUTH_CHCK                Nachrichten bzgl.
                                      Berechtigungsprüfung

  -----------------------------------------------------------------------

### Berechtigungsobjekt

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN                          Berechtigungsobjekt für
                                      prismat-Rakete

  -----------------------------------------------------------------------

## BAdI and Enhancement Framework

### Dictionary Objekte

#### Datenbanktabellen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/BEF_CFG                       BEF: Konfigurations Tabelle

  /PRIS/BEF_DEF                       BEF: Assignment of interface to
                                      enhancement.
  -----------------------------------------------------------------------

#### Strukturen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_S_BEF_INPUT_CLASS        Eingabedaten zur Anlage Logikklasse

  /PRIS/MAIN_S_BEF_INPUT_ENH          Eingabedaten zur Erweiterung

  /PRIS/MAIN_S_BEF_INPUT_IMPL         Eingabedaten zur Implementierung um
                                      dem generierten Code

  /PRIS/MAIN_S_BEF_INPUT_BADI         Eingabedaten zum neuen BAdI

  /PRIS/MAIN_S_BEF_INPUT_BADIOLD      Eingabedaten zum alten BAdI

  /PRIS/MAIN_S_BEF_INPUT_USEREXI      Eingabedaten zum UserExit
  -----------------------------------------------------------------------

#### Tabellentypen

  -----------------------------------------------------------------------
  Name                                 Beschreibung
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_TT_BEF_CFG                BEF: Configuration Table

  /PRIS/MAIN_TT_BEF_CHECK_RESUL        BEF: Classes for Enhancement

  /PRIS/MAIN_TT_BEF_CONFIG             BEF: Status Overview

  /PRIS/MAIN_TT_BEF_DEF                BEF: Assignment of interface to
                                       enhancement.

  /PRIS/MAIN_TT_BEF_ENHDATA_NAME       BEF: Enhancement Data per Name

  /PRIS/MAIN_TT_BEF_ENH_GROUP          BEF: Enhancement Groups

  /PRIS/MAIN_TT_BEF_ENH_TEXT           BEF: Enhancement Text

  /PRIS/MAIN_TT_BEF_EXCEPTION          BEF: Exception data for method
                                       call

  /PRIS/MAIN_TT_BEF_EXC_DESCR          BEF: Exception handling

  /PRIS/MAIN_TT_BEF_INSTANCE           BEF: Instance for key type and
                                       value

  /PRIS/MAIN_TT_BEF_INTF_ASSIGN        BEF: Interface and Class
                                       assignment

  /PRIS/MAIN_TT_BEF_METH_DESCR         BEF: Method Description

  /PRIS/MAIN_TT_BEF_PARAMETER          BEF: Parameter data for method
                                       call

  /PRIS/MAIN_TT_BEF_PARAM_DESCR        BEF: Paramater description

  /PRIS/MAIN_TT_BEF_TRANSP_DATA        BEF: Transport Data
  -----------------------------------------------------------------------

#### Suchhilfen

  -----------------------------------------------------------------------
  Name                                 Beschreibung
  ------------------------------------ ----------------------------------
  /PRIS/MAIN_SH_BEF_ENH_FILTER         BEF: Enhancement Name Search Help
                                       for Filter Function in OVR

  /PRIS/MAIN_SH_BEF_ENH_NAME           BEF: Search Help for all
                                       Enhancement Types

  /PRIS/MAIN_SH_DEVCLASS               BEF: Search Help for Packages
  -----------------------------------------------------------------------

### Klassenbibliothek

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_CL_BEF                   BAdI and Enhancement Framework

  /PRIS/MAIN_CL_BEF_GEN               BEF: Helper class for generation

  /PRIS/MAIN_CL_BEF_SH_ENH_NAME       BEF: Enhancement Logic Class

  /PRIS/MAIN_CL_BEF_UI                BEF: Enhancement Handling
  -----------------------------------------------------------------------

### Funktionsgruppen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_BEF_SH_EXITS             BEF: Search Help Exits

  -----------------------------------------------------------------------

### Reports

  -----------------------------------------------------------------------------------
  Name                         Beschreibung
  ---------------------------- ------------------------------------------------------
  /PRIS/MAIN_BEF_CONFIG        Control Framework (Switch + Config) - BAdI-Framework
                               (Configuration)

  /PRIS/MAIN_BEF_OVERVIEW      Control Framework (Switch + Config) - BAdI-Framework
                               (Overview)
  -----------------------------------------------------------------------------------

### Transaktionscodes

  -----------------------------------------------------------------------
  Name                         Beschreibung
  ---------------------------- ------------------------------------------
  /PRIS/BEF_OVR                Overview

  /PRIS/BEF_CFG                Configuration

  /PRIS/BEF_DEF                Definition
  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_BEF                      BEF: Message Class

  -----------------------------------------------------------------------

## GTB System

### Klassenbibliothek

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/CX_MAIN_GTB_SYSTEM            Exception for System

  /PRIS/MAIN_CL_GTB_SYSTEM            GTB: System data, e.g. client
  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_GTB_SYST                 GTB: System

  -----------------------------------------------------------------------

## GTB - Kleine Werkzeuge

### Datenelemente

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_DE_GTB_LOGIC_CLASS       GTB: Name of Logic Class

  -----------------------------------------------------------------------

### Strukturen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_S_GTB_LOGIC_CLASS        GTB: Name of Logic Class

  /PRIS/MAIN_S_GTB_SALV_POPUP         GTB: SALV popup data

  /PRIS/MAIN_S_SALV_FUNCTIONS         Main SALV Functions
  -----------------------------------------------------------------------

### Tabellentypen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_TT_GTB_LOGIC_CLASS       GTB: Name of Logic Classes

  /PRIS/MAIN_TT_GTB_RSTABLE           GTB: Table Lock Structure

  /PRIS/MAIN_TT_SALV_FUNCTION         Main SALV Functions
  -----------------------------------------------------------------------

### Klassenbibliothek 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/CX_MAIN_GTB_ALV               Exception Class for ALV

  /PRIS/CX_MAIN_GTB_ENQUEUE           Exception for Authority Check
                                      /PRIS/EWM_CL_GTB_ENQUEUE

  /PRIS/CX_MAIN_GTB_SYSTEM            Exception for System

  /PRIS/MAIN_CL_GTB_CLASS_DET         GTB: Logic for Class Determination

  /PRIS/MAIN_CL_GTB_DATA              GTB: Methods to get Information
                                      about Data Types

  /PRIS/MAIN_CL_GTB_ENQUEUE           GTB: Enqueue Help Class

  /PRIS/MAIN_CL_GTB_SALV              Utility Class for SALV

  /PRIS/MAIN_CL_GTB_SAP_GUI           GTB: SAP GUI

  /PRIS/MAIN_IF_GTB_SALV_EVENT        GTB: Event Handling Interface for
                                      SALV
  -----------------------------------------------------------------------

### Nachrichtenklassen 

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/MAIN_GTB_ENQ                  GTB: Enqueue Message Class

  /PRIS/MAIN_GTB_SGUI                 GTB: SAP GUI

  /PRIS/MAIN_GTB_SYST                 GTB: System
  -----------------------------------------------------------------------

## Easy Mapper

### Dictionary Objekte

#### Tabellentypen

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/EWM_TT_MAP_HUIDENT            HU-Identifikationen mit HU-GUIDs

  /PRIS/EWM_TT_MAP_PROD_APO           APO-Produkt

  /PRIS/EWM_TT_MAP_SYSUUID            System UUIDs
  -----------------------------------------------------------------------

### Klassenbibliothek

  -----------------------------------------------------------------------
  Klasse                              Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/EWM_CL_MAP                    Easy Mapper

  /PRIS/CX_EWM_MAP                    Easy Mapper Ausnahmeklasse
  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  Nachrichtenklasse                   Beschreibung
  ----------------------------------- -----------------------------------
  /PRIS/EWM_PACKSPEC                  Packspezifikation

  -----------------------------------------------------------------------

## RFC Hilfsklasse

### Klassenbibliothek

  -----------------------------------------------------------------------
  Klasse/Interface                   Beschreibung
  ---------------------------------- ------------------------------------
  /PRIS/CX_EWM_RFC_HLP_ERROR         RFC Help Error

  /PRIS/EWM_CL_HLP_RFC               RFC Help Class
  -----------------------------------------------------------------------

### Nachrichtenklassen

  -----------------------------------------------------------------------
  Nachrichtenklasse                 Beschreibung
  --------------------------------- -------------------------------------
  /PRIS/EWM_HLP_RFC                 RFC Help Messages

  -----------------------------------------------------------------------

# [Kundeneigene Anpassungen]{.mark}

## Key Values -- Schlüsselwerte

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## CFG -- Konfigurations-Framework

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## SWT -- Schalter-Framework

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## SDT Adjustment Report

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## Wizard

### Interface-Implementierung

Über das Interface /PRIS/MAIN_IF_SDT_WIZ können Assistentenklassen für
den Wizard zu den Lösungen angelegt werden.

Für die Implementierung einer Assistentenklasse sind folgende Schritte
erforderlich:

**[INITIALIZE]{.underline}**

Diese Methode wird dafür verwendet, um die Schlüsselart und den
Schlüsselwert an die Instanz der Assistentenklasse zu übergeben.

![Ein Bild, das Text, Screenshot, Display, Zahl enthält. Automatisch
generierte Beschreibung](media/image102.png){width="5.777777777777778in"
height="3.9166666666666665in"}**[\]{.underline}**

**[GET_SOLUTION_INFO:]{.underline}**

Die Methode dient dazu, Informationen zu einer bestimmten Lösung
abzurufen.

Zu diesen Daten gehören die Lösungsnummer, das Lösungskürzel, die
Vertriebsnummer, die Version, eine Beschreibung und der Status der
Konfiguration.

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. Automatisch
generierte Beschreibung](media/image103.png){width="5.901388888888889in"
height="5.56875in"}

**[GET_FIELDS_FOR_SELECTION]{.underline}**

Diese Methode gibt eine Tabelle mit Informationen für die benötigten
Eingabefelder auf dem Selektionsbild zurück.

Diese Tabelle muss Lösungsspezifisch aufgebaut werden.

Die Tabelle RT_FIELD_TAB ist vom Typ RSDSFIELDS_T. Die Felder TABLENAME,
FIELDNAME und TYPE müssen befüllt werden.

Für das Feld TYPE kann die Methode GET_INTERNAL_TYPE_BY_NAME aus der
Klasse /PRIS/MAIN_CL_GTB_DATE verwendet werden. Diese Methode gibt den
internen Typ basierend auf dem Namen des Datentyps zurück.

![Ein Bild, das Text, Elektronik, Screenshot, Display enthält.
Automatisch generierte
Beschreibung](media/image104.png){width="5.901388888888889in"
height="5.142361111111111in"}

**[CHECK_INPUTS]{.underline}**

Die Methode überprüft die Richtigkeit der vom Benutzer eingegebenen
Daten und stellt sicher, dass alle erforderlichen Felder korrekt
ausgefüllt sind, bevor die Konfiguration fortgesetzt wird.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image105.png){width="5.897916666666666in"
height="5.759027777777778in"}

**[COMPILE_BASE_CONFIG]{.underline}**

Mit der Methode können Konfigurationsdaten für eine prismat-Lösung
erstellt werden. Dabei werden wichtige Informationen wie Tabellennamen,
Transporttyp, Transporttyp-Objekt, Tabellendaten, Tabellentypname,
Viewname und Tabellenschlüssel generiert.

Dafür wird eine Tabelle vom Typ /PRIS/MAIN_TT_SDT_WIZ_DATA befüllt.

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. Automatisch
generierte Beschreibung](media/image106.png){width="5.824305555555555in"
height="5.102083333333334in"}

## Generische Tabellenleseklasse

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## Transport Order Tool

### Klassen ableiten

Die Klasse /PRIS/MAIN_CL_TOT hat das Final-Kennzeichen nicht gesetzt und
verfügt über keine Attribute oder Methoden welche als privat definiert
wurden.

Somit kann problemlos von der Klasse abgeleitet werden.

## Generische Suchhilfe

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## CSV-Handling

### Klassen ableiten

Die in Kapitel [**5.9.2**](#klassenbibliothek) definierten Klassen sind
nicht als final gekennzeichnet und lassen sich somit im Kundennamensraum
erweitern.

### Interface-Implementierungen

Das in Kapitel [**5.9.2**](#klassenbibliothek) definierte Interface ist
für das Testprogramm notwendig.

### Konfigurationsmöglichkeiten

In der Methode *CHANGE_CHR_FROM_CSV* in der Klasse
*/PRIS/MAIN_CL_GTB_CSV_HANDLING* können spezielle Konfigurationen für
einzelne Datentypen eingestellt werden, wie z.B. Datums oder Uhrzeiten
Konvertierungen.

## Access Control Definition -- Zugriffsfolgen

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## Generischer Löschreport

### Spezielle Felder hinzufügen

Die Datenbanktabelle /PRIS/GTB_RTABC und die Struktur
/PRIS/GTB_RTABC_OBJ können um kundeneigene Felder erweitert werden.

Bitte beachten Sie, dass bei einer Erweiterung der Tabelle
/PRIS/GTB_RTABC ein neuer Pflegedialog generiert werden muss, da die
zusätzlichen Felder sonst nicht gepflegt werden können.

### Klassen ableiten

Die Klassen /PRIS/CX_MAIN_GTB_RTAB und /PRIS/MAIN_CL_GTB_RTAB haben das
Final-Kennzeichen nicht gesetzt und verfügen über keine Attribute oder
Methoden welche als privat definiert wurden.

Somit kann problemlos von beiden Klassen abgeleitet werden.

Bitte beachten Sie, dass eine Ableitung der Klasse
/PRIS/MAIN_CL_GTB_RTAB nur durch einen neuen Report aufgerufen werden
kann.

### Interface-Implementierung

Zur Umsetzung kundenspezifischer Löschlogiken kann das Interface
/PRIS/MAIN_IF_GTB_RTAB ausimplementiert werden.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image107.png){width="5.901388888888889in"
height="1.7180555555555554in"}

Das Interface umfass die folgenden Methoden:

- IS_RELEVANT

  - Parameter

    - IO_LOG

    - IS_SETTINGS

    - RV_RELEVANT

  - Funktion

    - Die Methode IS_RELEVANT dient zum Prüfen, ob zum aktuellen
      Zeitpunkt Einträge aus der jeweiligen Tabelle gelöscht werden
      sollen.

    - Ist dies der Fall wird über den Parameter RV_RELEVANT der Wert
      ABAP_TRUE zurückgegeben.

    - Wird über den Parameter RV_RELEVANT der Wert ABAP_FALSE
      zurückgegeben wird die Tabelle für die weitere Verarbeitung
      verworfen.

- DELETE_ENTRIES

  - Parameter

    - IO_LOG

    - IS_SETTINGS

    - IV_TIMESTAMP_DELETE

  - Funktion

    - Die Methode DELETE_ENTRIES dient zur Abbildung der
      kundenspezifischen Löschlogik.

    - Falls für die Tabelle, in den Einstellungen, ein Feld für den
      Änderungszeitpunkt und die Lebenszeit der Einträge in Tagen
      hinterlegt wurde wird ein Zeitstempel zum aktuellen Zeitpunkt,
      welcher um die Anzahl an Tagen reduziert wurde über den Parameter
      IV_TIMESTAMP_DELETE übergeben.

### Konfigurationsmöglichkeiten

Der Report /PRIS/MAIN_GTB_RTAB wird über die Tabelle /PRIS/GTB_RTABC
konfiguriert.

![Ein Bild, das Text, Screenshot, Display, Software enthält. Automatisch
generierte Beschreibung](media/image30.png){width="5.901388888888889in"
height="4.9118055555555555in"}

![Ein Bild, das Text, Software, Computersymbol, Zahl enthält.
Automatisch generierte
Beschreibung](media/image31.png){width="5.901388888888889in"
height="2.4444444444444446in"}

Die Tabelle umfasst die folgenden Spalten:

  -----------------------------------------------------------------------
  Name                                Beschreibung
  ----------------------------------- -----------------------------------
  KEY_TYPE                            Schlüsselart

  KEY_VALUE                           Schlüsselwert

  TABNAME                             Tabellenname

  FIELDNAME                           Feldname

  OLDER_DAYS                          älter als \[in Tagen\]

  CLASSNAME                           Klassenname

  INACT                               Inaktivkennzeichen
  -----------------------------------------------------------------------

## GTB HTTP-Request

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## GTB Timer

### Klasse ableiten

Die im vorherigen Kapitel definierten Klasse ist nicht als final
gekennzeichnet und lässt sich somit im Kundennamensraum erweitern.

## Generische Berechtigungsprüfung

### Klassen ableiten

Die Klassen /PRIS/CX_MAIN_GTB_AUTH_CHECK und
/PRIS/MAIN_CL_GTB_AUTH_CHECK haben das Final-Kennzeichen nicht gesetzt
und verfügen über keine Attribute oder Methoden welche als privat
definiert wurden.

Somit kann problemlos von den Klassen abgeleitet werden.

## BAdI and Enhancement Framework

### Felder hinzufügen

Die Tabellen der Lösung sind alle erweiterbar.

### Klassen ableiten

Die Hauptklasse für BAdI- und Enhancement-Framework hat das Final Flag
nicht gesetzt und kann daher abgeleitet werden.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image108.png){width="5.427083333333333in"
height="3.7083333333333335in"}

Alle Methoden und Attribute sind öffentlich oder geschützt und können
daher problemlos in abgeleiteten Klassen verwendet bzw. redefiniert
werden.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image109.png){width="5.427083333333333in"
height="2.84375in"}

Die Klasse /PRIS/MAIN_CL_BEF_UI für BAdI- und Enhancement-Framework hat
das Final Flag nicht gesetzt und kann daher abgeleitet werden. Sie
umfasst die Logik für die Reports /PRIS/MAIN_BEF_OVERVIEW und
/PRIS/MAIN_BEF_CONFIG.

![Ein Bild, das Text, Screenshot, Zahl, Schrift enthält. Automatisch
generierte Beschreibung](media/image110.png){width="5.427083333333333in"
height="3.53125in"}

### Interfaces

Diese Lösung umfasst das Interface /PRIS/MAIN_IF_BEF.

Es dient dazu Logikklassen für Erweiterungen zu finden und die
entsprechenden Erweiterungsimplementierungen über den Wizard zu
generieren.

Das Interface umfasst die Methoden GET_DEFINITION_DATA und
GET_REFERENCE_INTERFACE_NAME.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. KI-generierte
Inhalte können fehlerhaft
sein.](media/image111.png){width="5.901388888888889in"
height="1.8180555555555555in"}

Die Methode GET_DEFINITION_DATA gibt eine Struktur des Typen
/PRIS/BEF_DEF zurück.

Die Struktur enthält die Art der Erweiterung, den Namen der Erweiterung,
das BEF-Interface für die Logikklassen und eine Beschreibung.

Die Methode GET_REFERENCE_INTERFACE_NAME gibt den Namen des
Standard-Interfaces der jeweiligen Erweiterung zurück.

### Konfigurationsmöglichkeiten

Es sind keine weiteren Konfigurationsmöglichkeiten vorgesehen.

## GTB System

### Klassen ableiten

Die Klassen /PRIS/CX_MAIN_GTB_SYSTEM und /PRIS/MAIN_CL_GTB_SYSTEM haben
das Final-Kennzeichen nicht gesetzt und verfügen über keine Attribute
oder Methoden welche als privat definiert wurden.

Somit kann problemlos von den Klassen abgeleitet werden.

## GTB - Kleine Werkzeuge

### Klassen ableiten

Die Klassen haben alle das Final-Kennzeichen nicht gesetzt und verfügen
über keine Attribute oder Methoden welche als privat definiert wurden.

Somit kann problemlos von den Klassen abgeleitet werden.

## Easy Mapper

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

## RFC Hilfsklasse

Für diese Lösung sind keine spezifischen Anpassungsmöglichkeiten
vorgesehen, die über die Möglichkeiten hinausgehen, die der Standard
anbietet.

# [Einrichtung im Zielsystem]{.mark}

## Key Values -- Schlüsselwerte

Zusätzlich zur Konfiguration (siehe [**3.1.4**](#konfiguration)) sind
für diese Lösung keine weiteren Schritte zur Einrichtung im Zielsystem
erforderlich.

## CFG -- Konfigurations-Framework

Zusätzlich zur Konfiguration (siehe [**3.2.4**](#konfiguration-1)) sind
für diese Lösung keine weiteren Schritte zur Einrichtung im Zielsystem
erforderlich.

## SWT -- Schalter-Framework

Zusätzlich zur Konfiguration (siehe [**3.3.4**](#konfiguration-2)) sind
für diese Lösung keine weiteren Schritte zur Einrichtung im Zielsystem
erforderlich.

## SDT Adjustment Report

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Wizard

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Generische Tabellenleseklasse

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Transport Order Tool

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Generische Suchhilfe

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## CSV-Handling

Zusätzlich zur Konfiguration (siehe [Fehler! Verweisquelle konnte nicht
gefunden werden.](#_Ref188619289)) sind für diese Lösung keine weiteren
Schritte zur Einrichtung im Zielsystem erforderlich.

## Access Control Definition -- Zugriffsfolgen

Zusätzlich zur Konfiguration (siehe [**3.10.4**](#konfiguration-9)) sind
für diese Lösung keine weiteren Schritte zur Einrichtung im Zielsystem
erforderlich.

## Generischer Löschreport

Zusätzlich zur Konfiguration (siehe [**3.11.4**](#konfiguration-10))
sind für diese Lösung keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## GTB HTTP-Request

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## GTB Timer

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Generische Berechtigungsprüfung

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## BAdI and Enhancement Framework

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## GTB System

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## GTB - Kleine Werkzeuge

Für die Klassen sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## Easy Mapper

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

## RFC Hilfsklasse

Für diese Lösung sind keine weiteren Schritte zur Einrichtung im
Zielsystem erforderlich.

# [Sonstiges]{.mark}

## Key Values -- Schlüsselwerte

Für diese Lösung gibt es keine zusätzlichen Informationen.

## CFG -- Konfigurations-Framework

### Pflegereport

Über die Transaktion /PRIS/CFG_MENU kann der Report zur zentralen Pflege
der CFG-Tabellen aufgerufen werden.

![Ein Bild, das Text enthält. Automatisch generierte
Beschreibung](media/image112.png){width="5.901388888888889in"
height="3.2309536307961504in"}

Der Report separiert die Steuertabellen in die Schritte „Definition",
„Werte zu Konstanten hinterlegen" und „Werte zu Parametern hinterlegen".

Diese Aufteilung dient dazu den jeweiligen Entwicklern die initiale
Pflege der Tabellen zu erleichtern.

Dabei gilt immer, dass Konstanten bzw. Parameter zuerst definiert,
danach zugeordnet und im Anschluss mit Werten versorgt werden müssen.

Somit können die jeweiligen Entwickler sich von oben nach unten
durcharbeiten.

Wenn die Formatierungsinformationen (Groß-/Kleinschreibung, Länge,
Ausrichtung oder Füllzeichen) von bestehenden Attributen geändert wurden
wird eine Aktualisierung der bestehenden Werte automatisch im
Hintergrund angestoßen. Diese Aktualisierungen sind jedoch System
spezifisch. Daher sollte nach dem Transport von Änderungen an den
Formatierungsinformationen die Aktualisierung der Werte, in dem
jeweiligen System, explizit über den Button „Formateinstellungen
anwenden" angestoßen werden.

Da sich hinter der Definition und der Zuordnung mandantenübergreifende
Customizing Tabellen verbergen werden für die Pflege dieser Daten
Workbench-Transporte benötigt.

Die Pflege von Werten zu konstanten Einzelwerten oder Wertegruppen
erfolgt jedoch abhängig von Mandanten und Schlüsselwerten und benötigt
daher Customizing-Transporte.

Aufgrund dessen, dass die Werte zu Parametern je System gepflegt werden
müssen wird dafür keinerlei Transport benötigt.

### Zugriff auf Konstanten- und Parameterwerte

Der programmseitige Zugriff auf Konstanten- und Parameterwerte erfolgt
über die Klasse /PRIS/MAIN_CL_CFG.

#### Instanz der Klasse /PRIS/MAIN_CL_CFG erzeugen

Über die Methode GET_INSTANCE wird eine Instanz zur Klasse
/PRIS/MAIN_CL_CFG erzeugt.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image113.png){width="5.901388888888889in"
height="2.9166666666666665in"}

Für die in der Standardauslieferung enthaltenden Schlüsselarten stehen
Konstanten in dem Interface /PRIS/MAIN_IF_KEY_VALUES_C zur Verfügung.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte Beschreibung](media/image2.png){width="5.901388888888889in"
height="2.426388888888889in"}

Falls Sie im EWM unterwegs sind, verwenden Sie bitte die Klasse
/PRIS/EWM_CL_CFG und deren Methode GET_INSTANCE_EWM, da dieser statt
einer Schlüsselart und einem Schlüsselwert direkt die EWM-Lagernummer
übergeben werden kann.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image114.png){width="4.158694225721785in"
height="2.741903980752406in"}

Die folgenden Parameter sind bei beiden Klassen und deren
GET_INSTANCE-Methoden vorhanden:

+------------------------+--------+-----------------------------------+
| Methode                | Art    | Beschreibung                      |
+:======================:+========+===================================+
| IV_PROGNAME            | Import | Programm, Report,                 |
|                        |        | Funktionsbaustein oder Klasse in  |
|                        |        | dem bzw. in der die Konstanten    |
|                        |        | und/oder Parameter verwendet      |
|                        |        | werden sollen.                    |
+------------------------+--------+-----------------------------------+
| IV_NEW                 | Import | Erstellung einer neuen Instanz    |
|                        |        | erzwingen.                        |
+------------------------+--------+-----------------------------------+
| IV_FORCE_DUMP_SYSID    | Import | Über diesen Parameter wird die    |
|                        |        | Force-Dump-Funktionalität für das |
|                        |        | angegebene System aktiviert.      |
|                        |        |                                   |
|                        |        | Wenn mit Force-Dump gearbeitet    |
|                        |        | werden soll sollte immer nur das  |
|                        |        | Entwicklungssystem angegeben      |
|                        |        | werden.                           |
|                        |        |                                   |
|                        |        | Zu Force-Dump:                    |
|                        |        |                                   |
|                        |        | Bei der Verwendung von Force-Dump |
|                        |        | wird bei falschen                 |
|                        |        | Datenkonstellationen ein Kurzdump |
|                        |        | ausgelöst.                        |
|                        |        |                                   |
|                        |        | Falsche Konstellationen können    |
|                        |        | zum einen in der Methode          |
|                        |        | INITIALIZE beim Einlesen der      |
|                        |        | Daten oder beim Zugriff über die  |
|                        |        | Methoden GET_VALUE_GROUP und      |
|                        |        | GET_VALUE_SINGLE festgestellt     |
|                        |        | werden.                           |
|                        |        |                                   |
|                        |        | Falsche Konstellationen in der    |
|                        |        | INITIALIZE-Methode:\              |
|                        |        | - Fehlende Zuordnungsdaten\       |
|                        |        | - Fehlende Definitionsdaten       |
|                        |        |                                   |
|                        |        | Falsche Konstellationen in den    |
|                        |        | GET-Methoden:\                    |
|                        |        | - Bei Übergabe eines unbekannten  |
|                        |        | Konstanten- oder Parameternamens  |
+------------------------+--------+-----------------------------------+
| IV_FORCE_DUMP_CLIENT   | Import | Nur wirksam in Kombination mit    |
|                        |        | IV_FORCE_DUMP_SYSID!              |
|                        |        |                                   |
|                        |        | Mit diesem Parameter kann die     |
|                        |        | Force-Dump-Funktionalität         |
|                        |        | zusätzlich auf einen Mandanten    |
|                        |        | eingeschränkt werden.             |
|                        |        |                                   |
|                        |        | Dieser Parameter ist für          |
|                        |        | Systemlandschaften gedacht, bei   |
|                        |        | denen statt mit einem Q-System    |
|                        |        | mit einem extra Mandanten im      |
|                        |        | Entwicklungssystem gearbeitet     |
|                        |        | wird.                             |
+------------------------+--------+-----------------------------------+
| IV_DUMMY_FOR_RANGE     | Import | Nur wirksam, wenn NICHT mit       |
|                        |        | Force-Dump gearbeitet wird.       |
|                        |        |                                   |
|                        |        | Ist dieser Parameter gesetzt gibt |
|                        |        | die Methode GET_VALUE_GROUP bei   |
|                        |        | einer fehlenden Wertzuweisung     |
|                        |        | eine Range mit dem Dummy-Eintrag  |
|                        |        | IEQZZZZZZZZZZ\... zurück.         |
|                        |        |                                   |
|                        |        | Andernfalls würde in einem        |
|                        |        | solchen Fall eine leere Range     |
|                        |        | zurückgegeben.                    |
+------------------------+--------+-----------------------------------+
| IV_EXC_BY_ACCESS       | Import | Dieser Parameter ist in Version   |
|                        |        | 1.1 hinzugekommen.                |
|                        |        |                                   |
|                        |        | Er steuert, ob beim Wertzugriff   |
|                        |        | über eine der GET_VALUE-Methoden  |
|                        |        | bei Übergabe eines Attributnamens |
|                        |        | zu dem kein Wert hinterlegt ist   |
|                        |        | eine Ausnahme vom Typ             |
|                        |        | /PRIS/CX_MAIN_CFG_MISSING         |
|                        |        | ausgelöst werden soll.            |
|                        |        |                                   |
|                        |        | Der Parameter ist standardmäßig   |
|                        |        | auf ABAP_TRUE gesetzt.            |
+------------------------+--------+-----------------------------------+
| IV_UPDATE_ASYNC        | Import | Dieser Parameter ist in Version   |
|                        |        | 1.2 hinzugekommen.                |
|                        |        |                                   |
|                        |        | Er steuert, ob beim Einlesen der  |
|                        |        | Daten eine Aktualisierung der     |
|                        |        | Werte (anhand der                 |
|                        |        | Formatierungs-einstellungen)      |
|                        |        | asynchron angestoßen werden soll. |
|                        |        |                                   |
|                        |        | Der Parameter ist standardmäßig   |
|                        |        | auf ABAP_TRUE gesetzt.            |
|                        |        |                                   |
|                        |        | Die entsprechende Logik wird      |
|                        |        | jedoch nur aufgerufen, wenn die   |
|                        |        | Formatierungseinstellungen der    |
|                        |        | vorhanden Attribute seit dem      |
|                        |        | letzten Lauf der Logik angepasst  |
|                        |        | wurden.                           |
+------------------------+--------+-----------------------------------+
| EO_INSTANCE            | Export | Eine Instanz der jeweiligen       |
|                        |        | Klasse.                           |
+------------------------+--------+-----------------------------------+

#### Instanz initialisieren

##### Methode INITIALIZE

Es kann Situationen geben, in denen es gewünscht ist fehlende Werte von
weniger wichtigen Konstanten oder Parametern zu dulden.

Um diesem Umstand gerecht zu werden wurde die Initialisierung der
Instanz aus dem Konstruktor in die INITIALIZE-Methode ausgelagert.

Das war notwendig, da wenn eine klassenbasierte Ausnahme geworfen wird,
keine Instanz erstellt wird.

Die INITIALIZE-Methode muss nach der Instanziierung einmal aufgerufen
werden, da über diese Methode das Einlesen der Daten angestoßen wird.

Ein erneuter Aufruf der Methode initialisiert jedoch nur die interne
Meldungstabelle. Falls aktuelle Konfigurationsdaten benötigt werden
sollte daher am besten mit einer neuen Instanz gearbeitet werden.

In Fehlersituationen wird eine Ausnahme vom Typ /PRIS/CX_MAIN_CFG_ERROR
ausgelöst.

Falls mit Force-Dump gearbeitet wird, wird stattdessen ein Kurzdump
ausgelöst.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image115.png){width="4.21259842519685in"
height="1.8714074803149607in"}

Da nur die INITIALIZE-Methode die Ausnahmeklasse /PRIS/CX_MAIN_CFG_ERROR
verwendet wird diese in diesem Kapitel näher beschrieben.

**[Hinweis:]{.underline}**\
Seit Version 1.1 enthält die Struktur /PRIS/MAIN_S_CFG_ATTR_DATA das
Feld S_ERROR welche die Fehlermeldung zu dem jeweiligen fehlenden
Attribut enthält.

##### Ausnahmeklasse /PRIS/CX_MAIN_CFG_ERROR

Die Ausnahmeklasse /PRIS/CX_MAIN_CFG_ERROR wurde, wie man es dem Namen
entnehmen kann, extra für die Lösung *CFG* und dessen Eigenheiten
entworfen.

Da bei der Initialisierung nicht jede Fehlersituation direkt zum
Auslösen einer Ausnahme führt, liefert die Methode GET_TEXT keinen
Fehlertext zurück.

Stattdessen kann über die Methode GET_BAPIRETTAB auf eine
BAPIRET-Tabelle mit allen Fehlermeldungen zugegriffen werden.

Bei welchen Konstanten oder Parametern Werte fehlen, kann über die
Methode GET_MISSING_DATA ermittelt werden.

Über die Methode IS_FATAL_ERROR kann programmseitig erkannt werden, ob
nur Werte fehlen oder ob es sich um schwerwiegende Fehler wie fehlende
Zuordnungen oder Definitionen handelt.

![Ein Bild, das Text, Screenshot, Software, Zahl enthält. Automatisch
generierte Beschreibung](media/image116.png){width="5.901388888888889in"
height="2.25625in"}

#### Einzelwert holen

Auf Einzelwerte kann mit der Methode GET_VALUE_SINGLE zugegriffen
werden.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image117.png){width="5.74216426071741in"
height="1.3751192038495188in"}

Dabei wird nicht zwischen Konstanten und Parametern unterschieden.

Wird nicht mit der Force-Dump-Funktionalität gearbeitet, dann wird bei
fehlendem Wert eine leere Zeichenkette zurückgegeben, wenn bei der
Instanziierung der Parameter IV_EXC_BY_ACCESS auf ABAP_FALSE gesetzt
wurde.

Ist dies nicht der Fall wird, seit Version 1.1, bei einem fehlenden Wert
eine Ausnahme vom Typ /PRIS/CX_MAIN_CFG_MISSING ausgelöst.

#### Wertegruppe holen

Auf Wertegruppen kann mit der Methode GET_VALUE_GROUP zugegriffen
werden.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image118.png){width="5.458806867891513in"
height="1.3917869641294838in"}

Dabei wird nicht zwischen Konstanten und Parametern unterschieden.

Wird nicht mit der Force-Dump-Funktionalität gearbeitet, dann wird bei
fehlenden Werten entweder eine leere Range oder eine Range mit dem
Dummy-Eintrag IEQZZZZZZZZZZ\... zurückgegeben, wenn bei der
Instanziierung der Parameter IV_EXC_BY_ACCESS auf ABAP_FALSE gesetzt
wurde.

Ist dies nicht der Fall wird, seit Version 1.1, bei einem fehlenden Wert
eine Ausnahme vom Typ /PRIS/CX_MAIN_CFG_MISSING ausgelöst.

Ob ein Dummy-Eintrag zurück gegeben werden soll wird über den Parameter
IV_DUMMY_FOR_RANGE bei der Instanziierung gesteuert.

Wurden bei der Instanziierung sowohl IV_EXC_BY_ACCESS als auch
IV_DUMMY_FOR_RANGE gesetzt, dann hat ersterer immer Vorrang.

Daher ist es nicht sinnvoll beide Parameter zu kombinieren.

#### Alle Werte holen

Falls die Werte direkt auf Programm- oder Klassenattribute mit den
richtigen Datentypen verteilt werden sollen, macht es Sinn alle Werte
auf einmal anzufordern.

Das ist über die Methode GET_DATA möglich, welche alle Werte als Tabelle
vom Typ /PRIS/MAIN_TT_CFG_ATTR_DATA zurückgibt.

Pro Attribut ist in dieser Tabelle neben den Wert(en) festgehalten, ob
es sich um eine Konstante oder einen Parameter und ob es sich um einen
Einzelwert oder eine Wertegruppe handelt.

Zusätzlich kann dem Feld FLG_MISSING entnommen werden, ob die
Wertzuweisung gefehlt hat.

![Ein Bild, das Text, Zahl, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image119.png){width="5.901388888888889in"
height="1.9861111111111112in"}

Seit Version 1.1 steht darüber hinaus in dem Feld S_ERROR die jeweilige
Fehlermeldung zu dem Attribut zur Verfügung

Der Inhalt der Felder VALUE_SINGLE und T_VALUE_GROUP entspricht dabei
den Rückgabewerten der entsprechenden GET-Methoden. D. h. wurde bei der
Instanziierung der Parameter IV_DUMMY_FOR_RANGE gesetzt so ist auch in
dem Feld T_VALUE_GROUP der Dummy-Eintrag vorhanden.

## SWT -- Schalter-Framework

### Zugriff auf die Erweiterungskonfiguration

Der programmseitige Zugriff auf die Erweiterungskonfiguration erfolgt
über die Klasse /PRIS/MAIN_CL_SWT.

#### Instanz der Klasse /PRIS/MAIN_CL_SWT erzeugen

Über die Methode GET_INSTANCE wird eine Instanz zur Klasse
/PRIS/MAIN_CL_SWT erzeugt.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image120.png){width="5.901388888888889in"
height="2.0708333333333333in"}

Für die in der Standardauslieferung enthaltenden Schlüsselarten stehen
Konstanten in dem Interface /PRIS/MAIN_IF_KEY_VALUES_C zur Verfügung.

![Ein Bild, das Text, Screenshot, Zahl, Software enthält. Automatisch
generierte Beschreibung](media/image121.png){width="5.901388888888889in"
height="2.332638888888889in"}

Falls Sie im EWM unterwegs sind, verwenden Sie bitte die Klasse
/PRIS/EWM_CL_SWT und deren Methode GET_INSTANCE_EWM, da dieser statt
einer Schlüsselart und eines Schlüsselwerts direkt die EWM-Lagernummer
übergeben werden kann.

![Ein Bild, das Text, Screenshot, Schrift, Reihe enthält. Automatisch
generierte Beschreibung](media/image122.png){width="3.591978346456693in"
height="1.5834700349956254in"}

Die folgenden Parameter sind bei beiden Klassen und deren
GET_INSTANCE-Methoden vorhanden:

  ------------------------------------------------------------------------
  Methode                  Art       Beschreibung
  ------------------------ --------- -------------------------------------
  IV_NEW                   Import    Erstellung einer neuen Instanz
                                     erzwingen

  EO_INSTANCE              Export    Eine Instanz der Klasse
  ------------------------------------------------------------------------

#### Erweiterung prüfen

##### Methode CHECK_ENHANCEMENT

Mit der Methode CHECK_ENHANCEMENT kann geprüft werden ob eine
Erweiterung aufgerufen werden soll.

Ist die entsprechende Erweiterung aktiv wird keine Ausnahme geworfen.

In Fehlersituationen und wenn die Erweiterung nicht aktiv sein sollte
werden Ausnahmen geworfen.

![Ein Bild, das Text, Screenshot, Schrift, Dokument enthält. Automatisch
generierte Beschreibung](media/image123.png){width="4.91829615048119in"
height="6.004991251093613in"}

Diese Ausnahmen werden in den folgenden Unterkapiteln näher beschrieben.

##### Ausnahmeklasse /PRIS/CX_MAIN_SWT_INACTIVE

Eine Ausnahme vom Typ /PRIS/CX_MAIN_SWT_INACTIVE wird von der Methode
CHECK_ENHANCEMENT ausgelöst, wenn die Erweiterung inaktiv sein und somit
nicht aufgerufen werden soll.

![Ein Bild, das Text, Schrift, Screenshot, Zahl enthält. Automatisch
generierte Beschreibung](media/image124.png){width="5.901388888888889in"
height="1.6145833333333333in"}

Eine Erweiterung ist inaktiv, wenn für die Erweiterung oder deren
übergeordneten Erweiterung das Kennzeichen Inaktiv in der
Erweiterungskonfiguration gesetzt ist.

##### Ausnahmeklasse /PRIS/CX_MAIN_SWT_INVALID

Eine Ausnahme vom Typ /PRIS/CX_MAIN_SWT_INVALID wird von der Methode
CHECK_ENHANCEMENT ausgelöst, wenn der Methode nur eine übergeordnete
Erweiterung übergeben wurde, obwohl für die übergeordnete Erweiterung
auch untergeordnete Erweiterungen definiert sind.

Wenn für eine Erweiterung untergeordnete Erweiterungen definiert sind
muss auch immer eine untergeordnete Erweiterung bei dem Aufruf der
Methode CHECK_ENHANCEMENT übergeben werden.

![Ein Bild, das Text, Schrift, Screenshot, Zahl enthält. Automatisch
generierte Beschreibung](media/image125.png){width="5.901388888888889in"
height="1.51875in"}

##### Ausnahmeklasse /PRIS/CX_MAIN_SWT_MISSING

Eine Ausnahme vom Typ /PRIS/CX_MAIN_SWT_MISSING wird von der Methode
CHECK_ENHANCEMENT ausgelöst, wenn zu der übergebenen Erweiterung kein
Eintrag in der Erweiterungskonfiguration vorhanden ist.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image126.png){width="5.901388888888889in"
height="1.601388888888889in"}

##### Ausnahmeklasse /PRIS/CX_MAIN_SWT_UNKNOWN

Eine Ausnahme vom Typ /PRIS/CX_MAIN_SWT_UNKNOWN wird von der Methode
CHECK_ENHANCEMENT ausgelöst, wenn zu der übergebenen Erweiterung keine
Definition vorhanden ist.

![Ein Bild, das Text, Screenshot, Schrift, Software enthält. Automatisch
generierte Beschreibung](media/image127.png){width="5.901388888888889in"
height="1.5645833333333334in"}

#### Beispiel-Coding

*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\**

*\* Test program for checking extensions*

*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\**

PARAMETERS p_balobj TYPE balobj_d OBLIGATORY DEFAULT \'ZEWM\'**.**

PARAMETERS p_balsub TYPE balsubobj OBLIGATORY DEFAULT \'ZEWM_CONF\'**.**

PARAMETERS p_lgnum TYPE /scwm/lgnum OBLIGATORY**.**

PARAMETERS p_top TYPE /pris/main_de_top_enh_name OBLIGATORY**.**

PARAMETERS p_sub TYPE /pris/main_de_sub_enh_name**.**

START-OF-SELECTION**.**

DATA lv_msg TYPE string**.**

DATA lo_log TYPE REF TO /pris/ewm_cl_applog**.**

DATA lo_swt TYPE REF TO /pris/ewm_cl_swt**.**

TRY**.**

lo_log = NEW /pris/ewm_cl_applog**(** iv_lgnum = p_lgnum

iv_object = p_balobj

iv_subobject = p_balsub **).**

CATCH /pris/cx_ewm_log_wrong_config INTO DATA**(**lx_config**).**

lv_msg = lx_config-\>get_text**(** **).**

MESSAGE lv_msg TYPE \'S\' DISPLAY LIKE \'E\'**.**

RETURN**.**

ENDTRY**.**

*\"
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--*

*\" Get Instance for EWM*

/pris/ewm_cl_swt=\>get_instance_ewm**(**

EXPORTING

iv_lgnum = p_lgnum

*\* iv_new =*

IMPORTING

eo_instance = lo_swt

**).**

*\" Check Enhancement*

TRY**.**

lo_swt-\>check_enhancement**(**

EXPORTING

iv_top_enhancement = p_top

iv_sub_enhancement = p_sub

**).**

CATCH /pris/cx_main_swt_unknown INTO DATA**(**lx_unknown**).**

*\" Enhancement is not defined*

lo_log-\>log_exception**(** io_exception = lx_unknown

iv_msgty = \'E\' **).**

lv_msg = lx_unknown-\>get_text**(** **).**

CATCH /pris/cx_main_swt_invalid INTO DATA**(**lx_invalid**).**

*\" Wrong Call*

lo_log-\>log_exception**(** io_exception = lx_invalid

iv_msgty = \'E\' **).**

lv_msg = lx_invalid-\>get_text**(** **).**

CATCH /pris/cx_main_swt_missing INTO DATA**(**lx_missing**).**

*\" Missing Entries in Master Data Table*

lo_log-\>log_exception**(** io_exception = lx_missing

iv_msgty = \'W\' **).**

lv_msg = lx_missing-\>get_text**(** **).**

CATCH /pris/cx_main_swt_inactive INTO DATA**(**lx_inactive**).**

*\" Enhancement is inactive*

lo_log-\>log_exception**(** io_exception = lx_inactive

iv_msgty = \'W\' **).**

lv_msg = lx_inactive-\>get_text**(** **).**

ENDTRY**.**

IF lv_msg IS NOT INITIAL**.**

MESSAGE lv_msg TYPE \'S\' DISPLAY LIKE \'E\'**.**

ELSE**.**

MESSAGE \'Enhancement is active.\' TYPE \'S\'**.**

ENDIF**.**

*\"
\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\-\--*

TRY**.**

lo_log-\>save_applog2db**(** **).**

CATCH /scwm/cx_basics**.**

ENDTRY**.**

## SDT Adjustment Report

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Wizard

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Generische Tabellenleseklasse

### Kopiervorlage zum Lesen mehrerer Datensätze

DATA lt_data TYPE \<table type\>**.**

TRY**.**

DATA**(**lo_table**)** =

NEW /pris/main_cl_gtb_table_read**(**

iv_table_name = \<table name\>

it_key_fields = VALUE \#**(** **(** key_name = \<c name 1\>

key_value = \<c value 1\> **)**

*\" \...*

**(** key_name = \<c name n\>

key_value = \<c value n\> **)** **)** **).**

DATA**(**ld_data_multiple**)** =

lo_table-\>get_multiple**(**

it_field_range =

VALUE \#**(** **(** fieldname = \<c where n 1\>

selopt_t = VALUE \#**(** **(** sign = \<sign\>

option = \<option\>

low = \<c where 1 v 1\> **)**

*\" \...*

**(** sign = \<sign\>

option = \<option\>

low = \<c where 1 v n\> **)**\
**)** **)**

*\" \...*

**(** fieldname = \<c where n n\>

selopt_t = VALUE \#**(** **(** sign = \<sign\>

option = \<option\>

low = \<c where n v 1\> **)**

*\" \...*

**(** sign = \<sign\>

option = \<option\>

low = \<c where n v n\> **)**\
**)** **)** **)** **).**

lt_data = ld_data_multiple-\>\***.**

CATCH /pris/cx_main_gtb_table_read INTO DATA**(**lx_table_read**).**

me-\>mo_log-\>log_exception**(** io_exception = lx_table_read **).**

ENDTRY**.**

### Kopiervorlage zum Lesen einzelner Zeilen

DATA ls_data TYPE \<structure / Database table\>**.**

TRY**.**

DATA**(**lo_table**)** =

NEW /pris/main_cl_gtb_table_read**(**

iv_table_name = \<table name\>

it_key_fields = VALUE \#**(** **(** key_name = \<column name 1\>

key_value = \<column value 1\> **)**

*\" \...*

**(** key_name = \<column name n\>

key_value = \<column value n\> **)**\
**)** **).**

DATA**(**ld_data_single**)** =

lo_table-\>get_single**(**

it_key_fields =

VALUE \#**(** **(** key_name = \<column name 1\>

key_value = \<column value 1\> **)**

*\" \...*

**(** key_name = \<column name n\>

key_value = \<column value n\> **)** **)** **).**

ls_data = ld_data_single-\>\***.**

CATCH /pris/cx_main_gtb_table_read INTO DATA**(**lx_table_read**).**

me-\>mo_log-\>log_exception**(** io_exception = lx_table_read **).**

ENDTRY**.**

## Transport Order Tool

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Generische Suchhilfe

Für diese Lösung gibt es keine zusätzlichen Informationen.

## CSV-Handling

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Access Control Definition -- Zugriffsfolge

### Instanziierung

Die Instanziierung wird über die statische Methode GET_INSTANCE
ausgeführt. Der Methodenaufruf sollte in einem Try-Catch erfolgen, damit
aufgetretene Meldungen im Fehlerfall über das Ausnahmeobjekt
zurückgegeben werden können.

![](media/image128.png){width="5.570570866141733in"
height="3.8645833333333335in"}

In diesem Beispiel werden nur die obligatorischen Parameter bedient.

Während der Instanziierung werden die Datentabelle und die
Suchfolgentabelle, gefiltert durch die Schlüsselwerte, von der Datenbank
selektiert und in der Instanz gespeichert.\
Falls übergeben, werden die Vergleichsoperatoren mit in die Selektion
aufgenommen.

### Datenermittlung

Für die Datenermittlung muss die Struktur für die Selektionsdaten, die
vom gleichen Typ wie die Datentabelle ist, übergeben werden. In dieser
müssen nicht alle Felder gefüllt werden, solange eine Suchfolge
existiert, die von den gefüllten Feldern abgedeckt wird.

![Ein Bild, das Text, Screenshot, Schrift, Zahl enthält. Automatisch
generierte Beschreibung](media/image129.png){width="5.583333333333333in"
height="4.9319444444444445in"}

Im besten Fall wird der Aufruf der Methode in dem gleichen
Try-Catch-Block wie die Instanziierung durchgeführt, um Dumps zur
Null-Referenz zu vermeiden.

## Generischer Löschreport

Für diese Lösung gibt es keine zusätzlichen Informationen.

## GTB HTTP-Request

Für diese Lösung gibt es keine zusätzlichen Informationen.

## GTB Timer

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Generische Berechtigungsprüfung

Für diese Lösung gibt es keine zusätzlichen Informationen.

## BAdI and Enhancement Framework

Für diese Lösung gibt es keine zusätzlichen Informationen.

## GTB System

Für diese Lösung gibt es keine zusätzlichen Informationen.

## Kleine Werkzeuge

Für die Klassen gibt es keine zusätzlichen Informationen.

## Easy Mapper

Für die Klassen gibt es keine zusätzlichen Informationen.

## RFC Hilfsklasse

Für die Klassen gibt es keine zusätzlichen Informationen.
