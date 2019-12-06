# Fiori-App-MaterialList
Eugen Komlovski Bachelorprojekt-Repo 

Die App wurde von Eugen Komlovski am 12.12.2019 erstellt und deployed.
BA-Projekt unterstützt von: peritia Consulting GmbH.


Dokumentation.
Fiori-MaterialList Applikation.


Material anlegen/ändern:
1. Material-NR               :                ID-Schlüssel (Eingabe-Pflicht)    
2. Material-Name             :                MaterialName(String, Nullabble)
3. Erstelldatum              :                Erstelldatum(EDM.Date/Time , SAP Format, BSP: 2020-01-01T12:00:00, obligatorisch)
4. Erstellt von              :                Erstellt von(String, SAP-Format) 
5. Mengeneinheit             :                Mengeneinheit(SAP Format, obligatorisch, BSP: Siehe unten "Mengeneinheit" ) 

Mengeneinheit: SAP-basiert:

ST - Stück,
STD -Stunden,
T  - Tage,
TTE - Tüte,
N - Newton,
MS - Millisekunde,
V- Volt,
M2- Quadratmeter,
M - Meter,
L - Liter,
KS - Kasten,
KM - Kilometer,
A   - Ampere,
% - Prozent,
......................usw. Siehe SAP-Basismengeneinheiten


::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::::
Material löschen:
1. Material-NR               :                ID-Schlüssel (Eingabe-Pflicht) 
