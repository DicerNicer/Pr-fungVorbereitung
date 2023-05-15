# Call by Reference / Call by Value
## Call by Value 
Nur Wert der Variable wird an Methode übergeben.
Variable wird nicht verändert.

Bsp. methode(x)

## Call by Reference
Speicherstelle der Variable wird an Methode übergeben.
D.h. Wert der Variable kann geändert werden
Es gibt 2 Möglichkeiten

### Ref
Variable muss zuvor einen Wert zugewiesen bekommen haben.
Muss jedoch nicht in Methode beschrieben werden.

Bsp.: methode(ref x)

### Out
Variable muss zuvor keinen Wert zugewiesen bekommen haben.
Muss jedoch in Methode beschrieben werden.

Bsp.: methode(out x)

# Klassen
Eine Klasse ist der Bauplan nach dem Objekte erstellt werden.

## Konstruktor
Zum erstellen des Objektes wird der Konstruktor der Klasse aufgerufen.
Dieser wird folgendermaßen deklariert:
public NameDerKlasse()
{
}

## Attribute
Attribute sind die Variablen eines Objektes.
Sie werden als private deklariert und werden nur von Methoden des Objektes gelesen und beschrieben.
Diese Methoden nennt man getter und setter.
Bsp:
private int nr;
public void setNr(){}
public int getNr(){}

## Methoden
Zusätzlich zu den Attributen besitzen Objekte auch Methoden. Zum Beispiel die Klasse Würfel hat die Methode würfeln().

## UML2-Notation (Unified Modeling Language, V2)

UML2 ist die Notationsweiße für Klassen.
Sie besteht aus 3 Kästen:
- Der oberste gibt den Klassennamen an.
- Die zweite die Attribute.
- Die dritte die Mehtoden.
### Private / Public / Protected
#### Public
+ vor Name
direkter Lese- und Schreibzugriff von außen auf das Attribut möglich
#### Private
- vor Name
kein direkter Lese- und Schreibzugriff von außen auf das Attribut möglich
#### Protected
\# vor Name
direkter Lese- und Schreibzugriff von Objekten einer Subklasse (→ Vererbung) auf
das Attribut möglich, jedoch kein direkter Lese- und Schreibzugriff von außen auf
das Attribut möglich

### Schreibweise Attribute

1. +/-/#
2. Name
3. :
4. Datentyp

Bsp.: 
+ augenzahl:int

### Schreibweise Mehtoden
1. +/-/#
2. Name
3. (übergabeVar:Datentyp)
4. :
5. Rückgabewert

Bsp.:
+ wuerfeln(void):int

# Präfixe für GUI
- Button:        btn
- Label:         lbl
- TextBox:       tbx
- RadioButton:   rbt
- ListBox:       lbx
- ComboBox:      cbx
- CheckBox:      chk
