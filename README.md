# README.txt

Datensatzbeschreibung 
Der Datensatz „housing.csv“ enthält Wohnungsdaten aus Kalifornien. Die Spalten sind: longitude und latitude (Koordinaten), housing_median_age (mittleres Alter der Häuser), total_rooms (Anzahl Zimmer), total_bedrooms (Anzahl Schlafzimmer), population (Einwohnerzahl), households (Anzahl Haushalte), median_income (mittleres Einkommen) und median_house_value (mittlerer Hauswert). ocean_proximity beschreibt die Nähe zum Meer (z.B. NEAR BAY). Für Machine Learning ist der Datensatz geeignet, weil viele Features vorhanden sind und man den Hauswert (Target: median_house_value) als Regressionsproblem vorhersagen kann.

Datenschutz
Der Datensatz enthält keine direkten Personendaten wie Name, Adresse, Telefonnummer oder E-Mail. Es sind nur geografische Koordinaten und zusammengefasste Werte pro Gebiet (Population, Haushalte, Medianwerte) enthalten. Dadurch ist der Datenschutz nur wenig betroffen. Damit trotzdem keine Rückschlüsse auf einzelne Personen entstehen, werden keine eindeutigen Identifikatoren gespeichert und die Daten bleiben auf Gebietsebene (aggregiert). Ich habe keine zusätzlichen Quellen verknüpft und nur diese aggregierten Felder im Repository veröffentlicht.
