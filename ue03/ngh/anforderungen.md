# Anforderungen — Terminplaner für die THM

| Nr. | Anforderung | Stakeholder | Art |
|---|---|---|---|
| A01 | Lehrende müssen Sprechstundentermine erstellen und zur Buchung freigeben können. | Lehrende | FA |
| A02 | Lehrende müssen Termine für mündliche Prüfungen anlegen können. | Lehrende | FA |
| A03 | Studierende müssen einen freien Sprechstundentermin bei einer Lehrperson buchen können. | Studierende | FA |
| A04 | Studierende müssen ihre Buchung bis spätestens 24 Stunden vor dem Termin absagen können. | Studierende | FA |
| A05 | Bei gleichzeitigen Buchungsversuchen für denselben freien Einzeltermin muss das System genau eine Buchung bestätigen und allen anderen Personen melden, dass der Termin vergeben ist. | Lehrende, Studierende | FA |
| A06 | Sekretariate müssen die Prüfungstermine ihres Fachbereichs in einer Liste mit Datum, Uhrzeit, Raum und Lehrperson ansehen können. | Sekretariate | FA |
| A07 | Für angemeldete Studierende muss eine Buchung von der Terminseite einer Lehrperson aus mit höchstens drei Klicks möglich sein. | Studierende | QA |
| A08 | Bei 2.000 gleichzeitig aktiven Nutzenden müssen mindestens 95 % der aufgerufenen Seiten innerhalb von zwei Sekunden vollständig geladen sein. | Studierende, Rechenzentrum der THM | QA |
| A09 | Die Anmeldung muss ausschließlich über das vorhandene THM-Hochschulkonto erfolgen. | Rechenzentrum der THM | RB |
| A10 | Der Terminplaner muss auf Servern des THM-Rechenzentrums betrieben werden. | Rechenzentrum der THM | RB |
| A11 | Die Benutzeroberfläche muss den Anforderungen der BITV 2.0 entsprechen. | Hochschulleitung, Studierende mit Behinderung | RB |
| A12 | Personenbezogene Buchungsdaten müssen gemäß der DSGVO verarbeitet werden. | Datenschutzbeauftragte der THM | RB |

## Eine Anforderung, die niemand ausgesprochen hat

A05: Bei einem Einzeltermin gehen alle davon aus, dass nur eine Person
den Platz bekommen kann. Dass das auch bei gleichzeitigen Buchungen
funktionieren muss, wird deshalb im Gespräch leicht vergessen.