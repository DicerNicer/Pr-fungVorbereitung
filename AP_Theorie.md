# Normalformen
## 1. Normalform
- atomare Attributwerte
### Nachteile
Es können Anomalien auftreten
- Änderungsanomalie
- Einfügeanomalie
- Löschanomalie
## 2. Normalform
- volle funktionale Abhängigkeit jedes Attributs vom Primärschlüsel
## 3. Normalform
- keine Abhängigkeiten zwischen Nicht-Schlüsselattributen

# Referentielle Integrität
Eine Datenbank besitzt Integrität, wenn ihr Datenbestand nicht korrupt oder inkonsistent, also
"unregelmäßig" oder "unsauber" ist. Die referentielle Integrität einer Datenbank wird z.B. dann
verletzt, wenn in einer Detailtabelle ein Datensatz vorhanden ist, für den in der Haupttabelle kein
entsprechender Eintrag existiert. Das heißt z.B. wenn in der Tabelle Aufträge ein Eintrag
existiert mit einer KundenNr, für die es in der Kundentabelle keinen Eintrag gibt.

# Vorgehensweise DB Entwurf
1. Alle Tabellen aufschreiben
2. Primärschlüssel festlegen
3. Atribute zuorden
4. m zu n mit Zwischentabellen auflösen

# Vorgehensweise SQL Anfragen
Wie man spricht!!
