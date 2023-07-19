# LOG-Daten

Es werden die Daten aus einer LOG-Datei so aufbereitet, das auch Ortsangaben in PowerBI angezeigt werden können.

Folgende Schritte sind:
1. Laden der Daten
2. Beibehalten der Daten, die in der Spalte "Stufe" "Warnung" enthält
3. Extraktion der IP-Adresse und der Fehlermeldung
4. Die extrahierten Daten dem eingelesenen Datensatz hinzufügen und entfernen der Spalte der diese Daten enthält
5. DataFrame erstellen der die einzigartigen IP-Adressen enthält, und dann die Ortsangaben hinzufügen
6. zusammenfügen der daten aus schritt 4 und 5
7. Abspeichern als CSV-Datei
