# Die Klimaerwärmung in der Region Zürichsee

Wie macht sich die Klimaerwärmung in der Zürichsee-Region bemerkbar? Analyse der Daten der Wetterstation Wädenswil seit 1981 (Temperatur) und Niederschlag (seit 1961).

## Mit den Resultaten der Datenanalyse publizierte Artikel

Klimabilanz 2019 (Zürcher Regionalzeitungen): \
https://www.zsz.ch/horgen/ein-weiteres-jahr-der-klimaextreme/story/16430930 \
Die Klimaveränderung am Zürichsee seit 1961 (Zürcher Regionalzeitungen) => noch nicht publiziert, erscheint erst im März!
https://www.zsz.ch/horgen/Aus-vier-werden-zwei-Jahreszeiten/story/16766857?cache=9efAwefu

## Idee und Ausgangslage

Die Auswirkungen der Klimaerwärmung werden immer deutlicher. Die Durchschnittstemperaturen steigen, markante Hitzephasen im Sommer werden zur Regel, die Winter werden milder. In der Regel sind statistische Auswertungen dazu aber nur grossflächig gemittelt und für "bekannte" Orte (Genf, Zürich, Bern, etc.) zu finden. Regionale Daten, welche die Entwicklung sozusagen "vor der Haustüre" verdeutlichen, werden selten analysiert. Dabei wären sie vorhanden, Meteoschweiz stellt sie frei zur Verfügung. Ich schnappe mir den entsprechenden Datensatz der SMA-Wetterstation Wädenswil und analysiere ihn. Ziel ist es, die Auswirkungen der Klimaerwärmung mit regionalem Fokus für einen regionalen Medientitel (Zürichsee-Zeitung) aufzubereiten.

## Die These

Das Klima in der Zürichseeregion hat sich in den letzten 40 Jahren stark erwärmt. Der Trend zur Erwärmung zeigt sich über alle Jahreszeiten, besonders markant aber im Sommer und in den Übergangsmonaten (Frühling, Herbst). Beim Niederschlag ist anhand der Daten (noch) kein eindeutiger Trend zu beobachten. Tendenziell ist jedoch kein Trend zur Trockenheit zu erwarten, da die Region sich in unmittelbarer Nähe zu den Voralpen befindet (Staueffekte). Die Erwärmung zeigt sich auch in einer Zunahme der Hitzetage (über 30 Grad) und einer gleichzeitigen Abnahme der Kältesumme im Winter.

## Einschätzung von Aufwand und Ertrag

Die Daten sind in gut aufbereiteter Form (.xls und .txt) vorhanden. Das Einlesen der Daten dürfte nicht viel Aufwand verursachen. Komplexer ist die mathematische / grafische Schiene dieser Story. Die Durchschnittswerte müssen korrekt berechnet werden und die Charts müssen aussagekräftig sein. Der Ertrag dürfte insgesamt aber gross sein, da sich Code/Datensatz über die kommenden Jahre hinweg mit leichten Anpassungen und Aktualisierungen immer wieder verwenden lassen! Folgestorys sind also zu erwarten.

## Schwierigkeiten/Knackpunkte

Herausforderungen bietet vor allem die grafische Darstellung (Pandas auf Highlevel, Kombination von Python und Pandas), zudem besteht hohe Fehleranfälligkeit durch viel Rechnerei.

## Briefing- und Fachperson

Stephan Bader, Klimatologe bei Meteoschweiz, wohnhaft in Uerikon (also auch aus der Zürichseeregion).

## Daten und Code

[Der Code (in komprimierter Form als ZIP-File hochgeladen)](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/blob/master/Klima%20Wa%CC%88denswil.ipynb.zip)\
[Die Grafiken](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/tree/master/Grafiken%20Wetter)\
[Die Rohdaten](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/tree/master/klima/waedenswil)\
[Climate-Sheets Meteoschweiz (Normwerte)](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/tree/master/Climate-Sheets%20Meteoschweiz) 

## Arbeitsprotokoll

Anfang Dezember 2019: Kontakt mit Meteoschweiz zur Datenbeschaffung, Erstes Gespräch zur Einordnung mit Klimatologe Stephan Bader\
Mitte Dezember 2019: Arbeitsbeginn am Code für die Monatswerte\
Ende Dezember 2019: Fertigstellung von Code und Grafiken für die Monatswerte, Recherche und Schreibarbeit für Klimabilanz 2019 (Veröffentlicht am 4. Januar 2020)\
Anfang Januar 2020: Erweiterung des Codes um die Tageswerte, Erstellung der Grafiken\
Bis Mitte Januar 2020: Laufendes "Feintuning" an Grafiken und Code. Journalistisches Gespräch mit Stephan Bader zur Einordnung der Daten, Recherche und Schreibarbeit.\
