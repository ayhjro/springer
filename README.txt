Kompilierung:
	gcc chess.c -std=c99 -c
	gcc main.c -std=c99 chess.o -o springer.exe


Verwendung: 
	springer [options] <Startposition>
	Startposition zB. in der Form "A6" oder "f1" angeben

Die meisten Optionen haben mehre Synonyme zur erleichterten Verwendung. Davon ist ein Synonym in der Regel die Kurzform.
Optionen:
  -h
  --h
  -help
  --help
	Im Program enthaltene Hilfe-Dokumentation anzeigen.

  -l
  -loop
	Geschlossenen Pfad berechnen. (Aufgabenteil C)

  -h=<Wert>
  -height=<Wert>
	Standardwert der Feldh�he von 8 auf Wert �ndern. Wert ohne <> eingeben.

  -w=<Wert>
  -width=<Wert>
	Standardwert der Feldbreite von 8 auf Wert �ndern. Wert ohne <> eingeben.

  -d
  -dynamic
	Dynamische Ausgabe aktivieren. Achtung: Die Wiederholte Ausgabe ist Zeitintensiv und erh�ht die Ausf�hrungszeit erheblich.

  -csv=<Filename>
	Das fertig berechnete Feld nach der Berechnung als CSV nach Filename schreiben. Filename ohne <> eingeben.

  -p=<n>
  -permutation=<n>
	Ermittelt die n'te Permutation. Das Program berechnet statisch f�r jede Eingabe die selbe L�sung. Mit dieser Option k�nnen nachfolgende L�sungen vom Programm ermittelt und ausgegeben werden. Achtung: Hohe Werte f�r n verlangsamen das Programm erheblich.


Beispieleingaben:
  