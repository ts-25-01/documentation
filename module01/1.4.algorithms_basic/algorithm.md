# Algorithmus
## Was ist ein Algorithmus?
Ein Algorithmus ist eine eindeutige Schritt-für-Schritt-Anweisung zur Lösung eines Problems oder zur Erfüllung einer Aufgabe. Er besteht aus einer endlichen Anzahl von Schritten und kann von Menschen oder Maschinen ausgeführt werden.
### Eigenschaften eines Algorithmus
- Eindeutigkeit: Jeder Schritt ist klar definiert.
- Endlichkeit: Der Algorithmus muss nach einer endlichen Anzahl von Schritten enden.
- Ausführbarkeit: Jeder Schritt muss durchführbar sein.
- Determinismus: Bei gleichen Eingaben liefert der Algorithmus immer die gleichen Ergebnisse.
- #### Beispiel für einen Algorithmus
Algorithmus zur Zubereitung eines Tees:
1. Wasser in den Wasserkocher füllen.
2. Wasser zum Kochen bringen.
3. Teebeutel in eine Tasse legen.
4. Heißes Wasser in die Tasse gießen.
5. Tee ziehen lassen.
6. Teebeutel entfernen und genießen.

## Programmiercode
Programmiercode ist die Umsetzung eines Algorithmus in eine für den Computer verständliche Form. Er wird in einer Programmiersprache geschrieben und kann dann von einem Computer ausgeführt werden.
### Was ist eine Programmiersprache?
Eine Programmiersprache ist eine formale Sprache, die von Computern verstanden wird. Sie besteht aus Syntax- und Semantikregeln, die festlegen, wie Programme geschrieben werden müssen.
```python
for i in range(5):
  print(i)
```
### Programmierparadigmen
Programmierparadigmen sind verschiedene Ansätze zur Entwicklung von Software. Sie beeinflussen die Art und Weise, wie Code strukturiert wird.
#### Imperative vs. Deklarative Programmierung
- Imperativ: Beschreibung, wie etwas gemacht wird (z.B. prozedurale oder objektorientierte Sprachen wie C, Java).
- Deklarativ: Beschreibung, was gemacht werden soll (z.B. funktionale oder logische Sprachen wie SQL, Haskell).
#### Historische Entwicklung
1. Maschinensprache (1940er-50er) - Programme wurden in Binärcode geschrieben.

2. Assembler (1950er-60er) - Einführung von mnemonischen Befehlen.

3. Prozedurale Programmierung (1960er-70er) - Verwendung von Funktionen und Prozeduren (z.B. C, Pascal).

4. Objektorientierte Programmierung (1980er-90er) - Einführung von Klassen und Objekten (z.B. Java, C++).

5. Funktionale Programmierung (seit 2000er populärer) - Verwendung von Funktionen als zentrale Bausteine (z.B. Haskell, Python).

## Struktogramme
Struktogramme (Nassi-Shneiderman-Diagramme) sind eine Möglichkeit, Algorithmen visuell darzustellen. Sie bestehen aus:

- Sequenzen (lineare Abläufe)

- Verzweigungen (z.B. "Wenn-Dann-Sonst")

- Schleifen (z.B. "Solange-Wiederholen")
```markdown
+----------------+
| Bedingung      |
+----------------+
     | Ja   | Nein
+-------+  +-------+
| Aktion |  | Aktion |
+-------+  +-------+
```
### Blockly Games
```markdown
  [Wiederhole 5 mal]
   [Geh einen Schritt vorwärts]
   [Drehe dich nach links]
```
```python
for i in range(5):
    gehe_vorwaerts()
    drehe_links()
```

### Python

