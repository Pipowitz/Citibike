Der Fahrradverleih CitiBike vermietet in New York über 12.000 Fahrräder an 750 Verleihstatio-
nen. Somit ist CitiBike eine echte Alternative zu den herkömmlichen Transportmitteln, wie z.B. U-
bahn oder Taxi.

Mit einem gültigen 24 Stunden (3 Tage) Pass bzw. einer jährlichen Mitgliedschaft können Kun-
den ein Fahrrad an einer Verleihstation abholen und an einer beliebigen Station wieder abgeben.
CitiBike stellt die durch den Verleih gesammelten Daten der Öffentlichkeit zur Verfügung. Ihre
Aufgabe als Data Scientist ist es, CitiBike dabei zu helfen diese Daten wertstiftend zu nutzen.
In einem ersten Pilotprojekt sollen Sie hierfür die Daten analysieren und ein Modell bauen, mit
welchem zwei Klassen von Nutzern identifiziert werden können; dies sind (i) customers (24
Stunden/ 3 Tage Pass) und (ii) subscribers (jährliche Mitgliedschaft). Eine Orientierungshilfe bei
dieser Aufgabenstellung bieten Ihnen die folgenen Arbeitsschritte:

1. Laden Sie diese Daten von Citibike für das Jahr 2018 herunter (https://s3.amazonaws.com/tripdata/index.html). Machen Sie sich mit dem
Inhalt des Datensatzes vertraut und bereiten Sie ihn für weitere Analysen auf.
2. Visualisieren Sie die Daten; seien Sie kreativ und überlegen Sie sich geeignete Darstel-
lungsformen für Ihre Entdeckungen. Nutzen Sie die Visualisierungen auch in Ihrer Er-
gebnispräsentation um Ihre Argumente zu unterstützen.
3. Überlegen Sie sich geeignete Features (Merkmale) als Input für Ihr customer-subscriber-
Modell. Konstruieren Sie gegebenenfalls neue Features um Ihr Modell zu verbessern.
4. Vertesten Sie verschiedene Modelle bzw. Methoden zur Klassifikation der Kundentypen
subscribers und customers. Evaluieren Sie die Performance der unterschiedlichen Model-
le und begründen Sie eine Modellauswahl.
5. Betrachten Sie zudem ein zufälliges Subset von ca. 200 Fahrten, die durch subscribers
unternommen wurden. Untersuchen Sie ob diese Nutzer mit dem Fahrrad tatsächlich
schneller zu ihrem Ziel gelangten als wenn sie zur gleichen Uhrzeit mit der U-bahn oder
mit einem Taxi gefahren wären.
Tipp: Nutzen Sie die API von Google Maps (https://developers.google.com/maps/?hl=de) und vergleichen Sie die benötigte Zeit für die
Strecke zwischen A und B mit Auto/Fahrrad/Bahn/. Achten Sie hierbei auf die Uhrzeit!
6. Laden Sie diese Daten vom NYPD herunter (https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95). Skizzieren Sie für CitiBike Kooperations-
möglichkeiten mit einer Versicherung (und/oder umgekehrt). Nutzen Sie gegebenfalls
weitere Datenquellen um Ihre Argumente zu untermauern.
