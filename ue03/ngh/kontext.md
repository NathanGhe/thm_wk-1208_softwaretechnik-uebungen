# Stakeholder und Systemkontext — Terminplaner für die THM

## Stakeholder

| Stakeholder | Worauf hat er Einfluss? |
|---|---|
| Hochschulleitung (Auftraggeber/Fachbereich) | Entscheidet über Ziele, Budget und Umfang des Terminplaners und trifft die grundsätzlichen Entscheidungen. |
| Lehrende | Bestimmen als Endanwender, welche Sprechstunden und Prüfungstermine angeboten werden und wie das Anbieten ablaufen muss. |
| Studierende | Bestimmen als Endanwender, wie das Suchen und Buchen von Terminen funktionieren muss. |
| Sekretariate | Bestimmen, welche Übersichten sie benötigen, um den Überblick über die Termine ihres Bereichs zu behalten. |
| Rechenzentrum der THM (IT-Bereich) | Gibt vor, wie das System betrieben und an das Hochschulkonto angebunden werden muss. |
| Datenschutzbeauftragte der THM | Bestimmt, welche personenbezogenen Daten gespeichert und wem sie angezeigt werden dürfen. |
| Prüfungsamt | Legt fest, welche Regeln für Prüfungstermine gelten, z. B. wer sie anlegen oder absagen darf. |

## Systemkontext

| Aspekt | Art | Warum gehört er zum Kontext? |
|---|---|---|
| Lehrende, Studierende und Sekretariate | Person | Sie bedienen das System über die Benutzeroberfläche, gehören aber selbst nicht zum System. |
| Hochschulkonto (Anmeldesystem der THM) | System im Betrieb | Der Terminplaner nutzt es für die Anmeldung, es wird aber vom Rechenzentrum verantwortet und nicht im Projekt gebaut. |
| Kalenderprogramme der Beteiligten | System im Betrieb | Sie müssen die iCal-Dateien des Terminplaners einlesen können, gehören aber nicht zum System. |
| KI-Agenten | System im Betrieb | Sie steuern den Terminplaner über die API, sind aber eigenständige Systeme außerhalb davon. |
| Prüfungsanmeldung | Prozess | Prüfungstermine hängen an diesem bestehenden Verfahren der THM, das der Terminplaner berücksichtigen, aber nicht ersetzen muss. |
| Semesterbeginn und Prüfungszeitraum | Ereignis | Zu diesen Zeitpunkten werden besonders viele Termine angeboten und gebucht. |
| Zeitumstellung | Ereignis | Termine müssen auch bei der Umstellung zwischen Sommer- und Winterzeit zur richtigen Uhrzeit angezeigt werden. |
| Prüfungsordnung | Dokument | Sie legt Regeln für Prüfungstermine fest, an die sich das System halten muss. |
| Datenschutz-Grundverordnung (DSGVO) | Dokument | Sie bestimmt, wie mit den personenbezogenen Daten der Beteiligten umzugehen ist. |

## Irrelevante Umgebung

- Mensa und Speiseplan — haben mit der Vereinbarung von Terminen nichts zu tun.
- Ausleihsystem der Bibliothek — Medienausleihen spielen für Sprechstunden und Prüfungstermine keine Rolle.