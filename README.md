# Die Klimaerwärmung in der Region Zürichsee

Wie macht sich die Klimaerwärmung in der Zürichsee-Region bemerkbar? Analyse der Daten der Wetterstation Wädenswil seit 1981 (Temperatur) und Niederschlag (seit 1961).

## Mit den Resultaten der Datenanalyse publizierte Artikel

Klimabilanz 2019 (Zürcher Regionalzeitungen): \
https://www.zsz.ch/horgen/ein-weiteres-jahr-der-klimaextreme/story/16430930 \
Die Klimaveränderung am Zürichsee seit 1961:

## Idee und Ausgangslage

Die Auswirkungen der Klimaerwärmung werden immer deutlicher. Die Durchschnittstemperaturen steigen, markante Hitzephasen im Sommer werden zur Regel, die Winter werden milder. In der Regel sind statistische Auswertungen dazu aber nur grossflächig gemittelt und für "bekannte" Orte (Genf, Zürich, Bern, etc.) zu finden. Regionale Daten, welche die Entwicklung sozusagen "vor der Haustüre" verdeutlichen, werden selten analysiert. Dabei wären sie vorhanden, Meteoschweiz stellt sie frei zur Verfügung. Ich schnappe mir den entsprechenden Datensatz der SMA-Wetterstation Wädenswil und analysiere ihn. Ziel ist es, die Auswirkungen der Klimaerwärmung mit regionalem Fokus für einen regionalen Medientitel (Zürichsee-Zeitung) aufzubereiten.

## Die These

Das Klima in der Zürichseeregion hat sich in den letzten 40 Jahren überdurchschnittlich stark erwärmt (im Vergleich zu den über die ganze Schweiz gemittelten Werten). Der Trend zur Erwärmung zeigt sich über alle Jahreszeiten, besonders markant aber im Sommer und in den Übergangsmonaten (Frühling, Herbst). Beim Niederschlag ist anhand der Daten (noch) kein eindeutiger Trend zu beobachten. Tendenziell ist jedoch kein Trend zur Trockenheit zu erwarten, da die Region sich in unmittelbarer Nähe zu den Voralpen befindet (Staueffekte). Die Erwärmung zeigt sich auch in einer Zunahme der Hitzetage (über 30 Grad) und einer gleichzeitigen Abnahme der Kältesumme im Winter.

## Einschätzung von Aufwand und Ertrag

Die Daten sind in gut aufbereiteter Form (.xls und .txt) vorhanden. Das Einlesen der Daten dürfte nicht viel Aufwand verursachen. Komplexer ist die mathematische / grafische Schiene dieser Story. Die Durchschnittswerte müssen korrekt berechnet werden und die Charts müssen aussagekräftig sein.

## Schwierigkeiten

Grafische Darstellung (Pandas auf Highlevel, Kombination von Python und Pandas), hohe Fehleranfälligkeit durch viel Rechnerei.

## Briefing- und Fachperson

Stephan Bader, Klimatologe bei Meteoschweiz, wohnhaft in Uerikon (also auch aus der Zürichseeregion).

## Daten und Code

[Der Code]()\
[Die Grafiken]\
[Die Rohdaten](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/tree/master/klima/waedenswil)\
[Climate-Sheets Meteoschweiz (Normwerte)](https://github.com/MartinSteinegger/Klimaerwaermung-am-Zuerichsee/tree/master/Climate-Sheets%20Meteoschweiz)



