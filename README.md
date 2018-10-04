# Call-Control in Ringnetzwerken
Algorithmen zur Lösung des Call-Control-Problems in Ringnetzwerken

This is a **German-only project**, based on **English sources**, that can be found here: https://link.springer.com/article/10.1007/s00453-006-0187-4

## Einführung

Bei der Optimierung von Kommunikationssystemen geht es oft darum, konkrete Probleme auf
abstrakte, mathematische Problemstellungen zurückzuführen, und man gelangt so in vielen
Fällen zu Problemen in Graphen. Eines dieser Probleme beschreibt Call-Control (auch Call-
Admission-Control), bei dem in einem Netzwerk eine Menge von Anfragen (sog. calls) gestellt
werden und jede Anfrage gemäß einer bestimmten Zielsetzung akzeptiert oder verworfen werden
muss. Es soll insbesondere sichergestellt werden, dass durch das Durchführen der akzeptierten
Anfragen die Bandbreiten, die das Netzwerk zur Verfügung stellt, nicht überstrapaziert werden.
Eine weitere Zielsetzung könnte dann beispielsweise sein, die Anzahl der akzeptierten Anfragen
zu maximieren.

Da es meist schwierig ist, über willkürliche Graphen weitreichende Aussagen zu treffen,
schränkt man sich oft auf bestimmte Typen eines Graphen ein. So beschränkt sich der Arti-
kel „Call Control in Rings“ [1] der vier Autoren Adamy, Ambühl, Anand und Erlebach auf
Netzwerke, die sich als Ring- oder Kettengraph darstellen lassen.

## PDF-Dateien

Die Ausarbeitung ist [hier](src/main.pdf) zu finden; ein dazugehöriger Foliensatz ist [hier](src/beamer/main.pdf) abrufbar.
